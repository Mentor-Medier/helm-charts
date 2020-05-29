# Helm Charts

Personnal collection of helm charts for software that I use but do not provide a chart or the chart is not published.

- [Wave](https://github.com/pusher/wave)

## How to use

Terraform:
```terraform
resource "helm_release" "my_release" {
  name       = "my-release"
  repository = "https://sytten.github.io/helm-charts/"
  chart      = "wave"
  version    = "1.0.0"
  namespace  = "kube-system"
}
```
