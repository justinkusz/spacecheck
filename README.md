# spacecheck
Bash shell script to check used space on mounted filesystems and report if any exceed a specified limit

## Variables
* 'max' - Percentage value between 0-100. If the used space in any of the listed filesystems exceeds this value, the script will notify the user.
* 'filesystems' - Array of strings containing the mount points of the filesystems to check, e.g.: (/media/foo /mnt/bar)

Requires grep, awk, and sed.
