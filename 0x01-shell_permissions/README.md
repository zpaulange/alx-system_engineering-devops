#Switch to user betty
su betty

#Print username of ther current user
id -un

#Prints all the groups the current user is part of
groups

#Change owner of the file hello
chown betty hello

#Create empty file called hello
touch hello

#Add execute permission to the owner of ther file hello
chmod u+x hello

#Add execute permission to the owner and the group ownerm and read permission to other user to the file hello
chmod 754 hello

#Adds execution permission to the owner the group owner and ther users to the file hello
chmod ugo+x hello

#Set permission to the file, owner: no pernission, group: no pernission, other:all
chmod 007 hello

#Set the mode of hello file
chmod 753 hello

#Sets the mode of the file hello the sames as olleh's mode
chmod --reference=olleh hello

#Execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
chmod -R +111 */

#creates a directory called my_dir with permissions 751 in the working directory
mkdir -m 751 my_dir

#changes the group owner to school for the file hello
chgrp school hello

# changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown vincent:staff *

#changes the owner and the group owner of _hello to vincent and staff respectively
chown -h vincent:staff _hello

#changes the owner of the file hello to betty only if it is owned by the user guillaume
chown --from=guillaume betty hello

#that will play the StarWars IV episode in the terminal
telnet towel.blinkenlights.nl

