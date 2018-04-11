# IaC Config for Client

By SomeEngineer

Background:
The CIO has given very clear direction that she wants to use Infrastructure as a Service (e.g. AWS, Azure, DigitalOcean, Google Cloud) rather than Platform as a Service (e.g. heroku, ECS, AppEngine) as she does not want to get locked into a particular vendor. 

Tools:
IAC - Terraform (Multi Cloud compatable)
Container - Kubernetes
Public Cloud - Azure
OS - Windows Server Datacentre 2016

Dependancies:
Access to GitHub
Powershell
Install Azure CLI 2.0 - https://docs.microsoft.com/en-us/cli/azure/install-azure-cli
Once installed check you have logged via $ az login;
Install K8s CLI - https://kubernetes.io/docs/tasks/kubectl/install/

API's:



Future Tasks:
In future we need to extend these scripts via the CI server to build deployment pipeline
- Setup team city Env and Octopus deploy to maintain CI
we need to add enviroment and extend and harden into a production system later on 
- Setup of 