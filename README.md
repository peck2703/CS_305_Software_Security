# CS_305_Software_Security
CS Portfolio for Software Security

•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial has a web-based application that follows the RESTful framework, who is looking to apply the latest and most effective security methods for its application. Artemis Financial is looking to overcome any and all security vulnerabilities that can be identified and patched over.

•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

After an initial assessment of the application code base that was given to our team, a Maven dependency report generated around 250 possible vulnerabilities, and after reviewing said vulnerabilities, it was quite clear that many of the vulnerabilities could have been fixed by using the most current package versions of each dependency. By using the most current package version for these dependencies, you can fix the known vulnerability that these dependencies have if the owner of the package is aware of the vulnerability and thereby patched it, thereby reducing the workload on the developer in terms of attempting to secure an unsecure vulnerability.

•	Which part of the vulnerability assessment was challenging or helpful to you?

The challenging part of the vulnerability assessment report was just getting the report to generate. This project code base was riddled with issues and build issues, because the code base was several years past the current acceptable build version. It took several hours of Internet research to resolve all build issues while running instances through multiple Java SDK versions to see which version runs a successful build.

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

We increase the layers of security by adding levels of encryption or decryption, using Secure Socket Layers (SSL) and using the appropriate HTTPS annotations when writing the code. When encrypting data, we encrypt the data at rest and in transit and decrypt the data when you can correctly identify an appropriate certificate authored by the company or by a defined Certificate Authority.

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After reviewing the vulnerability assessment report that the build generated, and then after updating the outdated packages to their most current version, the majority of the known vulnerabilities were patched over and the remaining few could be mitigated by well written code that follows the National Vulnerability Databases guidelines assessment of the known vulnerability and use that knowledge to mitigate the vulnerability yourself.

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Using the Internet was crucial to this task, but mostly for solving the issues with the old build version and Java SDK errors. Also checking on the NVD and the Common Vulnerability and Exposures (CVE) was important to analyze each of the known vulnerabilities and ways to mitigate these risks.

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think the most important thing that this assignment reveals to employers is how to solve problems that you don’t anticipate. Being able to think on your feet or how to conduct your own research to solve problems is more important than just following a checklist of sub-tasks.
