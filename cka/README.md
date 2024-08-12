# Certified Kubernetes Administrator (CKA)
|Topic|Sub-Topic|Description|Reference|
|-----|---------|-----------|---------|
|Installation|kubeadm|In exam we need to add a node and upgrade using kubeadm ||
||kops||
|Master Components|API server| With kubectl we need to create, modify, and delete resources. With RBAC to grant access to certain resources||
||etcd|- Backup and Restore etcd data<br>- Verify the health of etcd cluster<br>- Connectivity issue with etcd<br>- Access and query etcd data<br>- Add or remove etcd memebers<br>- Remove a failed member from etcd cluster<br>- secure etcd communication with certificates and authentication|
||Scheduler|- Configure custom scheduler policies<br>- Configure node affinity for deployment to ensure pods are scheduled on specific nodes<br>-  Configure Pod Tainits and Tolerations<br>- Set Resource Requests for Pods<br>- Configure Pod anti affinity rules pods dont run on same node||
||Controller Manager|It keep cluster in desired state||
||Kubelet|-Diagnose and resolve issues with nodes where Pods are not being scheduled or containers are not starting<br>-Set up kubelet to use custom certificates for communication with the Kubernetes API server<br>-Configure resource requests and limits for kubelet to manage node resource utilization<br>- Apply taints to a node and configure Pods to tolerate those taints<br>-  use a custom directory for storing Pod data and logs.||
|Worker Components|kube-proxy|- Verify the Current kube-proxy Configuration<br>- Modify the kube-proxy configuration to use IPVS instead of iptables<br>- Enable session affinity for a specific service to ensure that all requests from a single client are sent to the same Pod|||
