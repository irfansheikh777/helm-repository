kubectl create secret generic gitlab-secret --from-literal=username=gitlabadmin --from-literal=password='test123='
kubectl create secret generic posgresql-secret --from-literal=username=gitlabadmin --from-literal=password='test123='
kubectl create secret generic redis-secret --from-literal=username=gitlabadmin --from-literal=password='test123'
