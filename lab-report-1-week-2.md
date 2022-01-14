<p align="center">
Lab 1 Week 2 Report
</p>
<br />

### **Installing Visual Studio Code:**
<br />  

First thing's first, you want to go to this 
[link](https://code.visualstudio.com/) and click on the button shown below to download the program. 

<br />   
<p align="center">

![Image](VSCodeButton.png)

</p>

Once installed, you can open the program and should be greeted with a picture that looks similar to this:

![Image](vscode.png)

Now you're ready to write code!


<br /> 

### **Remotely Connecting:**

<br /> 

Next you need to learn how to connect to a remote server.

```
If you are on a computer with Windows click the link below to learn how to install ssh.
```
[SSH Download For Windows](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)


Once installed, reenter VScode and open a terminal. You can do this by pressing **Ctrl** or **Command** + **`** or by clicking this button in the top of the screen. 

![Image](NewTerminal.png)

To connect to a server you need to type in the ssh command followed by your UCSD course specific account that you can find [here](https://sdacs.ucsd.edu/~icc/index.php).

> $ ssh [your account name]

Say yes to what the terminal asks you and input your password. The output should look similar to this

```
Last login: Fri Jan 2 11:23:15 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello [acount name], you are currently logged into ieng6-[whatever computer # you are logged into].ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11

Fri Jan 14, 2022 11:23pm - Prepping [name]
```

<br /> 

### **Try Out Some Commands:**

<br /> 

Now that you're connected, you'll be put in some directory within this server. You will be able to move throughout and make changes to the directories and files in this server by using some of the commands below.


* ls -- Lists the files and subdirectories in your current directory
* cd -- changes your directory to the path the succeeds the command
* pwd -- prints the path you are currently in (you can use this to get back to this directory quickly)
* mkdir -- creates another directory within your current directory; is named whatever string succeeds it
* cp -- copy tool to either put a copy of a file in a new directory or to rename a file

Play around with the commands to get a better feel of how they work. Make sure to always know what directory you're in.

If you ever want to leave the remote server and return to your local computer, either type in **ctrl** + **d** or type **exit** into the terminal and hit **enter**. It will look like this when you leave the remote server:


<p align="center">

![Image](exitssh.png)

</p>
<br />

<br />

### **Moving Files From Client to Server:**
<br />  

If you want to move a file on your local computer to the server you're using, we must use the **scp command** from your local terminal. The format of the command is shown below:

> $ scp [File Name including .filetype] [your account name]:[desired path]

This means if you have a java file named ComparatorLookup and want it copied to your PA1 folder, the command might look like this:

> $ scp ComparatorLookup.java cse15lajw@ieng6.ucsd.edu:~/PA1

Then you can make sure that it copied correctly going into the correct directory and using the ls command. It should look something like this:

![Image](ls.png)

<br /> 

### **Setting Up an SSH Key:**

<br /> 

Logging into the remote server using the **ssh command** can be tedious so there is a way set up so you can enter the server without using your password.


<br /> <br />
[Lab Report 1](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

![Image](GithubPages.png)
