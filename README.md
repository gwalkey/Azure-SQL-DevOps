# Azure-SQL-DevOps
Azure Devops For SQL contains Code Repos, Build and Release PIpelines and Scrum Boards

## Setup Requirements ##
* Create a Development Project in your Organization
* Uploade your SQL Database Project to a Repo
* Create a Service Connection using your Resource Group to your SQL Server
* Create a Build Pipeline
* Create a Release Pipeline
* Make a Database design change and check it in

Devops can automate the updates to your live SQL Servers

## Build Pipeline 
* Connect your Repo
* Find your Solution
* Configure MSBuild
* Copy dacpac file to staging folder as an Artifact
* On-Prem Build Agents

## Release Pipeline 
* Add an Artifact
* Add Deployment tasks to a Stage
* Separate Dev/QA/Prod servers using stages
* Using KeyVault to hold your SQL admin passwords
* Configure CI/CD Triggers
* Assign Approvals and Notifications
