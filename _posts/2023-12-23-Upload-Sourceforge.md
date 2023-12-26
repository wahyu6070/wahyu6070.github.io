---
layout : post
type   : 
title  : Upload File SourceForge Using SSH In Termux or Ubuntu
date   : 2023-12-24
slug   : sourceforge-upload
categories: [Tutorial]
tags      : [sourceforge, ssh, sftp, sftp]
keywords  : [sourceforge, ssh, sftp, sftp]
author : wahyu6070
opengraph:
toc    :
excerpt:
---


Sourceforge is a website that provides unlimited online storage for free, all projects in sourceforge are open source which can be downloaded for free by anyone.

Sourceforge provides a place to upload via a web browser online on their website, which is not efficient when we want to upload lots of files or large files.  because sourceforge limits uploads via browser to only *max* **1GB** and usually when we upload a fairly large file there will be a crash during the upload process, but don't worry, I have a solution to overcome this problem.

So this time I will share a tutorial on how to upload files to SourcerForge using **SSH**: ``sftp`` and ``scp`` using the *Android Termux* or *Linux Ubuntu* platforms.  Just go straight to the tutorial:

## Account Sourceforge
The first thing you need to prepare is that you must have a SourceForge account and create at least one project. If you don't have an account, you can register for free on the SourceForge site and then you must create at least one project.

## Install
After you have prepared your account, you can install *ssh* in the Termux or Ubuntu terminal.

### Update list package
#### Linux Ubuntu
``apt-get update && apt-get upgrade``
#### Android Termux
``apt update && apt upgrade``

### Install SSH
#### Linux Ubuntu
``apt-get install ssh``
#### Android Termux
``apt install openssh``

## Usage

There are several ways to upload SourceForge files using the terminal, namely:
### SFTP
Before uploading you have to enter the directory of the file you want to upload, for example I have a file in ``/sdcard/file.txt`` you can do *cd* for example ``cd /sdcard``

#### Login shell sourceforge
First you have to enter the sourceforge shell by *`` sftp (username)@web.sourceforge.net``*

Example : *``sftp wahyu6070@web.sourceforge.net``*

#### Project Directory
After you enter the shell, you can enter your sourceforge project directory by: *``cd /home/frs/project/(project name)``*

Example : *``cd /home/frs/project/wahyu6070``*

#### Upload Files
You can upload to sourceforge with *``put (file name)``*

Example : *``put file.txt``*

### SCP

## Tips

- Use **sftp** to manually upload via terminal shell.
- Use **scp** to upload via *script.sh* with many files automatically.

## Conclusion
In conclusion, using SSH via the terminal is the most effective solution when we want to upload large files and large numbers to SourceForge, rather than uploading via a web browser.

