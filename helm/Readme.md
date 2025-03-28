Add repo :
helm repo add openmsa https://openmsa.github.io/helm/

Search Version:
helm search repo openmsa -l

Deploiement:
helm install --create-namespace --namespace <NAMESPACE> <RELEASE_NAME> openmsa/msa --version <CHART VERSION>

example:
helm install --create-namespace --namespace msa mymsa openmsa/msa --version 3.1.0

List:
helm list -n msa
