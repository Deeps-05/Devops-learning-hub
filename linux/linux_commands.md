# Linux Notes

## Navigation Commands

### Print Current Directory

```bash
pwd
```

Displays the current working directory.

### List Files and Directories

```bash
ls
ls -a
ls -l
ls -la
```

- `-a` : Shows hidden files
- `-l` : Long listing format

### Change Directory

```bash
cd directory_name
cd ..
cd ~
```

- `..` : Parent directory
- `~` : Home directory

---

## File Operations

### Create File

```bash
touch file.txt
```

### Create Directory

```bash
mkdir mydir
```

### Copy Files

```bash
cp source.txt destination.txt
```

### Move/Rename Files

```bash
mv old.txt new.txt
```

### Delete File

```bash
rm file.txt
```

### Delete Directory

```bash
rm -r directory_name
```

---

## Viewing File Contents

### Display Entire File

```bash
cat file.txt
```

### View Beginning of File

```bash
head file.txt
```

### View End of File

```bash
tail file.txt
```

### Read File Page by Page

```bash
less file.txt
```

---

## File Permissions

### View Permissions

```bash
ls -l
```

Example:

```text
-rwxr-xr--
```

### Change Permissions

```bash
chmod 755 script.sh
chmod 777 file.txt
```

Permission Meaning:

| Number | Permission |
|----------|----------|
| 4 | Read |
| 2 | Write |
| 1 | Execute |

Examples:

```text
755 = rwx r-x r-x
777 = rwx rwx rwx
644 = rw- r-- r--
```

---

## User Management

### Current User

```bash
whoami
```

### Display Logged-in Users

```bash
who
```

### User ID Information

```bash
id
```

