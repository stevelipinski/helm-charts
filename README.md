Once Helm has been set up correctly, add the repo as follows:

  helm repo add stevelipinski-github https://stevelipinski.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
stevelipinski-github` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> stevelipinski-github/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>
