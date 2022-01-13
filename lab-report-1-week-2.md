**CSE15L Week 2 Lab Report 1 by Helena Hundhausen** 
======================================================
Logging Into A Course-Specific Account On ieng6
-------------------------------------------------------
*Background*    : 

Software Engineers can't store a company's large amounts of data on their personal computers to complete their work, requiring them to access a personalized account from their local computers to a remote machine. To understand and replication how this process works this lab and the steps below, explain how to use a CSE15L course-specific account to access a computer in the CSE basement. 



*Step One*    : Installing Visual Studio Code 

Visual Studio Code is an Integration Development Environment (IDE) for macOS, Windows, and Linux, with integrated terminal access. Installing VS Code is important because we will use its integrated terminal palette to access our course-specific account on ieng6 and complete the remaining steps in this lab. 

>To download and install VSCode: 
1. Depending on the computer you're using different versions of VS Code are available. For a link to all versions, click [here](https://code.visualstudio.com/Download)! 
2. Then, click [here](https://code.visualstudio.com/docs/setup/setup-overview) for more information on the steps needed to finish installing VS Code onto the type of computer its downloaded on. 
3. Once installed, you'll be able to open a window very similar to the screenshot below...
![Image](InstallingVSCode.png)


*Step Two*   : Remotely Connnecting 

>
1. Open a **terminal** in VSCode 
2. Then, insert the command **ssh cs15lwi22zz@ieng6.ucsd.edu** (on the first line in the screenshot you can see how I put mine) 
3. Then, insert the password that you previously created, if you just resetted it might take a while this problem happened to me  
3. If this is the first time connecting to the server, you'll getting a message to continue connecting type **yes** 
4. Similary in the screenshot starting on line three it will inform you the last time you loggined in and a lot of other account specific information 
5. If you see this that means you were successful and that your terminal is connected to a computer in the CSE basement and any commands you run will run on that computer
 - - If you need to 


![Image](RemotelyConnecting.png)


*Step Three* : Trying Some Commands 

After ssh-ing, to demonstrate different commands that can be run a few different times. 
Here are some specific commands that can be found in the screenshot below. 


*Step Four*  : Moving Files with scp 


*Step Five*  : Setting an SSH Key 


*Step Six*   : Optimizing Remote Running 












