# SonarQube-AzureAppService
This project is to facilitate hosting [SonarQube](https://www.sonarqube.org/) in an [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/) directly. This does not require SonarQube to be in a Linux container. You can also use the same [HttpPlatformHandlerStartup.ps1](https://github.com/meyyazhagan/sonarqube-deployment/blob/master/wwwroot/HttpPlatformHandlerStartup.ps1) and [HttpPlatformHandler](https://docs.microsoft.com/en-us/iis/extensions/httpplatformhandler/httpplatformhandler-configuration-reference) extension to host SonarQube in IIS on a hosted machine. This would eliminate the need for more complicated setup of IIS as a reverse proxy.

This project uses the PostgreSQL database. 

[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

## Getting Started
Use the ***Deploy to Azure*** button above to deploy out an Azure App Service along with the additional files from this project. SonarQube may take up to 10 minutes to start the first time.

