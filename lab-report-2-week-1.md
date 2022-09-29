# **Week 1 Lab Report**
Hello! You're likely here because it's your first time logging into a your course specific account on `ieng6`, or maybe you've forgotten the steps and are just simply lost. To help you gain access, I have put together this tutorial!

To gain access to your account (*and learn how to use it properly*), there are **SIX** easy steps:

* Install VSCode
* Connect Remotely 
* Run Some Commands
* Transporting Files Accross Severs and Clients Using `scp`
* Setting the SSH Key
* Optimizing Remote Running

After following these steps, you should be well on your way!

---
## **Step 1** - Install VSCode
Before you can set up a remote connection, you need access to the VScode terminal. To do this, go to the visual studio code website https://code.visualstudio.com/ and follow the instructions to download the application. I already had the app downloaded beforehand, so I skipped this step. 

Upon opening the application, you should be greeted with a screen resembling the below pictured: 
<img width="1440" alt="Screen Shot 2022-09-28 at 4 28 26 PM" src="https://user-images.githubusercontent.com/114445845/193128596-d21861ec-7944-49a2-a4f0-3ede092c936f.png">
Your screen may look a little different depending on your visual settings(*for instance mines black because I chose the dark setting*) but it should work all the same!

---
## **Step 2** - Connect Remotely
Start by opening a terminal in VSCode and typing in the below command:

`ssh cs15lfa22cl@ieng6.ucsd.edu` 

if that doesn't work try: 

`ssh aortel@ieng6.ucsd.edu` 

If it is your first time connecting,type in yes and press enter. Then proceed by typing in your password. Once you are logged in, your terminal should look like this: 

<img width="482" alt="Screen Shot 2022-09-28 at 4 53 16 PM" src="https://user-images.githubusercontent.com/114445845/193134935-de342cf1-9a6d-4bf8-83cd-262fcbdfed80.png">

Congratulations! You are now logged into the remote ieng6 computer.

---
## **Step 3** - Run Some Commands
