# Implementing CI-CD pipeline using openshift pipelines based on tekton and argocd

This is a demonstrantion on implementing CICD pipelines on openshift.
For de CI part we used the pipelines operator based on Tekton and for the CD part we used Argocd which is also running on the Openshift cluster.

In order to successfully be able to access the resources running on the code-ready-containers openshift installation, a nginx reverse proxy was configured which was setup on an WSL 2 machine which was running on the same guest machine as the one for the core-ready hyper-v VM.


## Resources
Main starting point:
mvazquezc/code-to-prod-demo - https://www.openshift.com/blog/from-code-to-production-with-gitops
Extra adjustements taken from here (same guy, different github repo, slightly same scenario:
https://github.com/mvazquezc/reverse-words-cicd/tree/ci

Tekton Resource Starting Point:
https://github.com/tektoncd/triggers/tree/master/docs

## Environment description
To be completed


## Main problems encoutered
To be completed. Lots of windows bullshit.....
