# MongoDB-AutoconfigWin
this is a PowerShell script that will auto-configure MongoDB local storage path and log path in mongod.conf
and start a CMD session to run the database

-------------------------------------------------------------------------------------

IMPORTANT:
this script assumes PowerShell v3.0+

I created this scirpt for a single project with a set file structure so if the file traversing works in a specific way
but as long as the parts of the code that control the paths mentioned above are modified correctly the script should be
able to set correct paths to the local db and start the db at the IP and port set within the supplied config file


the project root is assumed to be 2 folders above the script file (ProjectRoot/Utils/this_script.ps1)

the main database folder is set to be in project root folder (ProjectRoot/db)

inside the db folder is the usual MongoDB file structure (ProjectRoot/db/data and ProjectRoot/db/logs)

in the project root folder there is a config named with the standard name mongod.cfg (ProjectRoot/mongod.cfg)

--------------------------------------------------------------------------------------
