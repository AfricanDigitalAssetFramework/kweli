
# KWELI - PAN-AFRICAN SELF-SOVEREIGN IDENTITY

# LITE VERSION (2020-01-25)

Eddie Kago, Marvin Coleby, Melissa Powell, Kenroy George

# Abstract

A Pan-African decentralized digital identity can support economic, social and cultural trade between the continent and its diaspora. This paper proposes a framework for a mobile-first identity that can connect a digital network of hundreds of millions of people of African descent. This digital network can create economic prosperity and cultural progress for a significant part of the global population. To make this possible, there is an urgent need for a Pan-African version of decentralized identity framework. This is because new developments in artificial intelligence and distributed ledger technologies will power the Internet’s decentralized infrastructure for these digital networks.

Fundamental to this infrastructure will be a new kind of identity protocol that empowers individuals and institutions with their sovereignty to create and share their own digital identities. We argue that there is both an opportunity and urgency to build a Pan-African self-sovereign digital identity. This paper presents the patterns for the opportunity, the reasons for the urgency and a conceptual framework for a Pan-African self-sovereign identity. It is important to distinguish that by self-sovereign, we do not imply a replacement to state issued identity or that individuals self-issue civic credentials. Self-sovereign in this paper is used in the sense that individuals determine when and for what purpose their identifying credentials are used in interactions. This paper respects the role of governments and institutions as issuers of identities and the need for decentralized identity to enable individuals to manage their identities and verifiable credentials (data attached to their profiles).

A Pan-African self-sovereign identity will need both a conceptual framework and technical architecture that both aim to create digital networks for the continent and its diaspora. This paper forms the conceptual framework. It will be followed by the release of a technical paper and open source code for communities of engineers, entrepreneurs and regulators to create Pan-African digital identity systems.

# Introducing Kweli

A Pan-African self-sovereign digital identity (“Pan-African SSI”) can support economic, social and cultural trade between the continent and its diaspora. This paper proposes an open source code for a Pan-African identity called Kweli. Kweli is a Kiswahili term that denotes that something is true, the basis of trust. Kweli is an effort by the Identity Working Group of the African Digital Asset Framework to propose an identity infrastructure rooted in the Web of Trust for African peoples. Kweli is the first technological standard supported by the African Digital Asset Framework (“ADAF”), an open source platform that aims to create transnational standards for digital assets and distributed ledger technologies. The first iterations of Kweli are built in partnership with a group of organizations and with Vibranium ID, a Kenyan-based identity company and Steward of the Sovrin network.

Kweli is an open-source codebase that people, companies and governments can use to create secure digital identity applications and systems with the security of distributed ledger technologies. Kweli’s infrastructure will be built around two major components:

1.  Distributed Ledger Database - Kweli is built on Hyperledger Indy, an open-source framework for self-sovereign identity rooted on a distributed ledger database.
    
2.  Pan-African - Kweli’s infrastructure is built to support Pan-African trade and natively encodes national and regional protocols, rules and legislations throughout Pan-African communities both on the continent and in the diaspora.
    

Kweli’s objective is to support Pan-African trade across the continent and its diaspora. It is specifically built to meet the social objectives set by organizations like the African Union, Caribbean Community and the United Nations. The initial version of Kweli’s open sourced codebase is still under development and will be released in the second quarter of 2020.

The immediate objective of Kweli 1.0 is to support trade under the African Continental Free Trade Area Agreement. This version will be released with a ready-built open source codebase. The codebase will contain standardized schemas and documentation that aim to extend the rights for freedom of movement afforded to all Africans under the African Union’s constitution. Users will be able to digitize personal or corporate credentials and verify their right to freedom of movement under the rules of the African Union.

Kweli is both an idea and technological standard. This paper explains the idea. Kweli as the idea to create a new understanding of identity: a Pan-African self-sovereign digital identity where every African, regardless of their geographic origin, can seamlessly engage in commercial activity on the African continent. This concept is a natural evolution of the cultural, economic and philosophical underpinnings of the Pan-African movement. Pan-Africanism stands to politically, economically and socially unite all peoples of African descent, regardless of their geographic origin. These rights are extended to all Africans under the African Union’s constitution, and the African Continental Free Trade Agreement is built under the African Union’s constitution. Therefore the African Union grants all Africans the legal right to freely move and trade on the continent.

Kweli stands for the idea that every African person may choose to create, hold and maintain their own identity - and if they do - it will grant them the right and access to economic, social and cultural activity in Africa, one of the fastest growing continents in the world. The future of trade is rapidly digitizing and there is an urgent need to create identity infrastructure built by Africans, for Africans to engage in this trade. At the same time, there is an opportunity to accelerate Pan-African trade with digital tools for commerce - with identity being a fundamental tool.

Kweli provides a  guiding technical framework for defining standardized schemas and credential definitions to support digital trade across Pan-African countries and people. This paper explains Kweli as both an idea and technology throughout four sections. The first sections of the paper focus on both defining a Pan-African identity and arguing its necessity.  The last sections outline technical details for Kweli’s first iteration and use cases for its first pilots.

The paper further argues that a Pan-African identity refers to two major groups of people: (1) nationals, residents and citizens of countries that are Member States of the African Union (“AU”) and/or Caribbean Community (“CARICOM”); and (2) diaspora groups, people and organizations that include, but not limited to, economic migrants, descendants of the Trans-Atlantic slave trade, refugees and people that are generally of African descent. This includes a diverse group of people that may not, or have already, traced their genetic origins to the African continent. This section explains that a Pan-African self-sovereign identity like Kweli can form the infrastructure that connects diverse groups of Africans across the world to engage in global trade and commerce. Identity is fundamental to engaging in trade - and there is an unprecedented opportunity to create a truly Pan-African identity. But, there is also an urgent need to create it. The next section argues that there is both an urgency and an opportunity to create a Pan-African self-sovereign digital identity.

The African Union grants every African the right to freely engage in commercial activity on the continent of Africa. This right exists, but as long as civil identity systems are fragmented and paper-based, it will be difficult to actualize this right. Kweli is both an idea and technological standard that aims to actualize this right by providing an initial infrastructure for Pan-African self-sovereign identities.

Kweli’s vision is simple - to support a world where any African can freely trade across the continent in the click of a button. It is up to all of us to build this world. Kweli is an example of one of the stepping stones necessary to build this world.

Kweli’s first versions in 2020 will focus on a standard for credential verification for both persons and corporations on the Sovrin Network. Subsequent versions will include documentation that enables businesses to simplify cross-border trade with automated document processing and filing. This project envisions a world where Kenyan, Nigerian, Bahamian and African-American businesses can engage in a commercial transaction at the click of a button.

# Implementing a Pan-African Identity Infrastructure

A Pan-African digital identity solution should support interoperability across digital systems and enable online to offline connection. The African Digital Assets Framework proposes a Pan-African identity ecosystem that entails individuals acquiring decentralized identities embodied by SSI in a way that supports; person to person interactions, person to business interactions and business to business interactions. In such an identity ecosystem, peer to peer transactions would thrive and commerce across the African Continental Free Trade Area (AfCFTA) would grow.

A decentralized Pan-African identity ecosystem based on a blockchain, would allow individuals access to their own records in a transparent manner with persistence. Such would provide for a continuous record of an individual’s profile on/off ledger hence enabling proofs for requirements like Know-Your-Customer and Anti-Money-Laundering checks, hence improved financial access and better chances for economic opportunity.

## Open standards for Pan-African Decentralized ID

To create a functional technical framework for personal decentralized identity and organizational SSI, Kweli implements open standards and seeks to collaborate with active organizations like the W3C and the Decentralized Identity Foundation. The result would be a robust decentralized identity infrastructure on which services and tools will be built.

![](https://lh5.googleusercontent.com/EPai6TmLcAU4IRVz98O_uqNEtfLquayuPc_jfxoto6AzLDOFFvPPVWue4dadXRKV4qS1JwxpU4y8JhAoiTk5Wd6VLwSz3B7wVIFEkGSivddkthDd1Bw6Ogp0gR81iQ7Y-lVlxxWh)

SSI Relationships in Kweli

## Guidelines for a Pan-African Decentralized Identity Infrastructure

We propose an Ubuntu guided approach with the following features by design when designing solutions for Pan-African SSI.

### Guidelines

- Self-sovereign ownership - A Pan-African decentralized ID infrastructure should allow user control over how their credentials are managed.

- Openness - A Pan-African decentralized ID infrastructure should support community involvement with an open-source approach.

- Interoperability - A Pan-African decentralized ID infrastructure ought to be built on open standards of information exchange.

- Accountability - A Pan-African decentralized ID infrastructure should be clear on terms of use and clearly define responsibilities of parties involved.

- Transparency - A Pan-African decentralized ID infrastructure should embody clear mechanisms of governance built and communicated in a decentralized manner.

- Guardianship - A Pan-African decentralized ID infrastructure should provide mechanisms to support management of credentials for individuals facing restrictions on managing their identity credentials.

- Longevity - A Pan-African decentralized ID infrastructure should support lifetime persistence of identity credentials issued and managed.

- Decentralized - A Pan-African decentralized ID infrastructure should ensure identities are not managed centrally.

- Inclusive - A Pan-African decentralized ID infrastructure should provide for all individuals seeking a Pan-African ID the ability to create one regardless of political or socio-economic classification.

- Pan-African - A Pan-African decentralized ID infrastructure should be at its root Pan-African in the sense that people of African origin within Africa and in the diaspora can uniquely create a decentralized digital ID.

- Security - A Pan-African decentralized digital ID infrastructure should embody best software security practices to guarantee safety of data and trust in issued IDs.

- Privacy - A Pan-African decentralized ID infrastructure should adopt a privacy first approach, in the sense of privacy by design.

  

## Interactions within the Kweli Identity Infrastructure

As earlier described, Kweli provides a registry supporting exchange of verifiable credentials as required by the AU Movement Protocol. Kweli will provide a public registry that will define schemas for credentials defined by protocols and annexes of the AfCFTA for organizations and companies in member-states to use for transactions across borders. Kweli’s registry shall be served on a platform which creates a network of verified organizations enabling trusted business transactions, supporting trade between parties in different jurisdictions in the AfCFTA block.

The registry would hold;

-   Licensing schemas.
    
-   Business Registration schemas.
    
-   Regulatory Permits schemas.
    

As a functional Pan-African identity infrastructure Kweli proposes including the various interactions between persons to persons, persons to institutions and institutions to institutions.

1.  Government Axis: Nation-State to Nation-State interaction.
    
2.  Organization Axis: Corporate to Corporate (including agencies) interaction.
    
3.  Peoples Axis: Person to Person interaction.
    

These interactions underpin day to day transactions that people are involved with. As such, the design of Kweli supports:

1.  Management of personal credentials and associated data. This entails a person having agency over data related to their health, property or academic records.
    
2.  Intra-African trade: Know Your Customer (KYC) and Anti-money Laundering (AML) checks for e-commerce and funds transfer. Services providing KYC/AML would be built on top of the Kweli network as decentralized by design.
    
3.  Intra-African travel: ID and Passport verification at border entry points. A state issued Passport document backed by SSI would reduce unnecessary checks and support e-commerce amongst AU citizens.
    

The steps to onboarding on the Kweli registry would be:

1.  User enrolls on Kweli backed service and have SSI credentials on their wallet.
    
2.  User invokes actions based on the Protocol on Trade in Goods and the Protocol on Trade in Services to register a new business entity.
    
3.  A new business is registered and the corresponding documents are sent to the business wallet.
    

### Kweli Systems Overview

Kweli is structured as a Verifiable Organizations Network defined by credentials about organizations and businesses being provided for assertion. This could either be self asserted or asserted by an authority and the credential provided for in a public ledger where anyone can refer for verified business entities. These proofs are done in such a way that a third party is not necessary due to the concept of zero-knowledge proofs (ZKPs).

Kweli is built on Hyperledger Indy blockchain framework utilizing the Sovrin network. Indy functions as a public permissioned blockchain in that records published on the ledger are available publicly for anyone to audit but the network nodes that ensure consensus of transactions are governed by the Sovrin Foundation. Therefore, only authorized entities serve as nodes with each node holding a copy of the ledger. Records can be audited in a transparent way by stakeholders while maintaining integrity of records since only authorized entities can commit.

Stewards validate identity transactions to assure consistency about what is written on the ledger and in what order. Consensus across the nodes is maintained by a Byzantine fault tolerant algorithm. To avoid correlation of one’s user profile, the system allows for an individual to have unique identifiers for connections made when transacting with other actors within the Kweli ecosystem.

These identifiers, called Decentralized Identifiers (DIDs) are a way to identify things, people or organizations over the decentralized internet while preserving privacy and not tying the user to an identity provider. For example, when interacting with a certificate issuing authority like a university, a unique DID is created for the interaction between you and the university. When presenting the degree certificate to an employer, the university creates a unique DID connection with the employer. Relying web services reference the shared ledger to ascertain credibility of DID Documents (DID Docs).

Kweli is provisioned on a decentralized ledger network on which credential definitions are publicly available for reference. Verifiers and issuers can query the network for proofs regarding a credential to ascertain or issue it. Alongside the network, is a screening interface for businesses to check credentials they require to operate within the African Continental Free Trade Area (AfCFTA). Such credentials include licenses, permits and business registration certificates as required by the AfCFTA agreement. An implementation of the Kweli Business Registry should allow for people to search through to check businesses registered within the trade area.

Other web based services and applications can be built to interact with the ledger as Agents, through individually provisioned APIs and software development kits (SDKs).

![](https://lh6.googleusercontent.com/wEuDBd8f8Dg7ioRna0lO6sazJzkGbOEi9PWP1Xx-jJ1-YSMe9_TD7f5rPGAs825rTVUtUYX88lC2VfIt-Z3MgjQL9EshK8ww0CqFcqNSz8ZeMhiKnzSQU6SCKSDFDgF-2KsfKl3J)

Kweli Infrastructure Overview

  

### Choice of blockchain protocol

Hyperledger Indy was preferred for building Kweli since Indy is so far the most advanced blockchain based identity protocol in terms of implemented applications, community of developers and the extensibility provided by Sovrin.

Other identity protocols we explored include uPort on Ethereum and Veres One.

  

# Conclusion

Having introduced the need for a digital Pan-African identity system, the foundational work remains in ensuring a stable infrastructure which supports services to be built on top. To support international interoperability, Kweli will continue embodying open internet identity standards.

For widespread adoption of Kweli and increased applicable domains for Afro-centric enterprises and institutions, continuous user education must be a priority. User awareness shall be conducted through blog and news articles, guides with industry specific use-case summaries, guides to get started as well as audio and visual content to be distributed freely for public access.

This can only be achieved through collective community ownership by industry practitioners, early adopters and educators alike. For Kweli to become a reality and achieve practical applicability, the community around it should leverage strong partnerships with forward looking institutions in the public and private sector and development institutions whose missions align with Kweli. It is going to take a village.
