# Encryption Techniques
## Learning objectives
- Understand cryptography basics.
- Differentiate between symmetric and assymetric encryption.
- Learn hashing and digital signature concepts.
## Cryptography
Cryptography is a technique of securing information and communication using codes to ensure confidentiality, integrity and authentication
 ## Symmetric Encryption
- Uses one key for both encryption and decryption 
- Fast, suitable for bulk data encryption.
## Asymmetric Encryption
- Uses two keys: Public key (for encryption) and Private key (for decryption).
- Used for secure key exchange and digital communication.
## Hashing 
- Converts data into a fixed-length string
- One-way process - cannot be reversed
- Used for password storage and integrity checking.
- Common Algorithms: SHA-256, MD5 (deprecated)
## Digital Signatures and Certification 
- Ensure authenticity and non-repudiation
- A digital signature uses private key to sign data and public key to verify.
- Certificates (X.509) are issued by certificate Authorities (CAs) for trust verification (used in HTTPs)
## Example
When visiting https://bank.com
- Browse verifies certificate signed by CA tom ensure authencity.
