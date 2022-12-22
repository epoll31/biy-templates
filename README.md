# biy-templates

This repository consists of a library of templates that you can use to easily create a website. 

## Getting The Templates

There are two ways to access these templates

### GitHub Templates

This repository is a GitHub Template repository which means that you can create your own repo directly from this one. However, this process will default to only migrate the `main` branch. In order to actually access the template you'd like to use you should select the option to copy all branches instead of just `main`. After cloning you must then switch to the branch you want to work on and begin customizing your project.

### Forking 

Since this repository is hosted on GitHub, you can fork it directly form their website. To do this, you can clik on the Fork button on this repo on GitHub. Then, enter the name of your project and you be set to start working!

## Cloning Your Repository

### Command Line Interface (CLI)
Firstly, make sure that you have git installed on your machine. If you do not, stop right now and go install it! 

After this, can navigate to the directory you want your repo to be in.


```
cd /local/project/location

```

Then, you can clone the repo, which will copy the entire repository. In order to clone the repository you must specify where it is located within GitHub. You can do this by providing a link using the foramt below. Replace `username` with your GitHub username and `repoName` with your repository name. 


```
git clone https://github.com/username/repoName.git
```

Following this, we will enter the repository folder.

```
cd repoName
```

Once you are in this repo can can navigate to any template by running the following command. Replace `templateName` with the template that you would like to use.

```
git checkout templateName
```

## Active Templates

### skeleton-grid

This template shows a basic skeleton for a navbar, scrolling content section, and footer using `display: grid` in for the skeleton. 

This can be used to create a basic webpage that has information at the top, bottom, and scrolling content section in the middle.

### skeleton-flex

This template shows a basic skeleton for a navbar, scrolling content section, and footer using `display: flex` in for the skeleton. 

This can be used to create a basic webpage that has information at the top, bottom, and scrolling content section in the middle.
