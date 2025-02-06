<!-- app-name: radarr -->
# radarr helm chart

```console
helm repo add anchorlytics https://charts.anchorlytics.com/
helm install anchorlytics/radarr
```

## Volumes
+ `appdata`: mounted at `/config`. Default (in `values.yaml`) is a 10G emptyDir (hence not persisted).
