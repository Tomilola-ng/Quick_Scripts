# Quick Script

This repository contains three executable scripts that help speed up your coding workflow. These scripts are designed to streamline common tasks while keeping your commands concise.

## Getting Started

To get started with these scripts, follow these detailed steps:

1. **Clone the Repository:**
   - Open your terminal or command prompt.
   - Clone this repository to your local machine by running the following command:
     ```bash
     git clone https://github.com/Tomilola-ng/Quick_Scripts.git
     ```
   This will create a local copy of the repository on your computer.

2. **Change to the Repository Directory:**
   - Navigate to the cloned repository's directory using the `cd` command. This is important to ensure you are in the correct location to work with the scripts:
     ```bash
     cd Quick_Scripts
     ```

3. **Confirm Files:**
   - It's essential to verify that you have all the necessary files. There should be five files in total:
   
      Three scripts: exe, gacp, and new.
      One README file: README.md.
      One License file: LICENSE (optional).
   
     ```bash
     ls
     ```
     The files should include `exe`, `gacp`, `new`, `README.md`, and `LICENSE`.

5. **Make Scripts Executable:**
   - Ensure that the scripts are executable by running the following command:
     ```bash
     chmod +x exe gacp new
     ```
     This command grants execute permissions to the scripts, allowing you to run them.

6. **Add Scripts to PATH:**
   - To use these scripts conveniently from any location in your terminal, you need to add them to a directory that's in your system's PATH. First, identify directories in your PATH using the following command:
     ```bash
     echo $PATH
     ```
   - Choose one of the directories listed in your PATH, and move the scripts there. For example:
     ```bash
     sudo mv exe gacp new /usr/local/bin/
     ```
     This ensures that the scripts can be executed from any location in your terminal.

7. **Start Using the Scripts:**
   - Now, you can start using the scripts from anywhere in your terminal:
     - To make a file executable, use the `exe` script:
       ```bash
       exe file_name
       ```
     - To quickly add, commit, and push your changes to a Git repository, use the `gacp` script:
       ```bash
       gacp "Your commit message here"
       ```
     - To create and edit a new Bash script, use the `new` script:
       ```bash
       new script_name.sh
       ```

These utilities are designed to make your coding tasks faster and more efficient. Enjoy the benefits of streamlined commands with `exe`, `new`, and `gacp`!
