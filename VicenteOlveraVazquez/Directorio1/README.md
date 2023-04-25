#Setting up a repository
##git init / git clone / git config
*Cursiva*
**Negritas**
This tutorial provides an overview of how to set up a repository (repo) under Git version control.
This resource will walk you through initializing a Git repository for a new or existing project.
Included below are workflow examples of repositories both created locally and cloned from remote repositories. 
This guide assumes a basic familiarity with a command-line interface.

The high level points this guide will cover are:

- Initializing a new Git repo
- Cloning an existing Git repo
- Committing a modified version of a file to the repo
- Configuring a Git repo for remote collaboration
- Common Git version control commands

By the end of this module, you should be able to create a Git repo, use common Git commands, commit a modified file, 
view your project’s history and configure a connection to a Git hosting service (Bitbucket).

##What is a Git repository?

A Git repository is a virtual storage of your project. It allows you to save versions of your code, which 
you can access when needed.

##Initializing a new repository: git init

To create a new repo, you'll use the git init command. git init is a one-time command you use during 
the initial setup of a new repo. Executing this command will create a new .git subdirectory in your 
current working directory. This will also create a new main branch. 

##Versioning an existing project with a new git repository

This example assumes you already have an existing project folder that you would like to create a repo 
within. You'll first cd to the root project folder and then execute the git init command.

Pointing git init to an existing project directory will execute the same initialization setup as mentioned 
above, but scoped to that project directory.

##Cloning an existing repository: git clone

If a project has already been set up in a central repository, the clone command is the most common way for 
users to obtain a local development clone. Like git init, cloning is generally a one-time operation. Once a 
developer has obtained a working copy, all version control operations are managed through their local repository.

git clone is used to create a copy or clone of remote repositories. You pass git clone a repository URL. 
Git supports a few different network protocols and corresponding URL formats. In this example, we'll be using the 
Git SSH protocol. Git SSH URLs follow a template of: git@HOSTNAME:USERNAME/REPONAME.git

An example Git SSH URL would be: git@bitbucket.org:rhyolight/javascript-data-store.git where the template values match:

HOSTNAME: bitbucket.org
USERNAME: rhyolight
REPONAME: javascript-data-store

When executed, the latest version of the remote repo files on the main branch will be pulled down and added to a new 
folder. The new folder will be named after the REPONAME in this case javascript-data-store. The folder will contain 
the full history of the remote repository and a newly created main branch.

For more documentation on git clone usage and supported Git URL formats, visit the git clone Page.
