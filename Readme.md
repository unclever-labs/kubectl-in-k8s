# Kubectl in K8s

## Introduction

Sometimes you want to run `kubectl` from inside k8s

## Contents

- [Usage](#usage)
- [Build](#build)
- [Push](#push)

## Usage

```bash
# Deploy
kubectl apply -f k8s.yaml

# Use it
kubectl exec -it kubectl-in-k8s sh

# While inside
kubectl get pods
```

## Build

```bash
./build.sh
```

## Push

```bash
./push.sh
```
