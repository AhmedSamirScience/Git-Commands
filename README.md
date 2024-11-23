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
| `git branch -r` | This command displays all the remote branches tracked by your repository | 
| `git branch -a` | If you want to see both local and remote branches | 
| `git branch [branch name]` | Create a new branch | 
| `git branch -d [branch name]` | Delete a branch | 
| `git branch -m <old_name> <new_name>` | Rename the local branch to the new name | 
| `git push origin --delete [branch name]` | Delete a remote branch | 
| `git checkout [branch name]` | Switch to a branch from local | 
| `git switch --track [origin/branch-name]` | Switch to a branch from remote | 
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
| First step-> `git reset --hard HEAD~1`| undo one commit | 
| Second Step-> `git push origin <branch_name> --force` | undo one commit | 


***
## change latest commit name:
[you can find the link if you want more details](https://stackoverflow.com/questions/8981194/changing-git-commit-message-after-push-given-that-no-one-pulled-from-remote)
| Command | Description |                                              
| ------------ |:-----------:|
| Step 1 -> `git commit --amend -m "New commit message"` | If it is the most recent commit, you can simply do this | 
| Step 2 -> `git push --force` | This brings up the editor with the last commit message and lets you edit the message. (You can use -m if you want to wipe out the old message and use a new one.) | 

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

Here are the idea codes in .gitignore
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/rm_cached_6.png" height="230" width="690" ></p>

***
## Merging Branches with a Specific Commit Message

To merge one branch into another with a specific commit message, follow these steps:

1. **Switch to the branch you want to merge into**:
    ```sh
    git checkout target-branch
    ```

2. **Merge the source branch into the target branch with a specific commit message**:
    ```sh
    git merge source-branch --no-ff -m "Your specific commit message"
    ```
**Example**
If you want to merge a branch named `feature-branch` into `main` with a specific commit message, use the following commands:

```sh
git checkout main
git merge feature-branch --no-ff -m "Merged feature-branch into main with specific commit message"
```
<p href="url"  align="center" ><img src="https://raw.githubusercontent.com/AhmedSamirScience/Git-Commands/Git_Commands/merge_one_branch_into_%20another_with_a_specific_commit_message.png" height="100" width="790" ></p>

# Explanation of `--no-ff` Option in Git Merge

The `--no-ff` option in the `git merge` command stands for "no fast-forward."

## What is Fast-Forward Merge?
In a fast-forward merge, Git simply moves the pointer of the current branch forward to point to the latest commit in the branch being merged. This happens when there have been no new commits on the current branch since it diverged from the branch being merged. This type of merge does not create a new commit, resulting in a linear history.

## What is a No Fast-Forward Merge?
When you use the `--no-ff` option, Git creates a new merge commit even if a fast-forward merge is possible. This merge commit will have two parent commits: one from the current branch and one from the branch being merged. This ensures that the history of the merge is preserved and makes it clear that a feature branch has been integrated.

## Why Use `--no-ff`?
- **Preserve History**: It helps in maintaining a clearer project history by showing when a feature was merged into the main branch.
- **Traceability**: It allows you to easily trace back all the commits that were part of a feature branch.
- **Grouping Changes**: It logically groups the commits of a feature or bug fix together under a single merge commit.

## Example

```plaintext
Consider a repository with the following commit history:

*   C4 - Main branch
|
* C3 - Main branch
|
| * C2 - Feature branch
|/
* C1 - Common ancestor

If you perform a fast-forward merge, the history might look like this:

* C4 - Feature branch (fast-forward)
|
* C3 - Main branch
|
* C2 - Feature branch
|
* C1 - Common ancestor

However, if you use the --no-ff option, the history will look like this:

*   M - Merge commit
|\
| * C2 - Feature branch
* | C4 - Main branch
* | C3 - Main branch
|/
* C1 - Common ancestor

So, using --no-ff helps in preserving the historical context of the changes, making the project history easier to understand and navigate.

```
***
## ➠ To rename (amend) a specific commit using its SHA, you can use an interactive rebase in Git. Here are the steps:
<p href="url"  align="center" ><img src="https://github.com/AhmedSamirScience/Git-Commands/blob/Git_Commands/To%20rename%20amend%20a%20specific%20commit%20using%20its%20SHA%2C%20you%20can%20use%20an%20interactive%20rebase%20in%20Git.%20Here%20are%20the%20steps_1.png" height="750" width="600" ></p>
<p href="url"  align="center" ><img src="https://github.com/AhmedSamirScience/Git-Commands/blob/Git_Commands/To%20rename%20amend%20a%20specific%20commit%20using%20its%20SHA%2C%20you%20can%20use%20an%20interactive%20rebase%20in%20Git.%20Here%20are%20the%20steps_2.png" height="150" width="400" ></p>


***
## ➠ Start Contributing ☺
I will be more than happy if you decide to contribute and/or fork my repo and make something awesome out of it. I will love seeing some feedback or stars from you guys.

***
#### ➠ To get more information about our repository, just send us a message from [here](https://www.linkedin.com/in/ahmedsamir13/) and we will send you the documents related to this study for a better understanding!
 
***
