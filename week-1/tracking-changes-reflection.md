**How does tracking and adding changes make developers' lives easier?**

Many changes are made to different parts of the code by different developers.  If something goes wrong down the road, we can look back through different versions to see what changes were made, why they were made and use this information to troubleshoot.

**What is a commit?**

A commit is a staged set of changes.

**What are the best practices for commit messages?**

Commit messages should use the imperative rather than past tense.  E.g. say "add description to readme text" rather than "adds" or "added".  The first line should be 50 characters or less.  We should capitalize the first letter and leave out the first full stop.

**What does the HEAD^ argument mean?**

HEAD is the current branch and HEAD^ is the first parent of the current branch.  It's actually HEAD^1 and there can be multiple parents, HEAD^2, HEAD^3 and so on.

**What are the 3 stages of a git change and how do you move a file from one stage to the other?**

I suppose these would be making the changes to the original file, adding file using git add, and then committing it.

After changes, we use git add "filename"
To commit, we use git commit -m "commit message" or git commit -v, which will open up the file for us to type a commit message

**Write a handy cheatsheet of the commands you need to commit your changes?**

- git add "filename"
- git status
- git commit -m "commit message"


**What is a pull request and how do you create and merge one?**

- A pull request is a way for a developer to let other team members know they have made changes
- Before creating the pull request, push your branch with changes to the GitHub repository
- Then on the repository in GitHub, click on pull request
- The branches can then be merged on the GitHub interface
- User can then pull from the origin so they have the updated master

**Why are pull requests preferred when working with teams?**

So we can check out the changes first before merging from our branch to the master when we are satisfied with the changes and sure they won't mess things up.
