# 3-tier-app-chart

# Helm Commands
```
$ helm package .
$ helm repo index .
$ helm repo index . --url https://github.com/doomokun/3-tier-app-chart.git

$ helm repo list
$ helm search repo
$ helm install #{chart name you like} #{helm search repo NAME}

$ helm list
$ helm delete #{NAME}
$ helm delete --purge #{NAME}
```