# Git Commands
Created : 01.02.2022

Modified : 21.08.2023

All notes from GitCommands.txt were transferred to this markdown page. GitCommands.txt will not be continued.

<h1>Description:</h1>
File for git commands that I've learned.

<h1>Notes</h1>
< message > - insert real data
  
" message " - insert real data

<h1>Global Credentials Configuration</h1>
For a certain repository only, omit --global

- Configuring user name : ```git config --global user.name "Insert user name here"```
- Configuring email : ```git config --global user.email "Insert email here"```
- Check configurations: ```git config -l```
- Check a certain configuration : ```git config <insert variable here>```
  - Checking username configuration : ```git config user.name```
 
<h1>Creating a remote repository</h1>

- Initialize repository: ```git init```
- Add remote repository: ```git remote add <remote> >repo-url>``` 
- Add file: ```git add <filename>```
- Add all files: ```git add .```
- Commit changes: ```git commit -m "Insert commit message here"```
- Transfer file from local repo to github repo: ```git push <remote> <branch>```


<h1>Branches</h1>

- Create a branch: ```git branch <Name of new branch name>```
- Change a branch: ```git checkout <Name of existing branch>```
- Delete a branch: ```git branch -d <name of branch to be deleted>```
