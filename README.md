# CPi-job-judilibre
Ce repos contient les jobs d'administration sur judilibre

## Activation Job 

Pour activer ou désactiver un job ou cronjob, vous pouvez acceder au fichier [values.yaml](helm/values.yaml) et changer les valeurs "enabled"  a  "true" ou "false".

```yaml
restoreJob:
    enabled: true
restoreSnapshot:
    enabled: false
snapshotter:
    enabled: false
```

