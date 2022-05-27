# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
<img width="541" alt="get_pods" src="https://user-images.githubusercontent.com/42094883/170787319-25d2ca9f-a333-40fd-8659-6b593787db3d.png">
<img width="982" alt="hpa" src="https://user-images.githubusercontent.com/42094883/170787326-c634f0f3-07b0-4514-a99a-b175692bc191.png">
<img width="981" alt="log_backend" src="https://user-images.githubusercontent.com/42094883/170787329-bc6ee544-de6f-4200-a788-e1fe078e8b3c.png">
<img width="929" alt="travis" src="https://user-images.githubusercontent.com/42094883/170787333-7849f604-b08c-4d9c-9f26-2e186e70f1f6.png">
<img width="1280" alt="udagram" src="https://user-images.githubusercontent.com/42094883/170787337-00fe28ec-051d-4b5f-a5b1-bfaa52545b41.png">
<img width="569" alt="descriable_services_1" src="https://user-images.githubusercontent.com/42094883/170787341-389e0218-bc49-4dcc-8b08-856700d6c926.png">
<img width="564" alt="descriable_services_2" src="https://user-images.githubusercontent.com/42094883/170787348-3ad96b14-2987-4055-b815-7718a531185b.png">
<img width="557" alt="descriable_services_3" src="https://user-images.githubusercontent.com/42094883/170787354-a1ec92c6-4d01-4fe1-bc65-d1d818ac3999.png">
<img width="520" alt="docker" src="https://user-images.githubusercontent.com/42094883/170787359-3e14a011-f8ce-4870-b333-fa4b35c356ba.png">
