#  Practice 

some description and more

## subHeader

some description on the topic ls -Hidden shows hidden files

## this is in theory of the git commands

### 1 create a repository in github [this will create a local repository in your machine so the changes made locally can be uploaded easily]

    after that come to the terminal and 
  * type "git clone  (url of the repository [brackets excluded()])"


### 2 to show files and hidden files (this is done in visual code terminal so some may differ) 
  * type "ls" for list the files 
  * type "ls -Hidden"  (works in vsCode) or "ls -a" (works in gitBash or windows terminal [i guess]) to show hidden files

### 3 To check if the files are modified/changed or added/removed 
  * type "git status" this will show somehting like this if there are some changes
    ex: modified:   Readme.md

    files which are not yet commited will show Untracked files
                                           ex: index.html

## Commit in git(git commit -m "Your message")
    Before we go on commit we need to know about staging files 
  * "git add [file name]" (brackets excluded[]) this for a single file staging
  * "git add ." is for staging all the files in the repository
    stages the changes in files in the repository which basically means you want these updates to be done
    if you added a new file or removed or modified it will all get staged
    ["git add" is like an checkpoint you need to have to save game with he current progress]

  * "git commit -m "some message"" this command line 
  * commit takes a snapshot of the updates (like you make a save file in a game)
    [this is like a save file which you can load back to or track everthing done until this commit]

### TO Upload upated commited files in..  remote repository (online) like in gitHub (making the project live)
  * YOU NEED SSH key first
  Step 1 >  -t rsa -b 4096 -C "YourEmail@gmail.com" in cmd or terminal
  Step 2 >  Enter file in which to save the key (C:\Users\91799/.ssh/id_rsa): "NameOfthefile" where you password will be saved(leave it empty) 
  Step 3 >  It will give you the location where you can find the file
  Step 4 >  Private key is yours and yours only and public which is used to share with the other members of the project

## git push [origin] [main]                     
  * use the above command to push your commited files in remote repository [without[]]
  * and You will have your files uploaded in the remote repository
