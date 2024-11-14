## Application deployment with helm charts

This README.md file contains the steps that helps us to deploy the application with the helm command. 


**ℹ️ Information: As we are using argocd, this steps should not be followed for the deployment of service in current infrastructure.**



### Install and Upgrade helm-chart for dev-api-env service
```
helm upgrade --install dev-api-env-chart seemore/ --values seemore/dev-values/dev-api-env-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-bullboard service
```
helm upgrade --install dev-bullboard-chart seemore/ --values seemore/dev-values/dev-bullboard-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-catalog-automation service
```
helm upgrade --install dev-catalog-automation-chart seemore/ --values seemore/dev-values/dev-catalog-automation-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-data-query service
```
helm upgrade --install dev-data-query-chart seemore/ --values seemore/dev-values/dev-data-query-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-db-watcher service
```
helm upgrade --install dev-db-watcher-chart seemore/ --values seemore/dev-values/dev-db-watcher-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-db-worker service
```
helm upgrade --install dev-db-worker-chart seemore/ --values seemore/dev-values/dev-db-worker-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-elastic-feeder service
```
helm upgrade --install dev-elastic-feeder-chart seemore/ --values seemore/dev-values/dev-elastic-feeder-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-insights service
```
helm upgrade --install dev-insights-chart seemore/ --values seemore/dev-values/dev-insights-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-integration-microservice service
```
helm upgrade --install dev-integration-microservice-chart seemore/ --values seemore/dev-values/dev-integration-microservice-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-lineage-engine service
```
helm upgrade --install dev-lineage-engine-chart seemore/ --values seemore/dev-values/dev-lineage-engine-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-query-history-analyzer service
```
helm upgrade --install dev-query-history-analyzer-chart seemore/ --values seemore/dev-values/dev-query-history-analyzer-values.yaml --namespace seemore
```

### Install and Upgrade helm-chart for dev-query-history-importer service
```
helm upgrade --install dev-query-history-importer-chart seemore/ --values seemore/dev-values/dev-query-history-importer-values.yaml --namespace seemore
```