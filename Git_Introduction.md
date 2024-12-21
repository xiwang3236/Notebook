# Git Introduction

## Getting Started
- **Version Control**
  - Local Version Control Systems (RCS)
  - Centralized Version Control Systems (SVN)
  - Distributed Version Control Systems (Git)
- **Installation**
- **Environment Setup**
  - Learn Linux Commands
    > ## Linux Command Cheat Sheet
    > 1. **`cd`**: Change directory.
    > 2. **`cd ..`**: Move up one directory level. Use `cd` to go directly to the default directory.
    > 3. **`pwd`**: Display the current directory path.
    > 4. **`ls` (`ll`)**: List all files in the current directory. `ll` provides more detailed information.
    > 5. **`touch`**: Create a new file. For example, `touch index.js` creates a new file named `index.js` in the current directory.
    > 6. **`rm`**: Delete a file. For example, `rm index.js` deletes the file `index.js`.
    > 7. **`mkdir`**: Create a new directory. For example, `mkdir new_folder` creates a directory named `new_folder`.
    > 8. **`rm -r`**: Delete a directory. For example, `rm -r src` deletes the directory `src`.
    > 9. **`mv`**: Move a file. For example, `mv index.html src/` moves `index.html` to the `src` directory. Ensure the source and target directories exist.
    > 10. **`reset`**: Reinitialize and clear the terminal.
    > 11. **`clear`**: Clear the terminal screen.
    > 12. **`history`**: View the command history.
    > 13. **`help`**: Display help information.
    > 14. **`exit`**: Exit the terminal.
    > 15. **`#`**: Used for comments.

  - Configuration

## Git Basics
- **Basic Theory**
  - **Working Areas**
    - Local
      - **Working Directory:** The workspace where files are dited. It contains the files currently being worked on.
      - **Repository (or Local Repository):** A secure storage area for data, containing all the versions of files you have committed. The HEAD pointer references the latest version committed to the repository.
      - **Staging Area (Stage/Index)** A temporary area for storing changes. Essentially, it is a file that holds information about the files that are about to be committed.
    - Remote
      - Remote Repository
  - **File States**
    - Untracked
    - Unmodified
    - Modified
    - Staged
- **File Operations**
  - View File States
  - Ignore Files (`.gitignore`)
  
    > ### Comments Example
    > *.txt # Ignore all files ending with .txt  
    > !lib.txt # Except for lib.txt   
    > /temp # Ignore the temp file only in the project's root directory, but not in other directories   
    > build/ # Ignore all files in the build/ directory   
    > doc/*.txt # Ignore doc/notes.txt but not doc/server/arch.txt

- **Basic Workflow**
  - Diagram of Workflow
  - ![Git Basic Workflow](fig\git_basic_workflow.png)
- **Other Operations**

## Git Branches
- **List Branches**
  - Local Branches
  - All Remote Branches
- **Create a New Branch**
  - Stay in Current Branch: git branch [branch-name]
  - Switch to the New Branch: git checkout -b [branch]
- **Merge Branches**
  - git merge [branch]
