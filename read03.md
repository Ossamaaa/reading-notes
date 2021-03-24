
**Version Control** is the main system can revisite old versions  of files by recoreding changes ,and compare changes ,and fixed any mistakes easily .
 
(CVCS) allowed to programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control


there's one problem in (CVS) that if the server goes down can't work on a file or save changes , to avoid like this problem (DVCS) can let  create mirrored for cllintes .

Snapshots
that stores data in a file system made up of snapshots. Each time you save a changed version of your project .
,,,, 
 default text editor
Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs.

 U can by this command in terminal  :
" $ git config --global core.editor emacs"

To check settings, use :

" git config --list command "

 

when you have import existing project  you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

,,,,

 * The local Git repository has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

The Life Cycle of File Status: 

1. After you edit a file, Git flags it as modified because of changes made 2. after the previous commit.
3. You stage the modified file.
4. Then, you commit staged changes.


Committing a File 

After staging one or multiple files, you should commit the changes and record what you did within the commit message: 

$ git commit -m “made change x,y,z”

