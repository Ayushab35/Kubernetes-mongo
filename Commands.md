# Kubernetes Concepts

## Ingress
Ingress connects the outer world with internal services, acting as a gateway. It handles routing and supports HTTPS, enabling TLS certification. Ingress allows configuring subdomains and paths to different services:

### Subdomains:
- shopping.myapp.com
- analytics.myapp.com

### Paths:
- myapp.com/shopping
- myapp.com/analytics

## Minikube Tunnel
Minikube Tunnel creates a tunnel between a host port and a service using the following command:

```
minikube service mongo-express-service
```

## Helm
Helm acts as a templating engine, facilitating the creation of YAML files by using templates and passing values through `values.yaml` (`{{.Value}}`). It is particularly useful in CI/CD pipelines. Helm allows creating Helm charts that can be used across different environments (dev, prod, staging).
