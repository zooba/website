---
title: Running Heroku apps on Azure
draft: true
tags:
---

ACS Kubernetes

```bash
az group create -n k8s -l southcentralus
az acs create -n nobunk8s -g k8s --type kubernetes
```

Deploy Helm (Tiller)
* It's already installed on new ACS clusters!
* Manual install info here: ???

Deploy apps
