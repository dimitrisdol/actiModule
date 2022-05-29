Module that enables fast creation of ActiNode CRD along with a client to create 4 actiNode objects.

In order to run:
	1. Pull the repo
	2. cd actiModule
	3. cd k8s-client
	4. Run: KUBE_NAMESPACE='default' go run . 
		(change default to the namespace you want your actiNode objects at)
	5. kubectl get actinodes (to check if all 4 actinodes were created)
