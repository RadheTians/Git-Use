# Git-Use
This is the process to use Github by Ubuntu 19.04 in command line(i.e Terminal) 



# This is the process to use git from command line that's Ubuntu 19.04 Terminal

1. sudo apt-get install git

2. git --version

3. git config --global user.name "RadheTians"

4. git config --global user.email "radheramantiwari87@gmail.com"

5. git config --list

6. ls -la

7. gedit .gitconfig (From home directory)

8. mkdir DS

9. cd DS

10. git clone https://github.com/RadheTians/Data-Structure.git

11. cd Data-Structure

12. ls -l

13. Do some changes in DS directory....

	1.) gedit abc.cpp

	2.) do some coding like printing of "HELLO WORLD!"

	3.) save the file abc.cpp 

14. git status

15. git add abc.cpp
	
	1.) git add -A (To add all changes) 

16. git status

17. git commit -m "committed message" abc.cpp

	1.) git commit -a (To commit all changes without message)

	1.) git commit -a -m "Change titles and styling on homepage" (To commit all changes with message)
	
18. git remote -v

19. git remote add origin https://github.com/RadheTians/Data-Structure

20. git remote -v

21. git push -u origin master --force
	
	1.) Provide user name....

	2.) Provide user password....

22. git remote add origin master "https://github.com/RadheTians/Data-Structure.git"

23. Create a new branch name called "issue"
	
	1.) git checkout -b issue 



