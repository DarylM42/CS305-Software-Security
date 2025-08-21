# 📁 CS 305 Portfolio Artifact – Module Eight Journal

##  Repository Contents

## 📄 Submitted Artifact  
**Artemis Financial Practices for Secure Software Report**  
Completed for Project Two. Demonstrates secure coding practices, HTTPS configuration, and cryptographic hashing implementation.

---

## 📝 Journal Reflection

**1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**  
Artemis Financial is a mid-sized financial services company focused on secure digital transactions and protecting client data. They needed a secure file verification system and encrypted communication between client and server. My task was to refactor their Java application to meet secure software development standards.

**2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**  
I successfully implemented SHA-256 hashing and configured HTTPS using a PKCS12 keystore. Secure coding protects sensitive data, ensures system integrity, and builds trust with users. It also reduces the risk of breaches that could damage a company’s reputation and finances.

**3. Which part of the vulnerability assessment was challenging or helpful to you?**  
Configuring the keystore and certificate for HTTPS was challenging. It required precise file paths, encoding formats, and Spring Boot configuration. This helped me better understand secure communications and certificate management.

**4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**  
I added SHA-256 hashing for data integrity, HTTPS for encrypted transmission, and used OWASP Dependency-Check to validate third-party libraries. In future projects, I’d use SonarQube, Snyk, and threat modeling to assess and prioritize mitigation strategies.

**5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**  
I tested the REST endpoints for functionality and re-ran dependency scans to confirm no new vulnerabilities were introduced. Manual code review and browser-based testing validated both security and stability.

**6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**  
I used Maven plugin documentation, OWASP guidelines, Spring Boot SSL configuration, and modular utility classes. These resources will support future secure development tasks and vulnerability assessments.

**7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**  
I would showcase this report to demonstrate my ability to implement secure communication protocols, refactor code for compliance, and validate software integrity using industry-standard tools. It reflects my commitment to secure software development and technical precision.

---


