126  helm repo add bitnami https://charts.bitnami.com/bitnami
  127  helm repo update
  128  helm install redis-test bitnami/redis
  129  kubectl get secret --namespace default redis-test -o jsonpath="{.data.redis-password}" | base64 --decode
  130  history 
