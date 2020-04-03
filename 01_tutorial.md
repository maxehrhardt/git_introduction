# Welcome to GIT (Git Initiative for Trainees) 
![linus](images/01/linus.jpg)  
Git is a version control system (VCS) programmed by Linus Torvald in 2005 to support the work on the Linux kernel.


Matthias ist cooler als MAx!

## Git Setup
First we need to add our Github credentials to git.
- Open git-bash
- Type:  
`git config --global user.name`  
`git config --global user.email`
- Should both be empty
- Set those values with:  
`git config --global user.name "Hans Wurst"`  
`git config --global user.email "mail@mail.com"`

## Get an Existing Repository
- Go to the [repository](https://github.com/maxehrhardt/git_introduction.git) you wanna clone.
- Click on "Clone or Download" and copy the link
- Open git-bash and `cd` to the folder you want the repo to be in
- `git clone https://github.com/maxehrhardt/git_introduction.git`
  
## Create Your Own Repo
### 1. Create a new repository on github.com  
You will see following message:  
```
…or create a new repository on the command line
echo "# git_introduction" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/maxehrhardt/git_introduction.git
git push -u origin master
                
…or push an existing repository from the command line
git remote add origin https://github.com/maxehrhardt/git_introduction.git
git push -u origin master
```
### 2. Get it on your computer
- Open git-bash
- `cd` to the folder where the repo should be
- Create a git repo locally 
  ```
  git init
  ```
- Create the file `README.md`
- Add it to a commit
  ```
  git add README.md
  ```
- Create commit
  ```
  git commit -m "Initial commit"
  ```
- Now we need to connect the local repository to the remote repository
  ```
  git remote add origin https://github.com/maxehrhardt/git_introduction.git
  ```
- And as last step we push our changes
  ```
  git push -u origin master
  ```

### 3. Explanations
The repository consists of 3 instances:

- The workspace is the directory with all the files in the current state
- The Index is a buffer, all added changes can still be reverted without tracks.
- The local repository contains all versions of all files in the repo. Everything committed to here is tracked.
- The remote repository is the shared repo on some server.

![image](images/01/git_workflow.png)

# Resources

# Command Library

| Command | Options | Explanation
| --- | --- | --- |
| `ls` |  | Shows content of current folder |
| `cd` |  <ul style="list-style-type:none;"><li>..</li><li>[filepath]</li></ul> | <ul style="list-style-type:none;"><li>Goes one folder up</li><li>Changes to the given file path</li></ul>  |
| `git init` |  | This command initializes a new git repo in the current  folder |
| `git add` | <ul style="list-style-type:none;"><li>.</li><li>[filepath]</li></ul> |<ul style="list-style-type:none;"><li>Adds all changes to commit</li><li>Only adds the changes of given file to commit</li></ul> |
| <nobr>`git commit` </nobr>| <ul style="list-style-type:none;"><li>-m "Message"</li></ul> |<ul style="list-style-type:none;"><li>Creates a commit with all added changes and the given message</li></ul> |
| `git clone ` | <nobr>[remote link] [folder name] </nobr> | Clones the repository from the remote link to the given folder. If no folder name is given the name of the repo is used. |
