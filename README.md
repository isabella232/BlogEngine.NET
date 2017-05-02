## BlogEngine.NET Source Code
This repository provides latest source code for BlogEngine.NET project (https://blogengine.codeplex.com) adapted to run on the Apprenda Platform. No changes to the actual source were made. The resulting application leverages SQL Server as the back-end store.

## Configuration Changes for Apprenda
We are leveraging tags in the repository to showcase the state of the application at different stages during the migration to Apprenda. 
1. web.config -> At this stage, we replaced the original web.config file with the one provided by BlogEngine for use with SQL Server
2. sqlserver -> At this stage, we renamed the Setup.sql script provided to ApplicationProvisioning_Script and added Apprenda conditional configuration tags to support running locally and on Platform
3. cleanup -> Removed unnecessary files for configuring the application with other database providers
4. archive -> Provided an Apprenda archive for easy deployment to your environment

## Environment
  * Visual Studio 2015 Community +
  * ASP.NET 4.5 +

## Deploying Application on Apprenda
To deploy the application, simply upload the Archive.zip file provided at the root of this repository otherwise follow the steps below. 

## Get started on Apprenda
  1. Clone repository
  2. Open solution in Visual Studio 2015
  3. Build the solution
  4. Create an Apprenda archive using the Visual Studio extension, Archive Builder, ACS or manually
  5. Deploy to your environment

![dashboard-3](https://cloud.githubusercontent.com/assets/1932785/11760070/0012f9d8-a052-11e5-84a8-e9097cb85f23.png)

## Themes
We will share everything about themes and how you can create your own theme on [This page](http://francis.bio/BlogEngine/).
