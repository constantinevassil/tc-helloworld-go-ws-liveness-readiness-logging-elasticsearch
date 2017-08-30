# tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch


## Deploy 

```bash
sudo kubectl apply -f https://raw.githubusercontent.com/topconnector/tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch/master/tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch-deployment.yaml
```

## Create service

```bash
sudo kubectl apply -f https://raw.githubusercontent.com/topconnector/tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch/master/tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch-svc.yaml
```

## Get service port

```bash
kubectl get svc
tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch   10.109.245.136   <nodes>       2020:31937/TCP   1m
```

```bash
curl 192.168.0.199:31937
Hello World from Go in minimal Docker container (4.28MB) - tc-helloworld-go-ws-liveness-readiness-logging-elasticsearch - v.1.0, it took 70ns to run
```
