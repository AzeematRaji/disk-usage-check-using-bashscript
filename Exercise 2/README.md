# Bash Script Project

This is a simple project on how to write a script that checks the disk usage of a given directory, that can take two optional arguments and one compulsory arguments.
-d: which means that all files and directory within the specified directory or directories should be listed.
-n: which means that the top N enteries should be returned.
list of directories: this will be the directories you want to check it's disk usage

if -n argument is not given, it should return 8 enteries by default.

## Procedures;

1. Create a bash file and edit with a script that runs the du of a given directory
2. Make it an executable file and run on it for a given directory ; ./script.sh -d /var, ./script.sh -n 5 /var

## Second project

Create a backup script. This script creates a backup of a given directory and saves it in another directory with a timestamp. It takes two arguments:
the source directory and the destination directory

## Procedures;
1. Create a bash file and edit wih a script that creates a backup in tar archive 
2. Make it an executable file and run it; ./backup_script.sh /var /etc
