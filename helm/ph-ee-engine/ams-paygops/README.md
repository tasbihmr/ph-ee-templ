# paygops_connector

![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational?style=flat-square) ![AppVersion: 1.0.0](https://img.shields.io/badge/AppVersion-1.0.0-informational?style=flat-square)

paygops_connector

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| LOGGING_LEVEL_ROOT | string | `"INFO"` |  |
| SPRING_PROFILES_ACTIVE | string | `"bb"` |  |
| ams.local.enabled | bool | `false` |  |
| configmap.apiversion | string | `"v1"` |  |
| deployment.annotations.deployTime | string | `"{{ .Values.deployTime }}"` |  |
| deployment.apiVersion | string | `"apps/v1"` |  |
| enabled | bool | `true` |  |
| image | string | `""` |  |
| imageTag | string | `"latest"` |  |
| ingress.apiversion | string | `"networking.k8s.io/v1"` |  |
| limits.cpu | string | `"500m"` |  |
| limits.memory | string | `"512M"` |  |
| paygops.authheader | string | `"PaymentHubTest"` |  |
| paygops.base_url | string | `"https://feature-test1.paygops.com/"` |  |
| requests.cpu | string | `"100m"` |  |
| requests.memory | string | `"256M"` |  |
| secret.apiversion | string | `"v1"` |  |
| service.apiversion | string | `"v1"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
