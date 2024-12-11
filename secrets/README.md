To create a secret YAML you can run this command:

```bash
kubectl create secret generic epatel-app \
    --from-literal="SECRET_APP_NAME=epatel" \ 
    --dry-run=client -o yaml > secret.yaml
```
