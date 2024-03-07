# Part 2 | Questions
### 1. List three major version control for software engineering.
- Git
- Mercurial SCM
- Apache Subversion

---
### 2. What are the main advantages to using Git in your software development, and how is it useful for game developers?
- **Feature branch workflow:** Provides an isolated environment for every change to your code base. 
This allows for developers to work on features without affecting the main branch and ensures that it always contains production-quality code.

- **Distributed development:** Developers get their own local repository, complete with a full history of commits. 
Having a full local history makes using Git fast, since a network connection isn't required to create commits, inspect previous versions of a file, or perform diffs between commits.

- **Pull requests:** A way to ask another developer to merge one of your branches into their repository, allowing for an easier way to keep track of changes and allows for discussions around their work before integrating it into the rest of the codebase.

---
### 3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge.
```Branch``` - A new/seperate version of the main repository, allows you to work on different parts of a project without affecting the main project. <br> 
```Pull``` -  Fetches and downloads from the remote repository and updates the local repository to match it. <br>
```Push``` - Upload any changes that have been commited to the repository. <br>
```Repository``` - A place where you can store your code, your files, and each file's revision history. Repositories can have multiple collaborators and can be either public or private. <br>
```Working Copy``` - A directory full of files with a .git subdirectory, which is the same as a local git repository. <br>
```Merge``` - Takes changes from a branch and applies them to another branch, merging them together. <br>

---
### 4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git?
- Security
- Copyright
- Privacy

---
### 5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
a

---
### 6. In a merged source code file, how does Git let you know there is a conflict?
a

---
### 7. What are the steps you can take to resolve Git conflicts?
a

---
### 8. What does git revert do, and how can you use it?
The ```git revert``` command is used to undo a single commit by taking you back to the staged files before the commit, and instead creates a new commit without the changes. <br>

``git revert`` 

---
### 9. What does git reset do, and how can you use it? 
The ```git reset``` command is used to undo all changes made in the working directory, and resets back to a specific commit while discarding all commits made. <br>

``git reset`` 

---
### 10. What is the difference between git revert and git reset?
```git revert``` <br>
a

```git reset``` <br>
a

---
### 11. True or False: It is okay to commit broken code to the main branch.
a

---
### 12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
a

---
### 13. Describe what is DevOps, how is it useful for game developers?
a

---
### 14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
a

---
### 15. What is CI/CD and how can it be used to automate the game development process?
a

---