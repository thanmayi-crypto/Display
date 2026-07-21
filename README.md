# Jenkins Multi-Configuration Project

## Project Title
Jenkins Multi-Configuration Project using Windows Batch Command

## Description
This project demonstrates the execution of a Windows Batch Command using a Jenkins Multi-Configuration (Matrix) Project. The project is configured to run the same build for different environments such as Development, Testing, and Production.

## Tools Used
- Jenkins
- Windows Batch Command
- GitHub

## Build Configuration
- Job Type: Multi-Configuration Project
- Build Step: Execute Windows Batch Command

## Batch Script

```bat
@echo off

echo Jenkins Multi-Configuration Project

echo Hello Ragathanmayi Elletla 23MIC7166!
echo Welcome to Jenkins.

echo.

echo Current Environment : %ENV%
echo Computer Name       : %COMPUTERNAME%
echo User Name           : %USERNAME%

echo.

echo Build for %ENV% completed successfully.
```

## Environments
- Development
- Testing
- Production

## Output
The project successfully executes the batch script for each configured environment and displays the environment name, computer name, user name, and a success message.

## Conclusion
This project demonstrates how Jenkins Multi-Configuration Projects can execute the same build process across multiple environments using a Windows Batch Command.
