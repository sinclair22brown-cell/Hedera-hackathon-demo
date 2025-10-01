# Blockchain Certificate Verifier - Hackathon Submission

## Problem Statement
Academic certificate fraud is widespread in Africa. Employers often struggle to validate the authenticity of certificates, leading to hiring risks, loss of trust, and wasted resources. Schools also face difficulties verifying alumni records for institutions or employers.

## Our Solution
Blockchain Certificate Verifier is a decentralized system built on Hedera Hashgraph. It enables:
- **Issuers (Schools/Universities):** Upload student certificate details (student name, course, year, etc.) which are hashed and stored on Hedera.
- **Verifiers (Employers/Institutions):** Instantly check the authenticity of a certificate using its unique transaction ID/hash.

## Why Blockchain?
- **Immutability:** Certificates cannot be tampered with once stored.
- **Transparency:** Anyone with the transaction ID can verify authenticity.
- **Scalability:** Hedera allows fast and low-cost transactions, perfect for mass certificate issuance.

## Key Features
- Certificate issuance (by schools).
- Certificate verification (by employers).
- Secure and transparent records.
- Scalable across schools and institutions in Africa.

## Architecture (Simplified)
1. Frontend form → Collect certificate details.
2. Backend API → Hash details & submit to Hedera testnet.
3. Verifier tool → Input transaction ID to confirm validity.

## Potential Impact
- Eliminates certificate fraud.
- Saves schools and employers time.
- Boosts trust in African education systems.
- Scalable to government-level integrations.

## Future Extensions
- Integration with national education boards.
- QR code on each certificate for instant verification.
- Mobile app for quick access.
