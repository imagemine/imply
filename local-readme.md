### Install

#### minikube
```
minikube start --cpus 3 --memory 4096 --disk-size 8g
minikube config set cpus 3
minikube config view cpus
minikube profile list
```

```
helm upgrade -n default --install druid . -f local-values.yaml
```

### Notes
* deployment agents : for data, query and manager

### Questions

* do i need license key?