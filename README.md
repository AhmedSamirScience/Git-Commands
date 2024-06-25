<p align="left"> <img src="https://komarev.com/ghpvc/?username=ahmedsamirscience&label=Profile%20views&color=0e75b6&style=flat" alt="ahmedsamirscience" /> </p>

## Getting & Creating Projects:
| Command | Description |                                              
| ------------ |:-----------:|
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository|


***
## Basic:
| Command | Description |                                              
| ------------ |:-----------:|
| `git status` | Check status | 
| `git add [file-name.txt]` | Add a file to the staging area | 
| `git add .` | Add all new files to the staging area | 
| `git commit -m "[commit message]"` | Commit changes | 

***
## Branching & Merging:
| Command | Description |                                              
| ------------ |:-----------:|
| `git branch` | List branches (the asterisk * denotes the current branch) | 
| `git branch [branch name]` | Create a new branch | 
| `git branch -d [branch name]` | Delete a branch | 
| `git branch -m <old_name> <new_name>` | Rename the local branch to the new name | 
| `git push origin --delete [branch name]` | Delete a remote branch | 
| `git checkout [branch name]` | Switch to a branch | 
| `git merge [branch name]` | Merge a branch into the active branch | 
| `git merge [source branch] [target branch]` | Merge a branch into a target branch | 





***
## Sharing & Updating Remote Projects:
| Command | Description |                                              
| ------------ |:-----------:|
| `git push origin [remote name] master [branch name]` | Push a branch to your remote repository | 
| `git push origin --delete [branch name]` | Delete a remote branch | 
| `git pull origin [branch name]` | Pull changes from remote repository | 
| `git remote add origin [remote name you defined. it is up to you] ssh://git@github.com/[username]/[repository-name].git [URL of the repo weather was https or ssh]` | Add a remote repository to my project | 
| `git remote set-url <remote_name> <remote_url>` | Change git gemote URL or you want to rename remote  | 


***
## Inspection & Comparison:
| Command | Description |                                              
| ------------ |:-----------:|
| `git log` | View changes | 
| `git log --summary` | View changes (detailed) | 
| `git log --oneline` | View changes (briefly) | 
| `git diff [source branch] [target branch]` | Preview changes before merging | 
| `Git log --all --graph` | View changes | 
| `git log --all --oneline` | View changes | 

***
## Tags:
| Command | Description |                                              
| ------------ |:-----------:|
| `git tag-a V2.0.0 -m "Your message Here"` | Tag your commits | 
| `git show v2.0.0` | show all commits related to this tag | 
| `git push origin v2.0.0` | push tag to the remote repo | 

***
## Undothings:
| Command | Description |                                              
| ------------ |:-----------:|
| `git reset --hard HEAD~1` | undo one commit | 

***
## Configuration:
| Command (User Name) | Description |  
| ------------ |:-----------:|
| `git config user.name "Ahmed Samir Ahmed"` | Set User Name for specific project |
| `git config --global user.name "Ahmed Samir Ahmed"` | Set User Name `Globally` |
| `git config user.name` | Get Saved User Name | 

| Command (User Email) | Description |  
| ------------ |:-----------:|
| `git config user.email "ahmed.samirelbakrey@gmail.com"` | Set User Email for specific project | 
| `git config --global user.email "ahmed.samirelbakrey@gmail.com"` | Set User Email `Globally` | 
| `git config user.email` | Get User Email | 

| Command (Author Name) | Description |  
| ------------ |:-----------:|
| `git config author.name "Ahmed Samir Ahmed"` | Set Author Name for specific project | 
| `git config --global author.name "Ahmed Samir Ahmed"` | Set Author Name `Globally` | 
| `git config author.name` | Get Author Name | 

| Command (Author Email) | Description |  
| ------------ |:-----------:|
| `git config author.email "ahmed.samirelbakrey@gmail.com"` | Set Author Email for specific project | 
| `git config --global author.email "ahmed.samirelbakrey@gmail.com"` | Set Author Email `Globally` | 
| `git config author.email` | Get Author Email | 

| Command (Commiter Name) | Description |  
| ------------ |:-----------:|
| `git config commiter.name "Ahmed Samir Ahmed"` | Set Commiter Name for specific project | 
| `git config --global commiter.name "Ahmed Samir Ahmed"` | Set Commiter Name `Globally` | 
| `git config commiter.name` | Get Commiter Name | 

| Command (Commiter Email) | Description |  
| ------------ |:-----------:|
| `git config commiter.email "ahmed.samirelbakrey@gmail.com"` | Set Commiter Email for specific project | 
| `git config  --global commiter.email "ahmed.samirelbakrey@gmail.com"` | Set Commiter Email `Globally` | 
| `git config commiter.email` | Get Commiter Email | 

***
## Git branching model (Git Flow):
<p href="url"  align="center" ><img src="https://nvie.com/img/git-model@2x.png" height="900" width="790" ></p>

***
## Remove Cached files:
git rm --cached file : removes the copy of the file from the index / staging-area, without touching the working tree copy. The proposed next commit now lacks the file. If the current commit has the file, and you do in fact make a next commit at this point, the difference between the previous commit and the new commit is that the file is gone. Below are the steps you can follow: 

<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_1.png" height="610" width="690" ></p>
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_2.png" height="610" width="690" ></p>
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_3.png" height="610" width="690" ></p>
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_4.png" height="470" width="690" ></p>
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_5.png" height="230" width="690" ></p>


***
## ➠ Start Contributing ☺
I will be more than happy if you decide to contribute and/or fork my repo and make something awesome out of it. I will love seeing some feedback or stars from you guys.

***
#### ➠ To get more information about our repository, just send us a message from [here](https://www.linkedin.com/in/ahmedsamir13/) and we will send you the documents related to this study for a better understanding!
 
***
