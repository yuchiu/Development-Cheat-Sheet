# Terminal

## Quick Links

- [Shortcuts](#Shortcuts)

- [Core Commands](#Core-Commands)

- [Netstat](#Netstat)

- [Grep](#Grep)

## Shortcuts

| **Shortcuts** | **description**                    |
| ------------- | ---------------------------------- |
| Ctrl + A      | jump to the start of current line  |
| Ctrl + E      | jump to the end of current line    |
| Ctrl + R      | search previous command            |
| !!            | run the previous command with sudo |

## Core Commands

| **Commands** | **description**                                                |
| ------------ | -------------------------------------------------------------- |
| ls -l        | detail listing                                                 |
| ls -a        | list file including "." hidden files                           |
| ls -R        | list all files including contents inside directory recursively |
| pwd          | full path of current directory                                 |
| rm -rf       | force remove file or directory recursively                     |

## Netstat

| **Commands**  | **description**                                        |
| ------------- | ------------------------------------------------------ |
| netstat -tlnp | list all tcp port that are currently occupied with PID |

## Grep

| **Commands**           | **description**                               |
| ---------------------- | --------------------------------------------- |
| grep "xxx" FILENAME    | search for string or REGEX in file            |
| grep -i "xxx" FILENAME | search for string as case insensitive in file |
