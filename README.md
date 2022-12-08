# workflow-tutorial
This repository will serve as onboarding material for future users managing the [PsyConnect website](https://github.com/PsyConnect/PsyConnect.github.io). 

## Prerequisites

### GitHub Account
You will be using this account to access the applications listed below. As all profiles and commits are public, I highly suggest choosing a professional handle and one that allows reviewers to clearly identify you. 

You should also read up on [how to work with GitHub](https://github.com/ClinicalBrainLab/clinicalbrainlab.github.io#getting-started-with-github-memo)


## Suggested Software
For new users without prior experience in coding, I highly recommend downloading a source-code editor (to edit code) and a version control system (VCS) graphical user interface (GUI). 

### Source-Code Editor/ Integrated Development Environment (IDE)
I personally use [Visual Studio Code](https://code.visualstudio.com/).

Other options include: 
- [Notepad++](https://notepad-plus-plus.org/downloads/)

### Git GUI
As our repositiory is hosted on github, [GitHub Desktop](https://desktop.github.com/) would be less troublesome to set up. 

Other GUIs such as [Sourcetree](https://www.sourcetreeapp.com/) may require additional user accounts to be created. 

## Required Resources
Without these software and dependencies installed, you will not be able to work with our sourcecode. 

**Note:** For Windows users, you may wish to utilise [scoop](https://github.com/ScoopInstaller/Scoop#installation) to install the belowmentioned applications for less hassle. I do not use the Apple ecosystem as such, you may need to research on how to install these yourself. 

You can access windows powershell by typing it in the search bar:
![](/assets/images/powershell-screenshot.png)

At any time, you may run the following code to identify which softwares you have already installed:
```
scoop list
```
![An example](/assets/images/scoop-list.png)

### Git
[Git](https://git-scm.com/downloads) is our VCS of choice.

For Windows scoop users, simply input the following one-liner in powershell:
```
scoop install git
```

### Hugo-extended
This is the framework used for our website, without which you cannot render your webpage locally.

**Important:** We are using [hugo-extended](https://gohugo.io/getting-started/installing#quick-install)

For Windows scoop users, simply input the following one-liner in powershell:
```
scoop install hugo-extended
```

### Go
A dependency for Hugo-extended.

For Windows scoop users, simply input the following one-liner in powershell:
```
scoop install go
```

### Nodejs
May be required for compiling the server on your local computer.

For Windows scoop users, simply input the following one-liner in powershell:
```
scoop install nodejs
```
