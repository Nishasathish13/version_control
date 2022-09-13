# version_control
Documentation of complete Version control system

#### What is version control?
A Version Control System is just software that helps you control (or manage) the different versions...of something (typically source code).

#### Version control system:
There are a number of Version Control Systems out there. This alone should prove that version control is incredibly important. Three of the most popular version control systems are:

- Git
- Subversion
- Mercurial

#### There are two main types of version control system models:

-the centralized model - all users connect to a central, master repository

<img width="550" alt="image" src="https://user-images.githubusercontent.com/75114179/189885189-9b398d11-f49e-4a4b-bda7-e2bd25530852.png">

-the distributed model - each user has the entire repository on their computer

<img width="550" alt="image" src="https://user-images.githubusercontent.com/75114179/189885290-cf4bd87f-f95e-46da-863c-f29833057fa3.png">

#### Git v/s Github

<img width="400" alt="image" src="https://user-images.githubusercontent.com/75114179/189885553-2497c6c5-dd09-4bf9-bf9e-34d71c1702eb.png">

### Terminologies

1. **Version Control System / Source Code Manager**

A version control system (abbreviated as VCS) is a tool that manages different versions of source code. A source code manager (abbreviated as SCM) is another name for a version control system. Git is an SCM (and therefore a VCS!). The URL for the Git website is https://git-scm.com/ (see how it has "SCM" directly in its domain!).

2. **Commit**

Git thinks of its data like a set of snapshots of a mini filesystem. Every time you commit (save the state of your project in Git), it basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. You can think of it as a save point in a game - it saves your project's files and any information about them.
Everything you do in Git is to help you make commits, so a commit is the fundamental unit in Git.

3. **Repository / repo**

A repository is a directory which contains project work, as well as a few files which are used to communicate with Git. Repositories can exist either locally on computer or as a remote copy on another computer. A repository is made up of commits.

4. **Working Directory**

The Working Directory is the files that we see in our computer's file system. When we open our project files up on a code editor, we're working with files in the Working Directory.

5. **Staging Area / Staging Index / Index**

A file in the Git directory that stores information about what will go into our next commit. We can think of the staging area as a prep table where Git will take the next commit. Files on the Staging Index are poised to be added to the repository.

6. **SHA**

A SHA is basically an ID number for each commit. Here's what a commit's SHA might look like: e2adf8ae3e2e4ed40add75cc44cf9d0a869afeb6.

It is a 40-character string composed of characters (0–9 and a–f) and calculated based on the contents of a file or directory structure in Git. "SHA" is shorthand for "Secure Hash Algorithm".

7. **Branch**

A branch is when a new line of development is created that diverges from the main line of development. This alternative line of development can continue without altering the main line. The key thing that makes branches incredibly powerful is that you can make save points on one branch, and then switch to a different branch and make save points there, too.


