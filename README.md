# GiteaHub Sync Script

This repository contains a Bash script that simplifies the process of syncing your GitHub and Gitea repositories. The script automates credential configuration, branch checking, remote setup, file staging, committing, and pushing changes to both repositories.

## Features

- **Credential Configuration**: Ensures your Git username and email are properly set.
- **Branch Validation**: Verifies you are on the correct branch before making changes.
- **Remote Management**: Adds GitHub and Gitea remotes if they are not already configured.
- **File Staging**: Stages specified files or all changes if no files are provided.
- **Commit and Push**: Prompts for a commit message and pushes changes to both GitHub and Gitea repositories.

## Prerequisites

Before using the script, ensure you have the following:

1. Git installed on your system.
2. A GitHub repository URL (provided in the script as `github_repo`).
3. A Gitea repository URL (provided in the script as `gitea_repo`).
4. Proper SSH or HTTPS authentication set up for both repositories.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/SpiXla/giteahub.git
   cd giteahub
