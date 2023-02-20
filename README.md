# CS-305
## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a company that provides financial advice to clients. They wanted us to create a secure website with certificates, a cipher, and HTTPS.
## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I did best with adding the SHA-256 cipher. It is important to code securely to minimize vulnerabilities. Coding securely creates less vulnerabilities that can be missed during code revision. Software security is a boon to a company's reputation. No one wants to work with a company with known security issues, while clients would feel safe working with a company that has a reputation for good security.
## What part of the vulnerability assessment was challenging or helpful to you?
Learning how to generate self-signed certificates was something that will definitely come in handy, however I struggled with implementing them.
## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by adding a cipher, HTTPS, and used certificates to confirm the site was the real deal. I also used a dependency check to identify vulnerabilities in the dependencies. All of the previously mentioned layers are important for software security, and I would use all that apply to whatever I am working on.
## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made sure to check the localhost port to assure that the application was working properly. I performed a dependency check before and after I refactored the code and compared the results. 
## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Self-signed certificates, ciphers, and dependency checks are all things I learned about in this course that I know will be useful to me in the future.
## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show the addition of a cipher. Knowing how to encrypt may seem trivial or basic to some, but it is an important security feature that is useful to know.
