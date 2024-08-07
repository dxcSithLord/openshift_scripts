# openshift_scripts

This repository scripts common openshift tasks:

* Backup of etcd
* Shutdown of cluster
* Startup monitoring of cluster
* reboot of the cluster
* review of certificates within the cluster

DeploymentConfig definitions in Openshift from 4.14.14 have been marked as depreciated and content integrating with service mesh has most examples using Deployments in preference.
To help with this, after much research (a couple of results from google search) and I came across this [python script](https://gist.github.com/bomboclat/1c53b7e692b1df58af67598337cc2b88).  After testing this, I found a problem - which was suggested back to the originator of the script.  I have repeated the script here for completeness (convert-deploymentconfig-to-deployment.py)
