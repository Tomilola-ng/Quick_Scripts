# Quick Script

This repository contains two executable scripts that help speed up your coding workflow. These scripts are designed to streamline common tasks while keeping your commands concise.

## `exe`: Make File Executable

The `exe` script allows you to quickly make a file executable by providing its name as an argument. This is especially useful for shell scripts or other executable files. Just place the `exe` script in a directory that's in your PATH, and you can make any file executable with minimal typing.

### Usage

To make a file executable, use the following command:

```bash
./exe file_name
```

Replace `file_name` with the actual name of the file you want to make executable.

--------

## `gacp`: Git Add, Commit, and Push

The `gacp` script combines the commands for adding changes, committing them, and pushing to a Git repository. You can provide an optional commit message as an argument, or it will use a default message. This script can save you time by reducing repetitive typing when pushing your changes.

### Usage

To quickly add, commit, and push your changes to a Git repository, use the following command:

```bash
./gacp "Your commit message here"
```

If you don't provide a commit message, it will use the default message "Push codes by exe :)".

## Installation

1. Clone this repository to your local machine.
2. Make sure the scripts are executable:

```bash
chmod +x exe gacp
```

3. Move the scripts to a directory that's in your PATH. This ensures you can run them from any location in your terminal. If you're not sure how to do this, you can refer to the following steps:

   - Identify directories in your PATH:
     ```bash
     echo $PATH
     ```
   - Choose one of the directories listed in your PATH, and move the scripts there. For example:
     ```bash
     sudo mv exe gacp /usr/local/bin/
     ```

These utilities are designed to make your coding tasks faster and more efficient. Enjoy the benefits of streamlined commands with `exe` and `gacp`!
