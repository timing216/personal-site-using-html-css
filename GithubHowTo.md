Checklist before following the steps
In your terminal, make sure you’re in your repository directory!!
If not, you need to “cd” into the correct directory
Write your code in your feature branch.
Do NOT commit anything to your main branch
Follow the git workflow steps below

Step 1: Creating new branch / Checking out to existing branch
// Creating a new branch - git checkout main - git pull - git checkout -b <your-branch-name>

// Checking out to an existing branch - git checkout <branch-name> - git pull origin main

Step 2: Working on your feature/code in a branch
// if you have multiple changes, but you only want to add specific file changes to staging, do
// not do git add . follow the “or” steps

    - git add .
        or
    - git status
    - git add <path-to-file>

    - Using VSCode SourceControl double check that all your code under “Staged Changes”
      are what you want to commit (screenshot)

    - git commit -m "<your-meaningful-commit-message>"

Step 3: After you're done working on your feature/code in a branch
In your terminal:

- git push origin <branch-name>

On your GitHub: - Refresh your repository page on GitHub - Click on “Compare & pull request” (screenshot) - Click on “Create pull request” (screenshot) - Click on “Merge pull request” (screenshot) and “Confirm merge”, afterwards

After you’ve merged your Pull Request - Follow Step 1 all over again.
