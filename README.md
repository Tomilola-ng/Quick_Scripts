# Fast Code Utilities

This repository contains two executable scripts that help speed up your coding workflow. These scripts are designed to streamline common tasks while keeping your commands concise.

## `Tomi`: Make File Executable

The `Tomi` script allows you to quickly make a file executable by providing its name as an argument. This is especially useful for shell scripts or other executable files. Just place the `Tomi` script in a directory that's in your PATH, and you can make any file executable with minimal typing.

### Usage

```bash
./Tomi file_name

Replace `file_name` with the actual name of the file you want to make executable.

## `Tomi_gitpush`: Git Add, Commit, and Push

The `Tomi_gitpush` script combines the commands for adding changes, committing them, and pushing to a Git repository. You can provide an optional commit message as an argument, or it will use a default message. This script can save you time by reducing repetitive typing when pushing your changes.

### Usage

```bash
./Tomi_gitpush "Your commit message here"
```

If you don't provide a commit message, it will use the default message "Push codes by Tomi :)".

## Installation

1. Clone this repository to your local machine.
2. Make sure the scripts are executable:

```bash
chmod +x Tomi Tomi_gitpush
```

3. Move the scripts to a directory that's in your PATH.
