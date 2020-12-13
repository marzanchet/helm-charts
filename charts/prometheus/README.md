
```sh
module "prometheus" {
source = "git@github.com:clouddrove/terraform-kubernetes-kubewatch.git"

  secretName = ""
  secretPath = ""
  kubernetesendpoint = ""

  namespace = ""
  prometheus_ingress_endpoint = ""
  alertmanager_ingress_endpoint = ""
  
}

```