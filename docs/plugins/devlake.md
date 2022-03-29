## 1 `devlake` Plugin

This plugin installs [DevLake](https://github.com/merico-dev/lake) in an existing K8s cluster.

Note that this isn't a production-ready installation; it's only meant as an alternative for [the original docker-compose installation](https://github.com/merico-dev/lake/blob/main/docker-compose.yml) should you prefer K8s.

## 2 Usage:

```yaml
tools:
- name: devlake
  plugin:
    # name of the plugin
    kind: devlake
    # version of the plugin
    # checkout the version from the GitHub releases
    version: 0.3.0
```

All the parameters in the example above are mandatory.