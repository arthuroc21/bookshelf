# The Git & Github Bootcamp
<details>
<summary>Installation & Set Up</summary>

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
   touch folderName1 folderName2 folderName3
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
</details>
