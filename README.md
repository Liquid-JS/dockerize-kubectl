# dockerize-kubectl
Image with docker, aws-cli, kubeclt, dockerize, and jq

### Persist config
Mount `~/.aws/` and `~/.kube/` if you wish to persist config for `aws-cli` and `kubectl`,
before running `aws configure` and `aws eks --region <region> update-kubeconfig --name <cluster_name>`.
