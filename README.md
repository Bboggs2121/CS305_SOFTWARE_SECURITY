# CS305_SOFTWARE_SECURITY

Q: Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
A: The client company was Artemis Financial, a consulting company that develops individualized financial plans for its customers. Artemis Financial wanted to modernize its operations and utilize the most current and effective software security. Artemis Financial operates a public web interface and they were seeking expertise on how to protect their clients' personal and financial information. 

Q: What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?
A: I feel that I did well in identifying security vulnerabilities from the code by carefully analyzing and documenting the dependency check report results. Secure coding is a crucial component of software development. Secure coding practices help protect the software from vulnerabilities that can be exploited by attackers, including data breaches, unauthorized access, and DoS attacks. Software securiy brings a company such as Artemis Financial more trust from its clients, overall protection of assets, and peace-of-mind when transacting with users. 

Q: Which part of the vulnerability assessment was challenging or helpful to you?
A: In the beginning, the manual review of the code for vulnerabilities was challenging due to the lack of familiarity with the code itself. As the course progressed, the code became easy to review and identify potential security vulnerabilities. 

Q: How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
A: With the use of static testing tools, I was able to identify security vulnerabilities and address them with the use of CVE identification and utilizing potential mitigation strategies labeled within the report. In the future, I would utilize both static and dynamic testing of the code to identify potential security vulnerabilities and address them both as the code is written, and in review. 

Q: How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? 
A: After a manual review of the code, the dependency check tool was implemented to run a static test on the code itself. Once the dependency check report was generated, it was simple to identify the presence of vulnerabilities and mitigate them as needed. Manual testing of the applications performance was completed, ensuring that proper error handling was implemented and logbacks were not being experienced through the use of the server. To ensure new vulnerabilities were not introduced, the dependency check report after corrections was compared with the original, prior to any code refactoring. False positives were addressed and eliminated to ensure the dependency check report reflected actual results. 

Q: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
A: The OWASP dependency check maven tool was very helpful throughout the assignments in this course and I will utilize that in the future to assist me in future tasks or assignments.

Q: Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
A: I would show my ability to refactor code that contains security vulnerabilities and my documented process flow of analyzing the dependency check report, removing false positives, and addressing the present vulnerabilities and mitigating them. 
