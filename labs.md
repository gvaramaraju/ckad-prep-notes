#### Get pod in default namespace

`kubectl get pods`

#### Create pod with nginx image

`kubectl run nginx --image=nginx`

#### Find image used in a pod

`kubectl get pod nginx-pod -o yaml | grep -i image`

#### Find the node on which the pod is running

`kubectl describe pod nginx-pod`

#### How many containers are part of pod

`kubectl get pods`
`kubectl get pod nginx -o yaml`

#### State of container in a pod

`kubectl describe pod nginx-pod`

#### Delete Pod

`kubectl delete pod nginx-pod`

#### Creat pod redis using definition file

`kubectl run redis --image=redis --dry-run=client -o yaml > redis.yml`
`kubect create -f redis.yml`

#### Edit pod image name

`kubectl edit pod nginx`
