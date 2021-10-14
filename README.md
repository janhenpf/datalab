# Data Analysis Lab

## Lab 1

### Prerequisites

* Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
* [Create a github account](https://github.com/join) (if you don't have one aready) and log into it. 
* Once you are logged in with your account, fork this repository by pressing the fork button on the upper right corner of this repository's page. 

![Screenshot 2021-10-14 at 11 47 03](https://user-images.githubusercontent.com/6952640/137299631-11d5982d-b60c-4484-943e-0e0b8f22ea26.png)


> Now you should have __your own repository__ in your namespace called datalab `<username>/datalab`.
> To make your life easier when you upload the solutions to the next exercises you should now generate on your machine a `ssh` key that will allow you to do operations on your repository without being asked for a username and password each time. 

*  Generate a ssh key using the terminal/command line (Try [this link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) first and try to figure it out. If all else fails [here] is a more detailed guide)







*    Copy the git url of this repository by going to your github page, the repository and clicking on `clone/git/copy`
* Open a command line/terminal an




## Get the code

### O



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
