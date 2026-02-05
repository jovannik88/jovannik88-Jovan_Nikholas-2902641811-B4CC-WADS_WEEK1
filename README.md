#WADS COURSE

Name : Jovan Nikholas
Student ID : 2902641811

What is Git?

Git is is a version control system that tracks every change made to files over time, allowing you to revisit any previous state of your project if things go south.
How Git works ?

Git operates using a "distributed" model. This means every developer has a full copy of the project history on their own machine, rather than relying on a single central server.

How Git Operates (four areas of git):

1. Working Directory: Where you are currently making changes to your files.
2.	Staging Area (Index): A middle ground where you format and "wrap" your changes before finalizing them.
3.	Repository (Local/Remote): Where Git permanently stores the changes as a "commit" (a snapshot in time).

Git Workflow :
1. Modify: You change files in your Working Directory.
2. Stage: You run git add. This moves those changes into the Staging Area. This allows you to group related changes together even if you edited 10 different files.
3. Commit: You run git commit. Git takes everything in the Staging Area and wraps it into a permanent snapshot with a message. This is now safely stored in your Local Repository.
4 .Push: You run git push. This sends your local commits to a Remote Repository for safekeeping or collaboration

Git Operating Principal :

1. Snapshots, Not Differences: Most systems store a base file and a list of edits. Git creates a miniature "filesystem" snapshot. If a file hasn't changed, Git doesn't copy it again—it just creates a link to the previous version to save space.

2. Integrity (Hashing): Everything in Git is check-summed using a SHA-1 hash (a long string of characters like 4a2b1...). This means it's impossible to change the contents of a file or a folder without Git knowing about it.

Git Branching and Merging :

Git operates using Pointers.
1. A Branch is just a lightweight pointer to a specific commit.
2. HEAD is a special pointer that tells Git which branch you are currently working on.
When you create a branch, Git simply creates a new pointer; it doesn't duplicate your files. This is why branching in Git is so much faster than in other version control systems.
