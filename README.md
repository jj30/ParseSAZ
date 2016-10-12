# ParseSAZ
This parses SAZ files outputted by Fiddler. It's a performance tool.

Steps: 
0) Create a DSN on a windows machine to the local SQL Database. Edit the connection string in the script. 

1) Save Fiddler output as SAZ file

2) Copy that file and rename the copy to WHATEVER.ZIP

3) Unzip that file into a folder called WHATEVER

4) Run the python script. This will process one record at a time into a SQL database (uncomment the SQLite3 part if you need to).
