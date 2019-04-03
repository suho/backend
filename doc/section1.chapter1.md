Written by: **[@suho][Su Ho]**

# Chapter 1: Git - Version Control

Everything you need to know about **git**.

> Thanks to **Scott Chacon** and **Ben Straub**, authors of the book **[Pro Git][Pro Git]**

In this chapter, I will show basic knowledges from [Pro Git][Pro Git] book, if you want more detail, you should download the book and read it.

**Table of Contents**
- [Chapter 1: Git - Version Control](#chapter-1-git---version-control)
  - [Getting Started](#getting-started)
    - [Version Control](#version-control)
  - [Git Basics](#git-basics)
  - [Git Branching](#git-branching)
  - [Git On The Server](#git-on-the-server)
  - [Distributed Git](#distributed-git)
  - [Github](#github)
  - [Git Tools](#git-tools)
  - [Custimizing Git](#custimizing-git)
  - [Git And Other Systems](#git-and-other-systems)
  - [Git Internals](#git-internals)

## Getting Started

This section will be about getting started with **Git**, then move on how to get **Git** running on system and set up to start working with.

### Version Control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a developer and you want to keep every version of your code, a Version Control System (VCS) is a very wise thing to use. It allows you to revert selected files back to a previous state, revert the entire project back to a previouse state, compare changes over time, see who last modified something that might be causing a problem (then you can burn them 🤣🤣🤣), and more.

Git is a **Distributed Version Control System** (DVCS), in a DVCS, clients don't just check out the latest snapshot of the files; rather, the fully mirror the repository, including its full history. Thus, if any server dies, and these systems were collaborating via the server, any of the client repositories can be copied back up to the server to restore it.

[Image 1]


## Git Basics

In this section, we will learn how to use Git in the 80% of cases you'll encounter most often. After this section, you will be able to clone a repository, see what has happened in the history of the project, modify files, and contribute changes.

## Git Branching

In this section, you will learn what truly sets Git apart from the pack

## Git On The Server

This section is for those of you who want to set up Git inside your organization or on your own personal server for collaboration.

## Distributed Git

We will go over in full detail various distributed workflows and how to accomplish them with Git, after this section, you will be able to work expertly with multiple remote repositories

## Github

We will cover signing up for and managing an account, creating and using Git repositories, common workflows to contribute to projects and more features of Github.

## Git Tools

Here you will learn about topics like mastering the scary **reset** command, using binary search to identify bugs, editing history, revision selection in detail, and a lot more.

## Custimizing Git

This section includes setting up hook scripts to enforce or encourage customized policies and using environment configuration settings so you can work the way you want.

## Git And Other Systems

This includes using Git in a Subversion (SVN) world and converting projects from ohter VCSs to Git

## Git Internals

After know all about Git and can wield it with power and grace, you can move on to discuss how Git stores its objects, what is object model is, details of packfiles, server protocols, and more

[Su Ho]: https://github.com/suho
[Pro Git]: https://git-scm.com/book/en/v2
[Image 1]: ../img/section1.chapter1/Image1.jpg