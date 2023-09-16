
# Skills

Below skills are required to complete the deployment steps:

Linux User Management, Permissions, Directory Structure, File Systems, File Management

# Pre-Requisites

* To complete the assignment below, log in to AWS cloud and create a Linux-based EC2 instance or run on VMware.

# Deployment
[1 to 4](md/1to4.md)

1. Login to the server as super user and perform below
* Create users and set passwords – user1, user2, user3
* Create Groups – devops, aws
* Change primary group of user2, user3 to ‘devops’ group
* Add ‘aws’ group as secondary group to the ‘user1’
* Create the file and directory structure shown in the above diagram.
* Change group of /dir1, /dir7/dir10, /f2 to “devops” group
* Change ownership of /dir1, /dir7/dir10, /f2 to “user1” user.

2. Login as user1 and perform below
* Create users and set passwords – user4, user5
* Create Groups – app, database

3. Login as ‘user4’ and perform below
* Create directory – /dir6/dir4
* Create file – /f3
* Move the file from “/dir1/f1” to “/dir2/dir1/dir2”
* Rename the file ‘/f2′ to /f4’

4. Login as ‘user1’ and perform below
* Create directory – “/home/user2/dir1”
* Change to “/dir2/dir1/dir2/dir10” directory and create file “/opt/dir14/dir10/f1” using relative path method.
* Move the file from “/opt/dir14/dir10/f1” to  user1 home directory
* Delete the directory recursively “/dir4”
* Delete all child files and directories under “/opt/dir14” using single command.
* Write this text “Linux assessment for an DevOps Engineer!! Learn with Fun!!” to the /f3 file and save it.




