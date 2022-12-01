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
