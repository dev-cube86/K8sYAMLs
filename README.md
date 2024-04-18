| **NAME**              | **PROMPT**                     | **DESCRIPTION**                    | **EXAMPLE**                       |
|-----------------------|--------------------------------|------------------------------------|-----------------------------------|
| app.yaml | create pod with nginx container |  Specification of the pod with nginx container which has port | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | create health probe which checks liveness of container | Configure container with liveness probe which checks availability of container | 
[yaml/app-livenessProbe.yaml] (./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create health probe which checks availability and readiness of container | Readiness and Liveness of the container | 
[yaml/app-readinessProbe.yaml] (./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create container with availability and readiness probes from previous example but mount volume additionally | Pod with container which have health probes and mount volumes | [yaml/app-volumeMounts.yaml] (./yaml/app-volumeMounts.yaml) |