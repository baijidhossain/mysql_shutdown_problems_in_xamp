# mysql_shutdown_problems_in_xamp

IMPORTANT: do NOT delete ibdata1 file. You could destroy all your databases.

#Instead, first try using the MySQL backup folder which is included with XAMPP. So do next steps:

## Rename folder mysql/data to mysql/data_old
## Make a copy of mysql/backup folder and name it as mysql/data
## Copy all your database folders from mysql/data_old into mysql/data (except mysql, performance_schema, and phpmyadmin folders)
## Copy mysql/data_old/ibdata1 file into mysql/data folder
## Start MySQL from XAMPP control panel
