# GitHub Actions

- Below are few sample github actions for reference.

    1. basic_workflow.yml
        - Desc: Used to explain a basic GitHub Actions pipeline
        - Run a one-line script
        - Run a multi-line script
        - Define input variables and print on the console


    2. dotnet_workflow.yml
        - Desc: Used to build a .Net Application
        - Setup .Net on GitHub Runner
        - Restore Dependencies
        - Using Dotnet Build
        - Using Dotnet Test

    3. dotnet_workflow.yml
        - Desc: Deploy a.NET Application to Azure Web App
        - Build 
            - Setup .Net on GitHub Runner
            - Restore Dependencies
            - Publish Aritfacts
            - Upload Artifacts
        - Deploy
            - Download artifact from build job
            - Deploy to Azure Web App