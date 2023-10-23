# CS-305-Software-Security

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client was Artemis Financial, a consulting company that makes individualized financial plans for their customers. Artemis Financial has a RESTful web application programming interface and was seeking our help to identify any software vulnerabilities in their application. Additionally, they wanted 

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I did a good job of thoroughly addressing and describing the vulnerabilities I found. Secure coding is extremely important when developing software. By coding securely, we can reduce the amount of vulnerabilities in our system. This should be important to companies for many reasons. Software vulnerabilities can put our systems at risk of being damaged or leaking sensitive data. Either case could result in added expenses for the company to fix the system. Additionally, failing to comply with data privacy regulations could result in fines, lawsuits, and damage the trust of our customers.

# What part of the vulnerability assessment was challenging or helpful to you?
One challenge I had was determining false positives when conducting dependency checks. I had not used dependency check reports previously so I found it difficult to understand why false positives occurred and how to identify them. However, I also think it was helpful learning how to use dependency checks. Dependency checks are a great tool for analyzing the security of the dependencies in our software.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The areas of security I addressed were cryptography, secure distributed composing, and code quality. First I created a self-signed certificate to use for a Secure Sockets Layer connection. With this certificate, I created an HTTPS connection using Tomcat. When assessing vulnerabilities, I would use the National Vulnerability Database or Common Vulnerabilities and Exposures to find techniques for mitigating these vulnerabilities. Additionally, I would use OWAPS Secure Coding Guidelines to ensure I properly address the vulnerability.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
When searching for vulnerabilities I ran a dependency check using the OWASP Dependency Check for Maven as well as performing manual code reviews. When performing a manual code review I would consult the OWASP Secure Coding Practices Checklist to find areas of the code that could be secured further. After refactoring the code I would repeat this process. Software security is a recursive process as we should reassess the software every time we refactor the code to ensure we have not added new vulnerabilities.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Some tools and resources I used that could be helpful for future projects are the OWASP Dependency Check for Maven, Java Security Standard Algorithm Names, the Oracle Key and Certificate Management Tool, and the OWAPS Secure Coding Practices Checklist.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would most likely show future employers that I have experience using these tools and resources. While I still have very limited experience when it comes to software security I think being exposed to using these tools and resources serves as a good foundation. There are so many different ways our systems can be vulnerable so using tools and resources to aid our assessment is crucial for covering the security of an entire system.
