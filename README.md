# Realtime-Face-Detection

The Realtime-Face-Detection app is a small demo of utilzing computer vision over the web. This application integrates with pre-built TensorFlow models that detect facial features such as gender, age, emotions, by using the facial landmarks on a persons face.  

# Getting Started

## Prerequisites
1. Git https://git-scm.com/downloads
2. Node: any 8.x version starting with 8.4.0 or greater https://nodejs.org/en/
3. Code Editor: Visual Studio Code https://code.visualstudio.com/download
4. Create a local development folder that will host your code. 
5. In the folder run `git clone https://gitlab.com/robinson-technology/healthdoc-api.git`

## Installation
1. `cd realtime-face-detection`
2. `npm` to install the project's dependencies

## Running Locally
1. `nodemon app.js` or `npm run start`
2. open `visual studio code Live Server Extension` to open site in your browser

# Contributing 

## Guidelines

In order to contriute to this project you must follow the branch and version control protocol to successfully and efficently merge new code features.

## Create Branch
1. `git checkout master` from any folder in your local healthdoc-api repository
2. `git pull origin master` to ensure you have the latest main code
3. `git checkout -b the-name-of-my-branch` (replacing the-name-of-my-branch with healthapi-number of corresponding gitlab issue) to create a branch

## Make a change
1. Follow the "Running locally" instructions
2. Save the files and check in the browser

## Test the change
1. If possible, test any visual changes in all latest versions of common browsers, on both desktop and mobile.
2. Run `Live Server` from the Visual studio code footer menu. 

## Push it
1. `git add .` to add code to the repository.
2. `git commit -m "Commit message"` to add a description of what the new code accomplishes.
3. `git push -u origin name-of-your-feature-branch`
4. Go to the realtime-face-detection repo and you should see recently pushed branches.
5. Create a merge request to merge your feature branch into the master branch for code review.
