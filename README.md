# BackupTool  
Create a directory called backups in the same directory as the script  
```
mkdir backups  
```
Run the script:  
```
sh ./backup.sh  
```  
On first launch, it asks you to insert the path of the directory you want to backup. Enter the path and hit enter. The script will create a tar.gz archive of the entered path with the current date and time as name. If you want to create another backup, you can simply run the script without entering the path ever again.  
If you want to change the directory, go into the backups/ dir and remove the "path" file. Now run the script and you'll be prompted to enter the path again.  

