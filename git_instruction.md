# Instruction how to use Git

![Git logo](Git-Logo-2Color.png)

## Creating repository

Enter next command for create local repository

    git init

## Status control

Enter next command for geting status

    git status

## Adding files for tracking

Enter next command for adding file into tracking

    git add file_name

## Saving this stage in local repository

    git commit -m "Your message"

Message need for information about changes in this stage

## Show history of commits

    git log

For hashes and names in one line:

    git log --oneline

## Traveling on history of commits

    git checkout commits_hash

comits_hash is may be first four number or branch name

## Showing changes

    git diff

This will show the changes in the file

If you want to compare another commits:

    git diff first_commit_hash second_commit_hash
    

## Branches

Branches are used in git for group work and separation of tasks.

### Branch list:

For showing branches list:

    git branch

### Create branch

For create new branch:

    git branch new_branch_name

### Merging branches

For merging (IMPORTANT: You must be in branch, which you want changing!):

    git merge another_branch_name

### Deleting branches

After the merge, you need to delete the non-master branch.

For deleting:

    git branch -d  deleting_branch_name

## Adding picture

You can add picture in your md file

For adding picture:

    ![message](path or url to picture)
    
If picture path or url nit be found, message in [] will be visible.

## Work with remote repositories

**Creating remote repository:**
- For working with remote repository need to register and login in on github.com. 
- After you need to create new repository with default settings on you main page on github.com. 
- On opened page choose you variant for connecting local and remote repository.

**Saving changes from local on remote repository:**
- When you set up connection local with remote repository, you can to save changes from local on remote repository. 

Send changes to remote from local:

    git push

**Upload changes from remote on local repository:**

- For uploading changes from remote repository use next commsnd:

    git pull

*IMPORTANT:*

- When you work with other programmers on the same project, your local project can become outdated at any moment.
- Before sending changes with "push" command exatly using "pull" command!

**Cloning from remote repository:**
- If you want to copy your or other users projects from github.com, then use "clone" command:

    git clone project_ref

You can take project ref on main page of project, which you want to copy. You need click on green button with "code" label and choose "http". This is ref for cloning.

**Pull request**

On github many open sourse project. If you want to help any open project, you can did it. You need ref with "fork" label on main project page and click that. Then you can copy this project to you remote repository on github. You already know how to copy it to you local repository. 

*Important:* you must to create new branch and adding changes to this branch!

When you're done with your changes, save them to your remote repository where you keep a copy of the project. 
Open main page this repository on your github repositories. Choose your branch, which you created, and click "contribute", then click on green button with "Open pull request' label.

That's all for starting! :)