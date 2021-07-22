# typesense-kubernetes


This repo hosts kustomize files for deploying typesense in a kubernetes cluster.


## Quickstart

> kubectl apply -f 
## Detailed setup:

1. Clone the repo

> git clone https://github.com/typesense/typesense-kubernetes


2. modify the overlays/org1/kustomization.yaml file according to your needs



Run below command:

To install

> kustomize build overlays/dev | kubectl apply -f - 

Clean up

> kustomize build overlays/dev | kubectl delete -f - 





