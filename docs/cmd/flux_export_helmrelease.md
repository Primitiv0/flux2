## flux export helmrelease

Export HelmRelease resources in YAML format

### Synopsis

The export helmrelease command exports one or all HelmRelease resources in YAML format.

```
flux export helmrelease [name] [flags]
```

### Examples

```
  # Export all HelmRelease resources
  flux export helmrelease --all > kustomizations.yaml

  # Export a HelmRelease
  flux export hr my-app > app-release.yaml

```

### Options

```
  -h, --help   help for helmrelease
```

### Options inherited from parent commands

```
      --all                 select all resources
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux export](flux_export.md)	 - Export resources in YAML format

