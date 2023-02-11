# Azure SQL Database - Relational Databases In Azure

https://www.youtube.com/watch?v=BgvEOkcR0Wk


## Connect to the database

### Connect by Firewall rule

This connection method is not required for security reasons.

- Add a firewall rule to enable connection from your home :
<img src="/pictures/firewall.png" title="connect by firewall rule"  width="800">

- Simply connect by providing login and password in MSSMS :
<img src="/pictures/firewall2.png" title="connect by firewall rule"  width="800">

### Connect by Active Directory

This connection method is better.

- Add an Admin User to the Active Directory :
<img src="/pictures/active_directory.png" title="activedirectory"  width="800">

- Simply connect by providing login and password in MSSMS :
<img src="/pictures/firewall2.png" title="connect by firewall rule"  width="800">








```
dotnet restore --interactive
cd path/to/package.nupkg
dotnet nuget push --source "AlexeiDemoFeed" --api-key az --force-english-output --interactive AlexeiHelperLibrary.1.0.0.nupkg
```