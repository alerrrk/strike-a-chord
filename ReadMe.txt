OPTIONAL GIT SYNC INSTRUCTIONS

Verify that Git is Installed 

1. Verify that git is installed in the environment: 

"git --version"

This should display a message like the one shown below: 

> git version 2.17.1

2. If git is not installed, you can install git by using the following command: 

"sudo apt install git"

---------------------------------------------------------------------------------------------------------

To Clone (Download) a Repository: 

1. Obtain (copy) the repository's HTTPS or SSH URL. The HTTPS URL will look like the example shown below: 

"https://github.com/account-name/repository-name.git"

2. In the environment's terminal, change the current working directory to the location you want to clone 
your files to. For example, if you want to clone your files into the 'music' directory type the following 
command: 

"cd music"

Be mindful that you do not accidently overwrite any of the resources provided in the lab. If you do, 
you can safely perform a lab reset. 

3. To clone the repository type the following command: 

"git clone https://github.com/account-name/repository-name.git"

This will prompt you for your username and password. When you type your password, the terminal will not 
display it, but you are still entering characters until you hit "Enter" ("Return"). 

----------------------------------------------------------------------------------------------------------

To Commit and Push Your Files to a Repository:

1. First, in the terminal, change your working directory to the directory you want to commit:

"cd rescue"

2. Next, set the git config file using your email and user name for the remote repository: 

"git config --global user.email 'you@example.com' "
"git config --global user.name 'username' "

Where "you@example.com" and "username" are your email and username. 

3. Then, add any new files to the local repository: 

"git add . "

4. Commit your changes to your local repository with an appropriate message (-m): 

"git commit -m 'Created the index.html file'"

5. Push your changes from the local repository to your remote repository: 

"git push origin branch-name"

The 'branch-name' will be "master" unless you create a new branch. 

6. You will be prompted to enter your username and password. 


-----------------------------------------------------------------------------------------------------------

Reconnect your Directory to a Remote Repository

1. First, in the terminal change your working directory to the directory you would like to commit: 

"cd student"

2. Then, initialize a local repository:

"git init"

3. To add a remote repository to the local repository use the following command: 

"git remote add origin https://github.com/account-name/repository-name.git"

Where the URL is the HTTPS URL to the remote repository. 

4. Next, follow the steps to commit and push your code to the remote repository. 

-----------------------------------------------------------------------------------------------------------

Useful Command Line Interface Commands: 

1. List directories: 

"ls"

2. Change the working directory: 

"cd destination-folder"

3. Move files:

"mv file1 ./destination-folder/"
