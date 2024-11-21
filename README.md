# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/user-attachments/assets/cd1a470e-fb0d-4a33-8386-0b0c17540a72)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/7724e6f9-0426-4949-beef-855e5c2bf79d)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/335512b0-ae59-48a1-a071-474caf8b9c9d)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/93658398-6dfe-4d6d-ba8b-c978b1b1d0f3)



## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/7cbbae52-d7b2-4828-b99e-25dbe13d9277)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```
## OUTPUT

![image](https://github.com/user-attachments/assets/bf2ce4ae-1942-4fa0-926c-14590f2e0f7d)


# RESULT:
The commands/batch files are executed successfully.
