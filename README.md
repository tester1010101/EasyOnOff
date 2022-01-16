# EasyOnOff :reminder_ribbon: :ticket:
* :heavy_check_mark: Script file to allow/deny ALL **outgoing** firewall rules.
* :x: Batch file allows for a "Run as administrator" option, pointing to the script.ps1 needed (allow/deny).

# Instructions ::
1) Create a new folder for the scripts/batch files. (C:/Users/Username/***ScriptFolder***/)
2) Unzip the folder & extract the files in the folder created above. (C:/Users/Username/***ScriptFolder***/\*extract_here*)
3) Open the ScriptFolder. "C:/Users/Username/***ScriptFolder***/"

![image](https://user-images.githubusercontent.com/91343617/149645577-da972061-129c-43ee-a160-53e9359327c4.png)

4) Right-click the "Allow.bat" & "Deny.bat"; on each: "Send to > Desktop (Create Shortcut)"
5) This should leave you with 2 shortcuts on the desktop (they can be moved anywhere you need it).

![image](https://user-images.githubusercontent.com/91343617/149645630-b6831ec6-8c08-46f6-9638-c329df82349c.png)

6) You can also rename the shortcut to something like: "Allow.bat" & add a custom icon to it.

![image](https://user-images.githubusercontent.com/91343617/149645639-a65953eb-6399-48d1-a26b-d71f261e84bd.png)

7) Modify the Allow.bat & Deny.bat to point the batch file (.bat) to your PowerShell (.ps1) script.

![image](https://user-images.githubusercontent.com/91343617/149645907-e231d732-d165-4f62-b17e-6e4f4033ece0.png)

* The "netsh" command needs Administrator access to be run, so here is why I made this little utility. 
* Can also be customized for inbound rules & others network profiles, don't hesitate to message me if you need help!
