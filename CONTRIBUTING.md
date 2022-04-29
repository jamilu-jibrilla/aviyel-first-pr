## Contribution Guidelines

### Never made an open source contribution before? Wondering how contributions work in the in our project? Here's a quick rundown!

## Fork this repository

* Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

* Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). 

```
git clone https://github.com/name/aviyel-first-pr.git
```

where `name` is your GitHub username. Here you're copying the contents of the Clone-IT repository on GitHub to your computer.

## Navigate to the project directory
* After cloning the project in your computer, navigate to the project file using the command below.
```
cd <cloned-repo>
```

## Add a reference(remote) to the original repository

```
git remote add upstream https://github.com/aviyelverse/aviyel-first-pr 
```

* Check the remotes for this repository.

```
git remote -v
```

* Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream main
```

## Create a new branch

```
git checkout -b <your_branch_name>
```

* Perfom your desired changes to the code base.


* Track your changes:heavy_check_mark: .

```
git add . 
```

* Commit your changes .

```
git commit -m "Relevant message"
```

* Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

* To create a pull request, click on `compare and pull requests`.


* Add appropriate title and description to your pull request explaining your changes and efforts done.


* Click on `Create Pull Request`.


* Congrats :exclamation: You have made a PR to the Aviyel-First-PR :boom: . Wait for your submission to be accepted and your PR to be merged.


* Wait for the pull request to be reviewed by a maintainer, Make changes to the pull request if the reviewing maintainer recommends them.


* Hooray 🥳  your success after your pull request is merged!