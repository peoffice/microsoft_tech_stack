#### Install nuget cli
* download nuget cli from nuget.org
* unzip nuget downloading file
* setting system path
  

####  Add artifactory local repository to vs
* open nuget package manager console in vs
* type ```nuget sources Add -Name DSPE_Artifactory -Source http://localhost:8081/artifactory/api/nuget/dspe-local -username admin -password APASSEuh7WsrkHya```
* type ```nuget setapikey admin:APASSEuh7WsrkHya -Source DSPE_Artifactory```
* open menu Tools -> Nuget Package Mananger -> Package Manager Setting
* select Nuget Package Manager -> Package Sources
* Add a new nuget source, set name:DSPE_Artifactory ;set source:http://localhost:8081/artifactory/api/nuget/dspe-local
* check the box of adding source, uncheck others
