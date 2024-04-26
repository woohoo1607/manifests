
| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|:----:|:------:|:-----------:|:-------:|
|app.yaml| kubectl apply -f app.yaml | Simple POD manifest | [app.yaml](./app.yaml)|
|app-livenessProbe.yaml| kubectl apply -f app-livenessProbe.yaml | Manifest with liveness probe   | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
|app-readinessProbe.yaml| kubectl apply -f app-readinessProbe.yaml | Manifest with readiness probe  |[app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
|app-volumeMounts.yaml| kubectl apply -f app-volumeMounts.yaml | Manifest with volume mount |[app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
|app-cronjob.yaml| kubectl apply -f app-cronjob.yaml | Cron Job manifest | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
|app-job.yaml| kubectl apply -f app-job.yam |Job manifest | [app-job.yaml](./yaml/app-job.yaml) |
|Multicontainer Application| kubectl apply -f app-multicontainer.yaml | Multicontainer POD manifest | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml)|
|app-resources.yaml|kubectl apply -f app-resources.yaml | Simple resources manifest | [app-resources.yaml](./yaml/app-resources.yaml)|
|app-secret-env.yaml|kubectl apply -f app-secret-env.yaml |Simple secret mount manifest |[app-secret-env.yaml](./yaml/app-secret-env.yaml) |

