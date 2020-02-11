# Q&A From Lab

1.	Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.  
Answer: In my local repository: git status

2.	Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.  
Answer: vim hello-world.txt
	git add hello-world.txt 
git commit -m “hello-world.txt is created”

3.	Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.  
Answer:  git diff README.md

4.	Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.  
Answer: git show abc123

5.	Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.  
Answer: git log --oneline -n 3

6.	Assuming that you are currently within a Git repository, write the command (or commands) that will check to see if the remote repository contains any new commits.  
Answer: git fetch  
	  git status  


