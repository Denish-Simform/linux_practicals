


# Linux Command Line Practical:
##Practical 1

### 1. Manipulating Files and Directories
		mkdir <fileName>
		cd <fileName>
		touch <fileName>
		gedit <fileName>
		cat <fileName>
		mv <fileName> <RenamedfileName>
		cp <fileName> <newfileName>
		head <fileName>
		tail <fileName>
		nano <fileName>
### 2. List all file permissions with example.
		ll	
### 3. List all running process.
		ps
		ps x
### 4. Find particular process by its name.
		pidof <process>
		ps aux | grep -i <process>
		pgrep <process>
### 5. How to kill any particular process.
		killall <process>
		kill pid
### 6. Vi or Vim for file editing.
		vim <fileName> 	
### 7. Change file owner and group.
		chown <userName/ownership> <fileName>
### 8. Change group ownership.
		chgrp <groupName> <fileName>
### 9. Moving and Renaming Files.
		mv <fileName> <RenamedfileName>
### 10. Remove Files and Directories.
		rm <fileName>
		rm -r <directoryName>
### 11. List the directory contents.
		ls
### 12. How I can get the path of working directory.
		pwd
### 13. How to Search in Vim/Vi.
		/Hello
		/Hello\c
### 14. How Do You Do a Search andReplace in Vim/Vi.
		%s/Hello/hello
### 15. How we can save and exit from Vim/Vi file.
		!wq


## Practical 2
### 1. Write a command to create new folder
		mkdir new-folder
### 2. Write a command to find the current path of the folder
		pwd	
### 3. Write a command to move into new created folder
		cd new-folder	
### 4. Write a command to create new file
		touch new-1.txt
		mkdir new-1.txt	
### 5. Write a command to add some content in a file
		echo "text needs to be added" >> new-1.txt
		gedit new-1.txt	
### 6. Write a command to find a specific word from a file
		grep "article" new-1.txt 	
### 7. Write a command to find the size of a file
		ls -s	
### 8. Write a command to rename that file
		mv new-1.txt file-1.txt
### 9. Write a command to make a copy of a file with another name
		cp file-1.txt new-1.txt	
### 10. Write a command to show the list of files in folder
		ls
### 11. Write a command to move that file to desktop
		mv file-1.txt /Desktop
		sudo mv file-1.txt /Desktop	
### 12. Write a command to change permissions of the file
		chmod 776 file-1.txt
### 13. Write a command to delete file
		rm file-1.txt	
### 14. Write a command to delete created folder
		rm -r <folderName>	
### 15. Write a command to find a any file on local machine
		find -name <fileName>	
### 16. Write a command to create a zip of files from specific path on local machine
		zip -r <zipFolderName> /Desktop/demo	
### 17. Write a command to unzip
		unzip <zipFolderName>	
### 18. Write a command to download file from specific location on the internet
		wget <url>	
### 19. Write command to see last 10 lines of a file.
		tail -10 file-1.txt	
### 20. Write command to see history of a file.
		stat file-1.txt
    
    

## Authors

- [@Denish-Simform](https://github.com/Denish-Simform)

