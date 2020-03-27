# Creating a Secret
## Create secret for postgres with imperative command
```
kubectl create secret generic <secret_name> --from-literal key=value
```
## Example
## Create secret is "pgpassword", key is "PGPASSWORD", value is "12345asdf"
```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdf
```