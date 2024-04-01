# helm-charts

This is an unofficial Helm chart repository collection.
It uses the [Chart Releaser](https://helm.sh/docs/howto/chart_releaser_action/) action to create a self-hosted Helm chart repo for
charts linked in the charts directory.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
  helm repo add jeff1010322 https://jeff1010322.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo jeff1010322` to see the charts.

To install the <chart-name> chart:

```
    helm install <chart-name> jeff1010322/<chart-name>
```

To uninstall the chart:

    helm delete my-<chart-name>

## Available Charts

- [lago](https://github.com/getlago/lago-helm-charts/blob/main/Chart.yaml)
  
