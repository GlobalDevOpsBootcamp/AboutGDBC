# Gotchas and workarounds for GDBC #

# General #
* Some issues with permission assignment. Use the gdbc-<venue>-admin to give permissions
    * all users are in VSTS-<venue> global VSTS group
    * should be added as Project admin/Build admin in the projects
    

# Challenge 1 #
* Add the client IP of your machine to SQL Azure
* Use the Azure App Service Buildtask instead of Web Deploy 
* 