# backupIsEasy

Loading the script and this files loading is displayed with a progress bar that shows the progress with 5% increasing, from 5% to 10% and so on.

Then backup to a remote location is executed choosing a source directory/file and a destination also a directory/file. 

Prettified output with appropiate statistics about the current transfer of files, like speed, size, number of files, directories and so on. Also selinux parameters are modified in order for rsync to work properly.

Option for loggin was made and actions are written in /var/log/backupIsEasy/easyBackup.log
