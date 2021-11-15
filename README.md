# Telemetry-kibana

Kibana is an free and open frontend application that sits on top of the Elastic Stack, providing search and data visualization capabilities for data indexed in Elasticsearch.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- kibana · elastic/kibana (https://artifacthub.io/packages/helm/elastic/kibana)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add elastic https://helm.elastic.co
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `kibana`:

```console
$ helm install kibana --version <version> elastic/kibana -f chart/values.yaml
```

## Uninstalling the Chart

To uninstall/delete the kibana deployment:

```console
$ helm delete kibana
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

