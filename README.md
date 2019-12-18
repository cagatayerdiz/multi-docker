# multi-docker

![](https://travis-ci.com/cagatayerdiz/multi-docker.svg?branch=master)

# commands
kubectl get deployment

kubectl delete deployment client-deployment

kubectl get service

kubectl delete service client-node-port

kubectl apply -f k8s

kubectl logs server-deployment-59dc9cc4b-nlltc

kubectl get storageclass

kubectl describe storageclass

kubectl get pv

kubectl get pvc

kubectl create secret generic pgpassword --from-literal key=value

kubectl get secrets

kubectl apply -f kubernetes-dashboard.yaml

kubectl proxy

http://localhost:8001/api/v1/namespaces/kube-system/services/https:kubernetes-dashboard:/proxy/

https://localhost