# tmc-fluxcd-kustomization

Secret docker-registry-creds-tkg needs to be previously created.

kubectl create secret docker-registry docker-registry-creds-tkg --docker-username=<your-name> --docker-password=<your-pword> --docker-email=<your-email> -n <your-namespace>