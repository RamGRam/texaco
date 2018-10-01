# texaco

This is a demo repository for learning process of git and Cordova, code named Texaco. And the Cordova App is a brochure, much like an simple website. Which features graphic media and content. And this makes use of Materialize CSS framework, since it resembles android app look and feel, and which follows Google Material Guideline.   


# Git Literacy
## First Step - Uploading to a new repository created at github
1. First step is to create a directory with the same name of the local dev. folder name.

2. echo __"# texaco" >> README.md__ use this command to create a readme in the dire.
3. Now add the command **git init**. this will initialise the needed git files, and this is a hidden file in git.
4. Now check for altered-files and newly created files using the following command **git status**.
5. And now we should add the files or the whole files to the repo. using the either of the command **"git add filename"** or **git add .**, now this will prepare the files to be uploaded to repo.
6. Now we commit the changes and also give a comment regarding the changes we are making. this is like finalizing the changes, beyond which no changes will be taken into account. And if we do make changes after the commit, we re run the step 4,5,6 again. so the command will be **git commit -m "comment"**, here _-m_ stands for master repo.

7. This is the final step we push the source file in local dev. system to git repo. and we use the following command **git remote add origin https://github.com/RamGRam/texaco.git** Here the link is the repo. name in github.

## To update an existing repo. 
1. Just follow the above steps 4, 5, 6. 
2. And finally do the following **git push origin master**


## Cordovo Basic Literacy

1. Install the Cordovo CLI using the npm as a global package. the code is as follows **npm install -g cordova**.
2. to create a Cordova app template, we give the following command **cordova create appname**. There are two extra parameter which are off course ignored in this tutorial. For now the code is enough to create an app template.
3. Now there should be a new directory called the appname, just go in and navigate to directory named www. this is where our web app should reside(HTLM, CSS, JS, Graphic-Media).
4. Now we get to add platform to which this app should be targeted to build, I am currently targeting Android. So I assume that you are inside the appname directory, and now in the terminal type the following **cordova platform add android**.


This is the final step we push the source file in local dev. system to git repo. and we use the following command **git remote add origin https://github.com/RamGRam/texaco.git** Here the link is the repo. name in github.
