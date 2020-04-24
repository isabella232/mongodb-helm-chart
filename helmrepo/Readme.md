This is Netdata's MongoDB Helm repository.

# Use

To use this repo with helm, add the repository:

```
helm repo add netdata-mongodb https://netdata.github.io/mongodb-helm-chart/helmrepo/
helm repo update
```

Install the mongodb-sharded chart:

```
helm install mongodb-sharded netdata-mongodb/mongodb-sharded
```

# Update helm package repo

```
./update.sh
git push
```
