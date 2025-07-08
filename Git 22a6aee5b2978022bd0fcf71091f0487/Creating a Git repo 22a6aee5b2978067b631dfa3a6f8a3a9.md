# Creating a Git repo

- **repository:** (repo) its like a folder that Git will track, it stores all project code files, changes and history
- create a new folder where we want to save our code files

### Git commands:

- `git init`
    - it will initialize a new git repository in our current folder
    - it creates a hidden `.git/` folder to start tracking our project
    - `.git` directory contains metadata of git repo that is used by version control system
    - this command is always used when we are starting a project from scratch
- `git status`
    - this cmmnd is used to used to see what’s going inside our current repo right now
    - it shows which files have changed, staged or not staged or are untracked
    - this command is usually used before committing to see what needs attention
- `git clone`
    - this cmmnd is used to download an existing repository from github to our local system
    - it automatically connects to remote repo so that we can directly pull and push
    - it is mainly used to work on any existing project or like to contribute to open source projects
- `git log`
    - it shows a history of commits in our repo
    - history includes commit hash(unique id), author name, date and commit message
    - it helps us track progress and identify who made changes
    - `git log -online` : it shows the compact version of history which great for quick history review