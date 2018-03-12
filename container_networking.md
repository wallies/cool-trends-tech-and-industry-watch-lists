# Container Networking

## eBPF/XDP
- eBPF/XDP programs to SmartNICs - http://netdevconf.org/1.2/session.html?jakub-kicinski
Agilio CX
- https://www.slideshare.net/Open-NFP/p4-epbf-and-linux-tc-offload

## Container Network Plugins
- Weave - mesos, kubernetes cni (Weave)
- Calico - mesos net modules, kubernets cni, kubernetes Network Policy (Calico)
- Flannel - mesos, kubernets cni (CoreOS, CNCF)
- Contiv - mesos, kubernets - Cisco
- Romana.io - mesos, kubernets cni, kubernetes Network Policy
- OpenShift - mesos, kubernets cni, kubernetes Network Policy
- OpenContrail vrouter - kubernets cni, kubernetes Network Policy - Juniper
- Cilium - kubernetes cni, mesos, IPAM
- CNI-Genie - kubernetes, mesos. Enables multi CNI 
- SR-IOV - (Intel)
- Infoblox 
- Multus - Enables multi CNI (Intel)
- Nuage CNI 
- Silk - Cloud foundry 
- Linen CNI - ovs
- Kube-Router - (Cloud Native Labs)  https://github.com/cloudnativelabs/kube-router
- HarmonStack - OpenDaylight network provider for kubernetes
- Kope Routing - 
- Kubermesh - Baremetal
- BaGPipe BGP CNI - Can do MPLS. cni plugin for bagpipe bgp  https://github.com/murat1985/bagpipe-cni
- Trireme - Zero trust network (Aporeto) https://github.com/aporeto-inc/trireme-kubernetes
- DCOS Navstar - orchestrates virtual overlay networks using VXLAN 
- Kubernetes RDMA(remote direct memory access) device plugin https://github.com/hustcat/k8s-rdma-device-plugin

## Virtual routers and switches
- Snaproute flexswitch
- Azure SONiC P4 Switch & router
- BaGPipe BGP
- Canal (calico + flannel)
- Snabb 
- OpenContrail vrouter
- Contiv

## Other network projects
- Plumgrid io visor
- Fd.io
- DPDK
- P4

## Notes
Keep track of mutli network spec proposal as part of kubernetes sig networking
