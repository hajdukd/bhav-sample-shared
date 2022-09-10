# Bhav-sample-shared

Sample charts for presentation purposes

## Usage

[Helm](https://helm.sh) must be installed to use the charts.\
Please refer to Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```shell
helm repo add bhav-shared https://hajdukd.github.io/bhav-sample-shared
```
If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.

You can then run `helm search repo bhav-shared` to see the charts.

To install the <chart-name> chart:
```shell
helm install my-<chart-name> bhav-shared/<chart-name>
```

To uninstall the chart:
```shell
helm delete my-<chart-name>
```
