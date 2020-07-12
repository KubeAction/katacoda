
# step 4 - test simple workflow

now make your first workflow!
`kubectl apply -f simple-flow.yaml`{{excute}}

check flow
`kubectal apply -f simple-flow.yaml -n kubeaction`{{excute}}

now cleanup your workflow
`kubectal delete -f simple-flow.yaml -n kubeaction`{{excute}}