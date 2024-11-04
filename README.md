
# Bash-Script-for-Automated-File-Backup

This project provides a **Bash script** that automatically backs up encrypted password files updated in the past 24 hours. The script creates a compressed archive of the files and stores it in a specified destination directory.

## Script Overview

The backup script:
- Takes two arguments: the target directory (where encrypted password files are located) and the destination directory (where backups will be saved).
- Checks if both directories are valid. If not, it displays an error message and exits.
- Identifies files in the target directory that have been modified within the last 24 hours.
- Compresses these files into a `.tar.gz` backup archive with a unique timestamp.
- Moves the backup file to the specified destination directory.

## Script Details

### Important Variables
- **`targetDirectory`**: The directory containing files to back up.
- **`destinationDirectory`**: The directory where the backup archive will be saved.
- **`currentTS`**: The current timestamp in seconds.
- **`backupFileName`**: The name of the backup file with a timestamp for uniqueness.





