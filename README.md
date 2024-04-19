| **NAME**              | **PROMPT**                     | **DESCRIPTION**                    | **EXAMPLE**                       |
|-----------------------|--------------------------------|------------------------------------|-----------------------------------|
| app.yaml | create pod with nginx container |  Specification of the pod with nginx container which has port | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | create health probe which checks liveness of container | Configure container with liveness <br> probe which checks availability of container | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |    
| app-readinessProbe.yaml | create health probe which checks availability and readiness of container | Readiness and Liveness of the container | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create container with availability <br> and readiness probes but mount volume additionally | Pod with container which have health probes and mount volumes | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | create cronjob which runs every 1 hour and prints some string in console | Creates cronjob resource | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job.yaml | create job object for training ML models which includes mounting of storage for input and output data | | [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer.yaml | create multicontainer object where one container is writing data in the folder and second reads data from that folder | Description | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml | create health probe which checks availability and readiness of container and resources | Description | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml | create container which retrieves env variables for secrets | Description | [app-secret-env.yaml](./yaml/app-secret-env.yaml) | 
