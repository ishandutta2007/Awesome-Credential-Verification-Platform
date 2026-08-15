# Awesome-Credential-Verification-Platform

## Top Credential Verification Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Verifiable Credentials, Digital Badges, Decentralized Identity, SSI, Open Badges & Tamper-Evident Credential Issuance/Verification*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Credential Verification Platforms**. These tools enable organizations to issue, hold, present, and verify digital credentials — including W3C Verifiable Credentials, Open Badges, professional certifications, academic records, and decentralized identity (SSI) solutions — with cryptographic integrity and selective disclosure.

**Examples** include Trinsic, Affinidi, Dock Labs, Sphereon, Validated ID, Credly, Accredible, Velocity Network Foundation, Hyland Credentials, and Digitary (the category leaders and widely used platforms).

**Open-source emphasis**: This space benefits from strong open standards (W3C VC, Open Badges, DIDs, Hyperledger Aries/AnonCreds). The section below prioritizes production-ready open-source agents, platforms, and frameworks that support self-sovereign credential ecosystems without proprietary lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Overview & Focus | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Trinsic](https://trinsic.id/)** | API-first verifiable credentials and decentralized identity acceptance platform for issuance, verification, and digital wallet integrations. | **$0.10 / verification** (Starter live credit blocks from $99/mo; volume tiers scale lower with higher commitments) | **Free Forever Test Sandbox**: Unlimited mock credential verifications, testnet DID creation, and API access with $0 transaction fees. |
| **[Affinidi](https://www.affinidi.com/)** | Decentralized identity and data-sharing platform supporting W3C VCs, consent-based exchange, and privacy-preserving verification. | **$49 / month** (Builder Plan; additional API credits at ~$0.005/credit) | **Essential Plan (Free Forever)**: 10,000 monthly Affinidi Credits and up to 100 Monthly Active Users (MAUs) for login and credential exchange. |
| **[Dock Labs](https://www.dock.io/)** (Truvera) | Verifiable credential infrastructure with blockchain anchoring on the Dock network, schema monetization, and DID management. | **$250 / month** (Production platform; Mainnet issuance at ~0.05 DOCK / ~$0.02 per credential) | **Free Forever Testnet**: Unlimited testnet DID creation, schema registration, and credential issuance via test faucet; 14-day guided evaluation trial on request. |
| **[Sphereon](https://sphereon.com/)** | Enterprise-grade SSI, W3C Verifiable Credentials, OpenID4VC/VP, and eIDAS 2.0 compliant wallet and verification infrastructure. | **€500 / month** (~$545/mo billed annually for Enterprise VDX API Gateway & developer agent licenses) | **30-Day Free Sandbox Trial**: Full access to REST APIs, test digital wallets, and eIDAS sandbox environment upon developer registration. |
| **[Validated ID](https://www.validatedid.com/)** | European digital identity, electronic signature, and SSI platform (VIDsigner/VIDidentity) compliant with eIDAS qualified credentials. | **€24.90 / month** (~$27/mo, or $10/mo billed annually for entry-level plans based on volume) | **30-Day Free Trial**: Complete feature access with up to 50 test signature and identity validation envelopes. |
| **[Credly](https://www.credly.com/)** (Pearson) | Enterprise digital badging platform with a global earner network, Open Badges standard support, and employer recognition tools. | **$2,500 / year** (~$208/month for entry organizational issuer plans with base badge volume) | **Free Forever for Earners** (unlimited badge receiving, storage, and sharing); organizations receive custom sandbox demos on request (no self-serve free trial). |
| **[Accredible](https://www.accredible.com/)** | Digital certificates and badges platform with design tooling, verification pages, LMS integrations, and Open Badges / W3C VC support. | **$45 / month** (Launch Plan, billed annually at $540/year for up to 100–250 unique recipients/year with unlimited issuances) | **Free Trial**: Full platform and design tooling access to issue digital credentials to up to 20 unique recipients. |
| **[Velocity Network Foundation](https://www.velocitynetwork.foundation/)** | Consortium-governed decentralized network ("Internet of Careers") for verifiable education and workforce credential exchange. | **$2,500 / year** (Associate / General member tier dues; token-native network usage at ~$0.02–$0.05 in $VLCT per credential transaction) | **Free Forever for Individuals/Earners** (claiming, storing, and sharing career credentials); free permanent developer Testnet access with test vouchers. |
| **[Hyland Credentials](https://www.hyland.com/)** | Enterprise blockchain-anchored credentialing platform (Blockcerts standard) for universities issuing tamper-proof diplomas and transcripts. | **$5,000 / year** (Institutional entry deployment packages with baseline student record issuance volume) | **Free Forever Verification Portal** for public verifiers and recipients; institutional pilot sandbox trial provided during evaluation. |
| **[Digitary](https://www.digitary.net/)** (Parchment / Instructure) | Higher-education academic credential and transcript verification platform used globally for tamper-evident digital records. | **$3,500 / year** (Institutional registry licenses, or student-pay platform pricing at ~$5–$15 per official transcript order) | **Free Forever for Students** (access, storage, and sharing via Digitary Core wallet); institutional guided sandbox demo on request. |
| **[Sertifier](https://sertifier.com/)** | Digital badge and certificate automation platform with skill mapping, LMS/CRM integrations, and verifiable credential tracking. | **$250 / year** (~$21/month for Pro Plan with custom branded credential portals; Enterprise from $1,200+/yr) | **Free Forever Plan**: Up to 250 unique recipients/year with unlimited credential issuance; plus a **14-day free trial** of all Pro features (no credit card required). |
| **[Open Badge Factory](https://openbadgefactory.com/)** | Modular Open Badges (1.2/2.0/3.0) and verifiable credential platform supporting badge creation, passport integration, and federation. | **€220 / year** (~$240/year for Basic Plan with up to 10 badge classes and 5,000 badges/year; Premium at €700/year) | **60-Day Free Trial**: Full Pro Plan access (up to 50,000 badges/yr, PDF certificates, API access, and reporting; no credit card required). |
| **[BadgeCert](https://www.badgecert.com/)** | Cloud-based digital credentialing and verification platform designed for professional associations, certification boards, and training bodies. | **$1,000 / year** (Bronze Plan for up to 500 badges/year; Silver Plan at $1,500/year for up to 1,000 badges/year) | **Free 1-Badge Trial Demo** via Discover portal + enterprise sandbox test environment available on request. |

## Open-Source GitHub Projects
- **[ACA-Py (Aries Cloud Agent – Python)](https://github.com/openwallet-foundation/acapy)**  
  Foundational open-source (Apache 2.0) self-sovereign identity agent maintained by the OpenWallet Foundation. Enables issuance, holding, and verification of verifiable credentials (AnonCreds and W3C VC/JSON-LD) using Aries protocols. Production-ready building block for non-mobile SSI services.
- **[CREDEBL Platform](https://github.com/credebl/platform)**  
  Open-source, open-standards-based decentralized identity and verifiable credentials platform supporting issuance, verification, and ecosystem tooling.
- **[Certo](https://github.com/schroedinger-hat/certo)**  
  Open-source platform for issuing, managing, and verifying Open Badges 3.0 (aligned with W3C Verifiable Credentials). Designed for communities, nonprofits, workshops, and events that need portable, standards-compliant credentials.
- **[Credo](https://github.com/openwallet-foundation/credo-ts)** (OpenWallet Foundation)  
  TypeScript framework for building decentralized identity and verifiable credential solutions, complementary to ACA-Py in the modern SSI stack.
- **[Bifold Wallet](https://github.com/openwallet-foundation/bifold-wallet)**  
  Extensible open-source React Native digital wallet for holding and presenting verifiable credentials.
- **[Business Partner Agent](https://github.com/hyperledger-labs/business-partner-agent)**  
  SSI wallet and controller built on ACA-Py, focused on organizational use cases for issuing, holding, and verifying credentials in B2B contexts.
- **[Sunbird RC](https://github.com/Sunbird-RC)**  
  Open-source framework for building electronic registries, attestation, and verifiable credentialing with minimal effort — widely used in public digital infrastructure.
- **Hyperledger AnonCreds** and related Indy/Aries components  
  Privacy-preserving verifiable credential implementations using zero-knowledge proofs, selective disclosure, and predicate proofs.
- **Open Badge / VC issuer and verifier libraries**  
  Community tools and SDKs for creating, signing, and verifying Open Badges 2.0/3.0 and W3C Verifiable Credentials in various languages.
- **Trust registry and federation components** (Sphereon OpenID Federation, TRAIN, and related open projects)  
  Open-source building blocks for trust lists, federation, and ecosystem governance around credentials.

### Additional Strong Open-Source Options
- Wallet SDKs and mobile agent frameworks from the OpenWallet Foundation and related communities.
- DID method implementations (did:web, did:key, did:ion, did:indy, etc.) and universal resolver tools.
- C2PA / content credentials libraries for media provenance (adjacent but relevant to verifiable claims).
- Academic and public-good credentialing pilots built on ACA-Py or Sunbird RC.
- Integration of open credential platforms with open LMS or SIS systems for education use cases.

**Frameworks for building custom systems**: Start with **ACA-Py** (or **Credo**) as the core agent for issuance and verification, add an open wallet (**Bifold**), use **Certo** or custom issuers for Open Badges 3.0 / W3C VC, and optionally layer **Sunbird RC** for registry and attestation needs. This produces a fully standards-based, self-sovereign credential ecosystem under your control.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Credential verification platforms should be evaluated for standards compliance (W3C VC, Open Badges 3.0, DIDs), privacy features (selective disclosure, ZKPs), interoperability, wallet support, revocation mechanisms, and long-term verifiability.
- Open-source SSI stacks provide maximum transparency and control but require expertise in cryptography, key management, and protocol implementation. Always validate legal and regulatory acceptance of issued credentials in your jurisdiction.
---
**Made for identity architects, education and certification bodies, HR and talent platforms, and anyone who wants portable, privacy-preserving, and standards-based digital credentials.**
Let's make verifiable credentials more open, interoperable, and free from proprietary silos.
