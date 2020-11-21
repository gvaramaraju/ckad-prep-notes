# POD

Create pod

`kubectl run nginx --image=nginx`

Get all pods in namespace with node and ip information

`kubectl get pods -o wide`

Get pod definition of a running pod to yaml

`kubectl get pod pod-name -o yaml > pod-definitio.yml`

Edit defintion of a running pod directly

`kubectl edit pod pod-name`

Delete pod

`kubectl delete pod pod-name`
