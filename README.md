# Artemis-Financial

##Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a company that specializes in creating individualized financial plans for their customers. As a financial corporation they have to be especially attentive when it comes to security due to the sensitive data they require from their customers. As such they have hired our company to modernize their API and applications with the latest security measures and to make sure that the software is free from any critical vulnerabilities which may impact their customers.

##What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think I did a good job of implementing the hash algortihm and securing their webpage via HTTPS. I also did a good job of detailing all the issues I found in their code in a readable and clearly understandable manner so that they can be dealt with promptly and without much hassle. It is very important to code securely especially when you are dealing with financial data since this can greatly impact the livelihoods of the clients who rely upon your services and any vulnerability or oversight can lead to drastic consequences. If a company is able to handle software security in a responsible manner it not only helps their reputations from the customers perspective it can also lead to greater cost savings as intrusions can be very expensive to deal with and recover from especially if your service is handling sensitive data. Not only can you be fined you will also lose customer trust and this can lead to less overall revenue.

##What part of the vulnerability assessment was challenging or helpful to you?

The most challenging part for me was getting the OWASP dependency check to work right since I had trouble figuring out how to run the check in the first place due to some problems I had with the Spring framework being used. The most helpful part was probably the HTTPS implementation because this can be very useful to know when you are coding for a company.

##How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

For this project we increased layers of security by first focusing on what vulnerabilities already existed and diagnosing those accurately and then adding onto that by implementing data integrity measures like the checksum and client/server secuirty via the HTTPS. I will definitely be using the OWASP tool the most becuase I found it to be a relatively reliable and convenient tool to use to make sure the that all my dependencies in my code base are up to date and secure.

##How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

First I did an automated check with the OWASP Dependency check by including the latest version (8.2.1) into our code base and analyzing the results. After that I did a manual check of the code by looking over it for any syntax or logical errors and fixing anything that seemed like it would cause a problem. Lastly, I ran the code to see if any errors occurred. After refactoring the code I repeated the same process and fixed any issues that popped up in any of the previous steps.

##What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The most useful tool in this whole class was the OWASP dependency check. I also used the documentation for Oracle in regards to different encryption algorithms and also used my old udemy Security + course that I still had saved in order to fill in some gaps I had in my knowledge about crypotgraphy and security in general. I think all of these will be helpful in the future since software security is always a top priority considering how common intrusions and ransomware are.

##Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think I will show them the final report I compiled for this class as it provides a useful summarization of all the practices we learned and also provides details about what steps I took in order to secure the code. I think this will the best showcase for future employers as it provides a good degree of detail about everything we learned in this course along with a general overview of the class as a whole.
