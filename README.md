# gitCommands-demo


1.create a new repo
2.make first commit
3.commit changes

</br>
~ //means root directory
git --version
ls //(lost files)for files and folders 
ls -a //for hidden files
pwd //working directory
clear
cd <- folderName -> //change directory
cd .. //exit directory
mkdir <- new dir name -> //make new directory

# configuring git
git config --global.username"abc" //global=>on local machine, local=>on specific repo
git config --global.useremail"abc@email.com"
git --list //credentials like username, email etc.

# Clone & Status
git clone <- link -> //cloning rep on local machine. local=>pc/laptop, remote=>github
   *On code editor 
   cd <- folder name -> //change directory(folder)
   
git status //code status
   <-- untracked/modified -> after add(staged) -> after commit(unmodified). -->

   *untracked 'U' //new file
   *modified 'M' //change in file
      step 1: add //after adding , the file will be staged
         git add <- file name -> //single file
         git add . //add all file
      step 2: commit
         git commit -m "some message"

   *staged //ready to commit.
      //after adding , the file will be staged

   *unmodified //changed

   # Push command 
   //all the changes done in code editor will not reflected unless until this command
   git push origin main //upload local content repo to remote

# init repo
//create a new git repo
git init
   //after mkdir-> invoke this command ->make new rep(github)-> git remote add origin
git remote add origin <- link -> // the link of github new repo
git remote -v //to verify remote
git branch //to check branch
git brach -M main //to rename branch
git push origin main
git push -u origin main //if we want to work on same file for a long time, then we use it. -u means set upstream
   after this, simply give command git push.

