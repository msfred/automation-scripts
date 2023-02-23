## A demo of deploying PowerShell scripts to Azure Automation Runbooks

This repository is using 1 automation workflow per team to deploy all of the PowerShell scripts, for the respective team, Azure Automation Runbooks.
For example, the **Deploy Audit Runbooks workflow** (*.github/workflows/deploy-runbooks-audit.yml*) will deploy all of the scripts in the **Audit** folder whenever one of those files is updated.

### Organizing Repositories
This repository is using separate folders (ie, *Audit*, *TeamsAuthomation*, *TenantSync*) to organize the PowerShell scripts by their respective teams.  Alternatively, a separate repository per team could be created.  This approach would allow permissions to be granted to just the members of those respective teams rather than giving users access to all teams' PowerShell scripts.

