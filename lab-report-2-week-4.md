# **Week 4 Lab Report 2**
---

# Code Change One: *A File With An Open Parenthesis*
- Screenshot of the *code change* from **Github**: 
![image](CodeChange1.png)

- [Click Here](https://github.com/hhundhausen/markdown-parse/commit/f0c2ad90724fe02d9e647ab3ade0b4b8b8c3160b) to access the link to the test file for a *failure-inducing input* that prompted the code change!

- Screenshot of the *symptom* of the failure-inducing input: 
![image](Fii_1.png)


- In this computer program, the failure-inducing input was a file with an open parenthesis at the end (shown in the screenshot above). For better reference, here is an example:  ```[link](print.com```
* * Yet, this input caused a bug in the computer program to execute, which was that it did not have the correct syntax for a file. Thus, the bug made a faulty symptom in the program behavior to be an output of an infinite loop.

# Code Change Two: *A File With An Image Reference* 
- Screenshot of the *code change* from **Github**: 
![image](CC2.png)

- [Click Here](https://github.com/hhundhausen/markdown-parse/commit/fc66a3fd7e838833d1364a7b26ea1be939d94948) to access the link to the test file for a *failure-inducing input* that prompted the code change!

- Screenshot of the *symptom* of the failure-inducing input: 
![image](Fii_2.png)


- In this computer program, the failure-inducing input was a file with an image reference (shown in the screenshot above). For better reference, here is an example: ```![image](print.png)```
* * Yet, this input caused a bug to excute because it had the wrong syntax. Furthermore, the input and bug made the program produce a symptom to appear which was an incorrect output; printing the image name with the other link names.


# Code Change Three :  *A File That Uses [] and (), But Very Far Apart*
- Screenshot of the *code change* from **Github**: 
![image](CC3.png)

- [Click Here](https://github.com/hhundhausen/markdown-parse/commit/decb1c81008ef03d0367d92e36876aecb25f0efe) to access the link to the test file for a *failure-inducing input* that prompted the code change!

- Screenshot of the *symptom* of the failure-inducing input: 
![image](Fii_3.png)


- In this computer program, the failure-inducing input was a file that used a pair of brackets **[]** and a pair of parenthesis **()** but was very spaced out from each other (this is shown in the screenshot above). For better reference, here is an example: ```[link]                  (spaces)```
* * Yet, this input caused a bug because the syntax for a link was incorrect. Furthermore, the program executed a similar behavior to the program above, which outputted the syntactically incorrect link along with the correct links. Thus, the symptom of having an incorrect output occurred due to the input and bug. 