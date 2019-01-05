Apply a new configuration to the cluster:

```bash
gcloud container clusters get-credentials gaia --zone us-central1-a --project api-in-k8s
kubectl apply -f .
```
