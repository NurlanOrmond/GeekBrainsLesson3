# Instruction on how to work with GitHub

## How to download project from GitHub

* Create Folder
* Start VS Code
* Open Folder

  But we should not make git init by now, because git init is for local repository. We will work with remote rep.

* Go to Git Hub and copy reference of interested project. Use the code  button.

* VS Code > Terminal> git clone  and paste reference.

    By this we copy the remote repository to our local Folder.
    After that we can observe new copied folder under our Folder tree.
*  cd “name of Folder” 

   name is that has come from Git Hub.

*  cd "folder name"

   Initially we worked with local folder. cd move us inside folder that we have copied. We can check it out by git status.

## How to send local repository to Git Hub.

* Start VS Code and create new Folder>file or open existing file.

* Our next step is to create account in Git Hub. 

  If you already have an account, in up-left side of the GitHub interface the + sign located. Click on it and options will be rolled out. Choose “New repository”. Name it and push the “Create repository” button.
  Then GitHub offers us three options for what to do further. In our case “...or push an existing repository from the command line” is OK!
  We can see three commands. Copy them and paste to our Terminal.

* git remote add origin https//………………. 

  We warn git that new remote repository created and it will be living at https// …address… . In other words we tie local rep with remote rep.

* git branch -M main
 - is to specify which branch is main
push -u origin main - is to send local rep content to remote.

* Verifying 

  in case of first push to a new rep we have to go through the Verifying process. 

 
* git push

  While we work in VS Code and make some changes, add and then commit them the remote file in GitHub is staying unchanged. If we want all changes in local rep to send to remote file we should use
