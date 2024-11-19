# Cryptographic Concepts

| **Concept**              | **Aspect**                | **Details**                                                                                                                                       |
|--------------------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Non-Repudiation**       | **Description**           | Uses asymmetric encryption (public/private key pairs) to bind actions to specific individuals.                                                   |
|                          | **Example**               | If a user signs a contract digitally with their private key, only their corresponding public key can validate the signature. This prevents them from denying that they signed it. |
| **Proof of Integrity**    | **Description**           | Uses hash functions (e.g., SHA-256) to generate a unique identifier (digest) for a set of data.                                                    |
|                          | **Mechanism**             | If any part of the data changes, the hash changes completely due to the avalanche effect.                                                         |
|                          | **Use Case**              | Useful in verifying files or messages haven’t been altered in transit.                                                                            |
| **Proof of Origin**       | **Description**           | Combines digital signatures with public-key infrastructure (PKI) for authentication.                                                             |
|                          | **Mechanism**             | The sender’s identity is verified by signing the data with a private key and verifying it with the public key. Public keys are distributed and verified through digital certificates issued by trusted Certificate Authorities (CAs). |
| **Hashing**               | **Description**           | A one-way function that converts input data into a fixed-length string (digest).                                                                  |
|                          | **Common Algorithms**     | SHA-256, SHA-1, and MD5 (though MD5 and SHA-1 are considered weak for secure applications).                                                      |
|                          | **Properties**            | Hashing is non-reversible; it's computationally infeasible to retrieve the original data from the hash, ensuring data security.                  |
| **Digital Signatures**    | **Description**           | Uses a private key to encrypt the hash of the message, creating a digital signature.                                                               |
|                          | **Verification Mechanism**| Only the corresponding public key can decrypt the signature, verifying it was signed by the private key holder.                                   |
|                          | **Common Algorithms**     | RSA, DSA/ECDSA cryptographic algorithms.                                                                                                           |
| **Verifying a Signature** | **Description**           | The recipient uses the sender’s public key to decrypt the digital signature and retrieve the hash.                                                |
|                          | **Verification Process**  | The recipient hashes the original message on their side and compares it with the decrypted hash. Matching hashes confirm that the message is authentic and unaltered. |
