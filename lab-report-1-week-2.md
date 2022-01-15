# Lab Report 1

## Installing VScode
1. Go to the [Visual Studio Code](https://code.visualstudio.com/) website to download and install VScode onto your computer.
2. Once you successfully install VScode, it should look like this when you open it (the colors and theme may vary depending on your computer settings):
![Image](vscode.png)

## Remotely Connecting
1. Go to [this link](https://sdacs.ucsd.edu/~icc/index.php) and look up your course specific account (for CSE 15L). You will have to change your password to activate your account.
2. Open a terminal in VSCode (command/ctrl + ` , or use menu option Terminal -> New Terminal). 
3. Type in the command (zz replaced by your account's specific letters):
```
ssh cs15lwi22zz@ieng6.ucsd.edu
```
4. If you are asked if you are sure you want to continue connecting (will happen if it's your first time connecting to this server),  end the command "yes".
5. Since it's your first time logging into your account, it will print out these messages:
![Image](sshlogin.png)

## Trying Some Commands
1. Here are some commands you can try:
- cd ~
cd
ls -lat
ls -a
ls <directory> where <directory> is /home/linux/ieng6/cs15lwi22/cs15lwi22abc, where the abc is one of the other group members’ username
cp /home/linux/ieng6/cs15lwi22/public/hello.txt ~/
cat /home/linux/ieng6/cs15lwi22/public/hello.txt

2. To log out of the remote server in your terminal, use Ctrl + D, or run the command "exit".
## Moving Files with scp
1. 

## Setting an SSH Key
1. 
## Optimizing Remote Running
1. 