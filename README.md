# Dry Run
``
helm upgrade azurecli <repo-directory>\azurecli-openshift --dry-run --debug --install --namespace azurecli-ns --timeout 10m
``
  
# Deploy
``
helm upgrade azurecli <repo-directory>\azurecli-openshift --debug --install --namespace azurecli-ns --timeout 10m
``

# Steps

1. Deploy the application
2. Run 'oc get pods' to find the running azurecli pod
3. Get shell access to azure cli pod 'oc exec -it pod/<azurecli pod name> -- sh'
4. login to azure using 'az login'
5. run other azure cli commands
