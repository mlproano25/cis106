#managing user accounts 
adduser is recommended
to mod users info use usermod
to delete user use userdel
must use sudo to add user 
must use userdel -r to delete home directory and more
##etc/default/useraddfile 
useradd -D
to view what is inside
##etc/passwd file
info on every account 
##etc/shadowfile
has users passwords
##etc/gshadow
has group passwords
##getent 
can be used to view info on users account/password
#Maintaining passwords
passwd + user
passwd -l and -u lock/unlock accounts
##How to create an alias
ex...![](alias.png)
alias + word + = + command
##Setting up the enviroment
setting up the enviroment is using shell scripting
##querying users
who -aH = can describe info on personal account
id username = information 
last pulls a list of users they logged in and out of the system