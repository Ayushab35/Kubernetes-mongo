### Running the application
- Install Minikube in your local machine using docker as your virtual environment
- Command 
```
minikube start
```
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

minikube tunnel mongo-express-ingress
--> Creates tunnel between host machine and minikube cluster
```

## Helm
Helm acts as a templating engine, facilitating the creation of YAML files by using templates and passing values through `values.yaml` (`{{.Value}}`). It is particularly useful in CI/CD pipelines. Helm allows creating Helm charts that can be used across different environments (dev, prod, staging).

![Charts](/images/chart.png)

mychart folder is name of chart
chart.yaml is meta info abt chart
value.yaml is values for template
charts will have chart dependencies
in Template actual template files are stored


### Values.yaml file : 

![value.yaml](/images/value.png)

### Persistant Volumes : 

![persistant volumes.yaml](/images/persitantVolume.png)
![persistant volumes.yaml](/images/persitantVolume.png)