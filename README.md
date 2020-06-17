# AnsibleTowerConfig

Source Code for AWX config

The whole idea for this lab is creating a CD pipeline containing:

Code commit to app Git branch -> starts ansible build for F5 infrastrcture -> F5 infrastructure and app config are tested -> clean up and if tests pass proceed to production merge -> merge branch into production -> test again

This is to be achieved by using:

- Github as GitRepo
- Deployment pipeline and test orchestration to be performed Ansible Tower

This should all be self service for the app team