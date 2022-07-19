# acm-applications
to install argocd for acm:

```oc apply -k manifests```

it will install argocd in namespace acm-gitops-dev and create all the required bindings for ACM.  The managed cluster set is defined as dev-clusters.
Feel free to change these values for your needs.
