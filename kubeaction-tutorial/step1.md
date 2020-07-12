
### Setp 1 - install argo & argo events

check minikube is running
`minikube status`{{execute}}

create argo namespace
`kubectl create namespace argo`{{execute}}

install argo 
`kubectl apply -n argo -f https://raw.githubusercontent.com/argoproj/argo/master/manifests/install.yaml`{{execute}}

create event namespace 
`kubectl create namespace argo-events`{{execute}}

install argo-events
`kubectl apply -f https://raw.githubusercontent.com/argoproj/argo-events/master/manifests/install.yaml`{{execute}}