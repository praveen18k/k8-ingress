### Ingress Controller 

Reference
```
https://kubernetes-sigs.github.io/aws-load-balancer-controller/v2.6/
```
First Step: Create an IAM OIDC provider, you can skip this step if you have cluster<br>
Second Step: Giving access to our nodes | Donload an IAM policy for the LBC | copy any other region one<br>
Third Step : Create an IAM policy named AWSLoadBalancerControllerIAMPolicy<br>
Fourth Step: Create IMA Role and Kubernetes ServiceAccount for the LBC(LoadBalancerCluster), use thr ARN from previous step


