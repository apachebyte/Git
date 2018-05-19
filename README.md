# Git
Some common Git commands

//Check out a repo : create a working copy of a local repository  
$git clone /path/repository  

//override local changes  
$git checkout  --  .    

//Add files : Add one or more files to staging  
$git add <filename>  
$git add *  

//Commit : Commit changes to Head (but not yet to remote repository)  
$git commit -m "commit message"  

//Push : Send changes to remote repository  
$git push origin master  

//Status : list modified files and new files yet to be added/committed/pushed to remote repo  
$git status  
	
//Branches - show your branch  
$git branch  

//Branches - switch from one branch to another  
$git checkout <branchname>  
	
//Update from remote repo  
$git pull  

Reference  
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html  
http://www.vogella.com/tutorials/EclipseGit/article.html  