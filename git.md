#What is Git? 
> Git is a **_free_** and _**opensource**_ _DVCS_(Distributed Versio Control System). 
> It is used to handle any kind of projects with **Speed** and **Efficiency**  
##Configuring Git  We can Configure Git for :-  
* Project -> Project Specific 
* global  -> User Specific 
* Sysytem -> System Specific / System Wide  
##_Configuring it Globally_  
1. git configure --global user.name "ABC" 
2. git configure --global user.email "xyz@gmail.com" 
3. git configure --global color.ui auto 
4. git congigure --global core.editor vim  
#Creating a Repository  
To create a repository we need to use **_bare_**  
* git init --bare myapp.git  
###Cloning into the repo  
* git clone --local myapp.git myapp  
### Creating a file  
* vim readme  
### Checking the Status  
* git status  
### Adding the newly created file  
* git add readme  
### Commit  
* git commit readme  
### Watch git Satus  
To watch git status we use this command  
* watch git status  
This command updates the status for every **2 seconds**.  
* git remote show  
This command will give the output as **Origin**  
* git remote show origin  
### Push to master  
* git push origin master  
##Here we are done wit git configuration and creating a repository....  [To Create Repository Click here](https://github.com)
