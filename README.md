# Create a configuration using metadata and startup scripts

## Overview

This is a Google Cloud Deployment Manager
configuration file which creates two virtual machine instances using multiple templates.

This is modified version of example templates provided which allows to create another firewall rule for ssh. 
This is created for a training assignment.

## Executing 

1) Install gcloud SDK shell

2) run glcoud init and configure the enviornment. (set project, zone etc)

3) run the command to deploy "gcloud deployment-manager deployments create test-deployment --config config.yaml"

4) To delete the resourses  "gcloud deployment-manager deployments delete test-deployment"