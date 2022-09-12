# DN-Tools
Repository of DN-Tools for DN People. 

## Overview For DN Contributors
Welcome to DN-Tools. The instructions below will describe how you can contribute.

## Development Process

### Git and GitHub
The development process will use GitHub (and Git) for Project Management, Issue/Bug Management , Wiki, CI/CD and of course Source Control. This means no Jira, no Confluence, no Bitbucket. GitHub is feature rich so there should be no reason to step outside Git/GitHub. 

The focus will be in social coding - or InnerSource - as GitHub is a social coding platform. Anyone within DN can contribute to these projects. 

It is assumed you have a basic understanding of Git and GitHub. 

### Projects
A GitHub project is an adaptable spreadsheet for tracking work. All work done within DN-Tools should be executed in the context of a project. More information on GitHub projects is available [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects).

### Issues
All code changes start here. Issues are new features; bugs are product faults or unexpected behaviour. From an Issue/Bug you create a branch leading to a pull request. More information on Issues is available [here](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues).

You can close issues automatically when a pull request closes by adding a comment in the pull request. For example, the comment: 

`Closes #8`

will close the Issue with the id 8 when the pull request closes. 

### GitHub Flow
We will use the [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) with some modifications. 

First, create your branch off main using the GitHub GUI (from the Issue/Bug page) and then `git pull` from your workstation to pull down the branch.  Don't create branches on your workstation. I want to tie pull requests to release notes. All changes should start at Issues/Bugs. We want the paperwork. 

Second, branches will be deleted when a pull request is merged; this will be done by the merge meister. At the same time, I'm looking to add [GitHub Apps](https://probot.github.io/) that can do this automatically. 


### GitHub Actions
GitHub Actions will be used to automate parts of the SDLC. 







