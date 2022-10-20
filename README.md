# apache-k8s

## Deploy a static httpd server using kubernetes with the following commands:

* `kubectl create namespace httpd-namespace`
* `kubectl apply -f deployment.yaml`
* `kubectl apply -f service.yaml`
* `kubectl scale --replicas=26 -f deeployment.yaml`