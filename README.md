# ansible-puff-lessons

## Learning Linux

These notes are a hands-on starting point for learning Linux. Use the
[Learning Linux TV video](https://www.youtube.com/watch?v=CMB5GCexb84) as a
companion, and try the commands in a Linux terminal or virtual machine.

### Learning path

1. Navigate the filesystem and manage files.
2. Read and search text files.
3. Understand users, groups, and permissions.
4. Install software and manage services.
5. Inspect processes, storage, and network connections.
6. Practice shell scripting and automate repeated tasks.

### Lesson 1: Filesystem navigation

Start by finding your location and listing its contents:

```sh
pwd
ls
ls -la
```

Linux paths begin at `/`. Use `cd` to change directories; `~` means your home
directory, and `..` means the parent directory.

```sh
cd ~
mkdir linux-practice
cd linux-practice
touch notes.txt
ls -l
```

Use `cp` to copy files and `mv` to move or rename them. Be cautious with
commands that delete files, especially when using elevated privileges.

**Practice:** Create a directory under your home directory, make two empty
files in it, and use `pwd` and `ls -l` to confirm where they are.
