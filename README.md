# googlecontainer
k8s镜像文件




KUBE_VERSION=v1.12.0
KUBE_PAUSE_VERSION=3.1
ETCD_VERSION=3.1.17
DNS_VERSION=1.14.11


kube-proxy-amd64:${KUBE_VERSION}

kube-scheduler-amd64:${KUBE_VERSION}

kube-controller-manager-amd64:${KUBE_VERSION}

kube-apiserver-amd64:${KUBE_VERSION}

pause-amd64:${KUBE_PAUSE_VERSION}

etcd-amd64:${ETCD_VERSION}

k8s-dns-sidecar-amd64:${DNS_VERSION}

k8s-dns-kube-dns-amd64:${DNS_VERSION}

k8s-dns-dnsmasq-nanny-amd64:${DNS_VERSION}

coredns:1.2.2
tiller:v2.11.0
defaultbackend:1.4
kubernetes-dashboard-amd64:v1.10.0
metrics-server-amd64:v0.3.0