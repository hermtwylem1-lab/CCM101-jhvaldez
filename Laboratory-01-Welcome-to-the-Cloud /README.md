# Mission Overview

This laboratory activity, *Welcome to the Cloud*, provides an introduction to using a cloud-based Linux environment. It covers working with the KillerCoda Linux Playground, managing user accounts, checking system information, creating directories and files, and documenting laboratory work through GitHub.

Throughout the activity, I gained practical experience with basic Linux commands, file management, and Markdown. The completed checkpoints allowed me to set up my Linux workspace, examine the system environment, organize my files, and create a GitHub portfolio for my laboratory activities.

## Objectives

* Use a cloud-based Linux environment through KillerCoda.
* Explore and test the Linux terminal.
* Create a Linux user with Bash, a home directory, and sudo access.
* Navigate and manage files and directories using Linux commands.
* Gather information about the Linux system, including the distribution, kernel, CPU, memory, and disk space.
* Create and modify Markdown files.
* Organize laboratory files and documentation in GitHub.
* Document completed activities using Markdown.
* Provide screenshots as evidence of completed tasks.

## Activities Performed

### Checkpoint 1 – Enter the Cloud

* Started an Ubuntu Linux Playground through KillerCoda.
* Tested the terminal and explored the Linux environment.
* Created a new user with Bash, a home directory, and sudo privileges.
* Set a password and logged into the new account.
* Recorded the username, current directory, and hostname.

### Checkpoint 2 – Meet Your Environment

* Examined the Linux system environment.
* Checked the Linux distribution, kernel version, CPU, memory, and disk space.
* Saved the system information in system-information.md.

### Checkpoint 3 – Build Your Workspace

* Accessed the home directory and created the required folders.
* Created the Notes folder and about-me.md file.
* Displayed the Markdown file in the terminal and captured the required screenshot.

### Checkpoint 4 – Create Your Cloud Computing Portfolio

* Created a public GitHub repository for the laboratory activities.
* Added the required laboratory folder, files, and screenshots directory.
* Organized the repository based on the given structure.

### Checkpoint 5 – Document Your Mission

* Created the laboratory README.md file.
* Added the required sections and documented the completed laboratory tasks.

### Checkpoint 6 – Capture Evidence

* Created the screenshots folder.
* Added and properly named screenshots showing the completed activities.

### Checkpoint 7 – Complete the Mission

* Checked the repository to make sure all required files were included.
* Reviewed the file organization.
* Committed the completed work and pushed it to GitHub.

## Linux Commands Used

### Checkpoint 1

sudo useradd -m -s /bin/bash jhvaldez
sudo passwd jhvaldez
sudo usermod -aG sudo jhvaldez
su - jhvaldez
whoami
pwd
hostname

### Checkpoint 2

grep PRETTY_NAME /etc/os-release
uname -r
lscpu | grep "Model name"
free -h
df -h /

### Checkpoint 3

cd ~
mkdir -p Notes
touch Notes/about-me.md
cat Notes/about-me.md

### Other Commands Used

ls
cd
mkdir
touch
cat

## Skills Learned

This laboratory activity helped me gain practical knowledge of working with a cloud-based Linux environment. I learned how to create and manage users, assign privileges, navigate the file system, and create files and directories using the terminal.

I also developed skills in checking system information, writing Markdown files, organizing project files, and managing a GitHub repository. These activities improved my understanding of Linux fundamentals, command-line operations, documentation, and cloud computing environments.
