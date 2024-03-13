# k8s yamlfiles
### k8s commands
    curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  ```  
   sudo install minikube-linux-amd64 /usr/local/bin/minikube
```minikube start --driver=docker
 
 minikube delete
   minikube start --driver=docker
    sudo minikube start --driver=docker
    sudo usermod -aG docker jaya && newgrp docker
  kubectl apply -f pod.yml
       kubectl get pod -w
   
   kubectl describe pod pkpod
  kubectl delete pod pkpod
 kubectl apply -f pod1.yml
   kubectl delete -f pod1.yaml
    kubectl run hello --image nginx --port 80
  
  kubectl run hello --image nginx --port 80 --dry-run=client

    kubectl get pod
   kubectl run hello --image nginx --port 80 --dry-run=client -o=yaml
   kubectl run hello --image nginx --port 80 --dry-run=client -o=yaml >podtest.yaml
   kubectl apply -f podtest.yaml
  
 kubectl exec -it hello --bash
  kubectl exec -it hello -- bash
   kubectl get pod
  kubectl get pod -A
   kubectl get namespace
    kubectl get ns
   kubectl create  ns poonam
   kubectl get ns
   kubectl get pod --namespace kube-system
  kubectl apply -f podtest.yaml
   kubectl delete helloc
   kubectl delete pod helloc
  
   kubectl delete pod hello
  export KUBECONFIG=akashsir.conf 
  kubectl get node
  export KUBECONFIG=/home/jaya/akashsir.conf
  minikube start
  kubectl get node
kubectl apply -f rc.yaml
  kubectl apply -f rc.yaml
  kubectl get pod
  kubectl get pod --show-lables
  kubectl get pod --show-labels
  kubectl get pod -o wide
  kubectl delete pod rc-tmmld
  kubectl get pod
kubectl edit rc rc
kubectl apply -f rc.yaml
kubectl get pod
kubectl edit rc rc
kubectl get pod
   kubectl apply -f rc.yaml
  kubectl expose pod pvpod-7ccc5b6fc7-5rr68 --type NodePort --port 80 
  kubectl get svc
  kubectl cluster-info
  kubectl get pv --kubeconfig=config --insecure-skip-tls-verify
 ``` 
kubectl config current-context

