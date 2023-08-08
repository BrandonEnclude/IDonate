# Donor Import Config Template
This is a template for creating a Donor Import Config metadata repository with a "Deploy to Salesforce" button, courtesy of [afawsett](https://github.com/afawcett/githubsfdeploy)

## How to Use
- Clone template by clicking the "Use this template" button, giving the new repository the name of the desired platform configuration (ex. PayPal Giving)
- Populate the force-app\main\default directory with metadata. Usually this includes:
   - A `Donor Import Config` Custom Metadata record
   - The processing flow defined in the Donor Import Config above
- Update the URL of the button below, replacing `{REPOSITORY-NAME}` with the name of your Github repo

## Deploy
<a href="https://githubsfdeploy.herokuapp.com?owner=EncludeLtd-Donor-Import-Configurations&repo={REPOSITORY-NAME}&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>