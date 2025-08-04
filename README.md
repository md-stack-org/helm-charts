### md-stack helm-charts

| Helm-chart name                                                      | Last version | Description                                             |
| -------------------------------------------------------------------- | ------------ | ------------------------------------------------------- |
| [raw](https://github.com/md-stack-org/helm-charts/tree/main/charts/raw) | 0.2.5        | raw helm definitions, clone of depricated incubator/raw |

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add md-stack-org https://md-stack-org.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo <alias>` to see the charts.

To install the `<chart-name>` chart:

    helm install `<chart-name>` md-stack-org/`<chart-name>`

To uninstall the chart:

    helm uninstall `<chart-name>`
