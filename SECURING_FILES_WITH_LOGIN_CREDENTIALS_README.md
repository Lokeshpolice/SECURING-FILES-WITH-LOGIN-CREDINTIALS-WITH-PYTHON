# 🛡️ Securing Files with Login Credentials  

### 👨‍💻 Author  
**P. Lokesh Reddy**  
📧 **reddypolicelokesh@gmail.com**

---

## 📘 Abstract  
This project focuses on securing files in cloud environments using a **hybrid cryptographic approach**. It integrates **AES, DES, and RC6 encryption algorithms** along with **file splitting** and **steganography (LSB encoding)** to provide multi-layered protection against unauthorized access. The system ensures that only authenticated users can encrypt, upload, and retrieve data securely from the cloud server, maintaining confidentiality, integrity, and trust.

---

## 🔍 Introduction  
Cloud computing has revolutionized the way data is stored and accessed but also raised concerns about privacy and security. Since cloud servers operate in distributed environments, ensuring file confidentiality is crucial.  
This project introduces a **hybrid cryptographic model** that combines symmetric and asymmetric encryption methods. By merging **AES, DES, and RC6**, along with **LSB steganography**, this system enhances protection and conceals encryption keys inside images, preventing external attacks. Users can securely upload, store, and retrieve files using their unique login credentials.

---

## 🧩 System Overview  
The system is designed to handle secure file transfer, encryption, and decryption in a cloud setup.  
Key operations include:  
- Encrypting files with AES, DES, and RC6.  
- Splitting encrypted files into fragments.  
- Embedding encryption keys within images using LSB steganography.  
- Uploading encrypted data to the cloud.  
- Allowing access only to authenticated users with valid credentials.  

This multi-level approach minimizes data breaches and unauthorized access while maintaining fast performance.

---

## 🧠 Technologies Used  

| Category | Tools & Technologies |
|-----------|---------------------|
| **Frontend** | HTML, JavaScript |
| **Backend** | Java (JSP, Servlet) |
| **Database** | MySQL |
| **Server** | Apache Tomcat 7.0 |
| **IDE** | NetBeans |
| **Development Kit** | JDK 1.7 |
| **Encryption** | AES, DES, RC6 |
| **Steganography** | LSB Encoding |

---

## ⚙️ Hardware Requirements  
- **Processor:** Intel Pentium IV or higher  
- **RAM:** 1 GB or more  
- **Storage:** 100 GB  
- **Display:** 15” VGA Color  

---

## 🏗️ System Architecture  

The system is structured into three layers:  
1. **User Interface Layer** – Handles user authentication and file management.  
2. **Application Layer** – Executes encryption, decryption, splitting, and steganography operations.  
3. **Cloud Storage Layer** – Manages encrypted file storage and retrieval.  

Data is processed securely from upload to access, ensuring end-to-end protection.

---

## 🔐 Hybrid Cryptographic Mechanism  
The core security of the system lies in combining multiple encryption algorithms:  
- **AES (Advanced Encryption Standard):** Ensures high-speed, strong block encryption.  
- **DES (Data Encryption Standard):** Adds transformation complexity to protect data patterns.  
- **RC6:** Enhances variability in encryption with adaptable block sizes.  

The keys are concealed using **LSB steganography**, embedding binary key data inside images without altering their appearance. During retrieval, hidden keys are decoded to reconstruct original files securely.

---

## 💻 Methodology (SDLC – Umbrella Model)  
1. **Requirement Analysis** – Identifying user and system needs.  
2. **Feasibility Study** – Ensuring technical and operational viability.  
3. **System Design** – Developing UML and data flow models.  
4. **Development** – Implementing modules in Java and MySQL.  
5. **Testing** – Performing unit, integration, and system-level testing.  
6. **Deployment** – Hosting on Apache Tomcat cloud environment.  
7. **Maintenance** – Continuous updates and security enhancements.

---

## 🧪 Testing & Validation  
The project is validated through multiple stages:  
- **Unit Testing:** Testing individual components like encryption and login.  
- **Integration Testing:** Checking module communication.  
- **System Testing:** Verifying full workflow correctness.  
- **Acceptance Testing:** Ensuring user requirements are satisfied.  

### ✅ Example Test Cases  
| ID | Description | Expected Result | Status |
|----|--------------|-----------------|--------|
| TC01 | File upload verification | File successfully uploaded | ✅ |
| TC02 | Encryption check | Data encrypted using AES/DES/RC6 | ✅ |
| TC03 | Steganography validation | Key embedded in image | ✅ |
| TC04 | Cloud storage retrieval | File retrieved accurately | ✅ |

---

## 📊 Results and Discussion  
The system demonstrates high data security with minimal processing delay.  
- Encryption and decryption are faster than traditional single-algorithm models.  
- Key concealment using steganography effectively prevents unauthorized extraction.  
- File splitting ensures that even if one fragment is compromised, the data remains unreadable.  
- Performance evaluation shows an improved throughput and reduced risk of breaches.

---

## 🌐 Applications  
- **Banking:** Secure transfer of customer and transaction data.  
- **Corporate:** Protecting business and confidential reports.  
- **Government:** Storing classified files securely.  
- **Academic:** Protecting student and research data.  
- **Personal Use:** Securing individual cloud-stored files.

---

## 🌟 Advantages  
- Multi-layer encryption with strong key management.  
- Hidden key embedding through steganography.  
- Robust cloud-based storage with authentication.  
- Portable, user-friendly, and efficient.  
- Open-source and easily extensible for advanced security research.  

---

## ⚠️ Limitations  
- Requires stable internet for cloud access.  
- Slight increase in processing time for large files.  
- File size grows due to encryption layers.  

---

## 🔮 Future Enhancements  
- Integration of **Single Sign-On (SSO)** authentication.  
- Adoption of **Elliptic Curve Cryptography (ECC)** for faster encryption.  
- Implementation of **Blockchain-based verification** for tamper-proof data.  
- Incorporation of **AI-based anomaly detection** for real-time threat monitoring.  

---

## 🏁 Conclusion  
The **Securing Files with Login Credentials** project delivers an effective solution for cloud file security using a combination of hybrid encryption and steganography. By merging AES, DES, and RC6 with key concealment techniques, it provides a dependable system for maintaining data confidentiality and integrity. The project highlights the importance of multi-layer encryption and access-based security in modern cloud infrastructures, making it a valuable model for real-world data protection.

---

## 📚 References  
1. Peter Mell & Tim Grace, *The NIST Definition of Cloud Computing*, 2010.  
2. Achill Buhl, *Rising Security Challenges in Cloud Computing*, World Congress on ICT, 2011.  
3. Jitendra Singh Adam et al., *Modified RSA Public Key Cryptosystem*, IJARCSSE, 2012.  
4. Tingyuan Nye & Tang Zhang, *An Investigation of DES and Blowfish Encryption Algorithm*, IEEE, 2009.  
5. Niles Maintain & Subhead Bhingarkar, *Comparative Study of Cloud Security Models*, IJCB, 2012.  

---

### 📞 Contact  
**Developed by:** *P. Lokesh Reddy*  
**Email:** *reddypolicelokesh@gmail.com*  
