# 3-tier-app-chart

# Chart pages
pages: https://doomokun.github.io/3-tier-app-chart

repo: https://github.com/doomokun/3-tier-app-chart
git: git@github.com:doomokun/3-tier-app-chart.git

branch: main

# Helm Commands
```
$ helm package .
$ helm repo index .
$ helm repo index . --url https://doomokun.github.io/3-tier-app-chart

$ helm repo list
$ helm search repo
$ helm install #{chart name you like} #{helm search repo NAME}

$ helm list
$ helm delete #{NAME}
$ helm delete --purge #{NAME}
```