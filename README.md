# Tasks Lister (Process Tree)

A kernel module that lists all current tasks in a Linux system

## How to use
```
$ cd src/[linear|dfs]
$ make                                  # Make module
$ insmod tasks_lister_[linear|dfs].ko   # Install module
$ dmesg                                 # Show message
$ rmmod tasks_lister_[linear|dfs]       # Remove module
$ dmesg                                 # Show message
$ dmesg -C                              # Clear message
```