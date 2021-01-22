---
layout: page
title: "GitLab Setup for CS 571 Projects"
permalink: /gitlab_setup.html
---

## Introduction

The following instructions describe how to create a Git source code
repository in the student.cs computing environment.

We will be using [Mason GitLab](https://git.gmu.edu/users/sign_in) for all our CS 571 coding projects,
including the C systems programming projects (Linux utilities, shell, caching policies, and
green threads) and Go-based distributed systems projects (Intro to Go, MapReduce,
and MDFS). 

> **IMPORTANT:** There are two ways of creating a new GitLab repository.
**(1) Fork:** You may fork the original project GitLab repositories
and then immediately change the permission of the project to
**Private**.
**(2) Download:** Alternatively, you may create a **Private**
project with the same project name, download the original project in
a tar.gz file to your working directory, copy and upload the
downloaded source code to your **Private** repository, and use <a
href="https://git-scm.com/">Git</a> to keep track of your code
editing history.
**Leaving your repository publicly visible violates GMU Honor Code and
Computer Science Department's Honor Code policies.**


For a newly created project, you can directly set the visibility to
`Private` upfront. For forked projects,
after the repository has been forked, go to your forked project, from
`Settings`, go to `General`, from there change `Visibility` level to 
`Private`.

Next, I provide instructions for the second way of creating and
populating a new GitLab repository (i.e., Download).

## Step 1: Create a GitLab Repo

First, you will need to login to <a
href="https://git.gmu.edu/users/sign_in">GitLab</a> by clicking
`Sign in with: GMU Login`. Username and Password never work
for some reason.

## Step 2: Clone Your GitLab Repo

Before cloning your GitLab repo to your computing environment (can be
a student.cs (Zeus) Linux server or a cloud virtual machine server),
you will need to first create an RSA SSH key by typing:

```bash
% ssh-keygen -t rsa -C "your_email_addr"
```

Or you can simply follow 
<a href="https://git.gmu.edu/help/ssh/README#generating-a-new-ssh-key-pair">this tutorial</a>.

Then, add an SSH key to your GitLab account by following 
<a href="https://git.gmu.edu/help/ssh/README#adding-an-ssh-key-to-your-gitlab-account">these instructions</a>.

<a href="https://git.gmu.edu/help/ssh/README#adding-an-ssh-key-to-your-gitlab-account">Test</a> if
the SSH-based access has been successfully set. 


Click on the **Clone** button at the right-top corner of your GitLab repo's webpage,
copy the string under **Clone with SSH** to clipboard.
Then, create a new directory called <tt>cs571_proj</tt> under your `$HOME` directory, 
`cd` to your working directory where you are supposed to put your project source code,
and clone your created GitLab repo on to your Linux box:

```bash
% mkdir $HOME/cs571_proj
% cd $HOME/cs571_proj 
% git clone git@git.gmu.edu:your_gid/<proj_name>.git
```

Assuming you have already downloaded the original project locally in your
<tt>$HOME</tt> directory,
you can then copy the downloaded project source code into this newly
created git directory:

```bash
% cd $HOME/cs571_proj/<proj_name>
% cp -r $HOME/<downloaded_proj>/* .
```

## Step 3: Check in Your Initial Source Code

Now, check in the source code which you have already copied into the git directory:

```bash
% git add *
% git commit -m "init commit" 
% git push  
```

If you are checking in for the first time on an empty repo (which is your case here),
you should run:

```bash
% git push -u origin master
```

Instead of

```bash
% git push
```

## Step 4: Share the Repo with Your Teammate

If you are working in a group, it is a good idea for all group
members to share access to a single GitLab repo. You can enable
sharing through the GitLab web interface. Hover over to **Settings**
on the left sidebar, and click **Members**. Enter your team member's
Patriot ID and choose a role (Developer or Maintainer) for him/her.


