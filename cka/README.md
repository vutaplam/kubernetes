# Certified Kubernetes Administrator (CKA)
|Topic|Sub-Topic|Description|Reference|
|-----|---------|-----------|---------|
|Installation|kubeadm|In exam we need to add a node and upgrade using kubeadm ||
||kops||
|Master Components|API server| With kubectl we need to create, modify, and delete resources. With RBAC to grant access to certain resources||
||etcd|Backup and Restore etcd data,Verify the health of etcd cluster, Connectivity issue with etcd, Access and query etcd data, Add or remove etcd memebers,Remove a failed member from etcd cluster, secure etcd communication with certificates and authentication|
||Scheduler|Configure custom scheduler policies,Configure node affinity for deployment to ensure pods are scheduled on specific nodes, Configure Pod Tainits and Tolerations,Set Resource Requests for Pods,Configure Pod anti affinity rules pods dont run on same node||
||Controller Manager|It keep cluster in desired state||
||Kubelet|It is an agent run on each node||
||Kube-Proxy|It maintain network rules on node to allow communication between pods and services||
