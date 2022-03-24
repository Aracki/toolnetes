<img src="assets/toolnetes-logo.jpeg" align="right" width="300" heigh="auto">

# toolnetes

Collection of miscellaneous [helper tools](#Tools), [must-read articles](#Articles). 

<br><br><br><br>

# Tools 
(those with 📦 can be installed via [krew](https://github.com/kubernetes-sigs/krew/))

### 🚀 Speed up workflow
* [kubectx + kubens (📦ctx + ns)](https://github.com/ahmetb/kubectx) - switch between clusters and namespaces
* [kube-fzf](https://github.com/arunvelsriram/kube-fzf) - findpod/tailpod/execpod/describepod with the power of [fzf](https://github.com/junegunn/fzf)
* [kubectl-neat (📦neat)](https://github.com/itaysk/kubectl-neat) - remove clutter from K8s manifests to make them more readable
* [kubeconform](https://github.com/yannh/kubeconform) - fast K8s manifests validation tool
* [kubefwd](https://github.com/txn2/kubefwd) - bulk port forwarding k8s services for local dev
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - K8s prompt for bash & zsh 
* [fish-kube-prompt](https://github.com/aluxian/fish-kube-prompt) - K8s prompt for fish (Use together with [Fish auto completion](https://gist.github.com/Aracki/cf422173371d2118ae94bb6821f074e0))


### 🛡 RBAC
* [rakkess (📦access-matrix)](https://github.com/corneliusweig/rakkess) - shows an access matrix
* [kubectl-who-can (📦who-can)](https://github.com/aquasecurity/kubectl-who-can) - shows which subjects have specific RBAC permissions
* [rbac-lookup (📦rbac-lookup)](https://github.com/reactiveops/rbac-lookup) - find k8s roles and cluster roles

### ⚖️ Resources
* [kube-capacity (📦resource-capacity)](https://github.com/robscott/kube-capacity) - provide an overview of the resource requests/limits
* [kubectl-view-utilization (📦view-utilization)](https://github.com/etopeter/kubectl-view-utilization) - show cluster CPU and Memory requests utilization
* [kubectl-df-pv (📦df-pv)](https://github.com/yashbhutwala/kubectl-df-pv) - check capacity for all PVCs

### 🗝 Secrets
* [k8sec](https://github.com/dtan4/k8sec) - CLI tools to manage K8s Secrets easily
* [k8s-unused-secret-detector](https://github.com/dtan4/k8s-unused-secret-detector) - Detect unused K8s Secrets 

### 📜 Logs
* [kubetail](https://github.com/johanhaleby/kubetail) - Bash script to tail K8s logs from multiple pods at the same time
* [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for K8s

### 📝 Evaluate cluster
* [popeye (📦popeye)](https://github.com/derailed/popeye) - k8s cluster resource sanitizer
* [sonobuoy](https://github.com/heptio/sonobuoy) - k8s diagnostic tool
* [kubescape](https://github.com/armosec/kubescape) - testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by NSA
* [kubecost](https://github.com/kubecost/cost-model) - give you visibility into current and historical K8s spend and resource allocation



# Articles
* K8s components - good introduction material
	* [Understanding kubernetes networking: pods](https://medium.com/google-cloud/understanding-kubernetes-networking-pods-7117dd28727)
	* [Understanding kubernetes networking: services](https://medium.com/google-cloud/understanding-kubernetes-networking-services-f0cb48e4cc82)
	* [Understanding kubernetes networking: ingress](https://medium.com/google-cloud/understanding-kubernetes-networking-ingress-1bc341c84078)
	* [Kubernetes NodePort vs LoadBalancer vs Ingress? When should I use what?](https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0)
	* [Tutorial for beginners in 4 Hours](https://www.youtube.com/watch?v=X48VuDVv0do)
* About networking:
	* [IP, subnets, CIDR](https://www.digitalocean.com/community/tutorials/understanding-ip-addresses-subnets-and-cidr-notation-for-networking)
	* [Network interfaces and protocols](https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols)
	* [Operating a Kubernetes network](https://jvns.ca/blog/2017/10/10/operating-a-kubernetes-network/)
* Best practices:
	* [The 12 Factor App](https://12factor.net/) - methodology for building modern software 
	* [12 Fractured Apps](https://medium.com/@kelseyhightower/12-fractured-apps-1080c73d481c) - Kelsey Hightower’s view on how 12FA and Docker can be a killer combo
	* [Modernizing Applications for Kubernetes](https://dev.to/digitalocean/modernizing-applications-for-kubernetes-1hon) - DigitalOcean guide
	* [Configuration Best Practices](https://kubernetes.io/docs/concepts/configuration/overview/#general-configuration-tips) - official kubernetes guide
* [Kubernetes the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way) - Kelsey Hightower’s guide on how to bootstrap k8s the hard way on GCP with no scripts
* Great [article](https://medium.com/spire-labs/utilizing-kubernetes-liveness-and-readiness-probes-to-automatically-recover-from-failure-2fe0314f2b2e) about utilizing k8s liveness & readiness probes to automatically recover from failure
* Great [article](https://docs.bitnami.com/kubernetes/how-to/configure-rbac-in-your-kubernetes-cluster/) about configuring *RBAC*
* [Pain(less) NGINX Ingress](https://danielfm.me/posts/painless-nginx-ingress.html) - Daniel Martins about Nginx Ingress outages and config reloading
* [33 Kubernetes security tools](https://sysdig.com/blog/33-kubernetes-security-tools/) - Sysdig article about security tools (both open-source & commercial)
* [Kubernetes failure stories](https://github.com/hjacobs/kubernetes-failure-stories) - Compilation of public failure/horror stories related to Kubernetes 
* [Inside of kubernetes controller](https://speakerdeck.com/govargo/inside-of-kubernetes-controller) - A deep dive into Kubernetes controllers
