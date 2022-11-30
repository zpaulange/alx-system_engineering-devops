#Execute the file using the Bash shell
#!/bin/bash

#Display the current working directory
pwd

#Display contentns list of current directory
ls

#Change working directory to the user's directory
cd ~

#Display current directory contents in long format
ls -l

#Display current directory contents, including hidden files (starting with .) using the long format
ls -a -l

#Display current directory in long format with user and group IDS numerically and hiddens file
ls -a -n

#Create a script that created a directory t tmp folder
mkdir /tmp/my_first_directory

#Mode file to another folder
mv /tmp/betty /tmp/my_first_directory

#Delete file to another folder
rm /tmp/my_first_directory/betty
