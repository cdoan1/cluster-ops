# cluster-ops

Given hosts listing of cluster names and their login credentials,
iterate and login to each cluster, to perform configuration, or
collect data.

## hosts

```ini
[managednodes]
cluster1 name=cluster1 username=kubeadmin password=changeme api=https://api.cluster.com:6443
cluster2 name=cluster2 username=kubeadmin password=changeme2 api=https://api.cluster2.com:6443
```


## role: common

1. using the `KUBECONFIG=/tmp/ansible` setting, `oc login` to cluster and verify connection

