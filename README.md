# MERNSTACK-NOTES

This is a place where you can find the notes for entire mern stack programme


MY NOTES:

		#  	Create New Repository in Github for your Website 		

		1.	# Move to the Folder location by entering inside command prompt--> cd paste_location_here (or) open that exact folder, clear the url and Type --> cmd

(One Time) 	2.	# After moving to the project location in command prompt -->  git init

		3.	# To Add files -->  git add index.html

		4.	# To Add all files -->  git add .

		5.	# After adding files to confirm -->  git commit -m "first commit"
			
			(Note: If u wanna switch to "main" branch from master -> git branch -M main)

(One Time) 	6.	# During first transfer tell the github repository location to git -->  git remote add origin https://github.com/Coder-Gokul/test.git

			(Note: origin is a user defined url name.)

		7.	# To push the files inside github repository --> git push -u origin master  /  git push -u urlName BranchName

		8. 	# To get the file data's from github to local --> git pull
	
(One Time)	9. 	# To create branch for  local copy --> git checkout -b "BranchName"
			(Note: To create new Branch-> git branch branchName)

		10. 	# To switch between branches --> git checkout master   /  git checkout BranchName

		11. 	# Inorder to copy files from branch to master, First switch to master (git checkout master) & enter --> git merge BranchName 

(Others) 	12.	# To know in which branch v r currently in --> git status

		[Note:Pull Request is used  to merge the files together btwn branch and master ]

---------------------------------------------------------------------------------------------------------------------------------
CLONING:

                CLONING file from Github to Local server:

                1.	Create New folder in local laptop 
                2.	open GitBash and move to that location by --> cd "..location.."
                3.	open Github file which u gonna clone and copy the HTTPS link
                4.	open Gitbash and enter -->  git clone "HTTPS link"
                5. 	To check the cloned folder enter in  Gitbash--> ls

                       ----------------

                AFTER CLONING to run the file 

                1. open vs-code and its specific folder
                2.open Terminal-New terminal
                3. enter --> npm i 
                4. enter --> npm start

---------------------------------------------------------------------------------------------------------------------------------

Git Basics: (cd-change directory)

1. To change directory location using command propmt -> cd locationName 
2. To go back previous/Back location -> cd ..
3. To check No. of files in that location -> dir
4. To create new folder -> mkdir newFolderName

---------------------------------------------------------------------------------------------------------------------------------

[Note: In Command Prompt v can't able to use linux commands.So v need to use GitBash inorder to use both Git & linux commands]

Git Bash:

1.  To change directory location using GitBash -> cd locationName
2.  To create new file //Linux cmd// -> touch newFile.txt
3.  To list all files in current location //Linux cmd// -> ls
4.  To list files in neigh folder //Linux cmd// -> ls .folderName
5.  To list hidden files/Folders like git inside the folder //Linux cmd// -> ls -a
6.  To clear the GitBBash screen -> clear
7.  To check the status (Staged/unStaged) & (modified or not) of files -> git status
    (Note: Initially the files will be un-tracked/Un-staged untill v make "git add" thn it'll get tracked/Staged)
8.  To Un-Track/unstage particular files -> git rm --cached fileName
9.  To check complete commited & staged  status/details -> git log
10. To move previously changed/commited file back & forth->git checkout <commit ID>
11. To create new Branch-> git branch branchName
12. To check the differences in two branch -> git diff branchName1 branchName2
---------------------------------------------------------------------------------------------------------------------------------

Git User/Email Configuration:

1.git config --global user.name "gitUserName"
2.git config --global user.email "gitEmail@gmail.com"

---------------------------------------------------------------------------------------------------------------------------------

// All Commands

	cd
	mkdir
	ls
	dir
	touch
    -------
	git init
	git status
	git add <file name>
	git commit
	git log
	git rm --staged fileName
	git checkout <commit id>
	git push -u urlName branchName

---------------------------------------------------------------------------------------------------------------------------------