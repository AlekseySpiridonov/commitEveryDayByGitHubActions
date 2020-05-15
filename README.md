# Commit Every Day By GitHub Action
Just for fun project for creating commit(s) every day by GitHub Actions.  

If you need (for some reasons) simulate activity on GitHub you can setup your repository with GitHub Action Workflow from this repository.  
Example of workflow: [action-just4fun.yml](https://github.com/AlekseySpiridonov/commitEveryDayByGitHubActions/blob/master/.github/workflows/action-just4fun.yml)  
  
You can configurate schedule of job:
```
  schedule:
    - cron: 0 12 * * *
  # Run job every day at 12:00 UTC
```
OR user credentials:
```
        git config --local user.email "action-commit-bot@example.com"
        git config --local user.name "Dummy Fake Activity Bot"
```
  
P.S. Do not forgot enable GitHub Action in repository's settings.
# Why?
Just for fun! :)
