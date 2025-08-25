A TPV database used primarily for the default installation of Galaxy using the
Galaxy Helm chart.

To use, add the following to your `values.yaml` file in the chart:

```yaml
galaxy.configs.galaxy\.yaml.galaxy.execution.environments.tpv_dispatcher.tpv_config_files: https://raw.githubusercontent.com/CloudVE/tpv-db-helm/refs/heads/main/tools.yml
```
