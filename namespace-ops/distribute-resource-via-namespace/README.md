# Configure BookInfo Application, Channels, Subscriptions, and Placement Rules in OCM

## Finish this readme

run `kubectl apply -k .` in this directory from your terminal.

# Expected Result
1. Deployable at `payload.yaml` will be promoted to 2 channels
2. A subscription will be created at spoke cluster(which is marked as production)
3. Within the subsription's namespace, there should be configmap, which is a
   child of the Deployable at step-1
