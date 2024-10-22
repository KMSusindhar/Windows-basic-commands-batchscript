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
mkdir %userprofile%\Desktop\MyLab
![329118072-e995f79f-aaba-442c-9656-a2a08254ae6e](https://github.com/user-attachments/assets/1bb219b3-b497-4063-a075-fa705ac14af9)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab
![329118150-42716050-4c57-409a-ba15-bc74916e236b](https://github.com/user-attachments/assets/df82e4fd-7854-4e12-8392-6a07e74224de)
![329118197-5261ae76-6da8-4099-af43-454d30a7bb0c](https://github.com/user-attachments/assets/11d7631f-6fa0-4913-a7e0-3a1cafad8f99)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
dir %userprofile%\Desktop\MyLa

![329118290-a75e0d20-0ba6-4908-9719-1e2b13aea1d4](https://github.com/user-attachments/assets/8df1774b-4d5b-4dbb-a8ce-a5e42be077df)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
![329118377-cb5e75d6-e7c9-4b0f-a0c1-89b066b228f6](https://github.com/user-attachments/assets/9f6eac21-9713-4e4f-927f-11a7f1025a97)
![329118411-526cd0df-ca0c-41cf-b4c1-555cd69d29dc](https://github.com/user-attachments/assets/08522f27-c1aa-4aa8-bb12-fb6419469552)

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![329118461-703084f3-b524-4ed7-bb9c-c6fba705eb95](https://github.com/user-attachments/assets/d92574ce-b92a-4336-a9cd-bd4e2a3870f6)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT
![329118577-469a4295-b9e1-44b5-9c40-ed949f8fb79e](https://github.com/user-attachments/assets/057beef4-89c7-437b-8387-2d49183316f2)





# RESULT:
The commands/batch files are executed successfully.

