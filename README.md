# CS305 - Software Security
## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client for this project was Artemis Financial, a fictional financial consulting company. Artemis Financial was looking to launch a RESTful web application to allow their clients to manage their accounts online. Before they took this application live, they sought the expertise of our company, Global Rain, in identifying and mitigating external security threats. As a financial company, they have a high risk of being targeted and a vested interest in protecting their clients and infrastructure.

## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I did a good job, in this project, of identifying and describing the vulnerabilities that were present in the application. I tried to keep my descriptions short and sweet, to prevent readers from being overwhelmed. I also tried to keep my recommendations short and simple, as well, to again keep readers from being overwhelmed and discouraged.

Creating secure code is important now more than ever. As more of our daily lives--and sensitive information--move online, the stakes for keeping this data secure get higher and higher. Attackers have never had more incentive to probe software for vulnerabilities than they do today, as the payoff has never been greater. Companies must do everything they reasonably can to protect their customers' data. This is crucial, not only from a legal liability standpoint, but also from a consumer trust perspective. All it takes is one major data breach to crater your customer's confidence in your company.

## What part of the vulnerability assessment was challenging or helpful to you?
The most helpful part of the vulnerability assessment for me was learning how to use the dependency check tool. I was unaware of this tools existence prior to this course and I found it to be a great tool to add to my vulnerability testing toolkit moving forward.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The main focuses for increasing security in this application were updating dependencies, performing better input validation, and encrypting communications.
In the future, I would plan to use vulnerability assessment tools, like the dependency check tool from this course and the code security analysis plugin for Eclipse that was mentioned in our textbook. These tools combined with peer review and perhaps some penetration testing would offer a good baseline security check for a project.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the security and functionality of the code, I manually reviewed the code to look for common types of vulnerabilities. I also tried to put myself in the shoes of a potential adversary to imagine how they might approach an attack. I ran the vulnerability assessment plugin both before and after refactoring code to ensure that my changes did not introduce additional vulnerabilities.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
In the future, I plan to utilize vulnerability assessment plugins and tools like the ones we made use of in this course. I also might make use of commercial vulnerability assessment services, such as CodeScene.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The piece I'm mostly likely to show employers from this course is Project Two. This assignment would be the best showcase because it demonstrates my ability to create and manage certificates, create secure code, and encrypt data in transit.
