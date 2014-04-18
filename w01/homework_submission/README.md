# To do once...
## Fork our repository
* Make your own copy of the class repository.  
![Fork a Repo](01_fork.png)

## Set up remotes on your machine.
* Copy the ssh clone url on your fork of the repository.
![Set up remotes](02_ssh_clone_url.png)

* Clone your fork of the repository down to your local machine.
![clone](03_clone.png)

* Have a look at your remotes with ```bash git remote -v```: 
![remote](04_git_remote_v.png)

* Copy the ssh clone url of the class repository.
![copy class ssh](05_upstream_ssh_url.png)

* Set the class repository as an upstream remote on your local machine.
![set upstream](06_upstream_remote.png)

# To do on a many times daily basis...
## Get materials from the class repository
* ```bash git pull upstream master``` will pull in files from the class repository, which is set as your `upstream` remote.
![pull upsream](07_git_pull_upstream_master.png)

## Do your work.
* Do your work.
![do work](08_do_work.png)

* Tell GIT to track your files. 
![git add](09_add_your_work_to_git.png)

* Tell GIT to take a snapshot of your working code. 
![git commit](10_commit_your_work_to_git.png)

* ```bash git status``` shows the state of your code base.  Here you will see that there are no additional changes to commit.
![git status](11_commit_your_work_to_git_2.png)

## Submit your work.

* Push your work to YOUR fork of the class repository, set is your `origin` remote.
![push to origin](12_git_push_origin_master.png)

* Make a `pull request`	
![pull 1](13_pull_request_1.png)
![pull 2](14_pull_request_2.png)
![pull 3](15_create_pull_request.png)

* Title your pull request in the following format `hw_w01_d01_submission`.  Rate the assignment's completeness and your comfortability with it. 
![title the pull](16_send_pull_request.png)

* Celebrate. 
![done](16_send_pull_request.png)


















