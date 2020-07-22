# Configure BookInfo Application, Channels, Subscriptions, and Placement Rules in OCM

## Finish this readme

run `kubectl apply -k .` in this directory from your terminal.

# Expected Result
1. Deployable at `payload.yaml` will be: 
   
- should NOT be promoted to channel `cm-delivery-ch`, which has a annotation
  promotion gate `dev: pass`. In other words, there sholdn't be a duplicate
  deployable at `delivery` namespace

- should be promoted to channel `ns`, which doesn't have any promotion gate.
  Therefore in ch-ns namespace there should be a duplicate deployable of this
  one 


2. A subscription will be created at spoke cluster(which is marked as production)
3. Within the subsription's namespace, there should be configmap, which is a
   child of the Deployable at step-1
