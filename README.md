# Data Analysis Lab

## Get the code

### Option 1 : Download zip archive

Click on the gren `clone` button and select `Download ZIP`. Download should begin automatically. Unzip files locally.

### Option 2: Using git

Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

I would recommend first to make a fork of the repository. - This allows you to have a copy of the repository and commit (upload) your changes to it. You can also pull (download) changes from the main repository to your local repository. 

Use git command to clone (copy/download) the repository files. 

Click on clone (select HTTPS if you have not setup the SSH key), copy the repository patha nd run `git clone <repo> <folder>` in your local terminal/command line:

```
git clone https://github.com/alebot/datalab.git
```

## Task 1 

The first task will be to compile the two `C` source files.
To do this you can try to simply run in your command line:

```
./Makefile
```

I expect you might get some errors, missing libraries, missing executable. Try to solve them. 

You can either do this in your local environment or use [docker](https://docs.docker.com/get-docker/) and run a container with c++ for example [this one](https://hub.docker.com/_/gcc). 
