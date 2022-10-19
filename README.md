# 3-tier-app-chart

# Chart pages
pages: https://doomokun.github.io/3-tier-app-chart

repo: https://github.com/doomokun/3-tier-app-chart
git: git@github.com:doomokun/3-tier-app-chart.git

branch: main

# Helm Commands
```
$ helm repo add 3-tier-app-repo https://doomokun.github.io/3-tier-app-chart

$ helm package .
$ helm repo index .
$ helm repo index . --url https://doomokun.github.io/3-tier-app-chart

$ helm upgrade --install 3-tier-app 3-tier-app-repo/3-tier-app-chart --set appServer.image.repository=${args.image} --set appServer.image.tag=${args.tag} --namespace=3-tier-app --create-namespace

$ helm repo list
$ helm search repo
$ helm install #{chart name you like} #{helm search repo NAME}

$ helm list
$ helm delete #{NAME}
$ helm delete --purge #{NAME}
```