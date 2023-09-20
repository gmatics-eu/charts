## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add gmatics-eu https://gmatics-eu.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
gmatics-eu` to see the charts.

To install the xcube chart:

    helm install my-<chart-name> gmatics-eu/xcube

To uninstall the chart:

    helm delete my-<chart-name>