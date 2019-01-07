Apply a new configuration to the cluster:

```bash
gcloud auth login
gcloud components install kubectl
gcloud container clusters get-credentials gaia --zone us-central1-a --project api-in-k8s
kubectl apply -f .
```

### Current deploys

#### Cron Jobs ([docs](https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/))
- [nateinaction/wordpress-integration-updater](https://github.com/nateinaction/wordpress-integration-updater)
    - Status: `kubectl get cronjob wordpress-integration-updater`
    - Logs: 