# Lab-06: Protect Data with Hashing and Encryption

**Course:** Cyber Security Awareness Workshop  
**Course code:** C506  
**Time:** 30 minutes  
**Alignment:** LO2, LO3  
**Tool:** [Cryptography Toolkit](https://alfredang.github.io/cryptography-toolkit/)

## Scenario

A clinic must distinguish confidentiality, integrity checking and password storage when protecting mock records.

## Safety and authorisation boundary

- Use only the named training tool and the mock files in this folder.
- Do not enter real passwords, personal data, payment details or confidential information.
- Do not test any other website, network, account or organisation.
- Stop immediately if the target, data or behaviour differs from the written scope.
- Prefer reversible actions and preserve synthetic evidence.

## Mock data

- `mock-sensitive-records.csv`
- `mock-secrets.txt`

## Detailed procedure

1. Classify each mock data item by sensitivity and identify whether confidentiality, integrity or both are required.
2. Use the toolkit to hash two similar messages; compare the outputs and explain the avalanche effect.
3. Encrypt one mock record with a training-only key, then decrypt it and verify accuracy.
4. Explain why encryption keys must be separated from encrypted data and why hashing is not reversible encryption.
5. Design a key-handling checklist covering creation, storage, sharing, rotation, backup and destruction.
6. Remove any locally copied training secret after evidence capture; never enter real personal or business secrets.

## Completion standard

- Data classification
- Hash comparison
- Encrypted/decrypted sample
- Key-handling checklist
- Security explanation

## Reflection

What evidence would make you reverse your decision, and who would need to know?
