# GitHub Workflow Documentation

This document outlines the formal process of uploading code to GitHub, forking a repository, making modifications, and submitting a pull request. The process involves two collaborators: the original repository creator (Owner) and another contributor (Contributor).

## Uploading Code to GitHub (Owner)

### Step 1: Create a New Repository

1. Navigate to the GitHub website.
2. Click on the "+" sign in the top right corner and choose "New repository."
3. Fill in the repository name, description, and other necessary details.
4. Initialize the repository with a README file if needed.
5. Click "Create repository."

### Step 2: Upload Code

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/repository-name.git
    ```

2. Move your code files into the local repository directory.

3. Add, commit, and push the changes to GitHub:
    ```bash
    git add .
    git commit -m "Initial commit"
    git push origin main
    ```

4. The code is now uploaded to the GitHub repository.

## Forking and Modifying Code (Contributor)

### Step 3: Fork the Repository

1. Visit the GitHub repository of the Owner.
2. Click the "Fork" button in the top right corner to create a personal fork.

### Step 4: Clone the Forked Repository

1. Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/your-username/repository-name.git
    ```

2. Move into the local repository directory.

### Step 5: Make Code Modifications

1. Make the necessary code changes.

2. Add, commit, and push the changes to your fork:
    ```bash
    git add .
    git commit -m "Description of changes"
    git push origin main
    ```

## Pull Request Process (Contributor)

### Step 6: Create a Pull Request

1. Visit your forked repository on GitHub.

2. Click on the "Pull Requests" tab and then "New Pull Request."

3. Ensure the base repository and branch are set to the Owner's repository and the main branch.

4. Describe the changes made and click "Create Pull Request."

### Step 7: Owner Reviews and Accepts

1. The Owner receives a notification of the new pull request.

2. The Owner reviews the changes, asks for clarification or further modifications if needed, and leaves comments.

3. If satisfied, the Owner merges the pull request.

4. The changes are now reflected in the original repository.

## Conclusion

This documented workflow ensures a systematic process for collaborating on GitHub. It promotes transparency, collaboration, and effective version control for software development projects.

