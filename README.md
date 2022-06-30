# ALM-for-PVA
Github Actions for Managing Microsofts PVA as a template for PVA Projects

## secrets you need to setup 
PowerPlatformSPN : service principal secret

## actions:
workflow dispatch:
deploy-development.yml :  Deploy a new development environment with content of repository (unmanaged)
export-branch-solution.yml: export a solution from dev to a new branch
