# **Week 2 Lab Report 1** 

---
# Logging Into A Course-Specific Account On ieng6

---

*Background*    : 

When working with a large amount of data accessing a remote machine may be necessary. To understand how this process works, this lab and the steps below demonstrate how to gain access to a computer in the CSE basement using a CSE15L course-specific ieng6 account. 


*Step One*    : Installing Visual Studio Code 

In this step, we'll be installing Visual Studio Code, an Integration Development Environment (IDE), which is important because this lab uses its integrated terminal palette to gain access to our CSE15L course-specific ieng6 account. 

>To download and install VS Code: 
1. Depending on the computer you're using, different versions of VS Code are available. For the link to all versions, click [here](https://code.visualstudio.com/Download)! 
2. Now, click [here](https://code.visualstudio.com/docs/setup/setup-overview) for more information on the steps needed to finish installing VS Code onto the type of computer it's downloaded on! 
3. Once installed, you'll be able to open a window very similar to the screenshot below...
* Note that I’ve changed specific settings in my VS Code, so my screenshot may look slightly different from the window you have opened
![Image](InstallingVSCode.png)



*Step Two*   :  Remotely Connnecting 

In order to connect to the computer in the CSE basement, we have to obtain a course-specific ieng6 account. 

>If you haven't found your account yet, follow these steps: 
1. Click here for [account lookup!](https://sdacs.ucsd.edu/~icc/index.php) 
2. Enter your AD and Username 
3. Find the CSE15L ieng6 specific account under *additional accounts*; it should very similar to *"cs15lwi22aco"*
* The three-letters at the end **aco** should be replaced with the particular combination given to you
![image](courseAccount.png)
4. Then, click on your account to reset the password 
* To avoid problems in the following steps, make the password short and straightforward while still secure 

>If you've gained access to your account, follow the steps in the screenshot below to establish a new terminal in VS code and enable a secure connection to the remote computer using a command called **ssh**. 
* Before continuing, read here for important information and clarification:  
- - It takes about 15-20min for the password to reset
* * If you're having issues or problems with completing this step there could be minimal typos in your code, so go back and check previous lines 

![Image](RemotelyConnecting.png)


*Step Three* : Trying Some Commands 

One important thing about *ssh* is that commands on your local computer will be executed on the remote computer while you're connected to the secure connection it establishes. The screenshot below provides a demonstration of the different commands I tested for fun. 

Feel free to experiment this step on your VS Code! 
![Image](TryingCommands.png)

*Step Four*  : Moving Files with scp 

Another essential thing to learn is transferring files back and forth between the local/remote computers using a command called *scp*. The *scp* command, however, takes a long time, and if you had to run it throughout a PA or anything else, simply checking to see whether you had the required output would be very time-consuming. Within the next steps, we'll see how to resolve this problem. 

>Follow these steps to understand how to move files (also the screenshot displays a very nice visual): 
1. Make sure you’re not logged into the remote computer
2. Create a .java file on your computer
- Feel free to copy the WhereAmI.java file on the screenshot below
3. Log into the terminal from the directory where the file was made and run the **scp** command along with your personal username to log back into the remote computer: 
* scp WhereAmI.java cs15lwi22aco@ieng6.ucsd.edu:~/
4. Enter your password
5. Try the command **ls** to list the file

![Image](MovingFiles.png)

*Step Five*  : Setting an SSH Key 

Every time we've had to log in or run *scp*, a password that isn't visible had to be typed for security purposes which is very time-consuming; yet, a helpful command called *ssh-keygen* allows us not to have to type a password by creating a pair of files on your local computer called: 
- *public key* 
- *private key*. 

Follow the steps in the screenshot below to generate the *public key* and *private key*.  
>Before continuing, read here for important information and clarification:  
- When prompted to enter a new password, press "enter" since we no longer want to have to endure the pain of password entering *(a password isn't needed because we aren't engaging with very secure data)* 

![Image](sshKey1.png)

Now that the *public key* and *private key* are generated follow the steps in the screenshot right below to understand how to copy the *public key* and create a *.ssh directory* to put it onto your course-specific account's server. 

![Image](sshKey2.png)

*Step Six*   : Optimizing Remote Running 

Now that we don't need to input a password to ***ssh*** or ***scp***, we can concatenate the command with other commands, such as the ones previously tested in *step three*. Additionally, this will make editing locally a lot more efficient and less time-consuming. 

To run several commands on the same line, write the command at the end in *" quotes,"* or divide the commands with *semicolons*.

The screenshot below displays a few examples. Feel free to experiment this step on your VS Code!

![Image](RemoteRunning.png)


---
You've reached the end. Thank you for reading this lab report!












