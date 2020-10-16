# Basic Operations in GitHub :octocat:

## Operations on the GitHub website:
  1. Making Repository (To start a work)
  2. Forking (To contribute to some other repos)
  3. Pull Request (To merge work to the forked repo)

Complete Picture of branching (Picture not loaded)

## From terminal:
-------------
#### To view details:
```
git config –global user.name
git config –global user.email
```
#### To avoid putting id credentials multiple times for xxxx seconds:
```
git config credential.helper ‘cache –timeout=xxxx’
```
#### To initiate git
```
git init
```
#### To Copy a repository from GitHub
```
git clone <Copied-link-from-the-repository>
```
#### To update the offline from the remote
```
git pull
```
### Works:
#### To view the fetch-details
```
git remote -v
```
#### To view the branchs
```
git branch
```
#### To make a new branch from the present one
```
git branch <new branch name>
```
#### To rename a branch
```
git branch -m <old branch> <new branch>
```
#### To go to a branch
```
git checkout <branch name>
```
### Delete Branch:
#### to delete the offline branch
```
git branch -d  <branch 2b deleted>
```
#### to delete the remote branch
```
git push origin –delete <branch 2b deleted>
```
### Merge Branch:
#### Branch-ii is merged with Branch-i
```
git checkout <Branch-i>
git merge <Branch-ii>
```
### Commiting (Taking a snapshot):
```
git add .
git commit -m “Msg+Instructions”
git status
```
#### Push to remote:
```
git push -u origin <Branch name>
```
####
uukuwiueou3uu
