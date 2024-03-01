# APIShell
This is a shell of a .NET 8 Web API that pulls from AWS Secrets and combines them with the appsettings configuration object.

To use, update the following:

.\Properties\launchSettings.json

Update "SECRET_NAME": "xxxxxxxxxxxxxxxxx" with the correct secret name.

appsettings.Development.json

Update "Profile": "xxxxxxxxxxxxxx" with the correct local IAM profile.
