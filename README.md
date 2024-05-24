# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# Developed By
```
Name : Sabitha P
Register Number : 212222040137
```

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


## COMMAND

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt

```

## OUTPUT:

![image](https://github.com/sabithapaulraj/Windows-basic-commands-batchscript/assets/118343379/5fbcf2b5-8ed5-4b94-a5e8-c714088990aa)




## COMMAND

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

## Output:
![image](https://github.com/sabithapaulraj/Windows-basic-commands-batchscript/assets/118343379/c57df128-f8ce-483f-a2fc-b2fa998f67a9)




## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```


## OUTPUT
![image](https://github.com/sabithapaulraj/Windows-basic-commands-batchscript/assets/118343379/4b485009-38f0-499a-b025-d98edae00a1e)




## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT:
![image](https://github.com/sabithapaulraj/Windows-basic-commands-batchscript/assets/118343379/580064dc-ef03-40ab-8972-7027e649655f)



```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```







## OUTPUT:
![WhatsApp Image 2024-04-28 at 21 44 20_41678a5b](https://github.com/sabithapaulraj/Windows-basic-commands-batchscript/assets/118343379/a4de0dc2-b8ff-4f3d-82cf-1490bac46e34)








# RESULT:
The commands/batch files are executed successfully..

