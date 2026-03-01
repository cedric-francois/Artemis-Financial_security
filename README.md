# Artemis-Financial_security
Secure software development and vulnerability assessment project for Artemis Financial

### Client Summary and Software Requirements
Artemis Financial is a company that provides financial planning services including savings management, wealth planning, retirement preparation, and financial analysis. Because the company handles highly sensitive personal and financial data, secure communication and data protection were critical software requirements. The primary issue the company wanted addressed was improving the security of its web application and REST API to prevent threats such as data interception, unauthorized access, and exploitation of vulnerable software components. My role was to analyze the system, identify vulnerabilities, and recommend secure solutions to strengthen the application.

### Identifying Security Vulnerabilities
One area I performed well in was identifying security risks through both manual review and automated static testing. I analyzed the application and discovered issues such as unsecured API endpoints, weak cryptographic practices, inconsistent input validation, and outdated third-party dependencies. Secure coding is important because financial applications store confidential client data, and vulnerabilities could lead to data breaches, financial loss, and damage to company trust. Software security adds value by protecting business operations, maintaining customer confidence, and supporting regulatory compliance.

### Challenges and Helpful Learning Experiences
The most challenging part of the vulnerability assessment was understanding how different vulnerabilities connect to real-world attack scenarios, such as man-in-the-middle attacks or dependency exploits. However, this was also the most helpful learning experience because it improved my ability to think like a security analyst rather than only a developer. Learning how vulnerabilities can originate from external libraries was especially valuable.

### Increasing Layers of Security
I increased layers of security by recommending authentication and authorization controls, enforcing HTTPS communication using modern TLS encryption, improving input validation, and updating vulnerable dependencies identified during static testing. In the future, I would continue using tools such as OWASP Dependency-Check, static code analysis, and vulnerability databases to assess risks and determine mitigation strategies. Layered security reduces the likelihood that a single weakness can compromise the entire system.

### Ensuring Functionality and Security
To ensure the software remained functional and secure, I verified application behavior after implementing recommended changes and reviewed dependency-check results to confirm vulnerabilities were reduced. After refactoring, I reassessed the application using static testing tools and manual inspection to ensure no new vulnerabilities were introduced while improving security.

### Resources, Tools, and Practices Used
Resources and tools used during this project included:
- OWASP Dependency-Check Maven plugin for static vulnerability scanning
- Manual code review techniques
- Secure coding principles
- Encryption and secure communication practices
- Dependency management and version updates

These tools and practices will be useful in future software development and cybersecurity projects.

### Demonstrating Skills to Future Employers
This project demonstrates my ability to perform a vulnerability assessment, analyze software risks, and apply secure software development practices. Future employers could review this artifact as evidence of my understanding of DevSecOps concepts, secure coding techniques, and my ability to improve application security while maintaining functionality.
