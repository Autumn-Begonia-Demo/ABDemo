### Welcome to the Visual Studio Code Setup Tutorial for HOI4 Modding! 


#### If you want to set up git integration with VS Code, a lightweight text editor, you've come to the right place.  
#### Visual Studio Code is a simple yet powerful development environment with built in git support and integrated development available for almost all programming languages. It is an excellent development tool for beginners and advanced programmers alike.

***
#### Before you begin, here is a list of software you need to have installed:
#### > Git (https://git-scm.com/download)  
#### > VS Code (https://code.visualstudio.com/Download)

***
When you have the aforementioned software installed, upon opening you VS Code, you will be greeted with a start up screen like this.  
![image](https://user-images.githubusercontent.com/77932983/147580920-f42ff486-01ab-41e2-aeef-fd20d1b5a097.png)

On the left side you can see the side panels, the third of which is source control, which should recognize git as your source control software automatically.  
![image](https://user-images.githubusercontent.com/77932983/147581050-7366eea0-bec2-4424-9ca1-95b727dc8879.png)


From there you may be greeted with a similar screen as such.  
![image](https://user-images.githubusercontent.com/77932983/147581087-1053a7ab-2290-4475-89fd-dbed1a2d9a86.png)  

If you have yet to clone a repository, click on the "Clone Repository" button and follow the prompt at the top of VS Code. Simply click the button to copy over the https link and paste it into the prompt at the top as instructed, and clone it into a local folder. For HOI4, it is recommended to clone into the path where you will be launching your mod, such as /mod.   ![image](https://user-images.githubusercontent.com/77932983/147581259-55a92fb3-c43c-4b74-9152-c0fb3bc4002d.png)  

If you already have downloaded the repository with git (nto the download with zip!), you can simply open the repository by opening the folder from git or like this.   
![image](https://user-images.githubusercontent.com/77932983/147581488-83625de5-6ee9-41ee-bccc-249a21d9ab4e.png)  

At the bottom left, you will see two buttons like this.   
![image](https://user-images.githubusercontent.com/77932983/147581744-6de282e1-b88b-40b4-bdb5-74413cf9d1b8.png)  

The one on the left (tick counter) is the branch you are on. Click on it and you will be able to switch branches. The one on the right is a "syncronize change" button, where you can do git pull and git push for your commits as well as update your repository to commits from source.

Other git commands can be prompted either with the terminal   
![image](https://user-images.githubuserco ntent.com/77932983/147582017-727a6cb8-ec79-482f-bf6c-8650a2d39bab.png)  

Which you can open here from the top panel   
![image](https://user-images.githubusercontent.com/77932983/147582065-8fd1d3f2-5f60-4357-8f81-fd0b577b774a.png).


Or you can simply do control/command + shift + p, and you will be able to see the command pallette   
![image](https://user-images.githubusercontent.com/77932983/147582148-9d206e30-097d-40c4-b781-bfce7f888110.png)  
where you can type in commmands both for git and or other extensions from VS Code.

For committing saved changes, you can see the changes like this when you open the source control panel.  
![image](https://user-images.githubusercontent.com/77932983/147582265-8f7f8a4b-fb5b-459e-92e0-ad10002e3bdf.png)

To commit, you will first need to click the plus sign on the changes (you can also discard all changes with the undo button next to it)    
![image](https://user-images.githubusercontent.com/77932983/147584000-ec28a0b1-413d-4971-b5dd-e1dd7b171fe6.png)
to stage your files, then you will see staged changes. These are the changes going into your commit. Type a message in the message box for commit comments and click the checkmark to commit.  ![image](https://user-images.githubusercontent.com/77932983/147584144-d6ba7b10-7b8d-44c8-9d58-bec3c6794619.png)

Afterwards, simply synchronize your changes with by clicking the button at the bottom left.
***

The details and tutorials for other git commands (such as git fetch) will not be detailed here as they are detailed in another document. However, the same commands and procedures apply here as well.


For more details about VS Code Source Control, you can check out the official documentation here: https://code.visualstudio.com/docs/editor/versioncontrol
