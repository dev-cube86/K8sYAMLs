| **NAME**              | **PROMPT**                     | **DESCRIPTION**                    | **EXAMPLE**                       |
|-----------------------|--------------------------------|------------------------------------|-----------------------------------|
| app.yaml | create pod with nginx container |  Specification of the pod with nginx container which has port | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | create health probe which checks liveness of container | Configure container with liveness <br> probe which checks availability of container | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |    
| app-readinessProbe.yaml | create health probe which checks availability and readiness of container | Readiness and Liveness of the container | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create container with availability <br> and readiness probes but mount volume additionally | Pod with container which have health probes and mount volumes | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
