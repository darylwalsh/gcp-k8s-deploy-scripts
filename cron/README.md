# Kubernetes - Cron
This is the cron segment in a multipart series about Kubernetes and some of the finer points 
I've learned along the way when using [Kubernetes](https://kubernetes.io/) with 
[Google Cloud Platform](https://cloud.google.com/).

You can read the accompanying post for this folder here: 
[Kubernetes - Cron Jobs](https://medium.com/google-cloud/kubernetes-cron-jobs-455fdc32e81a).

To run this code here are the quick steps.

### To startup and deploy:
```bash
git clone https://github.com/darylwalsh/gcp-k8s-deploy-scripts.git
cd ~/kubernetes-series/cron/scripts
sh startup.sh
sh deploy.sh
sh check-endpoint.sh
sh create_cronjob.sh
```

### To Teardown:
```bash
cd kubernetes-series/cron/scripts # if necessary
sh teardown.sh
```