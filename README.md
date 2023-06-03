# git_tutorial_terminal - This is all an old man needs to use git.
This is how I use github, old school. This readme file is actually the tutorial, no fancy youtuber here, and its purpose to remind me to actively use git.  I use a variety of IDEs, so I find it easyier to use the command line to use git, rather than try to use each IDEs' git "wedges".

I mostly store my files and projects as private because, I often have half baked ideas and models, then I do the rest in my head or imagine its done.

I hope I will try to do a few complete public projects in the spirit of sharing.

As I understand it, use git for organizing, storing, tracking changes/versions, and collaborating on software (or any file based) projects. 


# Secure setup to your git account
1. set up secure connection to github, I made ssh keys using another tutorial: <add link here>
  The good news is after you set up your keys and have git installed locally, you just use the commandline
  in your project folder.

# Operation
2. open a terminal window.

3. On MacOS, or linux I supose, you can use a variety unix/git commands:

cd ~. 
git status
pwd
ls
cd tf_stock1       <-  (this is a current project I am working on.)
ls -al
## The guts of the Tutorial: The git add - commit - push pattern.                    
git status 

### add ALL the new/changed files/folders in this folder, note you can specify an individual file folder and probably a list too.
                      
git add .    

git status
git commit -m " Adds comments for added file(s) \n"
git push
  
  

