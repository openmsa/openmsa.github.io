Add repo :
```bash
helm repo add openmsa https://openmsa.github.io/helm/
```

Search Version:
```bash
helm search repo openmsa -l
```

Deploiement:
```bash
helm install --create-namespace --namespace <NAMESPACE> <RELEASE_NAME> openmsa/msa --version <CHART VERSION>
```

example:
```bash
helm install --create-namespace --namespace cloudiamo myCloudiamo openmsa/msa --version 3.1.0
```

List:
```bash
helm list -n cloudiamo
```
