# Windows-basic-commands-batchscript

Ex08-Windows-basic-commands-batchscript

## AIM :

To execute Windows basic commands and batch scripting

## DESIGN STEPS :

### Step 1 :

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2 :

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3 :

Execute the necessary commands/batch file for the desired output. 

## WINDOWS COMMANDS :
## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT :

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab




List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab



Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab




Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup





mv Myfile.txt %userprofile%\Documents
![Screenshot 2025-05-19 093218](https://github.com/user-attachments/assets/b0eaa547-68ac-460b-9ced-027a8ce4eb2c)


## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT :
![Screenshot 2025-05-19 093240](https://github.com/user-attachments/assets/f33bf040-b1fc-43d8-82a7-c8aeab0e64e7)


## RESULT :
The command
s/batch files are executed successfully.

