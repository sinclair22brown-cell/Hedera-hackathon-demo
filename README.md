# Blockchain Certificate Verifier

## Problem
Certificate fraud is a growing issue across Africa. Many employers and schools waste time and resources verifying academic records, and fake certificates are common.

## Solution
A blockchain-powered certificate verification system built on the Hedera network. Schools can issue student certificates, which are stored as immutable records on Hedera. Employers can instantly verify the authenticity of certificates using a transaction ID or certificate hash.

## Features
- Schools issue certificates and store a hash on Hedera.
- Employers/stakeholders can verify authenticity online.
- Secure, transparent, and tamper-proof.
- Reduces fraud and builds trust in education systems.

## Tech Stack
- **Blockchain:** Hedera Hashgraph
- **Frontend:** Simple web form for issuing & verifying certificates
- **Backend (future):** Node.js or Python integration with Hedera SDK

## Impact
- Helps students prove their credentials faster.
- Protects employers from hiring fraud.
- Saves schools time on manual verifications.
- Builds trust in Africa’s education system.

## Next Steps
1. Build prototype UI for certificate issuance/verification.
2. Connect to Hedera testnet for certificate storage.
3. Deploy demo for judges to test.# Hedera-hackathon-demo
Demo repo for Hedera Africa Hackathon project ## Demo Prototype
[👉 Click here to view the prototype](./prototype/index.html)
## Demo Prototype
You can try out a simple demo of our certificate issuance and verification system.

### How to Demo
1. Open the [Prototype](./prototype/index.html).
2. In the **Issue Certificate** form, fill in a student’s name, course, and year.
3. Click **Issue Certificate**. A fake transaction ID and certificate hash will be generated.
4. Copy the transaction ID shown.
5. Scroll to the **Verify Certificate** section, paste the ID, and click **Verify**.
6. You’ll see either:
   - ✅ Certificate Verified (with student details), or  
   - ❌ Not Found (if you enter a wrong/random ID).
