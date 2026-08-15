# Awesome-Credential-Verification-Platform

# Top Credential Verification Platform Tools Ecosystem
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
- **[Trinsic](https://trinsic.id/)**  
  API-first verifiable credentials and decentralized identity platform focused on easy issuance, verification, and wallet experiences for product teams.
- **[Affinidi](https://www.affinidi.com/)**  
  Decentralized identity and data-sharing platform enabling verifiable credentials, consent-based data exchange, and privacy-preserving verification.
- **[Dock Labs](https://www.dock.io/)**  
  End-to-end verifiable credentials platform with blockchain anchoring, wallet support, and tools for issuing and verifying credentials at scale.
- **[Sphereon](https://sphereon.com/)**  
  Enterprise-focused decentralized identity and verifiable credentials solutions with strong support for open standards and federation.
- **[Validated ID](https://www.validatedid.com/)**  
  Digital identity and electronic signature platform with credential issuance and verification capabilities, particularly strong in European markets.
- **[Credly](https://www.credly.com/)** (Pearson)  
  Leading digital badge platform with a large earner network, Open Badges support, and strong employer recognition for professional credentials.
- **[Accredible](https://www.accredible.com/)**  
  Digital credentials platform supporting certificates and badges with design flexibility, analytics, LMS integrations, and Open Badges / VC capabilities.
- **[Velocity Network Foundation](https://www.velocitynetwork.foundation/)**  
  Industry network focused on trusted career and education credentials using decentralized identity principles.
- **[Hyland Credentials](https://www.hyland.com/)** (formerly Learning Objects / related offerings)  
  Digital credentialing solutions integrated into broader content and education technology ecosystems.
- **[Digitary](https://www.digitary.net/)**  
  Digital credential and diploma verification platform used by higher education institutions for secure academic record issuance and verification.
- **[Sertifier](https://sertifier.com/)** / **[Open Badge Factory](https://openbadgefactory.com/)** / **[BadgeCert](https://www.badgecert.com/)**  
  Additional platforms supporting Open Badges and verifiable digital credentials with varying degrees of standards compliance and self-serve options.

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
