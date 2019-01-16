## helm repo update

update information of available charts locally from chart repositories

### Synopsis


Update gets the latest information about charts from the respective chart repositories.
Information is cached locally, where it is used by commands like 'helm search'.

'helm update' is the deprecated form of 'helm repo update'. It will be removed in
future releases.


```
helm repo update [flags]
```

### Options

```
  -h, --help     help for update
      --strict   fail on update warnings
```

### Options inherited from parent commands

```
      --debug                           enable verbose output
      --home string                     location of your Helm config. Overrides $HELM-HOME (default "~/.helm")
      --host string                     address of Tiller. Overrides $HELM-HOST
      --kube-context string             name of the kubeconfig context to use
      --kubeconfig string               absolute path to the kubeconfig file to use
      --tiller-connection-timeout int   the duration (in seconds) Helm will wait to establish a connection to tiller (default 300)
      --tiller-namespace string         namespace of Tiller (default "kube-system")
```

### SEE ALSO

* [helm repo](../../helm/#helm-repo)	 - add, list, remove, update, and index chart repositories

###### Auto generated by spf13/cobra on 15-Nov-2018