# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
## Name:Mohanaprabha S
## Date:17.5.25
## Register no:212224040197
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

```
mkdir %userprofile%\Desktop\MyLab

```

![image](https://github.com/user-attachments/assets/55117a01-d2c2-4b1b-a6a3-dff1ec37d53f)

```
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/user-attachments/assets/c9ee7313-2f27-4958-8ef2-b999d081db77)

```
type nul > MyFile.txt
```
![image](https://github.com/user-attachments/assets/13c34a6d-dacb-4836-a80b-74f6ec954b4c)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

![image](https://github.com/user-attachments/assets/a3f0884e-2f3b-4f87-b735-ee72dd3646ba)




## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
type.
```
mkdir %userprofile%\Desktop\Backup
```

![image](https://github.com/user-attachments/assets/6f9c8665-de08-4ad3-8b48-825a1c5ed281)

```
copy MyFile.txt %userprofile%\Desktop\Backup
```

![image](https://github.com/user-attachments/assets/c7143c57-f9ee-4a47-b7bc-fbe33ab6316c)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Documents
```
```
move MyLab Documents
```

![image](https://github.com/user-attachments/assets/863e6152-0346-4ab8-9ccb-a76216a2be75)


## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

## OUTPUT


![image](https://github.com/user-attachments/assets/77a1b537-4bbf-4747-b164-44865c33e25e)


# RESULT:
The commands/batch files are executed successfully.

