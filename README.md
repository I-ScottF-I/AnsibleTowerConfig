# AnsibleTowerConfig

Source Code for AWX config

The whole idea for this lab is creating a CI pipeline containing:

infrastructure Code Update -> Git Repo -> Testing -> Production

This is to be achieved by using:

- Github as GitRepo
- Testing to be managed by Jenkins
- Infrastructure automation (test provisioning and production deployments) to be performed Ansible Tower
