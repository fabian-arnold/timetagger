## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
  helm repo add timetagger https://fabian-arnold.github.io/timetagger
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo wektimetaggeran` to see the charts.

To install the timetagger chart:

```sh
    helm install my-timetagger timetagger/timetagger
```

To uninstall the chart:

```sh
    helm delete my-timetagger
```
