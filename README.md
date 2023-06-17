# Examples of YAML files generated with open-ai

This repository contains various YAML files for configuring and deploying the My App application. All YAML files were generated with kubectl open-ai plugin. You can find PROMPTS in the table. 



| Name                      | Prompt                      | Description                 | Example                      |
|---------------------------|-----------------------------|-----------------------------|------------------------------|
| app.yaml                  |kubectl ai "generate example of default app.yaml file for kubernetes, kind: Pod"                             | Default configuration file   | [app.yaml](./yaml/app.yaml)       |
| app-livenessProbe.yaml    |kubectl ai "generate the example of app-livenessProbe.yaml"                             | Liveness probe configuration | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml   |kubectl ai "generate the example of app-readinessProbe.yaml "                             | Readiness probe configuration| [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml     |kubectl ai "generate the example of app-volumeMounts.yaml"                             | Volume mounts configuration  | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml          |kubectl ai "generate the example of app-cronjob.yaml"                             | CronJob configuration        | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job.yaml              |kubectl ai "generate the example of app-job.yaml"                             | Job configuration            | [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer.yaml   |kubectl ai "generate the example of app-multicontainer.yaml "                             | Multi-container configuration| [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml        |kubectl ai "generate the example of app-resources.yaml"                             | Resource configuration       | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml       |kubectl ai "generate the example of app-secret-env.yaml"                             | Secret environment variables | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |
