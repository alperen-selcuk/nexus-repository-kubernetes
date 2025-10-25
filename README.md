## helm

you can find values in repo

```
helm repo add sonatype https://sonatype.github.io/helm3-charts/

helm repo update

helm install nexus -n nexus --create-namespace sonatype/nexus-repository-manager -f nexus-values.yaml
```
