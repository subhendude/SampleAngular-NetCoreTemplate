## Sample Angular 7  + ASP.Net Core 2.1 Web API Project

This is a sample project to demonstrate a SPA developed in Angular 7 and ASP.NET Core 2.1 Web API.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Clone the repository

```
git clone https://github.com/subhendude/SampleAngular-NetCoreTemplate.git
```

Go to SPA project directory in Powershell or bash shell

```
$ cd ToDoSPA
$ npm install
$ ng build
$ cd..
$ dotnet restore
$ dotnet run
```

### Prerequisites

This requires following tools installed in your local development sandbox

```
Node.js
NPM
TypeScript
Angular CLI
dotnet core CLI
```

### Installing

A step by step series of examples to get a development env running

Node.js

```
https://nodejs.org/en/download/
```

NPM

```
npm install npm@latest -g
```

TypeScript

```
npm install -g typescript
```

Angular CLI

```
npm install -g @angular/cli
```

Dotnet Core CLI

```
https://www.microsoft.com/net/download/thank-you/dotnet-sdk-2.1.403-windows-x64-installer
```

## Deployment

* NPM Task - Install the angular CLI
* NPM Task - Install the node modules for the project
* Command Line Task - Build the Angular App
* .NET Core Tool Installer - Install the .NET CLI
* Command Line Task - Publish the Web API
* Azure App Service Manage - Stop the app deployed in Azure
* Azure App Service Deploy - Deploy the app to Azure
* Azure App Service Manage - Start the app deployed in Azure

## Authors

* **Subhendu De** - *Initial work* - [DotNet Artisan](http://dotnetartisan.in/)

See also the list of [contributors](https://github.com/subhendude/SampleAngular-NetCoreTemplate/contributors) who participated in this project.
