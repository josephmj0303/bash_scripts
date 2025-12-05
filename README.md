Bash Shell Scripts Collection

This repository contains a curated set of Bash scripts designed to support common DevOps, Linux administration, and automation workflows. Each script focuses on a specific operational use case—ranging from file handling and system inspection to process management and server information.

The repository is intended as a learning and reference resource for anyone practicing Bash scripting as part of their DevOps skill development.

Repository Contents

```
| File Name             | Purpose / Description                                                                         |
| ----------------------| --------------------------------------------------------------------------------------------- |

| acceptunamepwd.sh     | Accepts username and password from user input and processes/validates them.                   |

| callfunc.sh           | Demonstrates how to define and call functions within a Bash script.                           |

| filecontent.sh        | Reads and displays the content of a specified file.                                           |

| fileswithextension.sh | Lists files in a directory that match a given file extension.                                 |

| findfilespdir.sh      | Searches for files under a parent directory based on name patterns.                           |

| findip.sh             | Retrieves and prints the system’s IP address information.                                     |

| installpkg.sh         | Installs packages using the system package manager (apt/yum/dnf as applicable).               |

| loopcharacter.sh      | Iterates through characters of a string and prints them one by one.                           |

| looponnumoffiles.sh   | Loops based on the number of files in a specified directory.                                  |

| printcharno.sh        | Prints a character from a string at a user-defined position.                                  |

| removedupcharc.sh     | Removes duplicate characters from an input string.                                            |

| runningprocess.sh     | Displays currently running processes, optionally filtered by criteria.                        |

| serverdetails.sh      | Shows server information such as OS details, hostname, uptime, and more.                      |

| username.sh           | Accepts a username and performs basic validation or output (simple input script).             |

| varemptyvalue.sh      | Checks whether a variable is empty or unset and prints corresponding messages.                |

| wcfile.txt            | Sample text file used for testing scripts involving `wc`, file processing, or input handling. |
```
Usage

#1. Clone the repository
```
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```
#2. Make any script executable
```
chmod +x scriptname.sh
```
#3. Execute the script
```
./scriptname.sh
```
Some scripts require user input (e.g., username, file name, string, directory path).

Skills Demonstrated

These scripts help build practical understanding of:

* Conditional expressions (if, elif, else)

* Loop constructs (for, while)

* String manipulation

* File and directory traversal

* Basic function usage

* System and network inspection

* Process monitoring

* Error handling and input validation
  
Prerequisites
```
* Linux environment (Ubuntu, CentOS, AlmaLinux, Debian, etc.)

* Bash shell v4 or higher

* Execution permissions for .sh files

* sudo privileges for scripts that install packages (e.g., installpkg.sh)
```
Future Scope

Planned enhancements may include:

* Log automation scripts

* Backup and restore utilities

* System health monitoring scripts

* Interactive menus using select

Contributions

Pull requests, improvements, and suggestions are welcome.
Feel free to open an issue for any script enhancements or new ideas.
 
