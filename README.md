# kubeview
## KubeView is a Kubernetes cluster visualizer and graphical explorer

## Installation
- Install `helm` on your local machine, you can follow this guide https://helm.sh/docs/intro/install/

- clone this repo

- run `helm install -f ./kubeview-helm/values.yaml kubeview ./kubeview-helm -n namespace`. You can also customize your `values.yaml` file

- run `kubectl port-forward svc/kubeview -n namespace 8000` To view your Kubeview dashboard on `localhost:8000`
