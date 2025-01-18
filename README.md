# kustomize
kustomize the k8s manifest file.

## set alias
`alias k="kubectl kustomize"`

## cd base
`cd base`

## run kustomize to vire k8s manidest file (alreay set alias)
`k .`

## to apply kustomization run
`kubectl apply -k kustomization.yml`