## Create
```bash
mkdir folder_name   # Create folder
touch file.txt      # Create file
```

## Open / Go Inside Folder
```bash
cd folder_name       # Open folder
cd ..                # Go back
cd ~                 # Home directory
```

## Open File
```bash
cat file.txt        # Open (read)
less file.txt       # Open (scroll)
nano file.txt       # Open in nano editor
code file.txt       # Open in Vs Code
```

## Open Folder in File Manager / VS Code
```bash
xdg-open folder_name          # Open folder (Linux)
open folder_name              # Open folder (macOS)
code folder_name              # Open in VS Code
```

### List Files & Folders
```bash
ls          # List
ls -l       # Detailed List
ls -a       # Include hidden files
```

### Rename
```bash
mv old_name new_name         # Rename file or folder
```

### Copy
```bash
cp file.txt newfile.txt      # Copy file
cp -r folder newfolder       # Copy folder
```

### Move Folder / file

```bash
mv file.txt folder/      # Move file
mv folder1  folder2/     # Move folder
```

### Delete
```bash
rm file.txt           # Delete file
rm -r folder_name     # Delete folder
rm -rf folder_name    # Force delete (danger)
```


### Find
```bash
find . -name file.txt     # find file
```

### Clear Terminal
```bash
clear
```

### Must-Know Shortcuts
```bash
Tab        # Auto complete
ctrl + C   # Stop command
ctrl + L   # Clear screen
```
