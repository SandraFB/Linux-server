# Setting up a repository

## git init git clone git config

This tutorial provides an overview of how to set up a repository (repo) under Git version control. This resource will walk you through initializing a Git repository for a new or existing project. Included below are workflow examples of repositories both created locally and cloned from remote repositories. This guide assumes a basic familiarity with a command-line interface.

The high level points this guide will cover are:

- Initializing a new Git repo
- Cloning an existing Git repo
- Committing a modified version of a file to the repo
- Configuring a Git repo for remote collaboration
- Common Git version control commands

By the end of this module, you should be able to create a Git repo, use common Git commands, commit a modified file, view your project’s history and configure a connection to a Git hosting service (Bitbucket).

## What is a Git repository?

A [Git repository](https://www.atlassian.com/git/tutorials/setting-up-a-repository) is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed. 

## Initializing a new repository: git init

To create a new repo, you'll use the *git init* command. 'git init' is a one-time command you use during the initial setup of a new repo. Executing this command will create a new '.git' subdirectory in your current working directory. This will also create a new main branch. 

## Versioning an existing project with a new git repository

This example assumes you already have an existing project folder that you would like to create a repo within. You'll first cd to the root project folder and then execute the git init command.
