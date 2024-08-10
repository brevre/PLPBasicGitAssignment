# PLPBasicGitAssignmentTask 1: Repository Setup 

1.GitHub Repository Creation: 

   - Log in to your GitHub account. 

   - Click the+ icon in the upper right corner and selectNew repository. 

   - Name the repository `PLPBasicGitAssignment`. 

   - CheckInitialize this repository with a README. 

   - ClickCreate repository. 

  

Task 2: Local Setup 

2.Local Folder Setup: 

   - Create a new folder on your local machine named `PLPBasicGitAssignment`. 

   - Open a terminal (on macOS or Linux) or Command Prompt (on Windows). 

   - Navigate to the newly created folder using the command: 

```bash 

cd path/to/PLPBasicGitAssignment 

```  

  

3.Git Initialization: 

   - Initialize a Git repository in the folder: 

```bash 

git init 

``` 

  

4.Connecting to GitHub: 

   - Link your local repository to the GitHub repository. Use the URL provided on your GitHub repository page: 

```bash 

git remote add origin <repository-url> 

``` 

Replace `<repository-url>` with the actual URL of your GitHub repository (e.g., `https://github.com/username/PLPBasicGitAssignment.git`). 

  

Task 3: Making Changes 

  

5.Create a File: 

   - Inside your local folder, create a new text file named `hello.txt`. 

   - Open `hello.txt` in your code editor and add the text: 

``` 

Hello, Git! 

``` 

  

6.Committing Changes: 

   - Stage the changes: 

```bash 

git add hello.txt 

``` 

   - Commit the changes: 

```bash 

git commit -m "Add hello.txt with a greeting" 

``` 

  

Task 4: Pushing to GitHub 

7.Pushing to GitHub: 

   - Push the committed changes to GitHub: 

```bash 

git push -u origin main 

``` 

  

Task 5: Verification 

  

8.Verify on GitHub: 

   - Open your web browser and go to your GitHub repository URL. 

   - Verify that the `hello.txt` file is visible and that the commit message "Add hello.txt with a greeting" is present. 

  

This assignment covers fundamental Git and GitHub concepts, including repository creation, local setup, making changes, committing, and pushing updates to GitHub. 
