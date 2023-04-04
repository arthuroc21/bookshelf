# The Git & Github Bootcamp

These are my notes from an online bootcamp that I took about Git and Github.  
I'm gonna leave the bootcamp's link [HERE](https://www.udemy.com/course/git-and-github-bootcamp/) in case you wanna check for yourself.

<details>
  <summary>Set Up</summary>

  ### Some commands

  * **Configuring your git name & email**:

  ```git
    git config --global user.name "Arthur Candido"
  ```
  ```git
    git config --global user.email "carlos.arthur.candido@gmail.com"
  ```  

  * **Display current user name**:

  ```git
    git config user.name
  ```

  * **ls (List)**: List the contents of the working directory

  ```git
     ls
  ```

  * **start . (Windows) | open . (Mac)**: Open the working directory folder

  ```git
     start .
  ```
  ```git
     open .
  ```

  * **ls _folderName_**: List the contents of the selected folder _folderName_

  ```git
     ls folderName
  ```

  * **start _folderName_ (Windows) | open _folderName_ (Mac)**: Open the selected _folderName_ folder

  ```git
     start folderName
  ```
  ```git
     open folderName
  ```

  * **clear**: Clear the content of the terminal

  ```git
     clear
  ```
  > 📝 Note: The command just erases the content of the terminal, it doesn't restart the command lines.

  * **ls _folderName1/folderName2_**: List the contents of the selected folder _folderName2_ inside the folder _folderName1_

  ```git
     ls folderName1/folderName2
  ```

  * **pwd (Print Working Directory)**: Prints the path to the working directory

  ```git
     pwd
  ```

  * **cd (change directory) folderName**: Change and move between folders

  ```git
     cd folderName/
  ```

  * **cd ..**: "Back up" one directory

  ```git
     cd ..
  ```

  * Creates a file (or mutiples)

  ```git
     touch fileName.extension
     touch fileName1.extension fileName2.extension fileName3.extension
     touch folderName1/folderName2/fileName.extension
  ```

  * **mkdir (make directory)** Creates a directory (or mutiples)

  ```git
     mkdir folderName
     mkdir folderName1 folderName2 folderName3
  ```
  > 📝 Note: The folder name mustn't contain space. If necessary, you need to use quotes i.e "Sea Turtles".

  * **rm (remove)** Delete a file (or mutiples)

  ```git
     rm fileName
     rm fileName1 fileName2 fileName3
  ```
  > 📝 Note: It Permanently removes them!

  * **rm -rf (r = recursive; f = force)** Delete a directory

  ```git
     rm -rf folderName
  ```
  > 📝 Note: -rf is a flag. A flag can be used to modify the behaviour of the command.
</details>

<details>
  <summary>The Very Basics Of Git: Adding & Committing</summary>

  ### Some commands

  * Gives information on the current status of a git repository and its contents

  ```git
     git status
  ```
  > 📝 Note: [status documentation](https://git-scm.com/docs/git-status).

  * Creates a new git repository

  ```git
     git init
  ```
  > 📝 Note: [init documentation](https://git-scm.com/docs/git-init).  
  > 📝 Note: Do not init a repo inside of a repo!

  * **ls -a**: List all hidden files

  ```git
     ls -a
  ```
  
  * Add changes from the working directory to be commited later

  ```git
     git add fileName
     git add fileName1 fileName2 fileName3
  ```
  > 📝 Note: [add documentation](https://git-scm.com/docs/git-add).
  
  * Add all changes at once from the working directory to be commited later

  ```git
     git add .
  ```
  
  * Commits the files

  ```git
     git commit
  ```
  > 📝 Note: [commit documentation](https://git-scm.com/docs/git-commit).  
  > 📝 Note: It opens the terminal to edit the commit message. To use a code editor (e.g. Visual Studio Code) to edit the commit message, check the section "Configuring Git's Default Editor".

  * Commits the files with a message

  ```git
     git commit -m "my message"
  ```
  
  * Log of the commits for a given repository

  ```git
     git log
  ```
  > 📝 Note: [log documentation](https://git-scm.com/docs/git-log). 

</details>

<details>
  <summary>Commits In Detail (And Related Topics)</summary>

  ### Reference Manual To All Git Commands And Main Topics
  [Git Documentation](https://git-scm.com/docs). 
  
  ### Configuring Git's Default Editor
  [Git's Editor Configuration](https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Setup-and-Config). 
  
  ### Some commands
  
  * Commit a forgotten file to the previous commit command

  ```git
     git commit --amend
  ```
  > 📝 Note: It only works for the last commit command. If there's need to update a previous commit command, this tag --amend doesn't work.
  > 📝 Note: The command opens the terminal to edit the commit message. 
  
  * Ignoring files on Git

  ```git
     git touch .gitignore
  ```
  > 📝 Note: This command will create a file with .gitignore extension. All files to be ignored must be written down on this file.  
  > 📝 Note: The command opens the terminal to edit the text.  
  > 📝 Note: .fileName will ignore files named fileName.  
  > 📝 Note: folderName/ will ignore an entire directory.  
  > 📝 Note: *.log will ignore any files with the .log extension.  
  > 📝 Note: [GitIgnore documentation](https://git-scm.com/docs/gitignore).
  
</details>

<details>
  <summary>Working With Branches</summary>
  
  ### Some commands

</details>
