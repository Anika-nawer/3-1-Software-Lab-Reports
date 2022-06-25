**Experiment No:** 01

**Experiment Name:** Study and verification of different commands of git.

**Theory:** Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.It is a software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

There are a lot of different ways to use Git.Git supports original command-line tools and many graphical user interfaces of varying capabilities.The git command line is the only place where anyone can run all Git commands.

**Required Software:** vs Code

**Required Language:** Markdown
# Git Commands #
## 1 . Git Config command 

This command configues the user. This command sets the author name and email address to be used with commits.
```
$ git config --global user.name "Anika"
$ git config --global user.email "anikanawer8@gmail.com"
```
## 2. Git init command

This command is used to make a local empty repository.
```
$ git init 
```

## 3. Git clone command

This command is used to make a copy of a repository from an existing URL into the local repository.
```
$ git clone <URL>
```

## 4. Git add command

This command is used to add one or more files to staging area.

To add a single file 
```
$ git add <filename>
```
To add all existing files
```
$ git add .
```
## 5. Git commit command

This command records or snapshots the file permanently in the version history with a message.
```
$ git commit -m "Commit Message"
```
## 6. Git status command

The status command is used to display the state of the working directory and the staging area.
```
$ git status
```
## 7. Git restore command

This command is used to get back to the previous work and omit the recent changes.
```
$ git restore <filename>
```
## 8. Git branch command

This command shows all the branches available in the repository.
```
$ git branch
```
## 9. Git checkout command

This command is used to get back to the previous version or get back to the any previous commited version.
```
$ git checkout <branchname>
```
## 10. Git push command

This command is used to upload local repository content to a remote repository.
```
$ git push --all
```
## 11. Git pull command

Pull command is used to receive data from Github.It fetches and merges changes on the remote server to the working directory.
```
$ git pull origin master 
```
## 12. Git merge command

This command is used to merge the specified branch's history into the current branch.
```
$ git merge <branchname>
```
## 13. Git log command

This command is used to check the commit history.
```
$ git log
```
## 14. Git remote command

This remote command is used to connect the local repository to the remote server.
```
git remote add <name> <url>
```