# openldap-bitnami

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 2.5.11](https://img.shields.io/badge/AppVersion-2.5.11-informational?style=flat-square)

Helm chart for OpenLDAP based on the Bitnami image

## TL;DR
```console
$ helm repo add johanneskastl-excalidraw https://johanneskastl.github.io/excalidraw-helm-chart/
$ helm repo update
$ helm install openldap-bitnami johanneskastl-excalidraw/openldap-bitnami
```

## Installing the Chart
To install the chart with the release name `openldap-bitnami`:
```console
helm install openldap-bitnami johanneskastl-excalidraw/openldap-bitnami
```

## Uninstalling the Chart
To uninstall the `openldap-bitnami` deployment:
```console
helm uninstall openldap-bitnami
```
The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

Read through the [values.yaml](./values.yaml) file. It has several commented out suggested values.

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,
```console
helm install openldap-bitnami \
  --namespace openldap-bitnami \
    johanneskastl-excalidraw/openldap-bitnami
```

Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.
For example,
```console
helm install openldap-bitnami johanneskastl-excalidraw/openldap-bitnami -f values.yaml
```

