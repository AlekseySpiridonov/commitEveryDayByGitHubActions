# Commit Every Day By GitHub Action
Just for fun project for creating commit(s) every day by GitHub Actions.  

If you need (for some reasons) simulate activity on GitHub you can setup your repository with GitHub Action Workflow from this repository.  
Example of workflow: [action-just4fun.yml](https://github.com/AlekseySpiridonov/commitEveryDayByGitHubActions/blob/master/.github/workflows/action-just4fun.yml)  
Status of workflow: ![Commit4Fun](https://github.com/AlekseySpiridonov/commitEveryDayByGitHubActions/workflows/Commit4Fun/badge.svg)
  
You can configurate schedule of job:
```
  schedule:
    - cron: 0 12 * * *
  # Run job every day at 12:00 UTC
```
and user credentials:
```
        git config --local user.email "action-commit-bot@example.com"
        git config --local user.name "Dummy Fake Activity Bot"
```
  
P.S. Do not forgot enable GitHub Action in repository's settings.
# Why?
Just for fun! :)
# Why might this not work?
- GitHub Actions was disabled for repository
- Commits are not meet [GitHub conditions](https://help.github.com/en/github/setting-up-and-managing-your-github-profile/why-are-my-contributions-not-showing-up-on-my-profile)
```
Commits will appear on your contributions graph if they meet all of the following conditions:

The email address used for the commits is associated with your GitHub account.
The commits were made in a standalone repository, not a fork.
The commits were made:
In the repository's default branch (usually master)
In the gh-pages branch (for repositories with project sites)
```
