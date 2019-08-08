## Initiating Transactions using Kweli Schemas   
Below is a guide to use when initiating transactions on the ledger when using Credential Schemas on Kweli-Network

### Transcript

Here is how the **Government** creates and publishes the **Transcript** Credential Schema to the Ledger:

```python
transcript_schema = await Schema.create(government_did, 'Transcript', '1.2', ['first_name', 'last_name', 'degree', 'status', 'year', 'average', 'huduma_namba'], 0)
transcript_schema_id = await transcript_schema.get_schema_id()
```

**Chuo University** creates and publishes a Credential Definition for the known **Transcript** Credential Schema to the Ledger.

```python
# Chuo University Agent
chuo_transcript_cred_def = await CredentialDef.create(chuo_did, 'Chuo-Transcript', transcript_schema_id, 0)
chuo_transcript_cred_def_id = await chuo_transcript_cred_def.get_cred_def_id()
```

### Birth-Certificate

Similarly **Government** creates and publishes the **Birth-Certificate** Credential Schema to the Ledger:
```python
birth_certificate_schema = await Schema.create(government_did, 'Birth-Certificate', '0.2', ['first_name', 'last_name', 'date_of_birth', 'huduma_namba', 'fathers_first_name', 'fathers_last_name', 'mothers_first_name', 'mothers_last_name', 'home_address'], 0)
birth_certificate_schema_id = await birth_certificate_schema.get_schema_id()
```

**Local Hospital** creates and publishes a **Credential Definition** for the known **Birth-Certificate** Credential Schema to the Ledger.
```python
# Local Hospital Agent
hosi_birth_certificate_cred_def = await CredentialDef.create(hosi_did, 'HOSI-Birth-Certificate', birth_certificate_schema_id, 0)
hosi_birth_certificate_cred_def_id = await hosi_birth_certificate_cred_def.get_cred_def_id()
```
