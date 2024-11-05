<img src="assets/toolnetes-logo.jpeg" align="right" width="300" heigh="auto">

# toolnetes

Collection of miscellaneous helper tools.

<br><br><br><br>

# Tools 
(those with 📦 can be installed via [krew](https://github.com/kubernetes-sigs/krew/))

### 🚀 Speed up workflow
* [kubectx + kubens (📦ctx + ns)](https://github.com/ahmetb/kubectx) - switch between clusters and namespaces
* [kube-fzf](https://github.com/arunvelsriram/kube-fzf) - findpod/tailpod/execpod/describepod with the power of [fzf](https://github.com/junegunn/fzf)
* [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for K8s (with regex support)
* [kubectl-neat (📦neat)](https://github.com/itaysk/kubectl-neat) - remove clutter from K8s manifests to make them more readable
* [kubeconform](https://github.com/yannh/kubeconform) - fast K8s manifests validation tool
* [kubefwd](https://github.com/txn2/kubefwd) - bulk port forwarding k8s services for local dev
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - K8s prompt for bash & zsh 
* [fish-kube-prompt](https://github.com/aluxian/fish-kube-prompt) - K8s prompt for fish (Use together with [Fish auto completion](https://gist.github.com/Aracki/cf422173371d2118ae94bb6821f074e0))
* [kubectl aliases](https://github.com/Aracki/configs/blob/master/.aliases) - check the '#KUBERNETES' section
* [kubectl node-shell (📦node-shell)](https://github.com/kvaps/kubectl-node-shell) - ssh into your cluster nodes
* [k9s](https://k9scli.io/) - terminal UI to interact with your Kubernetes clusters
* [kubectl images (📦images)](https://github.com/chenjiandongx/kubectl-images) - list deployed images

### ⚖️ Cluster resources
* [kube-capacity (📦resource-capacity)](https://github.com/robscott/kube-capacity) - provide an overview of the resource requests/limits
* [kubectl-view-utilization (📦view-utilization)](https://github.com/etopeter/kubectl-view-utilization) - show cluster CPU and Memory requests utilization
* [kubectl-df-pv (📦df-pv)](https://github.com/yashbhutwala/kubectl-df-pv) - check capacity for all PVCs

### 🗝 Secrets
* [kubectl-view-secret (📦view-secret)](https://github.com/elsesiy/kubectl-view-secret) - easy secret decoding tool
* [k8s-unused-secret-detector](https://github.com/dtan4/k8s-unused-secret-detector) - Detect unused K8s Secrets 
 
### 🛡 RBAC
* [rakkess (📦access-matrix)](https://github.com/corneliusweig/rakkess) - shows an access matrix
* [kubectl-who-can (📦who-can)](https://github.com/aquasecurity/kubectl-who-can) - shows which subjects have specific RBAC permissions
* [rbac-lookup (📦rbac-lookup)](https://github.com/reactiveops/rbac-lookup) - find k8s roles and cluster roles

### 📝 Evaluate cluster
* [pluto](https://github.com/FairwindsOps/pluto) & [kubent](https://github.com/doitintl/kube-no-trouble) - utilities to find deprecated Kubernetes apiVersions
* [popeye (📦popeye)](https://github.com/derailed/popeye) - k8s cluster resource sanitizer
* [sonobuoy](https://github.com/heptio/sonobuoy) - k8s diagnostic tool
* [kubescape](https://github.com/armosec/kubescape) - testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by NSA
* [opencost](https://github.com/kubecost/cost-model) - give you visibility into current and historical K8s spend and resource allocation
