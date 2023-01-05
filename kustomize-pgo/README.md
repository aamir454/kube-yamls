# setup
Repo containing pgo setup with kustomize

#Step 1: Install PGO, the Postgres Operator
kubectl apply -k install/namespace
kubectl apply --server-side -k install/default
#Create a Postgres Cluster
kubectl apply -k postgres
