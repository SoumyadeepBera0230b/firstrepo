Firstly i had installed the latest version of git of 50mb

Then i had verified if git completely installed or not by typing "git --version"

Now i had created a folder and a file in it named as learn git and files are index.html, style.css, and readme.md

To add the folder into the repo we use the following comand "git init". So the dublicate folder has been created in the git repository of the folder learn git

To check the status of your file, we use the command "git status" or "git status --short"

So the folder has been tracked by the git but the files inside it are not added to git repository 

To add or stage the files of the folder to the repository we use the command "git add index.html"

Now all the files are staged and ready to be commited

So I have commited all the files in the folder by using the command "git commit -m "

All the files are commited now

To know the history of the modifications we use "git log"

If you forget about any of the command then we can use the command "git command -help" or "git help --all"

By using the git branch we can a new/seperate branch of the master/ main repo

We can create a branch by using the command "git branch img-update"

When we check the git branches then we see the we are currenty in the master branch

So to check out from the master branch we use "git checkout img-update" branch

Now i have created a img.jpg file in the img-update branch and then commited the file by using "git add --all"

Next, I had commited this file in the img-update branch 

Now if you check the all the list directories(ls) in the img-update branch then you can see the img.jpg file

But when you checkout to master branch then in the ls you will not find the img.jpg file

So this is how we can make changes by creating branches and then merging the branches to the master branch

The shortcut to make git branches and then checkouts, we use the command "git checkout -b branch-name"

To merge the other branches with the master branche then use the following command "git merge emergency-branch" note that you should be in the master branch to make the merge successful

Now as we have merged the emergency-fix branch to the master branch.

So, now to can delete the emergency-fix branch by using the command "git branch -d emergency-fix"



Now This changes are made in the github. So, github has a powerful code editor also

Pull from Github is the combination of fetch and merge. so, we use the command "get fetch origin" to fetch the present updates in the local 

To merge we use the command "git merge origin"

To check the history we use "git log origin/master"






