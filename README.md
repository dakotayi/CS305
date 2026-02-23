# CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that creates individual financial plans. These plans include savings, retirement, investment, and insurance. My job at Global Rain was to address security and vulnerability concerns with Artemis Financial's application.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I feel like I successfully reviewed outdated dependencies and created mitigation plans to combat those vulnerabilities. Additionally, I was able to successfully analyze the application's configuration and verify the TLS implementation. It is important to code securely to protect sensitive client data, prevent unauthorized access and compliance risks. This adds the value of the comapny's reputation and reinforces long-term stability of the company.

Which part of the vulnerability assessment was challenging or helpful to you?
The most challending part of the vulnerability assessment was determing the false positives. Manually going through the application to determine the false positives proved difficult because you had to determine if the conditions of those vulnerabilites were applicable. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by implementing HTTPS with a self-signed certificate and generated a secure checksum using SHA-256. I additionally validated that the application updated outdated dependencies when discovered. In the future I would continue to use the OWASP Dependency Check, static code analysis, and enforce industry standards like NIST. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made certain that the code and software application were functional and secure through the checksum validation and that the HTTPS configuration was properly enforced. Then I re-ran the dependency check to ensure no new vulnerabilities were created because of the changes I made. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I heavily relied upon documentation from Oracle, NIST, and OWASP throughout this course and will be relying on them throughout the remainder of my courses.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show future employers the successful implementation of checksum verification, HTTPS configuration, and the self signed certificate. This can help showcase my basic understanding of security standards and how to test an application's security.
