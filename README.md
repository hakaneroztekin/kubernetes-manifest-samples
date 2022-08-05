Hello,

This is a supplementary repository for [kubernetes in a nutshell](https://hakaneroztekin.medium.com/kubernetes-in-a-nutshell-f2916a138f59) article. 


#### Note about Ingress

For ingress to work, install the Ingress controller.

`kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.3.0/deploy/static/provider/cloud/deploy.yaml
`

For more details about installation, check [official documentation](https://kubernetes.github.io/ingress-nginx/deploy/#quick-start).
