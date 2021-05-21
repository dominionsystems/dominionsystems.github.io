
# Dominion Systems Downtime Maintenance Page

A static web app that displays a maintenance downtime page to users 
hosted as an Azure Static Web App and routed to from the Azure Route 
Traffic Manager. 

## How To

Make necessary modifications and then push to branch `main` 
to kick off CI/CD and delivery any new updates to the Azure Static Web 
App service. 

## CI/CD

The Azure Static Web App is built and deployed via the Github Actions that 
are made available by hosting our code in the github repository at: 
[DS Downtime Repo](https://github.com/dominionsystems/dominionsystems.github.io)

### Commit without CI/CD

Sometimes you may find that while doing work in the repo that you want to 
commit and push changes to the `main` branch without actually allowing Github to 
execute its CI/CD Actions. In order to do so, simply include `[skip ci]` somewhere in
your commit message and Github will skip the CI/CD Action. 
