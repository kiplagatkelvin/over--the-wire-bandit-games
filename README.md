# over--the-wire-bandit-games
The "OverTheWire Bandit" games are a series of cybersecurity challenges designed to teach fundamental skills in security and hacking. These games are part of a broader set of "wargames" offered by OverTheWire, a community dedicated to improving security knowledge through practical exercises. Here's a general description of the Bandit game:
OverTheWire Bandit Game
Objective: The primary goal of the Bandit game is to learn and practice basic Linux command-line skills and common security techniques. Each level of the game presents a new challenge that requires players to exploit or navigate through a Linux-based environment to find a password and move to the next level.

Structure:

Levels: The game consists of multiple levels, each with a different challenge. Players start from Level 0 and progress through increasingly complex levels.
Challenges: Each level provides clues or hints about how to solve the challenge. These may involve using Linux commands, exploiting file permissions, decoding data, or other techniques related to system and network security.
Skills Developed: The game helps players develop skills in areas such as file handling, process management, networking, and basic programming. It also teaches the importance of security best practices and how to identify potential vulnerabilities.
Gameplay:

Login: Players typically start by logging into a remote server using SSH. Each level has its own login credentials, which players must discover.
Exploration: Players explore the file system, examine files, and execute commands to find the next password.
Hints and Solutions: Hints are often provided within the game, and players can also find solutions and discussions online if they need additional help.
Educational Value:

Hands-On Learning: The game provides a hands-on learning experience, allowing players to apply theoretical knowledge in practical scenarios.
Problem-Solving: Players must use problem-solving skills to navigate through the challenges and discover the necessary information.
Security Awareness: By understanding common security issues and how to exploit them, players become more aware of potential vulnerabilities in real-world systems.
Here’s a paraphrased version with an updated introduction, tools used, and added details for your GitHub repository:

---

### OverTheWire-Bandit

This repository contains a comprehensive walkthrough for completing the Bandit levels in the OverTheWire wargames. It serves as both a documentation of my methodologies and thought processes and a revision guide highlighting key takeaways from each challenge.

**Introduction: **
Welcome to the OverTheWire-Bandit walkthrough repository. Here, you'll find detailed explanations and practical insights into solving the Bandit levels. This guide will help you understand the strategies used to tackle each challenge, the tools employed, and common pitfalls to avoid.

**Tools Used: **
- SSH (Secure Shell)
- `cat`
- `file`
- `find`
- `grep`
- `sort`
- `uniq`
- `strings`
- `base64`
- `tr`
- `xxd`
- `gunzip`
- `bunzip2`
- `tar`
- `telnet`
- `openssl`
- `nmap`

**Walkthrough Guide:**
Bandit Level 0 → Level 1
   - **Goal:** Log into a server using SSH from a command-line terminal.
   - **Takeaways:** Learn SSH login and password retrieval.
   - **File:** `readme`
   - **Password:** boJ9jbbUNNfktd78OOpsqOltutMc3MY1

Bandit Level 1 → Level 2
   - **Goal:** Read files with special characters in their names.
   - **Takeaways:** Handling files with special characters.
   - **File:** `-`
   - **Password:** CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
Bandit Level 2 → Level 3
   - **Goal:** Read files with spaces in their filenames.
   - **Takeaways:** Managing filenames with spaces.
   - **File:** `spaces in this filename`
   - **Password:** UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
Bandit Level 3 → Level 4
   - **Goal:** Display all files in a directory, including hidden ones.
   - **Takeaways:** Using `ls -a` to reveal hidden files.
   - **File:** `.hidden`
   - **Password:** pIwrPrtPN36QITSp3EQaw936yaFoFgAB

Bandit Level 4 → Level 5
   - **Goal:** Identify file types using the `file` command.
   - **Takeaways:** Discover file types and handle unusual filenames.
   - **File:** `-file07`
   - **Password:** koReBOKuIDDepwhWk7jZC0RTdopnAYKh
Bandit Level 5 → Level 6
   - **Goal:** Find a file with specific properties.
   - **Takeaways:** Utilizing the `find` command with multiple criteria.
   - **File:** `maybehere07/.file2`
   - **Password:** DXjZPULLxYr17uwoI01bNLQbtFemEgo7

Bandit Level  6 → Level 7

   - **Goal:** Locate a file based on ownership and size.
   - **Takeaways:** Advanced `find` command usage for file properties.
   - **File:** `./var/lib/dpkg/info/bandit7.password`
   - **Password:** HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

Bandit Level 7 → Level 8
   - **Goal:** Search for a specific word within a file.
   - **Takeaways:** Using `grep` to locate text.
   - **File:** `data.txt`
   - **Password:** cvX2JJa4CFALtqS87jk27qwqGhBM9plV

Bandit Level 8 → Level 9
   - **Goal:** Find a unique line in a file.
   - **Takeaways:** Combining `sort` and `uniq` to find unique lines.
   - **File:** `data.txt`
   - **Password:** UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

Bandit Level 9 → Level 10
    - **Goal:** Identify strings in a file that are not ASCII text.
    - **Takeaways:** Using `strings` and `grep` to filter data.
    - **File:** `data.txt`
    - **Password:** truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

Bandit Level 10 → Level 11
    - **Goal:** Decode base64 encoded data.
    - **Takeaways:** Using `base64` for decoding.
    - **File:** `data.txt`
    - **Password:** IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

Bandit Level 11  →  Level 12
    - **Goal:** Transform strings using the `tr` command.
    - **Takeaways:** Rot13 cipher transformation.
    - **File:** `data.txt`
    - **Password:** 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
Bandit Level 12  → Level 13
    - **Goal:** Convert hexdump files and extract compressed files.
    - **Takeaways:** Handling multiple layers of compression.
    - **File:** `data8.tar`
    - **Password:** 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

Bandit Level 13 → Level 14
    - **Goal:** Log into a server using an SSH private key.
    - **Takeaways:** Using SSH keys for authentication.
    - **File:** `sshkey.private`
    - **Password:** 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
Bandit Level 14 → Level  15
    - **Goal:** Send data to a port using telnet.
    - **Takeaways:** Telnet for data transmission.
    - **Password:** BfMYroe26WYalil77FoDi9qh59eK5xNr
Bandit Level 15 → Level 16
    - **Goal:** Send data using SSL encryption.
    - **Takeaways:** Using `openssl` for SSL communication.
    - **Password:** cluFn7wTiGryunymYOu4RcffSxQluehd

Bandit Level 16 → Level 17
    - **Goal:** Identify listening ports and use SSL.
    - **Takeaways:** Using `nmap` to scan ports and `openssl` for SSL connections.
    - **Password:** unknown (use SSH key to log into Level 17's server)


Bandit Level 17 → Level 18

**Key Takeaways:** Learn how to compare the contents of 2 files, using the `diff` command.

- **Files:** `passwords.old` and `passwords.new`
- **Task:** The password for the next level is in `passwords.new` and is the only line that has been changed between `passwords.old` and `passwords.new`.
- **Command:** `diff passwords.old passwords.new`
- **Note:** The output of the `diff` command is dependent on the order of the parameters supplied. If `passwords.new` is the second parameter, the second string that is printed in the output is the password for the next level.

**Password for Level 17:** xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn  
**Password for Level 18:** kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

---

Bandit Level 18 → Level 19

**Key Takeaways:** Learn how to log in to a server via SSH without running `.bash` files (e.g., `.bashrc` and `.bash_logout`), using the `ssh` command with a set of parameters.

- **Task:** The password for this level is stored in a file `readme` in the home directory. However, `.bashrc` logs you out upon SSH login.
- **Command to Log In:** `ssh bandit18@bandit.labs.overthewire.org -p 2220 -t /bin/sh`
- **Note:** The `-t` parameter forces pseudo-terminal allocation. `/bin/sh` is another Unix shell. This command helps prevent being logged out immediately.

**Password for Level 19:** IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

---

Bandit Level 19 → Level 20

**Key Takeaways:** Learn how to take on the role of another user, using a setuid binary.

- **Task:** Use the setuid binary in the home directory to find the password for the next level.
- **Command:** `./bandit20-do cat /etc/bandit_pass/bandit20`
- **Note:** Running the file allows us to temporarily become user bandit20.

**Password for Level 20:** GbKksEFF4yrVs6il55v6gwY5aVje5f0j

---
Bandit Level 20 → Level 21

**Key Takeaways:** Learn how to open a listening port and communicate using it, using the `nc` command.

- **Task:** Use a setuid binary to connect to a port and verify the level 20 password. The correct password will then be given for level 21.
- **Commands:**
  - Find open ports: `nc -z -v localhost 1-50000`
  - Open a listening port: `nc -l -p 1234 <password for level 20>`
  - Test the port: `nc -z -v localhost 1234`
  - Send the password and pincode: `./suconnect 1234`
- **Note:** Port scanning and connection details are crucial.

**Password for Level 21:** gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

---

Bandit Level 21 → Level 22


**Key Takeaways:** Learn how to read shell scripts that form part of a cron job.

- **Task:** Look in `/etc/cron.d/` for the configuration and see what command is executed. Find the shell script that holds the password.
- **Note:** The password is redirected to `/tmp` by the cron job.

**Password for Level 22:** Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

---

Bandit Level 22 → Level 23

**Key Takeaways:** Learn how to modify shell scripts that form part of a cron job.

- **Task:** Modify a shell script to copy the password to a file in `/tmp`.
- **Commands:**
  - Copy and modify the script.
  - Ensure the `/tmp` directory is writable.
  - Run the script.
- **Note:** The password will be in `/tmp`.

**Password for Level 23:** jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

---
Bandit Level 23 → Level 24

**Key Takeaways:** Learn how to insert a shell script into an existing cron job.

- **Task:** Create a shell script that copies the password from `/etc/bandit_pass` to `/tmp`.
- **Commands:**
  - Create and set permissions for your script.
  - Place the script in `/var/spool/bandit24`.
- **Note:** Your script will be executed by the cron job.

**Password for Level 24:** UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ

---

Bandit Level 24→ Level 25

**Key Takeaways:** Learn how to create a brute-forcing script, in conjunction with the `nc` command.

- **Task:** Brute-force a 4-digit pincode required to retrieve the password for the next level.
- **Commands:**
  - Use `nc` to connect to the port and send the password with each 4-digit pin attempt.
  - Use a shell script with a loop to automate the process.
- **Note:** The script runs multiple `nc` processes in parallel.

**Password for Level 25:** uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG

---

Bandit Level 25 → Level 26


**Key Takeaways:** Learn more about the intricacies of the `more` command, as well as the capabilities of a text editor.

- **Task:** Discover how to handle the `more` command and use text editors to retrieve the password.
- **Commands:**
  - Identify the shell for user bandit26.
  - Use `:set shell=/bin/bash` and `:shell` in Vim to spawn a shell.
  - Alternatively, directly open the password file.

**Password for Level 26:** 5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z

---

Bandit Level 26 → Level 27

**Key Takeaways:** Revise how a setuid executable works.

- **Task:** Use a setuid executable to retrieve the password for the next level.
- **Command:** `./bandit27-do cat /etc/bandit_pass/bandit27`

**Password for Level 27:** 3ba3118a22e93127a4ed485be72ef5ea




Bandit Level 27 → Level 28
Key Takeaways: Learn to use git commands, particularly git clone.
A Git repository is available at ssh://bandit27-git@localhost/home/bandit27-git/repo. The password for the bandit27-git user is the same as for bandit27.
Clone the repository and locate the password for the next level.
Create a directory within /tmp, clone the Git repository into this directory, and open the README file inside the repo to find the next level's password.
Command: git clone ssh://bandit27-git@localhost/home/bandit27-git/repo
Password for Level 28: 0ef186ac70e04ea33b4c1853d2526fa2
________________________________________
Bandit Level 28 → Level 29
Key Takeaways: Master git commands, especially git log, git checkout, and git reset.
The Git repository at ssh://bandit28-git@localhost/home/bandit28-git/repo requires you to find the password. The user bandit28-git has the same password as bandit28.
As in the previous level, clone the repository and open the README file. This time, the password is censored with 'x's. To uncover the actual password, use git log to review the commit history. You'll find three commits: the initial, one with the password, and the final censored one.
Check out the second commit to access the README with the plaintext password.
Password for Level 29: bbc96594b4e001778eee9975372716b2
________________________________________
Bandit Level 29 → Level 30
Key Takeaways: Use git commands, focusing on git branch and git checkout.
The Git repository is available at ssh://bandit29-git@localhost/home/bandit29-git/repo. The password for bandit29-git is the same as bandit29.
After cloning the repository and examining README.md, you'll see that it mentions no passwords in production. Use git branch -a to list all branches. Initially, you are on the master branch, but the password is in the dev branch. Switch to the dev branch to find the password.
Password for Level 30: 5b90576bedb2cc04c86a9e924ce42faf
________________________________________
Bandit Level 30 → Level 31
Key Takeaways: Utilize git commands, particularly git tag and git show.
The Git repository is located at ssh://bandit30-git@localhost/home/bandit30-git/repo. The password for bandit30-git matches bandit30.
Here, the usual methods for checking commit history and branches won't help. Instead, explore Git tags. Use git tag to list available tags, and git show to view the tag content. Tags contain the password, but you might face errors when using git checkout. Resolve this by using git show.
Password for Level 31: 47e603bb428404d265f59c42920d81e5
________________________________________
Bandit Level 31 → Level 32
Key Takeaways: Learn git commands like git add, git commit, and git push, and understand .gitignore.
The Git repository is found at ssh://bandit31-git@localhost/home/bandit31-git/repo. The password for bandit31-git is the same as bandit31.
The challenge here involves pushing a file to the remote repository. Create a file named key.txt with "May I come in?" and use git add, git commit, and git push commands. If you encounter "nothing to commit," check the .gitignore file, which might be excluding .txt files. Remove the relevant line from .gitignore, then run the commands to reveal the password.
Password for Level 32: 56a9bf19c63d650ce78e6ec0354ee45e
________________________________________
Bandit Level 32 → Level 33
Key Takeaways: Learn how to escape from an uppercase shell by examining the sh command options.
After logging in, you’ll encounter an uppercase shell where commands are converted to uppercase. The getent command reveals that the shell is executed with additional parameters. Use $0 to restart the shell without parameters, giving you access to /bin/sh. This allows you to use the setuid file to gain permissions for user bandit33 and access /etc/bandit_pass to find the password.
Password for Level 33: c9c3199ddf4121b10cf581a98d51caee
________________________________________
Bandit Level 33 → Level 34








