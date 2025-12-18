# CS305-Software_Security
SNHU CS 305 Software Security 

1. Briefly summarize your client, Artemis Financial, and it's software requirements. Who was the clinet? WHat issue did the companhy want you to address? 

Artemis Financial is a company primarily focused on consulting that develops financial plans (savings, retirement, investments, insurance) unique to each of it's customers. They have reached out to us at Global Rain for better software security protection. We were asked to look for vulnerabilities in their system and then implementing fixes to mitigate them. 

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

When I realized that many of the libraries  in their system were out of date, I looked into what the best and most updated/secure options available and updated them in the program. It is important to code securely so you don't get sloppy and accidentally leave vulnerabilities open, like leaving passwords or passkeys in the code where a hacker could use them to gain access to sensitive financial information. 
Software security adds so much value to a company's well being. First, it helps build their brand and establishes trust with customers, showing they are a reputable and safe organization. It also protects proprietary information. Finally, it's more cost effective to maintain good security upfront rather than cleaning up a breach later. 

3. Which part of the vulnerability assessment was challenging or helpful to you?

For me part 5 of Project Two, Secondary Testing, was the most difficult. When I tried to run that dependency-check I kept getting a build fail error because the tool couldn't connect to the NVD. After a lot of trial and error, I finally realized the version specified in the pom.xl file was outdated. Once I updated it to the newer version laid out in our class Resources, the dependency check ran successfully- THANK GOD! 

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by first adding a checksum verification using SHA-256, and then used HTTPS to encrypt connections. I also updated the outdated libraries. 

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure that the software app was working I ran the refactored code. Then I used the dependency check to check for other vulnerabilities in the report. 

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I think that using SHU-256 for checksums and the owasp dependency check would definitely we helpful in the future to catch vulnerabilies in programs early on. 

7.  Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignmnet I could demonstrate to employers that I know how to use checksums, HTTPS, update old libraries, and use owasp dependency checks. 
