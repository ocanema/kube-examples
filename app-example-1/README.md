# Deploy app generica


Un deployment di un container hello-world e sporre il servizio tramite NodePort e/o Ingress

## Start Minikube

```
minikube start --addons=ingress --ports=80:80,443:443
```

Imagine da deployare: gcr.io/google-samples/hello-app:1.0


