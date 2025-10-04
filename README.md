# Cross-Project-File-Transfer-Pipeline
This project contains GitLab workflow to transfer file from one GitHub Repo to another and create a merge request for that change.

# Implementation
1. Checks out to the 'portfolio' repository.
2. Copies the README.md file from 'portfolio' to 'file-update' branch in this repo.
3. Creates a pull request from 'file-update' branch to 'test' branch in this repo.
