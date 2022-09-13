# Hands-on

#### Create A Git Repo

Before we make commits or do anything else with a git repository, the repo needs to actually exist. To create a new repository with Git, we'll use the ```git init``` command.

The init subcommand is short for "initialize", which is helpful because it's the command that will do all of the initial setup of a repository.

**Other useful commands:**

ls - used to list files and directories
mkdir - used to create a new directory
cd - used to change directories
rm - used to remove files and directories
pwd - print working directory

#### Create Course Directories

Enter the desired working directory using ```cd``` command

create a directory ABC (udacity-git-course), inside that, create another directory called XYZ (new-git-project)
use the cd command to move into the new-git-project directory

Run the below command in the cmd
```- mkdir -p udacity-git-course/new-git-project && cd $_ ```

<img width="549" alt="image" src="https://user-images.githubusercontent.com/75114179/189935700-580e51d8-f40f-411a-9cd0-e93d6b1f44b2.png">

#### run ```git init``` command

Running the ```git init``` command sets up all of the necessary files and directories that Git will use to keep track of everything. All of these files are stored in a directory called .git. This .git directory is the "repo"! This is where git records all of the commits and keeps track of everything!

**Contents of .git: Brief synopsis on each of the items in the .git directory:**

<img width="133" alt="image" src="https://user-images.githubusercontent.com/75114179/189953177-2af65380-61af-4d3c-931f-b53c07d2b6f8.png">

config file - where all project specific configuration settings are stored.

description file - this file is only used by the GitWeb program, so we can ignore it

hooks directory - this is where we could place client-side or server-side scripts that we can use to hook into Git's different lifecycle events

info directory - contains the global excludes file

objects directory - this directory will store all of the commits we make

refs directory - this directory holds pointers to commits (basically the "branches" and "tags")

#### ```git clone```

command: ```$ git clone https://path_of_folder_to_be_cloned```

- takes the path to an existing repository
- by default will create a directory with the same name as the repository that's being cloned
- can be given a second argument that will be used as the name of the directory
- will create the new repository inside of the current working directory

The git clone command is used to copy an existing repository into a folder in the current directory. ```cd``` newly cloned directory

#### ```git status```

The git status is key to the mind of Git. It will tell us what Git is thinking and the state of repository as Git sees it.
The output of git status will change depending on if files have been added/deleted/modified, what's on the staging index, and the state of the repository
