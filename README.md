# googlecontainer
k8s镜像文件

那好



KUBE_VERSION=v1.12.0
KUBE_PAUSE_VERSION=3.1
ETCD_VERSION=3.1.17
DNS_VERSION=1.14.12


kube-proxy-amd64:${KUBE_VERSION}

kube-scheduler-amd64:${KUBE_VERSION}

kube-controller-manager-amd64:${KUBE_VERSION}

kube-apiserver-amd64:${KUBE_VERSION}

pause-amd64:${KUBE_PAUSE_VERSION}

etcd-amd64:${ETCD_VERSION}

k8s-dns-sidecar-amd64:${DNS_VERSION}

k8s-dns-kube-dns-amd64:${DNS_VERSION}

k8s-dns-dnsmasq-nanny-amd64:${DNS_VERSION}



kube-proxy:${KUBE_VERSION} 

kube-scheduler:${KUBE_VERSION} 

kube-controller-manager:${KUBE_VERSION} 

kube-apiserver:${KUBE_VERSION} 

pause:${KUBE_PAUSE_VERSION} 

etcd:${ETCD_VERSION} 

k8s-dns-sidecar:${DNS_VERSION} 

k8s-dns-kube-dns:${DNS_VERSION} 

k8s-dns-dnsmasq-nanny:${DNS_VERSION}

coredns:${COREDNS}


coredns:1.2.2
tiller:v2.11.0
defaultbackend:1.4
kubernetes-dashboard-amd64:v1.10.0
metrics-server-amd64:v0.3.0