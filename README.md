# kustomize
kustomize the k8s manifest file.

## set alias for long running commands
`alias k="kubectl kustomize"`

## cd to base dir
`cd base`

## run kustomize to view k8s manidest file (already set alias)
`k .`

## to apply manifest kustomization run
`kubectl apply -k kustomization.yml`