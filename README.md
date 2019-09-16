# Gin Gonic Basic

## Getting started

⚠️  to do

## What we want

To have a go service running on the cluster. It should have an healthcheck route. 
We should have an other service that will send an email if the first service is
not healthy. 

## What needs to be done 

### A micro service with `/health`

- [ ] Read about `go mod`
- [ ] Finish Dockerfile
- [ ] Make the server run on k8s
- [ ] Expose service in k8s

```
kubectl run gingonicbasic --image=golang:latest --port=8080
```


