# in_house_indexing
In-House File and Directory Search Engine

# in_house_indexing
In-House File and Directory Search Engine

# set up a cron job scheduler
set up a cron job scheduler on Linux following these steps:
open the cron table. 
add a new line to specify the cron job schedule and the command you want to run as follows.
* * * * * command_to_be_executed.
* Minute (0 - 59) :
* Hour (0 - 23) :
* Day of the month (1 - 31) :
* Month (1 - 12) :
* Day of the week (0 - 7) (Sunday is both 0 and 7) 
then save crontab
# eg: to set the cron job to run at 00:00 (midnight) every day
0 0 * * * /usr/bin/python3 /path/to/your_script.py >> /path/to/your/logfile.log 2>&1     

# Configure meilisearch API      
download meiliSearch ;
Set Executable Permissions: chmod +x meilisearch ;
Run MeiliSearch: ./meilisearch --master-key API_KEY   //with master key argument

# Provide Directory path       
locat the file: .../in_house_indexing/assets/config.json    
Provide the directory path of the server that needs to be indexed and searched
       

