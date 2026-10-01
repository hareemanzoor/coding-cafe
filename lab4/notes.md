#q1
--global means that the Git configuration is applied to my user account on the computer, so it applies to all my repositories. If I leave it out, the configuration would only apply to the current repository.

#q2
ls -a showed hidden files that ls normally does not show. The important one was .git, which contains Git's information and history for the repository.

#q3
Git was offering to track roughly all the files and folders in my project. Some of them looked like files I did not create myself, such as virtual environment or cache files.

#q4
After adding the .gitignore rules, files and folders such as .venv/ and 
python cache files no longer appeared as untracked files in git status. Git was now ignoring those files instead of offering to track them.

#q5
.gitignore itself should be committed, not ignored, because it is part of the project and tells Git which files should be ignored.

#q6
README.md moved from Untracked files to Changes to be committed. This means it was staged and is now ready to be included in the next commit.

#q7
Git printed information about the commit, including the commit ID, the commit message, and the number of files changed. It said that 4 files were changed.

#q8
The first seven characters of the commit ID are the short form of the commit's unique hash. They identify that particular commit and can be used to refer to it.

#q9
The four steps are edit, stage, commit, and check the history. We edit a file, use git add to stage the changes, use git commit to save them as a new version, and then use git log to view the history.

#q10
README.md has a special name and location because it is normally the main introduction to a repository. GitHub displays the README from the repository's root as the front page, so visitors can understand what the project is about.

#q11
gh auth login authenticated my GitHub account through GitHub CLI and stored authentication credentials for future GitHub operations. This means Git can authenticate me when I push without asking me to enter my GitHub password each time.

#q12
After refreshing the GitHub repository page, the README is displayed on the front page because GitHub automatically recognizes a root-level README.md as the repository's main documentation. Running git log --oneline locally shows that pushing did not change my local history; it only copied my existing commits to GitHub.

#q13
No, pushing did not change my local Git history. git push only sent my existing local commits to the GitHub repository, so the output of git log --oneline remained the same.

#q14
A private repository exists on GitHub, but its contents can only be accessed by the owner and people who have been given permission, such as my TAs. A repository that does not exist on GitHub at all has not been created or pushed there, so there is no GitHub repository for anyone to access.


