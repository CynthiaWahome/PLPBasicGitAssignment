# PLPBasicGitAssignment
## Hands-On Assignment: Basic Git And GitHub Workflow

Objective: The purpose of this assignment is to instruct students in the rudimentary procedures of establishing a GitHub repository, synchronizing it with a local directory, and executing commits and pushes.

Requirements: 
- Secure a GitHub account (if you haven't already).
- Install Git on your local device.
- Choose a preferred code editor (for example, Visual Studio Code, Sublime Text).

Steps:

Task 1: Repository Initialization
1. Access your GitHub account and create a new repository named "PLPBasicGitAssignment", initializing it with a README file.

Task 2: Local Setup
2. Create a new folder on your computer (e.g., "PLPBasicGitAssignment").
3. Open a terminal or command prompt, then navigate to the newly created folder.
4. Commence a Git repository within the local folder.
5. Connect your local repository to the GitHub repository you created in Task 1 using the command `git remote add origin <repository-url>`. Replace `<repository-url>` with the actual URL of your GitHub repository.

Task 3: Implementing Changes
6. Inside your local folder, create a new text file (e.g., `hello.txt`). Add a simple text message (e.g., "Hello, Git!").
7. Stage the changes using `git add hello.txt`.
8. Commit the changes with `git commit -m "Add hello.txt with a greeting"`.

Task 4: Uploading to GitHub
9. Push the committed changes to your GitHub repository using `git push -u origin main`.

Task 5: Verification
10. Check your GitHub repository in a web browser to confirm the presence of the `hello.txt` file and the commit message.
