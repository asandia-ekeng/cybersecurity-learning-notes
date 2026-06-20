Cybersecurity Note #15

Essential Linux Commands (Part 1)

Introduction

Linux systems are often managed through a command-line interface called the terminal.

Instead of clicking icons and menus, users type commands to perform tasks.

Learning basic Linux commands is an important skill for cybersecurity professionals, cloud engineers, DevOps engineers, and system administrators.

What is a Terminal?

A terminal is a text-based interface that allows users to interact directly with the operating system.

Through the terminal, users can:

* Navigate directories
* Create files
* Manage folders
* View information
* Execute program

pwd

Meaning

Print Working Directory

Purpose

Displays the current directory you are in.

Example

pwd

Example Output:

/home/asandia

This tells you your current location in the file system.

ls

Meaning

List

Purpose

Displays files and directories in the current location.

Example

ls

Example Output:

Documents
Downloads
Pictures

cd

Meaning

Change Directory

Purpose

Moves from one directory to another.

Example

cd Documents

This moves you into the Documents folder.

mkdir

Meaning

Make Directory

Purpose

Creates a new folder.

Example

mkdir cybersecurity-notes

This creates a directory named:

cybersecurity-notes

touch

Purpose

Creates a new empty file.

Example

touch note1.txt


cat

Meaning

Concatenate

Purpose

Displays the contents of a file.

Example

cat note1.txt

The terminal will show the contents of the file.


Why These Commands Matter

These commands are used frequently in:

* Linux administration
* Cloud computing
* DevOps
* Cybersecurity

They help users navigate systems efficiently and manage files directly from the terminal.

Practical Example

Imagine you want to create a folder and file for your notes.

Commands:

mkdir cybersecurity-notes
cd cybersecurity-notes
touch note1.txt
ls

Output:

note1.txt

You have successfully created and viewed a file using Linux commands.

Key Takeaway

The first Linux commands every beginner should know are:

* pwd
* ls
* cd
* mkdir
* touch
* cat

These commands provide the foundation for working with Linux systems.

🎯 Reflection

Imagine entering a new city.

Before doing anything else, you would want to know:

* Where am I? (pwd)
* What is around me? (ls)
* How do I move elsewhere? (cd)

Linux commands work in a similar way.

They help you understand and navigate your environment efficiently.


