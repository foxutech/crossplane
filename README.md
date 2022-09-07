# Crossplane
This repo will be used for crossplane example

Follow this page to create the azure service principle and azure provider secret configuration. 

https://foxutech.com/how-to-provision-azure-resources-using-crossplane/[https://foxutech.com/how-to-provision-azure-resources-using-crossplane/]

# To Create a secret use, 
$ kubectl create secret generic azure-creds -n crossplane --from-file=creds=./creds.json

Name of the file is creds.json and namespace is crossplane, change it if you want. 

About Crossplane: https://foxutech.com/crossplane-let-your-kubernetes-to-build-your-cloud-infrastructure/[https://foxutech.com/crossplane-let-your-kubernetes-to-build-your-cloud-infrastructure/]
