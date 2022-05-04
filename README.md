# PowerAppsIntegration

## Overview

This repository contains example code for Power Platform. I have included some useful link to get you started. The 2 topic areas cover are **ALM for Power Platform** and **Coauthoring for Power Apps**.
## Coauthoring

Power Apps previously had a core problem in it came to collaborative development\. The problem was you couldn't do it\. Previously trying to open a power app in edit mode that was opened by another developer you would get that annoying message that states this App is locked by Bobby Smith\. Recently a new experimental feature has been released by Microsoft that now allows Git to be the source control solution. With a few steps in using your git solution of choice you can now collaborate with your fellow developers at the same time.  

### Useful Links

- [Co-authoring in canvas apps (experimental)](https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/git-version-control)
- [Known Limitations](https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/git-version-control#known-limitations)
- [GitHub - Creating a personal access token](https://docs.github.com/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Azure DevOps - Use personal access tokens](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate)

## ALM for Power Platform

Traditional developer has normal CI/CD processes. Well how do you manage Non-Prod and Prod environments for your power platform solutions? Well the links I provide can give you a jump start and I have sample GitHub Actions for branching, unpacking, packing, exporting, and importing managed and unmanaged solutions. 

### Useful Links

- [Getting Started](https://docs.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-start)
- [Service Principal - Register an app with Azure Active Directory](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/walkthrough-register-app-azure-active-directory)
- [Tutorial: Automate solution deployment using GitHub Actions for Microsoft Power Platform](https://docs.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-deploy)
- [Power Platform GitHub Actions](https://github.com/microsoft/powerplatform-actions)
- [Lab and Sample workflows](https://github.com/ChrisMcKee1/powerplatform-actions-lab#power-platform-actions-lab)
- [GitHub Environment Variables](https://docs.github.com/en/actions/learn-github-actions/environment-variables)
- [Microsoft Docs GitHub Action for Power Platform](https://docs.microsoft.com/en-us/power-platform/alm/devops-github-actions)
- [About the GITHUB_TOKEN secret](https://docs.github.com/en/actions/security-guides/automatic-token-authentication)