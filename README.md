> [!IMPORTANT]
> **NFID Access Attestation Data Model (2025 draft, superseded)**
>
> This repository holds a 2025 working draft that described an access attestation as a W3C Verifiable Credential with did:nfid identifiers. The Foundation's position has since changed. Its 2026 paper, *Beyond Credentials: A Trust Framework for Identity-Based Physical Access*, specifies the access attestation envelope as a presentation-time record signed with COSE_Sign1, not a credential and not a credential data model, and consumes government-issued credentials on their own trust paths. This draft is kept as a historical record and is not maintained. For the Foundation's current specifications, see https://nfid.foundation/specifications.

---

**NFID Access Attestation Data Model**

This repository contains the official specification for the NFID Foundation's Verifiable Credential (VC) schema data model, specifically designed for physical access control.

**📄 Overview**

The NFID Access Attestation is a standardized, secure, and privacy-preserving digital credential used to grant access to physical locations. It is built upon the foundation of the W3C Verifiable Credentials Data Model v2, ensuring interoperability with the broader decentralized identity ecosystem.

This data model defines the precise data structures and attributes for representing granular, time-bound, and rule-based access rights. It is optimized for use in resource-constrained environments like locks and readers, while also being fully compatible with modern web services.

**✨ Key Features**

* **W3C Verifiable Credentials Compliant**: Fully adheres to the W3C VC Data Model v2, enabling trust and interoperability.

* **Decentralized Identity (DID) Integration**: Utilizes did:nfid for issuers and holders, promoting a decentralized and robust identity system.

* **Optimized for Physical Access Control**: The data model is tailored for the unique requirements of physical security systems, including:

  * **Granular Access**: Permissions can be specified for individual access points or zones.

  * **Flexible Scheduling**: Supports a rich schedule definition, including recurring schedules and specific exceptions.

  * **Compact Binary Encoding**: A highly optimized CBOR encoding is specified for efficient transmission and processing on low-power devices.

* **Enhanced Security**: The model supports a strong cryptographic framework, including:

  * Digital Signatures for authenticity and integrity.

  * Encryption for confidentiality.

  * Robust Revocation mechanisms for handling compromised credentials.

* **Extensible**: The design allows for manufacturer-specific and future extensions to support proprietary features without breaking the core standard.

**🚀 Getting Started**

This repository primarily serves as the source of truth for the data model specification. Developers and implementers should consult the following documents:

* **NFID Access Attestation Data Model v0.1.md**: The complete, normative specification document detailing all attributes, data types, and encoding rules.

* **Section 7**: Examples: Provides a full JSON example and a conceptual CBOR example to help you understand the data model in practice.

* **Section 8**: Future Roadmap: Outlines potential enhancements and future directions for the data model.

We welcome contributions and feedback from the community to help shape the future of self-sovereign identity in physical access control.

**🤝 Contributing**
We encourage you to get involved! Please feel free to open an issue for any questions, suggestions, or bug reports. If you'd like to contribute, please refer to our CONTRIBUTING.md file for guidelines on how to submit pull requests.

**📄 License**
This project is licensed under the **Apache-2.0** License - see the LICENSE file for details.
