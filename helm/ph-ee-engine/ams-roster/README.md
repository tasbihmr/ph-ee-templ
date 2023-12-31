# roster_connector

![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational?style=flat-square) ![AppVersion: 1.0.0](https://img.shields.io/badge/AppVersion-1.0.0-informational?style=flat-square)

ph-ee-connector-ams-roster

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| SPRING_PROFILES_ACTIVE | string | `""` |  |
| ams.local.enabled | bool | `true` |  |
| configmap.apiversion | string | `"v1"` |  |
| deployment.annotations.deployTime | string | `"{{ .Values.deployTime }}"` |  |
| deployment.apiVersion | string | `"apps/v1"` |  |
| enabled | bool | `true` |  |
| image | string | `""` |  |
| imageTag | string | `"latest"` |  |
| ingress.apiversion | string | `"networking.k8s.io/v1"` |  |
| limits.cpu | string | `"500m"` |  |
| limits.memory | string | `"512M"` |  |
| pesacore.auth_header | string | `"PaymentHub"` |  |
| requests.cpu | string | `"100m"` |  |
| requests.memory | string | `"256M"` |  |
| secret.apiversion | string | `"v1"` |  |
| service.apiversion | string | `"v1"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
