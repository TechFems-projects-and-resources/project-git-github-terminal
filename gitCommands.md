**Useful commands:**

Command | Explanation
------- | -----------
`git init` | initialises your project as git repository (git will track the files)
`git add *filename*` | stages a new file to be tracked by git
`git add . ` | stages all files
`git diff` | will show the code that has changed in a file: code that was added will show up in green and code that was deleted in red. To get out of `git diff`, type `q`.
`git commit -m *message*` | commit a change means git takes a *snapshot* of your current code
`git push` | if you have a remote repository (for example on GitHub), this will upload your code there
`git branch *branchname*` | if you want to work on part of the project but do not want to change your original code
`git checkout *branchname*` | will change to the branch (you can also use it to go back to the main or master branch: `git checkout main`)
`git merge *branchname*` | will merge your branch with main/master; NB: **you have to be on the main/master branch to merge**


----

TIP: if you are not sure you have Git tracking your files, you can find out by going to your folders and files on your laptop and making the hidden files visible. 
1. On Mac, you click the project folder in Finder and then press Cmd Shift . (period), and you will see a folder called .git, probably greyed out. 
1. On Windows, you go to the Control Panel and click on File Explorer Options. Click on the View tab and find the option "Show hidden files, folders and drives". You have to check that item. You can then also check the option "Hide protected operating system files". You probably get a warning about protected operating system files, but you can ignore that and just click Yes. This brings you back to the File Explorer Options box and you can click OK.