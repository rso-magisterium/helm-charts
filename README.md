# Magisterium Helm chart repository

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add magisterium https://rso-magisterium.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.
You can then run `helm search repo magisterium` to see the charts.

To install a chart:

```sh
helm install <my-chart-name> magisterium/<chart-name>
```

To uninstall the chart:

```sh
helm delete <my-chart-name>
```
