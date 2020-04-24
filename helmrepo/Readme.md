This is Netdata's MongoDB Helm repository.

# Use

To use this repo with helm, add the repository:

```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo update
```

Install the mongodb-sharded chart:

```
helm install mongodb-sharded bitnami/mongodb-sharded
```

# Update helm package repo

```
./update.sh
git push
```
