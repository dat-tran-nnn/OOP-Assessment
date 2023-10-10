# Assessment Part 2

### 1. List three major version control for software engineering.
AccuRev, AzureDevOps, Git
### 2.What are the main advantages to using Git in your software development, and how is it useful for game developers.
Git is a distributed version control system. It records changes made to codes and enables collaboration, thus making it useful for game developers.
### 3.Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
* Branch: A seperate version of the main repo
* Pull: Fetch a remote repo and update the local
* Repository: A collection of files
* Working copy: A directory with .git files
* Merge: Combine branches into one unified history
### 4.If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Data backup policy & procedure.
### 5.Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
Tower GIT GUI, mergetool
### 6.In a merged source code file, how does Git let you know there is a conflict?
An error will appear "A conflict in the file ... occured" and the file will include the differences between 2 branches
### 7.What are the steps you can take to resolve Git conflicts?
Use certain tools to get a good visualization of the the conflict, edit change, commit
### 8.What does git revert do, and how can you use it?
Git revert command can be use to undo changes to a repository's commit history. Type "git revert [branch name]"
### 9.What does git reset do, and how can you use it? 
Git reset command moves the repo back to a previous commit. Type "git reset [soft/hard] [branch name]"
### 10.What is the difference between git revert and git reset?
Revert is similar to undo while reset allow us to return to previous commit
### 11.True or False: It is okay to commit broken code to the main branch. 
False
### 12.True or False: A commit should only include files that are related to the change you are committing to the repo.
True
### 13.Describe what is DevOps, how is it useful for game developers?
DevOps is a practice that combines Development and Operations to enable collaboration and coordination. This would speed the game developing process and increase productivity
### 14.List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
* Miro: Collaborative brainstorming for teams
* Github: Collaborative coding for teams
* Jira Software: Project management for teams
### 15.What is CI/CD and how can it be used to automate the game development process?
CI (Continuous integration) automatically integrate code changes and updates while also detect bugs. 
CD (Continuous Deployment) automates the delivery of updates directly to clients. Once the game dev team
made quick fixes to the game, it could be automatically checked for errors through CI and sent to CD for
the game to update
