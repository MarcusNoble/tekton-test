# tekton-test

## Install

```sh

kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
kubectl apply --filename https://storage.googleapis.com/tekton-releases/triggers/latest/release.yaml
kubectl apply -f tekton/
kubectl apply -f tekton/tasks
```
