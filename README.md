# Linux
# Ubuntu Commands and Explanations

A beginner-friendly list of essential Ubuntu terminal commands, cleaned up and explained clearly.

---

## 🔐 Superuser Access

### `sudo su`
Switch to the root (superuser) account with full administrative privileges.  
⚠️ Use carefully, as you can modify critical system files.

---

## 📍 Navigation

### `pwd`
Prints the current working directory (your location in the filesystem).

### `cd [directory]`
Changes directory to the specified folder.

### `ls`
Lists files and directories in the current location.

### `ls -l`
Lists files and folders with detailed info (permissions, size, date, etc.).

### `ls -al`
Lists all files, including hidden ones (those starting with a `.`), with details.

---

## 📂 File and Directory Management

### `mkdir [foldername]`
Creates a new directory (folder).

### `touch [filename]`
Creates an empty file.

### `rm [filename]`
Deletes the specified file.

### `rm -r [foldername]`
Deletes a folder and all its contents (recursive delete).

### `rmdir [foldername]`
Deletes an **empty** folder only.

### `mv [oldname] [newname]`
Renames or moves a file or directory.

### `cp [source] [destination]`
Copies a file or folder.

---

## 📄 File Viewing

### `cat [filename]`
Displays the entire contents of a file.

### `less [filename]`
Opens file in a scrollable viewer. Use `q` to quit.

### `more [filename]`
Similar to `less`, scrolls one screen at a time.

### `head [filename]`
Shows the first 10 lines of a file.

### `tail [filename]`
Shows the last 10 lines of a file.

### `tail -f [filename]`
Follows a file and updates output as the file grows (useful for logs).

---

## ✏️ Creating/Writing to Files

### `echo "text"`
Displays the given text.

### `echo "text" > file.txt`
Writes the text to a file, **overwriting** existing content.

---

## 🕘 Command History

### `history`
Shows a list of all previously entered terminal commands.

---

## ✅ Summary of Concepts

| Concept               | Commands                                 |
|-----------------------|------------------------------------------|
| Navigation            | `pwd`, `cd`, `ls`, `ls -l`, `ls -al`     |
| File Management       | `mkdir`, `touch`, `rm`, `rm -r`, `rmdir` |
| Viewing Content       | `cat`, `less`, `more`, `head`, `tail`    |
| Writing to Files      | `echo`, `echo >`                         |
| Superuser Access      | `sudo su`                                |
| Command History       | `history`                                |

---

## 📌 Notes

- Use `Tab` to auto-complete file or folder names.
- Use the `up ↑` and `down ↓` arrows to scroll through command history.
- You can always use `man <command>` to read the manual for any command (e.g., `man ls`).

---
DAY-1 Complete 🎉
