---
title: vela live-diff
---

Dry-run application locally, and diff with a deployed application version

### Synopsis

Dry-run application locally, and diff with a deployed application version.

```
vela live-diff
```

### Examples

```
vela live-diff -f app-v2.yaml -r app-v1 --context 10
```

### Options

```
  -r, --Revision string     specify an application Revision name, by default, it will compare with the latest Revision
  -c, --context int         output number lines of context around changes, by default show all unchanged lines (default -1)
  -d, --definition string   specify a file or directory containing capability definitions, they will only be used in dry-run rather than applied to K8s cluster
  -e, --env string          specify environment name for application
  -f, --file string         application file name (default "./app.yaml")
  -h, --help                help for live-diff
  -n, --namespace string    specify the Kubernetes namespace to use
```

### SEE ALSO



#### Go Back to [CLI Commands](vela) Homepage.


###### Auto generated by spf13/cobra on 12-Jan-2022, refer to [script in KubeVela](https://github.com/oam-dev/kubevela/tree/master/hack/docgen).