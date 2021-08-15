# AnsibleTowerConfig

Source Code for F5 & AWX config

A way to create self service abstracted F5 load balancing config. SPlit into 3 parts:
 - Application team, this is where the load balancing declarations are stored. These may be stored as part of a source code repo of an application.
 - Network team, this team is responsible for the implementation of the FAST templates
 - Platform team, may also be a network team. This team are responsible for the Ansible Tower infrastructure.
