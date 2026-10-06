# Linux Basics Lab

## Goal

Practice basic Linux terminal commands and learn how to navigate directories, manage files, and work with text files in Ubuntu.

## Commands practiced

```bash
pwd
ls
cd
mkdir
touch
cp
mv
cat
echo
rm
```

## What I practiced

- checking my current location with `pwd`
- listing files and directories with `ls`
- moving between directories with `cd`
- going one directory up with `cd ..`
- returning to the home directory with `cd` or `cd ~`
- using paths to move through multiple directories
- using `Tab` to autocomplete file and directory names
- creating directories with `mkdir`
- creating empty files with `touch`
- copying files with `cp`
- moving files with `mv`
- renaming files with `mv`
- reading file contents with `cat`
- writing text to files with `echo`
- redirecting output to a file with `>`
- appending text to a file with `>>`
- deleting files with `rm`

## Practical Exercises

### Creating a directory and files

```bash
mkdir lab-linux
cd lab-linux
touch notatka1.txt
touch notatka2.txt
ls
```

### Copying a file

```bash
cp notatka1.txt kopia_notatka1.txt
```

### Renaming a file

```bash
mv notatka2.txt archiwum.txt
```

### Writing text to a file

```bash
echo "To jest test" > notatka1.txt
```

### Reading file contents

```bash
cat notatka1.txt
```

### Appending text without overwriting the file

```bash
echo "Druga linia" >> notatka1.txt
```

### Deleting a file

```bash
rm kopia_notatka1.txt
```

### Creating a backup directory and moving a file

```bash
mkdir backup
mv archiwum.txt backup
cd backup
ls
```

## Important Concepts

### `>` vs `>>`

`>` overwrites the existing content of a file.

```bash
echo "New text" > file.txt
```

`>>` adds new text to the end of the file without deleting the existing content.

```bash
echo "Another line" >> file.txt
```

### Basic directory navigation

```bash
cd ..
```

Moves one directory up.

```bash
cd
```

or:

```bash
cd ~
```

Returns to the home directory.

I also learned that I can use a full path instead of moving through every directory one by one, and I can use the `Tab` key to autocomplete file and directory names.

## What I Learned

During this lab I practiced basic Linux file and directory management in Ubuntu.

I learned how to:

- navigate through the filesystem
- create files and directories
- copy, move and rename files
- delete files
- read file contents
- write and append text to files
- use simple terminal shortcuts to work faster

This lab helped me become more comfortable using the Linux terminal and gave me a foundation for future IT and cybersecurity labs.
