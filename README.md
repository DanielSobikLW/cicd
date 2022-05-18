Lacework Shield swimming app CICD DEMO 

- Based on The SimpleWhaleDemo App https://github.com/usha-mandya/SimpleWhaleDemo
- Based on Jerome Baude's demo https://github.com/jeromebaude/my-tweet-app-lacework
- Jerome's Demo https://www.youtube.com/watch?v=YsnVe8S1-xg

Build a simple 2 node EKS Cluster

- https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html

Deploy and expose app on EKS

- https://cloud.google.com/kubernetes-engine/docs/tutorials/hello-app#deploying_the_sample_app_to
- Link is for GCP but easiest deployment guide i could find

Create a Docker Hub Registry

- https://hub.docker.com/

Configure GitHub Actions

- https://docs.docker.com/ci-cd/github-actions/

SECRETS Required

AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY

DOCKER_HUB_ACCESS_TOKEN
DOCKER_HUB_USERNAME

KUBE_CONFIG_DATA

LW_ACCESS_TOKEN
LW_ACCOUNT_NAME


DEMO WORKFLOW

IMAGES

nginx:alpine - latest image - may or may not be clean - if not tweak lacework scanner workflow for vuln check
nginx:1.21.5-alpine - DEC 2021 - has critical vulnerabilities

