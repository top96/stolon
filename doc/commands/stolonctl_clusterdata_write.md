## stolonctl clusterdata write

Write cluster data

### **Warning: This shouldn't be used if you don't know what you're doing**

### Synopsis

Write cluster data

```
stolonctl clusterdata write [flags]
```

### Options

```
  -f, --file string   file containing the new cluster data
  -h, --help          help for write
  -y, --yes           don't ask for confirmation
```

### Options inherited from parent commands

```
      --cluster-name string             cluster name
      --kube-context string             name of the kubeconfig context to use
      --kube-namespace string           name of the kubernetes namespace to use
      --kube-resource-kind string       the k8s resource kind to be used to store stolon clusterdata and do sentinel leader election (only "configmap" is currently supported)
      --kubeconfig string               path to kubeconfig file. Overrides $KUBECONFIG
      --log-level string                debug, info (default), warn or error (default "info")
      --metrics-listen-address string   metrics listen address i.e "0.0.0.0:8080" (disabled by default)
      --store-backend string            store backend type (etcdv2/etcd, etcdv3, consul or kubernetes)
      --store-ca-file string            verify certificates of HTTPS-enabled store servers using this CA bundle
      --store-cert-file string          certificate file for client identification to the store
      --store-endpoints string          a comma-delimited list of store endpoints (use https scheme for tls communication) (defaults: http://127.0.0.1:2379 for etcd, http://127.0.0.1:8500 for consul)
      --store-key string                private key file for client identification to the store
      --store-prefix string             the store base prefix (default "stolon/cluster")
      --store-skip-tls-verify           skip store certificate verification (insecure!!!)
```

### SEE ALSO

* [stolonctl clusterdata](stolonctl_clusterdata.md)	 - Manage current cluster data

###### Auto generated by spf13/cobra on 24-Nov-2018