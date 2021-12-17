# Git Cheat sheet

1. Cloning a repository:

    -   To begin using a repository you must clone a repository
    
        ``` git clone <repository name>``` 
        
        Example : ```git clone https://github.com/krc92001/HLTGitcheatsheet.git```

2. Make sure your Local repository is updated:

    - To ensure that the Repository is updated use a ```GIT PULL```  
        - This is a combination of a ```git fetch``` and ```git merge``` (Fetch grabs the changes and merge pushes them to your local repo)
    - ```git pull``` (While in the repository)



## Commands to know:

``` git commit``` - This commits changes to the local repository and stages for a push
<p align="center"> Options</p> 

***

-m : sets a commit message; Requires a filename unlike -a EX: ```git commit -m "This is an example message" <filename> ```

-a :  commits all files that have been modified EX: ``` git commit -am  "-a commits all files" ```

***

```git push ``` - this will push changes to the branch in the Bitbucket repository

```git checkout  ``` - Changes the branch simply insert the branch after EX: ```git checkout example_branch ```

<p align="center"> Options</p> 

***
-b : creates a new branch ```git checkout -b new_branch```

***

```git status ``` - Shows the current status of the git repo and the branch you are currently on

```git diff ``` - Shows the changes from the previous version of a file EX: ```git diff <filename> ```

```git add``` - adds a local file to git repo EX: ```git add file_path.md  ```
