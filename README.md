# Important Notes

1. Git remote add orgin https://github.com/terraawsuser/aws-terraform.git >> linking the locala and remote repository so we can push code from local 

2. git remote set-url orgin https://terraawsuser@github.com/terraawsuser/aws-terraform.git
3. git push  
4. git push --set-upstream orgin new-feature
5. git branch -d branch-name
6. Git checkout main - to switch to branches
7. git push origin --delete branch-name


git init Initialize a Git repository (only required once per project)
git add <file(s)> Stage code changes (for the next commit)
git commit -m “…” Create a commit for the staged changes (with a message)
git status Get the current repository status (e.g., which changes are staged)
git log Output a chronologically ordered list of commits
git checkout <id> Temporarily move back to commit <id>
git revert <id> Revert the changes of commit <id> (by creating a new commit)
git reset <id> Undo commit(s) up to commit <id> by deleting commits
GitHub Actions: Availability & Pricing
In public repositories, you can use GitHub Actions for free. For private repositories, only a certain amount of monthly usage is available for free - extra usage on top must be paid.

The exact quotas and payment details depend on your GitHub plan, a detailed summary can be found here: https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions

If you can't find an "Actions" tab in your GitHub repository, you can should enable them as described here: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository
