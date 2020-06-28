1. create a k8s cluster  
   `doctl k8s cluster create my-cluster --node-pool "name=pool1;size=s-1vcpu-2gb;count=2" --region sgp1`

> TIP: monitor your k8s resources by using `watch -x kubectl get all`

1. create resources  
   `kubectl create -f.`

1. cleanup your cluster  
   `doctl k8s cluster delete my-cluster`

> NOTE: for cleanup, you may need to manually delete your `loadbalancers` and `volumes`
