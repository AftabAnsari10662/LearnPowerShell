#Learning PowerShell basic commands
SCP Command
scp -r /c:\temp\myapp mymachine@aftabansari.cloudapp.net:~/myapp

SSH command
ssh aftabansari.cloudapp.net


##Get stopper services and export to CSV files.
* `ise`
* `get-service`
* `get-service | where-object status -eq 'stopped'`
* `get-service | where-object status -eq 'stopped' | export-csv c:\scripts\service-stopped.csv`
* `get-service | where-object status -eq 'stopped' |select-object Status,Name,DisplayName| export-csv c:\scripts\service-stopped.csv`



