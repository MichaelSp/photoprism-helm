# Photoprism Helm Charts

[Helm](https://helm.sh) repo for different charts related to Photoprism which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add photoprism https://michaelsp.github.io/photoprism-helm/
helm repo update
```

### Helm Charts

* [photoprism](charts/photoprism)

  ```bash
  helm install my-release photoprism/photoprism
  ```

For more information, please checkout the chart level [README.md](charts/photoprism/README.md).

#### Bugs and other Issues
If you have a bug to report or a feature to request, you can first search the [GitHub Issues](https://github.com/photoprism/photoprism/issues), and  if you can't find what you're looking for, feel free to open an issue.

#### Contributing to the Code
We're always happy to review a pull request :) Please just be sure to check the pull request template to make sure you fufill all the required checks, most importantly the [DCO](https://probot.github.io/apps/dco/).
