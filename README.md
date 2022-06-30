# Application Lifecycle Managment for Microsofts Power Virtual Agent
Github Actions for Managing Microsofts PVA as a template for PVA Projects

## secrets you need to setup 
PowerPlatformSPN : service principal secret

## actions:
workflow dispatch:
deploy-development.yml :  Deploy a new development environment with content of repository (unmanaged)  
export-branch-solution.yml: export a solution from dev to a new branch  
release-solution-to-xxx-reusable.yml: master file for releasing code to an environment  
release-to-staging.yml: automated action to release to staging, please adjust to your needs  
release to-production.yml:  automated action to release to production, please adjust to your needs  
