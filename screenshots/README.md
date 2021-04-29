# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed

![dockerhub](dockerhub.png)

* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)

![travis integration](travis-integration.png)

* Travis CI showing a successful build and deploy job

![travis-successful-build](travis-successful-build.png)

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
![kubernetes-pods-deployed](kubernetes-pods-deployed.png)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```

![kubenetes-services-properly-set-up](kubenetes-services-properly-set-up.png)

* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
![horizontal-scaling](horizontal-scaling.png)

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```

![kubectl-logs](kubectl-logs.png)