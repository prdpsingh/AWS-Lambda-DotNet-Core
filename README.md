# AWS-Lambda-DotNet-Core
Sample AWS lambda in Dotnet Core - Build and Package lambda function in .net core c#

1. Install AWS Toolkit for Visual Studio - https://aws.amazon.com/visualstudio/
2. Create a New Lambda Function Project
3. Build Project

Package Lambda function using dotnet CLI

1. Install lambda tools for dotnet core CLI. Run following command on comand prompt - dotnet tool install -g Amazon.Lambda.Tools
2. Move to directory containing lambda csproj file
3. Run following command to package lambda - dotnet lambda packge
4. This will generate a zip file in /bin/release/<.netversion> folder
5. Upload this zip to the lambda function in AWS.


