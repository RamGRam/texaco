# texaco
This is a demo repository for learning process of git and cordova, code named Texaco.

## First Step - Uploading to a new repository created at github
1. First step is to create a directory with the same name of the local dev. folder name.

2. echo __"# texaco" >> README.md__ use this command to create a readme in the dire.
3. Now add the command **git init**. this will initialise the needed git files, and this is a hidden file in git.
4. Now check for altered-files and newly created files using the following command **git status**.
5. And now we should add the files or the whole files to the repo. using the either of the command **"git add filename"** or **git add .**, now this will prepare the files to be uploaded to repo.
6. Now we commit the changes and also give a comment regarding the changes we are making. this is like finalizing the changes, beyond which no changes will be taken into account. And if we do make changes after the commit, we re run the step 4,5,6 again. so the command will be **git commit -m "comment"**, here _-m_ stands for master repo.
This is the final step we push the source file in local dev. system to git repo. and we use the following command **git remote add origin https://github.com/RamGRam/texaco.git** Here the link is the repo. name in github.
