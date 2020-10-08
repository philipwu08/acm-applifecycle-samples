# applifecycle-samples
This repo intents to hold some typical use cases, which involve multiple
components of applifecycle. I guess if we have enough test cases, then we can
automate them.

If you find some edge case or you want to include some use case, you can just
create a folder for you case. The folder should have such layout,
1. all the YAML files, name them in order would be nice
2. a README, which explain 
   - what's the expect outcome of such case(the outcome should be at k8s
	 resource level, meaning you are expecting pod instead of deployment)
   - if these case has been test on a hub-spoke env, if so, include the version
	 of the ACM and OCP


# ACM test cases

**Note, make sure the following case could pass**
https://github.com/open-cluster-management/acm-test/tree/master/Doc/Samples
test
test
