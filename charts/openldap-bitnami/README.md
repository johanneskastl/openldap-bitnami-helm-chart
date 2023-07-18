# openldap-bitnami

![Version: 1.5.0](https://img.shields.io/badge/Version-1.5.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 2.6.5](https://img.shields.io/badge/AppVersion-2.6.5-informational?style=flat-square)

Helm chart for OpenLDAP based on the Bitnami image

## TL;DR
```console
$ helm repo add johanneskastl-openldap-bitnami https://johanneskastl.github.io/openldap-bitnami-helm-chart/
$ helm repo update
$ helm install openldap-bitnami johanneskastl-openldap-bitnami/openldap-bitnami
```

## Installing the Chart
To install the chart with the release name `openldap-bitnami`:
```console
helm install openldap-bitnami johanneskastl-openldap-bitnami/openldap-bitnami
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
    johanneskastl-openldap-bitnami/openldap-bitnami
```

Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.
For example,
```console
helm install openldap-bitnami johanneskastl-openldap-bitnami/openldap-bitnami -f values.yaml
```

