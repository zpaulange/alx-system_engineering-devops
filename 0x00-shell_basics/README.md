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

#Delete Directory
rm -rf /tmp/my_first_director

#Back to the previous directory
cd -

#List all files in current directory and ohter directory in long format
ls -al . .. /boot

#get type of file
file name_file

#create a symbolic link file
ln -s old_file new_file

#copies all the HTML files from the current working directory to the parent of the working directory,
cp -nu *.html ..

#moves all files beginning with an uppercase letter to the directory /tmp/u
mv [[:upper:]]* /tmp/u

#deletes all files in the current working directory that end with the character ~
rm *~

#creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
mkdir -p welcome/to/school



