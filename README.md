# kubernetes cmd for deployment ,scaling, replicasets using kubectl
<br>
-minikube start <br>
-kubectl apply -f pods.yaml<br>
-kubectl get pods(check storage)<br>
-kubectl create deployment pod-deployment --image=kicbase/echo-server:latest<br>
-kube scale deployment pod-deployment --replicas=3/4/5...

<br>
-kubectl describe pod pods-name(details info of the pods)<br>
-minikube services service-name(open service in browser)
<br>
-kubectl get svc(checks creation of the services)