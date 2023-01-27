## Krateo Template AKS
This is a template used to deploy a fully functional AKS cluster through crossplane Azure provider.

### Prerequisites: ###
1) Krateo
2) Krateo Module Core
3) Provider Azure and it's configuration

### Install ###
- Option 1: manual install (mainly for testing purpose):
1)      kubectl apply -f defaults/package.yaml
2)      kubectl apply -f defaults/test_claim.yaml

- Option 2: install it using the Krateo Dashboard that will populate and apply defaults/claim.yaml