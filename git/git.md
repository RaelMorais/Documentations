<h1>Essentials</h1>

```git status``` Use to check init status

````git init```` Use init for initialize repository

````git add .```` For add files to git, uses git add . for all or git add <filename></p>

```git commit -m "your menssage here"``` Add git commit to make changes

```git rm -r <file_name>``` Remove file or directory

```gi pull``` Update local repository to the newest commit

```git pull origin <branch_name>``` Pull changes from remote repository

```git clone <link_git>``` To clone repository


<h1>Inspection</h1>

```git diff``` Command shows the differences between files in your repository.

```git log``` Command shows the commit history of your repository. 

```git revert <hash_commit>``` Command is used to create a new commit that undoes the changes introduced by a specific commit. 

```git reset --hard <hash_commit>``` Command moves the current branch pointer to a specific commit and erases any changes in your working directory and staging area.

```git commit --amend -m "..."``` Edits the most recent commit. 


<h1>Connect with Github</h1>
<p>To connect your github account with Git</P>

```git config --global user.name "name"``` Config your local name in commits

```git config --global user.email "mail@mail.com"```  Config your local email in commits

:exclamation: Git typically requires the global username to be configured to ensure that your contributions are correctly attributed to you in remote repositories :exclamation:


```git remote add origin <git_link_repository>``` Add origin for remote repository

```git remote -v``` Check your remote repository

```git push --set-upstream origin <branch_name>``` or ```git push -u origin <branch name>```

<p>:sparkles:Git Push's list</p>

1. ````git push origin <branch name>```` -> Push a branch to your remote repository (don't remenber)

2. ````git push -u origin <branch name>```` -> Push changes to remote repository (and remember the branch)

3. ````git push```` -> Push changes to remote (only for the remembered branch)

4. ````git push origin --delete <branch_name>```` -> Delete branch for remote 

5. ````git branch -d <branch_name>````-> Delete local branch

To force delete branch locally, uses ```git branch -D <branch_name>```

`````git remote set-url origin <nova_url>````` To set new remote origin

<h1>Branch's</h1>

```git branch``` List all branchs

```git branch -a``` List all branchs (local and remote)

```git branch <name_new_branch>``` Create a new branch

```git switch <name_branch_switch>``` To switch branch

```git switch -c <nome_branch>``` To create and switch for new branch

<h1>To Merge</h1>

To merge two branches, use ````git status```` to check the current branch, switch to the branch to merge using ````git switch branch_name````, use ```git branch_two```.
Or use  ```git merge branch_main branch_two```



<h1>Logs</h1>

```git log``` View changes

```git log --summary``` View changes (detailed)

```git log --oneline``` View changes (briefly)

```git log --graph``` View Timeline changes

```git show <hash_commit>``` Show information about a specific commit

<h1>:sparkles:Bonus</h1>
<p>Github CLI</p>

To install, open Powershell and type ```winget install Github.cli``` or visit <a href="https://cli.github.com/">Github CLI

Use ```gh auth login``` to autentication and select https login

Before, use ```gh repo create "name_repository" --public (--private)``` to create repository in CLI. 
