<h1>Essentials</h1>


````git init````

<p>Use init for initialize repository</p>

````git add .````

<p>For add files to git, uses git add . for all or git add <filename></p>

```git commit -m "your menssage here"```

<p>Add git commit to make changes</p>

```git log```

<p>To logs in git</p>




<h1>Errors</h1>

```git diff```

```git log```

```git revert <hash_commit>```

```git reset --hard <hash_commit>```

```git commit --amend -m "..."```


<h1>Connect with Github</h1>
<p>To connect your github account with Git</P>

```git config --global user.name "name"```

```git config --global user.email "mail@mail.com"```

```git remote add origin <git_link_repository>```

```git remote -v```

<p>Git Push's list</p>

1. >>>git push origin <branch name> -> Push a branch to your remote repository (don't remenber)

2. >>>git push -u origin <branch name> -> Push changes to remote repository (and remember the branch)

3. >>>git push -> Push changes to remote (only for the remembered branch)

4. >>>git push origin --delete <branch_name> -> Delete branch for remote 

5. >>>git branch -d <branch_name> -> Delete local branch

To force delete branch locally, uses ```git branch -D <branch_name>```
`````git remote set-url origin <nova_url>`````
<p>To set new remote origin</P>

<h1>Inspections</h1>

```git log```
<p>View changes</p>

```git log --summary```
<p>View changes (detailed)</p>

```git log --oneline```
<P>View changes (briefly)</p>

```git log --graph```
<P>View Timeline changes</p>

```git show <hash_commit>```
<p>Show information about a specific commit</P>
