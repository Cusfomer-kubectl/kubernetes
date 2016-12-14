## Guestbook Example in Cloud Container Engine (CCE)

This example shows how to build a simple, multi-tier web application using Kubernetes and [Docker](https://www.docker.com/) in CCE.

Run the example app:

```console
$ kubectl create -f examples/guestbook/cce-all/
service "redis-master" created
deployment "redis-master" created
service "redis-slave" created
deployment "redis-slave" created
service "frontend" created
deployment "frontend" created
```

Delete the example app:

```console
$ kubectl delete -f examples/guestbook/cce-all/
```
