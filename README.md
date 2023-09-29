# git_tutorial_notes

## Commands of git
### 1. git config --global --list
   
    The `git config --global --list` command is used to display a list of Git configuration settings that are set globally for your user account on your computer. 

    Here's what each part of the command means:
    
    - `git config`: This is the Git command for configuring various settings in Git.
    
    - `--global`: This flag indicates that you want to view or set a global configuration setting that applies to your user account across all Git repositories on your system. Global settings     are stored in a file typically located in your home directory, often named `.gitconfig` or `.config/git/config`.
    
    - `--list`: This flag tells Git to list the current configuration settings. Git will display a list of configuration variables and their values.
    
    When you run `git config --global --list`, Git will list all the global configuration settings that have been set, including your name, email, core.editor, and any other configuration         options you may have set. This can be helpful for checking your Git configuration to ensure it's set up correctly.

 ### 2. Setting your user name
     git config global user.name "Your name"
 ### 3. Setting your email id 
     git config global user.email "example@gmail.com"

     


    
