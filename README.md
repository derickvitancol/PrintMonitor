# PrintMonitor

GENERATE THE PRINTER LOGS
Run Get-WinEvent -Path D:\HomeProjects\PrintMonitor\Logs\PrinterLogs.evtx | Export-Csv PrinterLogs.csv to create a CSV
    NOTE: this command may have an error if there are no print events in the evtx file

AFTER GENERATING THE PRINTER LOGS
read the log file made by event viewer
check if a print is necessarry
use a interface or log file to be able to know app result
Print Monitor, check when was the last print made


THINGS TO SEARCH
Make Java do a print command

Make Java app run as a service (Tomcat?)

Make branches for different units
UNITS:
1. print command
2. Log Reader - branch_log_reader
3. log generator and watcher
4. Making the app run in the background 
5. unit tests


In Event Viewer, Application and Services Logs -> Microsoft -> Windows -> PrintService 
