# kubectl-bash-plugins
Bash scripts for working with Docker variables, secrets and configmaps in kubectl

### kubectl-find-key

Find a key by name in kubernetes ConfigMaps and Secrets and displays the content

`kubectl-find-key ${namespace} "variable name"`

### kubectl-find-key2env

Find a key by name in kubernetes ConfigMaps and Secrets and displays the content in the format "ENV var=content"

`kubectl-find-key2env ${namespace} "variable name"`

### kubectl-find-key2yml

Find a key by name in kubernetes ConfigMaps and Secrets and displays the content as a yaml reference to the ConfigMap or Secret:

`kubectl-find-key2yml ${namespace} "variable name"`
