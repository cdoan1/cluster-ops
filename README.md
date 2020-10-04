# cluster-ops

Given hosts listing of cluster names and their login credentials,
iterate and login to each cluster, to perform configuration, or
collect data.

## role: common

1. using the `KUBECONFIG=/tmp/ansible` setting, `oc login` to cluster and verify connection
