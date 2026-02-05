#WADS COURSE

Name : Jovan Nikholas
Student ID : 2902641811

How Git works ?

Git operates using a "distributed" model. This means every developer has a full copy of the project history on their own machine, rather than relying on a single central server.

Git Operating Principal :

1. Snapshots, Not Differences: Most systems store a base file and a list of edits. Git creates a miniature "filesystem" snapshot. If a file hasn't changed, Git doesn't copy it again—it just creates a link to the previous version to save space.

2. Integrity (Hashing): Everything in Git is check-summed using a SHA-1 hash (a long string of characters like 4a2b1...). This means it's impossible to change the contents of a file or a folder without Git knowing about it.
