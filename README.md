# Dry Run #
``
helm upgrade azurecli <repo-directory>\azurecli-openshift --dry-run --debug --install --namespace azurecli-ns --timeout 10m --set fullnameOverride=azurecli
``
  
# Deploy #
``
helm upgrade azurecli <repo-directory>\azurecli-openshift --debug --install --namespace azurecli-ns --timeout 10m --set fullnameOverride=azurecli
``
