# THM-MERRY-CLICKMAS
what am i doing by the way
____________________________________________________________________________________________________________________________________________________________________________________________________________________

# TASK 1 - Introduction
In this task, you will be part of the TBFC local red team with the elves Recon McRed, Exploit McRed, and Pivot McRed. You will help them plan and execute their phishing campaign. It is time to see if more cyber security awareness training is required.

Learning Objectives:
-Understand what social engineering is

-Learn the types of phishing

-Explore how red teams create fake login pages

-Use the Social-Engineer Toolkit to send a phishing email

# TASK 2 - EXERCISE
_Setting up the VPN : using the Linux instead of AttackBox.
;setupissuccesfull
<img width="935" height="907" alt="Screenshot 2026-01-04 220609" src="https://github.com/user-attachments/assets/a3c3e225-0cba-4d4c-a922-f6a732b13ebe" />

ATTACK IP ADDRESS: 192.168.217.70 [VPN]
<img width="808" height="105" alt="image" src="https://github.com/user-attachments/assets/9df8eb35-367b-435c-b012-e1e802296819" />


Questions Asked:
1. Sent email to factory@wareville.thm
2. How to deliver the email: Use your own server or open relay
3. From address: We know that the guys at the toy factory communicate regularly with Flying Deer, the shipping company, so that we will use updates@flyingdeer.thm as the source email address

4. Name: Let’s use the name Flying Deer
5. Username for open-relay:  Leave it blank + Enter.
6. Password for open-relay: Leave it blank + Enter.
7. SMTP email server address: 10.49.181.191
<img width="1582" height="297" alt="image" src="https://github.com/user-attachments/assets/3b41d16e-abe5-4f24-9b3d-82aa8044ee31" />

Port number for the SMTP server: Default 25 + Enter key.
The next set of questions will ask if you want to send it as a high priority or attach a file.

Flag this message as high priority: no
Do you want to attach a file: n
Do you want to attach an inline file: n
Finally, we pick an email subject and enter the message contents in plaintext or HTML.

Email subject: We need to think of something convincing, for example, “Shipping Schedule Changes”
<img width="944" height="414" alt="Screenshot 2026-01-04 212633" src="https://github.com/user-attachments/assets/2d8cd573-cff5-400a-acf7-be1826d010cc" />

MESSAGE SENDS SUCCESFULLY.
to the RoundCube Webmail.
<img width="944" height="606" alt="Screenshot 2026-01-04 214223" src="https://github.com/user-attachments/assets/d349aed6-ea7c-48a6-b401-8f8d39627ac3" />

-----------------------------------------------------------------------------------------------
Question:

A.What is the password used to access the TBFC portal?

Answer: unranked-wisdom-anthem

B.Browse to Target-IP from within the AttackBox and try to access the mailbox of the factory user to see if the previously harvested admin password has been reused on the email portal. What is the total number of toys expected for delivery?

Answer: 1984000

