# Active Directory Security Audit Solution


[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAsithaD%2FOMS%2Fmaster%2Fazuredeploy.json) 

AD Security Audit Solution collects security events from domain controllers and filter them with Azure log analytics queries to visualize in OMS Dashboards. It have two attractive dashboard to display following information. 

*	Created and deleted domain users with time and by whom
*	Created and deleted domain groups with time and by whom
*	Group membership changes with the group, added or removed user and time. (ex – Domain admin or Enterprise admin group membership changes)
*	Number of Users logged in to the domain by last 24 hours
*	Domain users logged in to the domain with time and user name
*	Failure logon attempts by user
*	Failure logon attempts by computer
*	Locked user accounts with the source where account locked
*	Domain user logged on Computer by its IP address and the updated time and date.

![alt text](images/Overview_tiles.png "Overview")

Users And Groups Monitoring
![alt text](images/Users&GroupsView.png "Users and Groups View")
User Account Security Monitoring
![alt text](images/UserAccountSecurity_View.png "Users Account Security View")
![alt text](images/UserAccountSecurity_View2.png "Users Account Security View")

