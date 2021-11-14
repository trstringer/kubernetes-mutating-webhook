# Kubernetes Mutating Webhook example

This shows a basic implementation of a mutating webhook.

## Setup

*Note: This relies on TLS certificates to function correctly. Soon that will be added to this repo for a full end-to-end working example.*

This example utilizes a local kind cluster.

```bash
$ make build
$ make build-image-kind
$ make push-kind
$ make deploy
```

## Cleanup

```bash
$ make cleanup
```
