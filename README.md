# mininode

my new project
simple http listener in node

```
docker build -t slimslender/minikube-test-node -f docker/Dockerfile .
```

Note that there are two mandatory endpoints for our deployment to kube

* `/health` must return a status 200 to indicate that it is ready to receive requests
* `/info` must return a status 200 to indicate readiness

Both of these endpoints are defined in server.js along with a / endpoint for the hello world

You're good enough, you're smart enough, and doggone it, people like you.

You're good enough, you're smart enough, and doggone it, people like you.
