# Expect Result

## github_channel_e2e
1. in the spoke cluster, there should be:
	1. a subscription
	2. service and deployments from the https://github.com/ianzhang366/acm-applifecycle-samples
	   with path defined at the configmap(`path: git-ops/bookinfo/guestbook`)

## github_helm_channel_e2e 
1. in the spoke cluster, there should be:
	1. a subscritpion
	2. a helmrelease

## helm_channel_e2e 
1. in the spoke cluster, there should be:
	1. deployments and service create from the guestbook application

## namespace_channel_e2e
1. in the spoke cluster, there should be:
	1. a subscription
	2. a configmap at the subscription namespace

## object_bucket_channel_e2e
1. in the spoke cluster, there should be:
	1. a subscription
	2. a configmap at the subscription namespace
