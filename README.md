# Linux Commands Practice

This repository contains practice tasks (1–7) for basic Linux commands with explanations and screenshots.

## Tasks Covered
1. Creating and Renaming Files/Directories
2. Viewing File Contents
3. Searching for Patterns
4. Zipping and Unzipping
5. Downloading Files
6. Changing Permissions
7. Working with Environment Variables

## How to Use
- Open the `Linux_Commands_Practice.docx` (or PDF) file for detailed commands, explanations, and screenshots.
- Each task includes:
  - The command used
  - A short explanation
  - A screenshot of the output

## Example Commands

### Creating a Directory and File
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt
```

### Viewing File Contents
```bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

### Searching for Patterns
```bash
grep "root" /etc/passwd
```

### Zipping and Unzipping
```bash
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir
```

### Downloading Files
```bash
wget https://example.com/sample.txt
```

### Changing Permissions
```bash
touch secure.txt
chmod 444 secure.txt
```

### Working with Environment Variables
```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```
