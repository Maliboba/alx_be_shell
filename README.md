# alx_be_shell
----------------------------------------------------------------------
# Shell Permissions Project

This project contains a series of shell scripts designed to demonstrate an understanding of Linux file permissions and basic shell scripting. Each script adheres to the following rules:
- All scripts are tested on Ubuntu 20.04 LTS.
- Each script is exactly two lines long.
- The first line of each script is `#!/bin/bash`.
- All scripts end with a new line.
- No backticks, `&&`, `||`, or `;` are used.
- All scripts are executable.

## Scripts

### 0-iam_betty
Switches the current user to `betty`.

### 1-who_am_i
Prints the effective username of the current user.

### 2-empty
Creates an empty file named `hello`.

### 3-execute
Adds execute permission to the owner of the file `hello`.

### 4-multiple_permissions
Adds execute permission to the owner and the group owner, and read permission to others for the file `hello`.

### 5-John_Doe
Sets the file `hello`'s permissions to:
- Owner: `rwx` (read, write, execute)
- Group: `r-x` (read, execute)
- Others: `-wx` (write, execute)

---

## How to Run
1. Clone this repository.
2. Navigate to the `shell_permissions` directory.
3. Run each script using the following command:
   ```bash
   ./<script_name>
eg. ./0-iam_betty


