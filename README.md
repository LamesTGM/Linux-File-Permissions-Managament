# Linux File Permissions Management

## Description
This project demonstrates my ability to automate Linux file permissions management using a Bash script. The script ensures secure access control for sensitive files and directories by modifying permissions and ownership.

## Tools Used
- **Linux Commands**: `chmod`, `chown`, `chgrp`.
- **Bash Scripting**: Automating permission updates.
- **File System**: Managing permissions for files and directories.

## Steps
1. **Set Permissions**:
   - The script uses `chmod` to set file permissions (e.g., `chmod 600 file.txt` for read/write access by the owner only).

2. **Change Ownership**:
   - The script uses `chown` to change file ownership (e.g., `chown user:group file.txt`).

3. **Change Group Ownership**:
   - The script uses `chgrp` to change group ownership (e.g., `chgrp group file.txt`).

4. **Automate Updates**:
   - The script loops through a list of files and directories to apply permission and ownership updates.

## Outcome
- Enhanced system security by restricting unauthorized access to critical files and directories.
- Reduced manual effort and potential errors through automation.
- Ensured compliance with organizational security policies.

