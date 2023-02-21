# Useful-Linux-and-Git-Commands
Listed below are some lesser known but extremely useful linux and git commands that every developer should know.
## Linux Commands
As a software developer, it is important to know Linux commands for several reasons. Having a strong understanding of Linux commands is crucial for software developers, as it can improve productivity, debugging abilities, and collaboration, while also allowing them to manage servers and version control systems more effectively.
Listed below are the top 15 commands I personally feel are most useful:

### 1. curl
This command is used for sending and receiving data over the internet, such as sending HTTP requests or downloading files. It is useful for testing and interacting with web services and APIs.
### 2. rsync
This command is used for synchronizing files and directories between systems. It is useful for backing up files and for transferring large amounts of data efficiently.
### 3. ssh-keygen
This command is used for generating and managing SSH keys, which are used for secure remote access to systems. It is useful for setting up secure access to remote servers and for managing multiple keys.
### 4. head and tail
These commands are used for displaying the first and last lines of a file, respectively. They are useful for quickly viewing the contents of a file without having to open it in an editor, or for displaying log files in real-time.
### 5. tmux
This is a terminal multiplexer that allows multiple terminal sessions to run within a single terminal window. It is useful for managing multiple processes and tasks at the same time, and for preserving terminal sessions even after logging out.
### 6. netstat
This is a network monitoring tool that provides information about network connections, including open sockets, routing tables, and network statistics.
### 7. dstat
This is a versatile resource statistics tool that provides real-time information about system performance, including CPU, memory, disk, and network usage.
### 8. screen
This is a terminal multiplexer that allows multiple terminal sessions to run within a single terminal window. It is useful for managing multiple processes and tasks at the same time, and for preserving terminal sessions even after logging out.
### 9. ctags
This is a code tagging tool that generates an index of function definitions and variables within a code base, making it easier to navigate and understand the code.
### 10. gdb
This is a debugging tool used for debugging and analyzing program crashes. It provides information about the cause of a crash, the state of the program at the time of the crash, and the values of variables.
### 11. strace
This is a debugging tool used for tracing system calls and signals made by a process. It is useful for identifying the cause of errors and finding potential performance issues.
### 12. ssh
This is a secure shell client used for remote access to systems. It is useful for remotely accessing and managing servers, as well as transferring files securely between systems.
### 13. alias
The linux alias command is used to create custom, simplified commands for frequently used commands or sequences of commands.
### 14. shred
The shred command is used to securely erase a file, wiping its contents and making it difficult to recover the data, by overwriting the file multiple times with random data.
### 15. tee
The tee command is used to simultaneously write output from a command to both the terminal and a file, allowing for the preservation of output for later use.

## Git Commands
It is important to know Git commands because Git is a widely used version control system that allows for collaboration, tracking of changes, and efficient management of code. With Git, developers can work on a project with other team members, track changes to their code, and easily revert to previous versions if necessary. By knowing Git commands, a software developer can effectively manage their code, work with other developers, and keep their code organized and easily accessible.
Below are the top 15 Git commands that developers should familiarize themselves with:

### 1. clone
This command is used for cloning an existing repository to a local machine. It allows developers to create a local copy of a remote repository and work on it independently.
### 2. checkout
This command is used for switching between branches in a Git repository. It allows developers to work on different branches simultaneously, and to switch between them easily.
### 3. merge
This command is used for merging the changes from one branch into another branch. It is used to bring together the changes from multiple branches into a single branch, and to resolve conflicts between branches.
### 4. stash
This command is used for temporarily saving changes in a Git repository, without committing them. It allows developers to switch between branches, work on different tasks, and later restore their changes.
### 5. diff
This command is used for displaying the differences between two Git branches or commits. It is useful for comparing changes, reviewing code, and finding conflicts.
### 6. rebase
This command is used for modifying the base branch of a Git repository. It allows developers to update their branch with the latest changes from the main branch, and to resolve conflicts between branches.
### 7. cherry-pick
This command is used for selecting specific changes from one branch and applying them to another branch. It is useful for picking changes from multiple branches and combining them into a single branch.
### 8. revert
This command is used for undoing changes in a Git repository. It allows developers to revert changes that were made in error, or to undo a previous commit.
### 9. blame
This command is used for finding the author of specific changes in a Git repository. It is useful for finding out who made changes to a file, and for reviewing code changes.
### 10. tag
This command is used for adding tags to specific commits in a Git repository. It is used to mark important points in the development history, such as releases or milestones.
### 11. bisect
This command allows a developer to find a specific commit in the repository that introduced a bug. It works by performing a binary search through the commit history, narrowing down the possible cause of the bug.
### 12. submodule
This command allows a developer to include a Git repository within another Git repository as a sub-project. This is useful for managing dependencies and for keeping related projects organized and separate.
### 13. reflog
This command displays a log of all the reference updates in a Git repository, including branch updates and HEAD updates. This is useful for tracking changes and for recovering lost work or commits.
### 14. apply
This command allows a developer to reapply stashed changes to a branch. It is useful for bringing back changes that were temporarily stashed away, without having to reapply the changes manually.
### 15. diff --cached
This command allows a developer to compare the changes that have been staged for commit, with the previous version of the repository. It is useful for reviewing changes before committing, and for ensuring that the changes are ready to be committed.
