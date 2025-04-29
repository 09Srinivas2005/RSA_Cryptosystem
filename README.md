
# 🔐 RSA Cryptosystem Project

This repository provides a complete implementation of the RSA cryptographic algorithm using Python. It includes the source code for RSA key generation, encryption, and decryption, as well as a detailed technical report and results for evaluation.

---

## 📁 Project Structure

```
RSA-Project/
├── Code/
│   └── rsa_code.py             # Python implementation of RSA
│
├── Report/
│   └── RSA_Cryptosystem_Report.pdf  # Detailed project report
│
├── Result/
│   └── result_image.jpg        # Output visualization or encryption result screenshot
│
└── README.md                   # Project description and instructions
```

---

## 🧠 About RSA

**RSA (Rivest-Shamir-Adleman)** is an asymmetric cryptographic algorithm used for secure data transmission. It is widely used in digital security systems and underpins many secure protocols.

RSA uses two keys:
- **Public Key (e, n)** to encrypt messages.
- **Private Key (d, n)** to decrypt them.

The security of RSA lies in the computational difficulty of factoring large prime products.

---

## 🚀 Features

- RSA Key Pair Generation
- Encryption of plaintext messages
- Decryption of ciphertext back to original message
- Message chunking for handling long messages
- User-friendly command line interface
- Includes technical documentation and result visualizations

---

## 🛠️ How to Run the Code

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/RSA-Project.git
cd RSA-Project
```

### 2. Run the RSA Program
```bash
python Code/rsa_code.py
```

Follow the prompts to input your plaintext message and see encrypted and decrypted results.

---

## 📚 Report

The complete technical explanation of RSA is provided in the [`Report/RSA_Cryptosystem_Report.pdf`](Report/RSA_Cryptosystem_Report.pdf). It covers:
- Overview of RSA
- Methodology (Key Generation, Encryption, Decryption)
- Applications of RSA
- Keyspace and security analysis
- Conclusion

---

## 📸 Result

An example result of RSA encryption and decryption is available in the [`Result/result_image.jpg`](Result/result_image.jpg) file.

---

## 📌 Applications of RSA

- Secure email communication (PGP)
- Digital signatures
- SSL/TLS certificates
- Secure authentication
- Blockchain wallets and identities

---

## 🔐 Security Considerations

- Key lengths of 2048 bits or more are recommended for modern applications.
- RSA is theoretically vulnerable to quantum attacks (e.g., Shor's algorithm).
- Use padding schemes like OAEP in production for added security.

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repo and submit pull requests for improvements or new features.

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## ✍️ Author

**Lakshmi Srinivas Panchananam**  
B.Tech Computer Science, NIT Puducherry  
Email: [your-email@example.com]
