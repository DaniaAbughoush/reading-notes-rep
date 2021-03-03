# read-02b
# Version control 
is system allow us to revisit various files and track the changes ,so install a version control system VSC so you can track Mistakes, and there is a local version control created many years ago store changes to files. And for the need of collaboration between developers on one files or more they created .
Centralized Version Control CVS which allow access for multiple users, with no need for local version control.
But there was a major problem in CVS which is there is backups for data and if one server had a failure all for clients share one file all work will lost ,  a need for Distributed Version Control System DVCS found ,which will create mirrored repositories and allow clients to work in different way with no data loss.
# What is Git:
## Advantages:
First you need to know snapshot: which every time you make a change Git will create snapshot with store it with reference, if there is no change then will store reference to already exist file.
Local Operations
Git will depend on local operation, so even if there is no online will continue to work
 Git as a gate keeper: That’s mean every single change will track and store ,and detect loss information
Loss of Data :Loss of data nearly is impossible because of snapshot
### Git reside in three
 :Committed data stored in database ,Modified file change but not stored in database, Staged will flage the change in the next snapshot
## History of Git :
It was created because problem between two company in 2005 then become one of the most utilized Version Control Systems in the world.
### Installation:
To install git you have to get latest version ,you can install it by these three way Git can be installed in three ways: Install as a package, Install via another installer or Download and compile the source code.If you have Mac OS X install it by running Git from the Terminal, or from its website or from GitHub,.For Windows Install it through website, GITHub or through Linux like the following: for Fedora:$ sudo yum install git  ,For Ubuntu:$ sudo apt-get install git
### Graphical Clients  Git already have a graphiacal tools but you can install more via https://git-scm.com/downloads/guis
## Initial Customization
1.	git config:tool in Git allow you to control aspects and operation,Identity Setting:use youe user name and password ,By Typing  the following  Command Line: git config --global user.name "daniaabughoush"  ,git config --global user.email something@email.com,To make sure its right, enter the following command: git config --global user.name (should return daniaabughoush)
2.	git config --global user.email (should return something@email.com)
you can choose different identity,globle option above means  that  Git settings apply to anything on the system. To configure a different text editor enter$ git config --global core.editor emacs,Check it by  git config –list,
### You can get help by this three commands:
git help command
git command --help
man git-command
now to import existing project on git use :  $ cd test (cd = change directory) ,then $ git init
now for tracking 
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”
#Cloning
To copy existing git use the command clone like this from particular server using the repository’s URL:
$ git clone https://github.com/test
By doing this you have all version of the files
To clone in specific directory with different name:
$ git clone https://github.com/test (name you want)
##Local Repository Structure
 333local Git repository has three iteam: 
*Working Directory: The existing files reside here.
*Index: The staging area
 *Head: which m,eans Points to the most recent commit
##The files in working in two states: tracked or un track
Tracked :we can modify them and they are a part of last snapshot
Untracked: not in the last snapshot or in the stage area
##The Life Cycle of File Status
 Modified, stage , commit 
##To check file stages use command:
$ git status
3##Tracking for one file use 
git add filename
for all file use
$ git add *
Reuse this command when file added
git status
###for commiting a file use 
$ git commit -m “made change x,y,z”
####For all changes
$ git commit –a
###For Pushing change:
$ git push origin master
###For Stashing Changes
git stash
