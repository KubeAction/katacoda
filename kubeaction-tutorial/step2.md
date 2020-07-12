
# step 2 - install kubeaction

create kubeaction namespace
`kubectl create namespace kubeaction`{{execute}}

install kubeaction CRD 
`kubectl apply -n kubeaction -f https://raw.githubusercontent.com/spaceone-dev/KubeAction/tutorial/k8s/crd.yaml`{{execute}}

install kubeaction Controller
`kubectl apply -n kubeaction -f https://raw.githubusercontent.com/spaceone-dev/KubeAction/tutorial/k8s/controller.yaml`{{execute}}


