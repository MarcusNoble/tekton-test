# tekton-test

## Install

```sh
# Install Tekton
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
kubectl apply --filename https://storage.googleapis.com/tekton-releases/triggers/latest/release.yaml
# Install standard triggers and CI template
kubectl apply -f tekton/
# Install all reusable tasks
kubectl apply -f tekton/tasks
```

## Usage

1. Set up Webhook pointing at the Tekton event listener
2. Add a `.tasks.yaml` file to the root of your repo
3. See [.tasks.yaml](.tasks.yaml) for an example of how to structure
