# Automated Entra ID Authentication Methods Report

This repository automates the execution of the [Invoke-EntraAuthReport](https://www.powershellgallery.com/packages/Invoke-EntraAuthReport) script within a GitHub Actions workflow. It runs against a Microsoft 365 tenant as an application, generating scheduled authentication reports for analysis.

## Features

- Uses [Invoke-EntraAuthReport](https://www.powershellgallery.com/packages/Invoke-EntraAuthReport) by [Daniel Brady](https://ourcloudnetwork.com/about/) [LinkedIn](https://www.linkedin.com/in/danielbradley2/). Be sure to give him a follow and say thanks!
- Runs on a schedule using GitHub Actions
- Authenticates via an Entra ID application (app registration required)
- Collects Entra ID authentication methods insights
- Uploads the report as an artefact on the run action

## Prerequisites

TBC

