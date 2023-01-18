## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add econradar https://econradar.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
econradar` to see the charts.

To install chart:

    helm repo add econradar https://econradar.github.io/charts
    helm repo update
    helm install <chart-name> econradar/<chart-name>

To uninstall the chart:

    helm delete <chart-name>