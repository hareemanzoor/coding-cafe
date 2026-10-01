## Question 1
--global means that the Git configuration is applied to my user account on the computer, so it applies to all my repositories. If I leave it out, the configuration would only apply to the current repository.

## Question 2
ls -a showed hidden files that ls normally does not show. The important one was .git, which contains Git's information and history for the repository.

## Question 3
Git was offering to track roughly all the files and folders in my project. Some of them looked like files I did not create myself, such as virtual environment or cache files.

## Question 4
The files and folders that were supposed to be ignored disappeared from git status after adding the .gitignore rules.

## Question 5
.gitignore itself should be committed, not ignored, because it is part of the project and tells Git which files should be ignored.

## Question 6
README.md moved from Untracked files to Changes to be committed. This means it was staged and is now ready to be included in the next commit.

## Question 7
Git printed information about the commit, including the commit ID, the commit message, and the number of files changed. It said that 4 files were changed.

## Question 8
The first seven characters of the commit ID are the short form of the commit's unique hash. They identify that particular commit and can be used to refer to it.
