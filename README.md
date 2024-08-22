# PLPBasicGitAssignment

This repository demonstrates basic Git and GitHub usage.

## Setup Instructions

### Repository Setup

1. **Create a GitHub Repository:**
   - Log in to GitHub.
   - Create a new repository named `PLPBasicGitAssignment`.
   - Initialize with a README file.

### Local Setup

2. **Local Folder Setup:**
   - Create a local folder named `PLPBasicGitAssignment`.
   - Navigate to the folder in the terminal:
     ```bash
     cd path/to/PLPBasicGitAssignment
     ```

3. **Git Initialization:**
   - Initialize a new Git repository:
     ```bash
     git init
     ```

4. **Connecting to GitHub:**
   - Link the local repository to GitHub:
     ```bash
     git remote add origin <https://github.com/fredjuma007/PLPBasicGitAssignment.git>
     
### Making Changes

5. **Create a File:**
   - Create `new-text_file.txt` with the message "Hello, Git!".

6. **Committing Changes:**
   - Stage the file:
     ```bash
     git add hello.txt
     ```
   - Commit the changes:
     ```bash
     git commit -m "text file with a quote"
     ```

### Pushing to GitHub

7. **Push Changes:**
   - Push to GitHub:
     ```bash
     git push -u origin main
     ```

## Verification

8. **Verify on GitHub:**
   - Check the repository on GitHub to ensure the file and commit are present.