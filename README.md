# todo-app-k8s

# Topologi
![todo-topo](https://github.com/teghitsugaya/todo-app-k8s/assets/44857533/37c4ab59-10a6-4f7c-b3bc-ca62c7b7ea72)

# Prequisites
  ### To On Boarding todo-apps, k8s cluster must have:
   - CSI Cinder StorageClass with name: csi-sc-cinder
   - Cloud Controller Openstack for Loadbalancer
   - Pointing IP Loadbalancer to DNS server api.oohara.my.id

### execute
    kubectl apply -f https://raw.githubusercontent.com/teghitsugaya/todo-app-k8s/main/todo-apps-all-in.yml


