# CS 305 Portfolio Submission – Artemis Financial Secure Software Report

## Overview

This repository contains my final portfolio artifact for CS 305: Secure Software Development. As a developer on Global Rain’s agile scrum team, I collaborated with Artemis Financial to modernize their web application and implement secure communication protocols. The submitted report documents the integration of checksum verification, HTTPS, certificate validation, and other secure coding practices. It reflects my ability to assess vulnerabilities, apply mitigation strategies, and deliver production-quality software aligned with real-world security standards.

## Artifact Submitted

**Artemis Financial Practices for Secure Software Report**  
(Completed in Project Two – Demonstrates secure coding practices, checksum verification, and layered security implementation)

## Reflection Responses

**1. Client Summary**  
Artemis Financial is a consulting firm that creates personalized financial plans for clients, including savings, retirement, investments, and insurance. As part of Global Rain’s agile scrum team, I was tasked with modernizing Artemis’s software and integrating secure communication mechanisms. Their public-facing web application required a file verification step using checksums to ensure data integrity during transfers.

**2. Strengths in Vulnerability Detection & Importance of Secure Coding**  
I successfully identified and mitigated vulnerabilities using OWASP Dependency-Check and schema-compliant suppression logic. Secure coding is critical to prevent data breaches, protect client information, and maintain trust. For Artemis, these improvements directly support their mission of safeguarding financial data.

**3. Challenges and Insights from the Assessment**  
One of the most challenging aspects was ensuring suppression files were properly encoded, schema-compliant, and correctly loaded by the plugin. This required careful troubleshooting and validation. It reinforced the importance of precision in configuration and the need to test suppression logic against actual CVEs.

**4. Security Enhancements and Future Assessment Tools**  
I implemented HTTPS, certificate validation, checksum verification, and static analysis to strengthen security. In future projects, I would use tools like SonarQube, OWASP ZAP, and schema validators to assess vulnerabilities and guide mitigation strategies.

**5. Ensuring Functionality and Post-Refactor Validation**  
To confirm functionality and security, I ran integration tests, validated checksum outputs, and re-scanned the codebase after refactoring. I compared pre- and post-refactor reports to ensure no new vulnerabilities were introduced and suppression logic remained effective.

**6. Tools and Practices for Future Use**  
Key tools included Maven, OWASP Dependency-Check, schema validators, and secure encoding libraries. Practices like defensive coding, explicit error handling, and version alignment will be essential in future assignments and professional work.

**7. Employer-Facing Takeaways**  
This artifact demonstrates my ability to deliver production-quality, secure software solutions within an agile team. It showcases my skills in vulnerability assessment, layered defense implementation, and documentation. Future employers will see my commitment to secure development and my ability to meet real-world client requirements.

## Repository Contents

