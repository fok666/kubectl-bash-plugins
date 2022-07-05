# kubectl-bash-plugins
Bash scripts for kubectl

## Find a key by name in kubernetes ConfigMaps and Secrets and displays the content
kubectl-find-key ${namespace} "variable name"

## Find a key by name in kubernetes ConfigMaps and Secrets and displays the content in the format "ENV var=content"
kubectl-find-key2env ${namespace} "variable name"

## Find a key by name in kubernetes ConfigMaps and Secrets and displays the content as a yaml reference to the ConfigMap or Secret:
kubectl-find-key2yml ${namespace} "variable name"
