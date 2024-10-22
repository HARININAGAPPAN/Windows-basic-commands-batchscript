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
![Screenshot 2024-10-22 083443](https://github.com/user-attachments/assets/a2738ba0-0bf2-4659-b334-33d72f7c01aa)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![Screenshot 2024-10-22 083456](https://github.com/user-attachments/assets/51e3e82f-fecc-4943-bd7c-5b91b0784a8c)
![Screenshot 2024-10-22 083509](https://github.com/user-attachments/assets/147bf705-882f-46a5-8811-b03f7581b4db)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![Screenshot 2024-10-22 083524](https://github.com/user-attachments/assets/d03db370-bd93-42a5-8342-698fd9a8dc57)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder. %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![Screenshot 2024-10-22 083534](https://github.com/user-attachments/assets/4dceaf5a-72c5-4ced-9c9b-37737c09f18f)

![Screenshot 2024-10-22 083548](https://github.com/user-attachments/assets/d22142ee-d686-42a2-8819-f304d4d86060)


## COMMAND AND OUTPUT

![Screenshot 2024-10-22 083600](https://github.com/user-attachments/assets/ab773a2f-0707-4359-bd93-d9982ea36ee4)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT

![Screenshot 2024-10-22 083613](https://github.com/user-attachments/assets/a1365d79-463c-4be0-98c5-ae3d2e12c5f4)




# RESULT:
The commands/batch files are executed successfully.

