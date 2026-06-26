# CS-305-Software-Security
Projects completed for SNHU CS 305: Software Security.
# CS 305 – Software Security Portfolio

## Artifact

For this course, I chose to include my **Artemis Financial Practices for Secure Software Report**. This project demonstrates my ability to improve the security of an existing Java application by implementing secure coding practices, HTTPS communication, SHA-256 hashing, SSL certificates, and security testing.

## Reflection

### Briefly summarize your client, Artemis Financial, and its software requirements.

The client for this project was Artemis Financial, a company that develops personalized financial plans for its customers. Because the company stores and transfers sensitive financial information, they wanted to improve the security of their web application. My job was to identify security weaknesses, implement secure communication using HTTPS, generate a self-signed certificate, add checksum verification with SHA-256 hashing, and verify that the application remained secure after the changes were made.

### What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company?

One thing I did well was carefully reviewing the application and following secure coding practices throughout the project. I used OWASP Dependency-Check to identify known vulnerabilities and verified that my own code changes did not introduce new security issues. Writing secure code is important because it helps protect sensitive information, reduces the risk of cyberattacks, and builds trust with users. Strong software security also helps companies avoid data breaches, financial losses, and damage to their reputation.

### Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of this project was configuring HTTPS and generating the SSL certificate because it required several different tools and configuration steps. However, working through those challenges gave me a much better understanding of how secure communication works. I also found OWASP Dependency-Check very helpful because it automatically identified known vulnerabilities in third-party libraries and helped me understand the importance of keeping dependencies updated.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased the application's security by enabling HTTPS, creating a self-signed SSL certificate, implementing SHA-256 checksum verification, and using static analysis to review project dependencies. In the future, I would continue using tools such as OWASP Dependency-Check, code reviews, vulnerability scanners, and current security best practices to identify risks and determine the most appropriate mitigation strategies.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After making changes to the application, I ran the program to verify that it functioned correctly and confirmed that the HTTPS connection and SHA-256 checksum generation worked as expected. I also performed another OWASP Dependency-Check scan to make sure my changes did not introduce additional security vulnerabilities. Reviewing both the application output and the dependency report helped verify that the software remained functional and secure.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Throughout this course, I used Java Keytool, OWASP Dependency-Check, Maven, Eclipse, Spring Boot, and SHA-256 hashing. I also practiced secure coding principles, dependency management, static testing, and secure communication using HTTPS. These tools and techniques will continue to be valuable in future software development and cybersecurity projects.

### What might you show future employers from this assignment?

I would show future employers this project because it demonstrates my ability to analyze software for security risks, implement secure communication, generate SSL certificates, perform vulnerability testing, and apply secure coding practices in a real Java application. It also shows that I can troubleshoot technical problems and use industry-standard security tools to improve an application's overall security.
