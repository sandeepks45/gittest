this read me is used for git tutorial

1. how to download git bash for windows

2. git command
	git config --global user.name "sandeep.s"
	git config --global user.email "sandeep.s@gmail.com"
	git status
	git add
	git log

how to add git:
	mkdir gittutorial			#creates a directory
	cd gittutorial				#enters the directory
	git init .				#initialization of git
	vim readme.txt				#make changes in readme file
	git status				#shows the status of git as red at first
	git add readme.txt			#in order tocahnge the status from red to green

	git status				#status changes to green after ading add readme.txt step

	git commit -m "Added readme file"	#to commit the git commits
	git log					#to show the commit logs
