## Git Commands Cheat Sheet

### Basic Commands

- **`git init`**: Initialize a new Git repository in the current directory.
- **`git clone [url]`**: Clone a remote repository to create a local copy on your machine.
- **`git add [file]`**: Add file changes to the staging area in preparation for committing.
- **`git commit -m "[message]"`**: Record changes to the repository with a descriptive commit message.
- **`git status`**: Check the status of files in the working directory, staging area, and repository.

### Branching and Merging

- **`git branch`**: List all branches in the repository.
- **`git branch [branch_name]`**: Create a new branch with the specified name.
- **`git checkout [branch_name]`**: Switch to the specified branch.
- **`git merge [branch_name]`**: Merge changes from the specified branch into the current branch.

### Remote Repositories

- **`git remote -v`**: List all remote repositories associated with the local repository.
- **`git remote add [name] [url]`**: Add a new remote repository with the specified name and URL.
- **`git remote remove [name]`**: Remove the remote repository with the specified name.
- **`git pull`**: Fetch changes from the remote repository and merge them into the current branch.
- **`git push`**: Push local changes to the remote repository.

### Viewing History

- **`git log`**: Display the commit history of the repository.
- **`git log --oneline`**: Display the commit history in a condensed format.
- **`git diff`**: Show the changes between the working directory and the staging area.

### Miscellaneous

- **`git reset [file]`**: Unstage the specified file, keeping its changes in the working directory.
- **`git stash`**: Stash changes in the working directory for later use.
- **`git config`**: Configure Git settings, such as user name, email, and aliases.
- **`git tag`**: Create, list, or delete tags in the repository.


### Creating .gitignore File

- **Creating a .gitignore file**: Create a `.gitignore` file to specify intentionally untracked files that Git should ignore. Here's how to create one:
  1. Create a new file named `.gitignore` in the root directory of your repository.
  2. Add patterns for files or directories you want Git to ignore. Each pattern should be on a new line.
     Example:
     ```
     # Ignore files with .log extension
     *.log
     
     # Ignore directory named "temp"
     temp/
     ```
  3. Save the `.gitignore` file.
