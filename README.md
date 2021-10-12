# Plumtech Helm Chart Repository

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add plum-helm https://helm.plum-ops.com/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
plum-helm` to see the charts.

To install the chproxy chart:

    helm install my-chproxy plum-helm/chproxy

To uninstall the chart:

    helm delete my-chproxy