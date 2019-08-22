Website blocker application written in Python, works in the background, for Windows change the extension of the file to .pyw, by doublclicking it it'll run on the background, dobule check in the Task Manager
You need to run it as Admin since the script is accessing the hosts file in "C:\Windows\System32\drivers\etc\hosts"
If you change hosts_path to hosts_temp_path in the script you can just double click the file

You can go to Task Scheduler on Windows to configure the script to run on start up