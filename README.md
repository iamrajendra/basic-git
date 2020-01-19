<!----- Conversion time: 1.251 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Sat Jan 18 2020 21:46:16 GMT-0800 (PST)
* Source doc: https://docs.google.com/open?id=13wcEYbRq8R1b2knHWh4e6mjNkA3x9zO1mfskNIQ7fII
* This is a partial selection. Check to make sure intra-doc links work.
----->


# Basic of git

## Commands to create a repository and upload project to GitHub

 


<table>
  <tr>
   <td>S.no
   </td>
   <td>Command
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>git init
   </td>
   <td>Convert the normal repository to git
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>git status
   </td>
   <td>It will inform the status of files, like TRACK, UN-TRACK, MODIFIED, DELETED 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>git add <file-name>
   </td>
   <td>This command will use to add the file, if it is in the status of UN-TRACK, MODIFIED
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>git add .
   </td>
   <td>This command is used to all files of the directories, good practice is too add the files in which you worked because it give bad impact in to the git history.
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>git commit -m
   </td>
   <td>This will commit the state of the files and directories. Git commit -m “initial commit”, is used in the terminal
   </td>
  </tr>
  <tr>
   <td>6.
   </td>
   <td>git commit
   </td>
   <td>This will also commit the sate of the files and directories, but the commit message, it uses the default editor like VIM.
<p>
 
   </td>
  </tr>
  <tr>
   <td>7
   </td>
   <td>git remote add <origin-name> <url.git>
   </td>
   <td>This command is use to add the repository to the server.
<p>
 
   </td>
  </tr>
  <tr>
   <td>8
   </td>
   <td>git remote -v
   </td>
   <td>It is used see the list of remote origin to push and pull the repository code
   </td>
  </tr>
  <tr>
   <td>9
   </td>
   <td>git remote rm <origin-name>
   </td>
   <td>It is used to delete the origin.
   </td>
  </tr>
</table>


 

## Commands to add the repository from the remote server and manage the project.

 


<table>
  <tr>
   <td>S.no
   </td>
   <td>Commands
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>git clone <url.git>
<p>
 
<p>
from http
   </td>
   <td>This command is used to take the project from the remote repository. In http mode SSL key is not require and it is less secure
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>git clone <url.git>
   </td>
   <td>This command is used to take the project from the remote repository. In http mode SSL key is require and it is highly secure. To   use this command, a developer have to save ssl key to the git server. 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>git branch
   </td>
   <td>It will show the list of the branch associated with the repository
<p>
 
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>git branch -b <branch-name>
   </td>
   <td>It is used to create new branch
   </td>
  </tr>
  <tr>
   <td>5.
   </td>
   <td>git checkout <branch-name>
   </td>
   <td>It is used to switch to the particular branch.
   </td>
  </tr>
  <tr>
   <td>6.
   </td>
   <td>git checkout <file-name>
   </td>
   <td>Restore the file to the committed state
   </td>
  </tr>
  <tr>
   <td>7
   </td>
   <td>git checkout <directory>
   </td>
   <td>Restore the directory to the committed state
   </td>
  </tr>
  <tr>
   <td>8
   </td>
   <td>git merge <branch-name>
   </td>
   <td>It merges the code with the particular branch
   </td>
  </tr>
  <tr>
   <td>9
   </td>
   <td>git merge <commit-hash code>
   </td>
   <td>It merges the code with the commit hash-code
   </td>
  </tr>
</table>


 

 

## Commands to work with the local changes

 


<table>
  <tr>
   <td>S.no
   </td>
   <td>Command
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>git stash
   </td>
   <td>It is used to save the local changes, and worked on other experimental things
   </td>
  </tr>
  <tr>
   <td>2.
   </td>
   <td>git stash list
   </td>
   <td>It will show the list of all the stash changes
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>git stash pop <position>
   </td>
   <td>It will pop the stash of a particular position
   </td>
  </tr>
  <tr>
   <td>4.
   </td>
   <td>git stash clear
   </td>
   <td>It will clear all the stash
   </td>
  </tr>
</table>


 

## Commands to edit the git user profiles

 


<table>
  <tr>
   <td>S.no
   </td>
   <td>Command
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>git config user.name
   </td>
   <td>To show ,add and edit the username at the project level
   </td>
  </tr>
  <tr>
   <td>1.
   </td>
   <td>git config user.name
   </td>
   <td>To show,add and edit the username at the project level
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>git config –global user.name
   </td>
   <td>To show,add and edit the username at the System level
<p>
 
   </td>
  </tr>
  <tr>
   <td>3.
   </td>
   <td>git config –global user.name
   </td>
   <td>To show,add and edit the username at the System level
<p>
 
   </td>
  </tr>
</table>


 

 

 

                                                                                                         


<!-- Docs to Markdown version 1.0β17 -->
