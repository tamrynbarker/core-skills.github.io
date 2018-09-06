---
title: Get started
permalink: /setup
layout: page
order: 2
icon: fa-cloud-download
icon-style: solid
---

## Getting set up for the course

### Github

All course content is delivered using GitHub. If you don't already have a GitHub account you will also need to sign up for one [here](https://github.com/join).

Please let [Jess](mailto:jesse.robertson@csiro.au) or [Sophie](mailto:sophie@corehub.com.au) know what your GitHub username is so that we can add you to the [core-skills GitHub organization](https://github.com/orgs/core-skills). Then you should have read access to all the repositories for each week.

### Local software

There are two software prerequisites you should try to get installed on your machine - you will need both Git (a software collaboration/versioning tool) and a Python installation. There will be a prerequisite two-day course (run by the Curtin Uni Data Carpentry team) to introduce you to these tools and get you up and running, but if you're keen to get started we recommend:

- [**GitKraken**](https://www.gitkraken.com) for managing Git repositories - this is a nice cross-platform GUI which removes some of the confusion of the commandline. It's free for non-commercial use and pretty cheap for commercial licenses. There are other git clients out there but this is the easiest we've found so far. They also have a good [getting started guide](https://support.gitkraken.com/start-here/guide). [Get it here](https://www.gitkraken.com/download)
- [**Anaconda**](https://www.anaconda.com/) for managing Python and R dependencies - we will be managing several Python environments over the course of the program and conda provides a way of doing this easily. [Get it for your platform here](https://www.anaconda.com/download)

You should make sure that GitKraken has access to your Github account so that it can see what repositories you have read access to. You can then use their GUI to clone the relevant repositories to your local machine.

Some notes:

- GitKraken have a good cheat sheet for GitHub users here: https://www.gitkraken.com/resources/gitkraken-github-cheat-sheet
- We recommend that you clone your repositories into your home folder - this means that Anaconda Navigator can find your cloned notebooks when you start it up

Once you've got these tools you can proceed to getting set up each week

## Getting set up for the week (do this every week)

All you should need to do is open the relevant repository in GitKraken, hit 'pull' to merge in any new changes and you're good to go with the latest version. Contact a facilitator if you have any issues with this.

Then you need to do two things to get set up: (a) build the conda environment and (b) run the notebook server to run the examples. This will be covered in detail in the pre-requisite days and will hopefully become second nature to you over the course of the course. However if you have any issues please contact one of the facilitators.

#### Building the conda environment:

This makes sure that you have all the Python libraries available on your machine that are required for the week's code examples. 

#### Run the Jupyter notebook server

Now you can 



### How to find your way around in the repos

Each week has its own repo. Inside the folder are several different files and subfolders:

- **README.md** - do as it says! We'll put important information, suggested reading and other special bits and bobs for the week in here. 

- **environment.yml** - this contains the Python dependencies required to run the jupyter notebooks and code examples

- **data** - contains the data for the week, feel free to have a poke around. Note that some data sources we use may be live databases online - we'll try and provide you with instructions for setting these up for yourself where we use these.

- **notebooks/\*.ipynb** - these are the Jupyter notebooks with the code examples. If you click these on Github they will get rendered nicely to HTML. But if you want to run the code you will need to either do so in Binder or locally on your machine.

## Other things

Some other bits and pieces can go here...

### Having your own repo on GitHub to track your changes

You will need to [fork this repo](https://help.github.com/articles/fork-a-repo/) into your own github account to be able to push changes into it. All you need to do is click the **Fork** button (see below) and you've got your own copy. ![fork button	https://help.github.com/assets/images/help/repository/fork_button.jpg](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Then you need to [clone the repository](https://help.github.com/articles/cloning-a-repository/) to your local machine. If you're using GitKraken, you can sign in with your Github account to make this easier, [following these instructions](https://support.gitkraken.com/working-with-repositories/open-clone-init). Make sure that you pick your personal repository so you can push changes back to it (participants have read-only access to the main core-skills repository).

If you want to push changes back to the main repository then you can take a look at [submitting a pull request in Github](https://help.github.com/articles/about-pull-requests/)