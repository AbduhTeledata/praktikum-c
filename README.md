# GIT OVERVIEW
## Rules

The student will be graded:

<ol>
    <li>Presence must >70%</li>
    <li>All Assignments must be uploaded to github (100%)</li>
    <li>Quiz</li>
    <li>UTS</li>
    <li>UAS</>
</ol>

## Objectives

<ul>
    <li>Describe git</li>
    <li>How to install git</li>
    <li>How to upload assigmnent to git repository</li>
</ul>

## Overview

Git is a version control system

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later

It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead.

https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

## Create new directory

<ul>
    <li>Create folder like following image in windows</li>
</ul>
<br>

![Folder, open folder](/images/foldertugassabtu.png)

<ul>
    <li>Right click mouse and create folder in windows</li>
    <li>Folder name -> tugas-praktikum-c-sabtu</li>
</ul>
<br>

![Folder, open folder](/images/newfolder.png)

<li>copy all assigment to folder </li>

## Install git bash

<ul>
    <li>Download and install git bash for windows from https://git-scm.com/downloads</li>
</ul>

## Github repository

<ul>
    <li>Create new github account https://github.com/</li>
    <li>Create new github account can be accessed by smartphone</li>
</ul>

<ul>
     <li>Create new repository -> tugas-praktikum-c-sabtu</li>
</ul>
<br>

![Repo 1, Repo 1](/images/repo1.png)

<li>Repository name must be same with directory name in windows -> tugas-praktikum-c-sabtu </li>
<br>

![Repo 2, Repo 2](/images/repo2.png)

<li>Create repository</li>
<br>

![Repo 3, Repo 3](/images/repo3.png)

## Git bash command with new github account
    
<li>Open folder with git bash</li>
<li>Right click mouse and click git bash here</li>

![Repo 4, Repo 4](/images/repo4.png)

<li>Git bash terminal</li>
<br>

![Git bash 1, Git bash 1](/images/gitbash1.png)

<li>Insert following command step 1 to step 8 at git bash terminal</li>
<br>

1. > `$ git init`
2. > `$ git config --global user.email abduh@gmail.com`

<li>Insert your`s github account</li>
<br>

3. > `$ git status`
4. > `$ git add .`
5. > `$ git status`
6. > `$ git commit -m "first commit"`
7. > `$ git remote add origin https://github.com/AbduhTeledata/tugas-praktikum-c-sabtu.git`
8. > `$ git push -u origin master`