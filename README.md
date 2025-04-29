
# RSA Cryptosystem Project

This repository contains a complete RSA (Rivest–Shamir–Adleman) cryptosystem implementation in Python, developed for the CS1702 Network Security Assignment. It includes key generation, encryption/decryption functionality, a technical report, and result analysis.
---

## Project Structure

```
RSA_Cryptosystem/
├── Code/
│   └── RSA_CS22B1040_Implementation.py   # Python implementation of RSA
│
├── Report/
│   └── RSA_CS22B1040_Report.pdf          # Detailed project report
│
├── Result/
│   └── RSA_CS22B1040_Results.png         # Output visualization or encryption result screenshot
│
└── README.md                             # Project description and instructions
```

---

## About RSA

**RSA (Rivest-Shamir-Adleman)** is an asymmetric cryptographic algorithm used for secure data transmission. It is widely used in digital security systems and underpins many secure protocols.

RSA uses two keys:
- **Public Key (e, n)** to encrypt messages.
- **Private Key (d, n)** to decrypt them.

The security of RSA lies in the computational difficulty of factoring large prime products.

---

## Features

- RSA Key Pair Generation
- Encryption of plaintext messages
- Decryption of ciphertext back to original message
- Message chunking for handling long messages
- Includes technical documentation and result visualizations

---

## How to Run the Code

### 1. Clone the Repository
```bash
git clone https://github.com/09Srinivas2005/RSA_Cryptosystem.git
cd RSA_Cryptosystem
```

### 2. Run the RSA Program
```bash
python Code/RSA_CS22B1040_Implementation.py
```

Follow the prompts to input your plaintext message and see encrypted and decrypted results.

---

## Report

The complete technical explanation of RSA is provided in the [`Report/RSA_CS22B1040_Report.pdf`](Report/RSA_CS22B1040_Report.pdf). It covers:
- Overview of RSA
- Methodology (Key Generation, Encryption, Decryption)
- Applications of RSA
- Keyspace and security analysis
- Conclusion

---

## Result

An example result of RSA encryption and decryption is available in the [`Result/RSA_CS22B1040_Results.png`](Result/RSA_CS22B1040_Results.png) file.

---

## Applications of RSA

- Secure email communication (PGP)
- Digital signatures
- SSL/TLS certificates
- Secure authentication
- Blockchain wallets and identities

---

## Security Considerations

- Key lengths of 2048 bits or more are recommended for modern applications.
- RSA is theoretically vulnerable to quantum attacks (e.g., Shor's algorithm).
- Use padding schemes like OAEP in production for added security.

---
