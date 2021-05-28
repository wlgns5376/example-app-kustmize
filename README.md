# kustmize

## build
```sh
kustomize build overlay/dev/
```

## apply kubernetes
```sh
kustomize build overlay/dev/ | kubectl apply -f -
```