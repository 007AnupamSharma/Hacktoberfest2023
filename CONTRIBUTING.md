# Guidelines for Contributions 📚
-Before you commence contributing, please familiarize yourself with our Code of Conduct. <br>
-We anticipate all contributors to adhere to these instructions to maintain a positive and inclusive community.<br>

-🎯Name you files appropriately. Ensure that your file name is unique, and does not previously exist in folder.
-🎯Preferably solve new problems. Dont submit solutions to problems that have already been solved in the repo.
-🎯Initiate an issue regarding the code or contributions you plan to make.<br>
-🎯Browse through existing issues to prevent duplicate submissions.<br>
-🎯Once assigned, proceed with your contributions and initiate your initial PR.<br>
-🎯Kindly furnish a brief description of your code or contribution to facilitate learning and enhancement by others.<br>
-🎯Refrain from removing any existing content.<br>
-🎯Do not make changes to existing files.
-🎯Endeavor to keep pull requests concise to mitigate merge conflicts.<br>
<br>


# Specific Directories<br>
-🧩We have categorized the project into DSA_CP and Theory_Explanation. <br>
-🧩Select the directory that aligns with your interests.<br>
-🧩Only folders DSA_CP and Theory_Explanation are open to contributions.<br>



## Getting Started 🤩🤗

- Fork this repo (button on top)
- Clone on your local machine

```terminal
git clone https://github.com/akanksha1331/DSA_CP_Hacktoberfest23.git
```
- Navigate to project directory.
```terminal
cd DSA_CP_Hacktoberfest23
```

- Create a new Branch

```markdown
git checkout -b my-new-branch
```
- Make your changes `folderName/fileName`

- Add your changes
```markdown
git add .
```
- Commit your changes.

```markdown
git commit -m "Relevant message"
```
- Then push 
```markdown
git push origin my-new-branch
```


- Create a new pull request from your forked repository

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream https://github.com/akanksha1331/DSA_CP_Hacktoberfest23
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/main
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.

```terminal
git merge upstream/main
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
