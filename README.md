# Cloud landscape by sendai


# Infrastructure platforms


| Name                                                         | Year | Company              |
| ------------------------------------------------------------ | ---- | -------------------- |
| [OpenStack](https://www.openstack.org/)                      | 2010 | OpenStack Foundation |
| [vSphere](https://www.vmware.com/uk/products/vsphere.html)   | 2009 | VMWare               |
| [Azure Stack VMs](https://azure.microsoft.com/en-gb/overview/azure-stack/) | 2010 | Microsoft            |
| [AWS Outposts](https://aws.amazon.com/outposts/)             | 2018 | Amazon               |

## Hosted

| Name                                        | Date | Company   |
| ------------------------------------------- | ---- | --------- |
| [AWS](https://aws.amazon.com/)              | 2006 | Amazon    |
| [GCP](https://cloud.google.com/)            | 2008 | Google    |
| [Azure](https://azure.microsoft.com/en-gb/) | 2010 | Microsoft |



# Configuration management

| Name                                           | Date | GitHub stars | Company     |
| ---------------------------------------------- | ---- | ------------ | ----------- |
| [CFEngine](https://cfengine.com/)              | 1993 | 0.3          | CFEngine    |
| [Puppet](https://puppet.com/)                  | 2005 | 5.1          | Puppet      |
| [Chef](https://www.chef.io/)                   | 2008 | 5.4          | Chef        |
| [Rudder](https://www.rudder-project.org/site/) | 2011 | 0.2          | Open Source |
| [SaltStack](https://www.saltstack.com/)        | 2011 | 9.2          | SaltStack   |
| [Juju](https://jujucharms.com/)                | 2012 | 1.2          | Canonical   |
| [Ansible](https://www.ansible.com/)            | 2012 | 32.9         | RedHat      |



# Infrastructure As a Code

| Name                                                         | Date | GitHub stars | Company   | Language |
| ------------------------------------------------------------ | ---- | ------------ | --------- | -------- |
| [Saltstack](https://github.com/saltstack/salt)               | 2011 | 9.2          | SaltStack | Python   |
| [Cloudformation](https://aws.amazon.com/about-aws/whats-new/2011/02/25/introducing-aws-cloudformation/) | 2011 | n/a          | Amazon    | n/a      |
| [Terraform](https://github.com/hashicorp/terraform)          | 2014 | 14.3         | Hashicorp | Go       |


# CI/CD



## Framework

| Name                                                         | Date | Github star | Company     | Language     |
| ------------------------------------------------------------ | ---- | ----------- | ----------- | ------------ |
| [Jenkins](https://jenkins.io/)                               | 2011 | 11.5        |             | Java         |
| [GitLab](https://about.gitlab.com/)                          | 2011 | 21.3        | GitLab      | Ruby         |
| [Travis CI](https://travis-ci.org/)                          | 2011 | 7.1         | Open Source | Ruby         |
| [Circle CI](https://circleci.com/)                           | 2011 | n/a         |             | Clojure/Ruby |
| [Drone](https://drone.io/)                                   | 2014 | 16.1        | Drone       | Go           |
| [GoCD](https://www.gocd.org/)                                | 2014 | 4.5         | Open Source | Java         |
| [Spinnaker](https://www.spinnaker.io/)                       | 2015 | 5.3         | Spinnaker   | Python       |
| [Argo](https://argoproj.github.io/)                          | 2017 | 1.8         |             | Go           |
| [Skaffold](https://github.com/GoogleContainerTools/skaffold) | 2018 | 5.2         | Google      | Go           |
| [Jenkins X](https://jenkins.io/projects/jenkins-x/)          | 2018 | 1.8         | Jenkins     | Go           |



## Code analysis

| Name                                    | Date | GitHub star | Company | Language   |
| --------------------------------------- | ---- | ----------- | ------- | ---------- |
| [SonarQube](https://www.sonarqube.org/) | 2008 | 3.0         |         | Java       |
| [Codacy](https://www.codacy.com/)       | 2012 | n/a         |         | Scala/Ruby |




# Multi Cloud

## Control Plane

| Name                                                     | Year | GitHub star | Company                                                      | Language |
| -------------------------------------------------------- | ---- | ----------- | ------------------------------------------------------------ | -------- |
| [Crossplane](https://github.com/crossplaneio/crossplane) | 2018 | 0.6         | [Upbound](https://blog.upbound.io/introducing-crossplane-open-source-multicloud-control-plane/) | Go       |

## Application Platform

| Name                                          | Year | Company            |
| --------------------------------------------- | ---- | ------------------ |
| [CloudFoundry](https://www.cloudfoundry.org/) |      | Cisco, Google, IBM |



# Organizations

| Name                                              | Date | Governs    | Founded                                                      | Mission |
| ------------------------------------------------- | ---- | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [CNCF](https://www.cncf.io/)                      | 2015 | Cloud      | Google, CoreOS, Mesosphere, Red Hat, Twitter, Huawei, Intel, [Cisco](https://en.wikipedia.org/wiki/Cisco), [IBM](https://en.wikipedia.org/wiki/IBM), [Docker](https://en.wikipedia.org/wiki/Docker_(software)), [Univa](https://en.wikipedia.org/wiki/Univa), and [VMware](https://en.wikipedia.org/wiki/VMware) | The Cloud Native Computing Foundation builds sustainable ecosystems and fosters a community around a constellation of high-quality projects that orchestrate containers as part of a microservices architecture. |
| [OpenContainers](https://www.opencontainers.org/) | 2015 | Containers | Docker                                                       | Promote a set of common, minimal, open standards and specifications around container technology. |



# Containers

## Framework

### Standard framework

| Name                                                   | Date | GitHub star | Company       | Language |
| ------------------------------------------------------ | ---- | ----------- | ------------- | -------- |
| [Docker](https://www.docker.com/)                      | 2013 | n/a         | Docker Inc.   | Go       |
| [rkt](https://github.com/rkt/rkt/)                     | 2014 | 8.3         | CoreOS/RedHat | Go       |
| [containerd](https://github.com/containerd/containerd) | 2017 | 3.3         | CNCF          | Go       |
| [cri-o](https://github.com/kubernetes-sigs/cri-o)      | 2017 | 1.4         | RedHat        | Go       |



### Runtime

| Name                                          | Date | GitHub star | Company                | Language | Description                      |
| --------------------------------------------- | ---- | ----------- | ---------------------- | -------- | -------------------------------- |
| [runc](https://blog.docker.com/2015/06/runc/) | 2015 | 5.1         | Docker/OpenCountainers | Go       |                                  |
| [runv](https://github.com/hyperhq/runv)       | 2015 | 0.6         | HyperHQ                | Go       | Hypervisor-based Runtime for OCI |
| [Railcar](https://github.com/oracle/railcar)  | 2017 | 0.7         | Oracle                 | Rust     |                                  |
| [Pouch](https://pouchcontainer.io/)           | 2018 | 3.5         | Alibaba                | Go       |                                  |
| [runq](https://github.com/gotoz/runq)         | 2018 | 0.4         | Open Source            | Go       | KVM/Qemu-based Runtime for OCI   |
| [crun](https://github.com/giuseppe/crun)      | 2018 | 0.03        | RedHat                 | C        | High perf runtime                |

​	


### CLI

| Name                                                   | Date | Company         |
| ------------------------------------------------------ | ---- | --------------- |
| [docker](https://github.com/docker/docker-ce)          | 2013 | Docker Inc.     |
| [crictl](https://github.com/kubernetes-sigs/cri-tools) | 2017 | Kubernetes SIGs |
| [podman](https://podman.io/)                           | 2018 | RedHat          |



### Sandbox containers

| Name                                       | Date | GitHub star | Company |
| ------------------------------------------ | ---- | ----------- | ------- |
| [gVisor](https://github.com/google/gvisor) | 2018 | 7.1         | Google  |



### Hypervisor based containers

| Name                                                 | Date | GitHub star | Company              |
| ---------------------------------------------------- | ---- | ----------- | -------------------- |
| [Hyper Container](https://hypercontainer.io/)        | 2015 |             | HyperHQ              |
| [Clear Container](https://clearlinux.org/containers) | 2015 |             | Intel                |
| [frakti](https://github.com/kubernetes/frakti)       | 2017 | 0.4         | Google               |
| [Kata](https://github.com/kata-containers/runtime)   | 2018 | 0.7         | OpenStack Foundation |



## Build

| Name                                                         | Date | GitHub star | Company                                   | Language | Description       |
| ------------------------------------------------------------ | ---- | ----------- | ----------------------------------------- | -------- | ----------------- |
| [Docker](https://www.docker.com/)                            | 2013 | n/a         | Docker Inc.                               |          |                   |
| [Packer](https://www.packer.io/)                             | 2013 | 8.1         | Hashicorp                                 | Go       |                   |
| [Box](https://box-builder.github.io/box/)                    | 2016 | 0.2         | Open Source                               | Go       |                   |
| [Buildah](https://buildah.io/)                               | 2017 | 1.0         | RedHat                                    | Go       |                   |
| [Buildkit](https://blog.mobyproject.org/introducing-buildkit-17e056cc5317) | 2017 | 0.7         | Moby                                      | Go       |                   |
| [Jib](https://github.com/GoogleContainerTools/jib)           | 2018 | 4.9         | Google                                    | Java     | Containerize Java |
| [Img](https://blog.jessfraz.com/post/building-container-images-securely-on-kubernetes/) | 2018 | 1.9         | [GenuineTools](https://genuinetools.org/) | Go       |                   |
| [Kaniko](https://github.com/GoogleContainerTools/kaniko)     | 2018 | 2.5         | Google                                    | Go       |                   |
| [Makisu](https://github.com/uber/makisu)                     | 2018 | 0.8         | Uber                                      | Go       |                   |




## Orchestration

| Name                                                  | Date | GitHub star | Company     | Language |
| ----------------------------------------------------- | ---- | ----------- | ----------- | -------- |
| [Apache Mesos](http://mesos.apache.org/)              | 2009 | 3.9         | UC Berkeley | C++      |
| [Kubernetes](https://kubernetes.io/)                  | 2014 | 43.6        | Google      | Go       |
| [Portainer](https://portainer.io/)                    | 2014 | 9.8         | Open Source | HTML     |
| [Nomad](https://www.nomadproject.io/)                 | 2015 | 3.9         | Hashicorp   | Go       |
| [Hyper.sh](https://hyper.sh/)                         | 2015 | 1.9         | Hyper       | Go       |
| [Docker Swarm](https://docs.docker.com/engine/swarm/) | 2016 | 5.3         | Docker Inc. | Go       |
| [Nelson](https://getnelson.io/)                       | 2017 | 0.2         | Verizon     | Scala    |
| [Titus](https://github.com/Netflix/titus)             | 2018 | 1.7         | Netflix     | Go       |

### Hosted

| Name                                                         | Year | Company   |
| ------------------------------------------------------------ | ---- | --------- |
| [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/) | 2015 | Google    |
| [Elastic Container Service](https://aws.amazon.com/ecs/)     | 2015 | Amazon    |
| [Azure Container Service](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft.acs) | 2015 | Microsoft |
| [OpenShift Container Platform](https://www.openshift.com/products/container-platform/) | 2016 | RedHat    |
| [Azure Kubernetes Service](https://azure.microsoft.com/en-gb/services/kubernetes-service/) | 2017 | Microsoft |
| [Elastic Kubernetes Service](https://aws.amazon.com/eks/)    | 2018 | Amazon    |




## Registry

| Name                                                         | Year | GitHub | Company     | Language |
| ------------------------------------------------------------ | ---- | ------ | ----------- | -------- |
| [JFrog Artifactory](https://jfrog.com/)                      | 2008 |        |             | Java/Go  |
| [GitLab](https://about.gitlab.com/)                          | 2011 | 21.4   | GitLab HQ   | Ruby     |
| [Docker Registry](https://docs.docker.com/registry/)         | 2013 |        | Docker Inc. |          |
| [Harbor](https://github.com/goharbor)                        | 2016 | 6.2    | Harbor      | Go       |
| [Nexus Repository OSS](https://www.sonatype.com/nexus-repository-oss) | 2016 |        | Sonatype    |          |



### Hosted

| Name                                                         | Year | Company |
| ------------------------------------------------------------ | ---- | ------- |
| [Quay](https://quay.io/)                                     | 2013 | CoreOS  |
| [Container Registry](https://cloud.google.com/container-registry/) | 2014 | Google  |
| [Elastic Container Registry](https://aws.amazon.com/ecr/)    | 2015 | Amazon  |
| [Azure Container Registry](https://azure.microsoft.com/en-gb/services/container-registry/) |      | Azure   |
| [RedHat Container Catalog](https://access.redhat.com/containers/) |      | RedHat  |



# Kubernetes

## Kubernetes installation

| Name                                                         | Date | GitHub star | Company     | Language | Support                    |
| ------------------------------------------------------------ | ---- | ----------- | ----------- | -------- | -------------------------- |
| [Kupespray](https://github.com/kubernetes-incubator/kubespray) | 2015 | 4.4         | Open Source | Python   | AWS, GCE, Azure, OpenStack |
| [KOPS](https://github.com/kubernetes/kops)                   | 2016 | 7.0         | Google      | Go       | AWS                        |
| [kube-aws](https://github.com/kubernetes-incubator/kube-aws) | 2016 | 0.8         | CoreOS      | Go       | Declarative K8s on AWS     |
| [Kismatic](https://github.com/apprenda/kismatic)             | 2016 | 0.7         | Apprenda    | Go       |                            |
| [RKE](https://github.com/rancher/rke)                        | 2017 | 0.8         | Rancher     | Go       | On premise, AWS, GCE       |
| [kubeadm](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/) | 2017 |             | Google      | Go       |                            |
| [Pharos](https://www.kontena.io/pharos/)                     | 2018 | 0.1         | Kontena     | Ruby     |                            |

## Controllers

| Name                                                         | Year | GitHub star | Company     | Language |                                |
| ------------------------------------------------------------ | ---- | ----------- | ----------- | -------- | ------------------------------ |
| [Compose](https://github.com/docker/compose-on-kubernetes)   | 2018 | 0.4         | Docker Inc. | Go       | Manage K8s with docker-compose |
| [AWS ALB  Ingress](https://github.com/kubernetes-sigs/aws-alb-ingress-controller) | 2017 | 0.7         | Kubernetes  | Go       |                                |



# Microservice ecosystem

## Service Mesh

### Control plane

| Name                                              | Year | GitHub star | Company                                                      | Language | Description                |
| ------------------------------------------------- | ---- | ----------- | ------------------------------------------------------------ | -------- | -------------------------- |
| [Synapse](https://github.com/airbnb/synapse)      | 2012 | 1.9         | AirBnB                                                       | Ruby     | Service Discovery          |
| [Consul](https://www.consul.io)                   | 2014 | 14.0        | Hashicorp                                                    | Go       | Service Discovery          |
| [Linkerd](https://linkerd.io/)                    | 2016 | 4.7         | [Buoyant](https://buoyant.io)                                | Scala    |                            |
| [Istio](https://istio.io/)                        | 2017 | 12.7        | [Google](https://www.google.com/)/[IBM](https://www.ibm.com)/[Lyft](https://www.lyft.com/) | Go       |                            |
| [Linkerd2](https://github.com/linkerd/linkerd2)   | 2018 | 2.8         | [Buoyant](https://buoyant.io)                                | Go       | Ex-Conduit                 |
| [SuperGloo](https://github.com/solo-io/supergloo) | 2018 | 0.1         | [Solo](https://www.solo.io/)                                 | Go       | Service Mesh Orchestration |




### Data plane

| Name                                                  | Year | GitHub star | Company                       | Language |
| ----------------------------------------------------- | ---- | ----------- | ----------------------------- | -------- |
| [Linkerd](https://linkerd.io/)                        | 2016 | 4.7         | [Buoyant](https://buoyant.io) | Scala    |
| [Envoy](https://www.envoyproxy.io/)                   | 2016 | 7.0         | [Lyft](https://www.lyft.com/) | C++      |
| [Linkerd2](https://github.com/linkerd/linkerd2-proxy) | 2018 | 2.8         | [Buoyant](https://buoyant.io) | Rust     |



### HTTP Tester

| Name                                     | Year | GitHub star | Language |
| ---------------------------------------- | ---- | ----------- | -------- |
| [Siege](https://github.com/JoeDog/siege) | 2015 | 2.9         | C        |
| [Fortio](https://fortio.org/)            | 2017 | 0.5         | Go       |




## Serverless

| Name                                       | Year | GitHub star | Company                             | Language |
| ------------------------------------------ | ---- | ----------- | ----------------------------------- | -------- |
| [Fission](https://fission.io/)             | 2016 | 3.8         | Platform9                           | Go       |
| [Iron](https://www.iron.io/)               | 2016 | 2.4         | Iron                                | Go       |
| [Nuclio](https://nuclio.io/)               | 2018 | 2.3         | [Iguazio](https://www.iguazio.com/) | Go       |
| [OpenWhisk](https://openwhisk.apache.org/) | 2018 | 3.6         | Apache                              | Scala    |


### Hosted

| Name                                                         | Year | Company |
| ------------------------------------------------------------ | ---- | ------- |
| [Lambda](https://aws.amazon.com/about-aws/whats-new/2014/11/13/introducing-aws-lambda/) | 2014 | Amazon  |
| [Azure Functions](https://azure.microsoft.com/en-gb/resources/videos/build-2016-introducing-azure-functions/) | 2016 | Azure   |
| [Google Cloud Functions](https://cloud.google.com/functions/docs/release-notes) | 2017 | Google  |




## Package management

| Name                                             | Year | GitHub star | Company                        | Language | Description   |
| ------------------------------------------------ | ---- | ----------- | ------------------------------ | -------- | ------------- |
| [Helm](https://helm.sh/)                         | 2015 | 8.2         | [Deis](https://deis.com/)/CNCF | Go       |               |
| [Weave Flux](https://github.com/weaveworks/flux) | 2016 | 1.4         | Weave Works                    | Go       |               |
| [Forge](https://github.com/datawire/forge)       | 2017 | 0.3         | DataWire                       | Python   |               |
| [CNAB](https://cnab.io/)                         | 2018 | n/a         | Docker Inc.                    | n/a      | Specification |
| [Docker App](https://github.com/docker/app)      | 2018 | 0.9         | Docker Inc.                    | Go       | CNAB support  |



## Controller frameworks

| Name                                                         | Year | GitHub star | Company | Language |
| ------------------------------------------------------------ | ---- | ----------- | ------- | -------- |
| [Operator](https://github.com/operator-framework/operator-sdk) | 2018 | 1.1         | RedHat  | Go       |
| [KubeBuilder](https://github.com/kubernetes-sigs/kubebuilder) | 2018 | 0.8         | Google  | Go       |



## Network

### DNS

| Name                                                         | Year | GitHub star | Company                                                      | Language | Desciption            |
| ------------------------------------------------------------ | ---- | ----------- | ------------------------------------------------------------ | -------- | --------------------- |
| [CoreDNS](https://coredns.io/)                               | 2016 | 2.7         | [Open Source](https://miek.nl/2016/march/18/announcing-coredns/)/CNCF | Go       |                       |

### Networking

| Name                                                         | Year | GitHub | Company           | Language |
| ------------------------------------------------------------ | ---- | ------ | ----------------- | -------- |
| [Weave Net](https://www.weave.works/oss/net/)                | 2014 | 5.3    | Weave Works       | Go       |
| [Flannel](https://github.com/coreos/flannel)                 | 2014 | 3.7    | CoreOS            | Go       |
| [Romana](https://github.com/romana/romana)                   | 2016 | 0.2    | Open Source       | Go       |
| [Cilium](https://cilium.io/)                                 | 2017 | 3.2    | Isovalent Inc.    | Go       |
| [Calico](https://www.projectcalico.org/)                     | 2017 | 0.8    | Open Source       | Go       |
| [kube-router](https://github.com/cloudnativelabs/kube-router) | 2017 | 0.9    | Cloud Native Labs | Go       |




## Ingress controllers
| Name                                                         | Year | GitHub star | Company                            | Language | Desciption                                                   |
| ------------------------------------------------------------ | ---- | ----------- | ---------------------------------- | -------- | ------------------------------------------------------------ |
| [Kong](https://konghq.com/)                                  | 2015 | 19.0        | Kong                               | Lua      |                                                              |
| [Traefik](https://traefik.io/)                               | 2016 | 18.2        | [Containous](https://containo.us/) | Go       | Commercial support                                           |
| [Ingress Nginx](https://kubernetes.github.io/ingress-nginx/) | 2016 | 3.2         | Google                             | Go       |                                                              |
| [Nginx Ingress](https://github.com/nginxinc/kubernetes-ingress) | 2016 | 1.1         | Nginx                              | Go       | [Differences](https://github.com/nginxinc/kubernetes-ingress/blob/master/docs/nginx-ingress-controllers.md) |
| [Contour](https://heptio.com/products/#heptio-contour)       | 2017 | 1.1         | Heptio                             | Go       | Ingress for Envoy                                            |
| [Cert Manager](https://github.com/jetstack/cert-manager)     | 2017 | 2.2         | JetStack                           | Go       |                                                              |
| [BIG-IP Controller](https://clouddocs.f5.com/products/connectors/k8s-bigip-ctlr/v1.7/) | 2017 | 0.0         | F5                                 | Go       | [kubernetes.io](https://kubernetes.io/docs/concepts/services-networking/ingress/) |
| [Istio Gateway](https://istio.io/docs/tasks/traffic-management/ingress/) | 2017 | 13.0        | Google/IBM/Lyft                    | Go       | kubernetes.io                                                |
| [HAProxy](https://github.com/jcmoraisjr/haproxy-ingress)     | 2017 | 0.3         | Open Source                        | Go       | kubernetes.io                                                |
| [Ambassador](https://www.getambassador.io/)                  | 2017 | 1.3         | DataWire                           | Python   |                                                              |
| [Gimbal](https://heptio.com/products/#heptio-gimbal)         | 2018 | 0.4         | Heptio                             | Go       |                                                              |
| [Kong Ingress](https://konghq.com/blog/kubernetes-ingress-controller-for-kong/) | 2018 | 0.2         | Kong                               | Go       | [kubernetes.io](https://kubernetes.io/docs/concepts/services-networking/ingress/) |




## Cluster/Resilience

| Name                                            | Year | GitHub star | Company     | Language |
| ----------------------------------------------- | ---- | ----------- | ----------- | -------- |
| [Ark](https://github.com/heptio/ark)            | 2017 | 1.6         | Heptio      | Go       |
| [ChaosCube](https://github.com/linki/chaoskube) | 2017 | 0.4         | Open Source | Go       |



## Backup

| Name                                 | Year | GitHub star | Company | Language |
| ------------------------------------ | ---- | ----------- | ------- | -------- |
| [Ark](https://github.com/heptio/ark) | 2017 | 1.6         | Heptio  | Go       |



## Compliance/Governance

| Name                                                     | Year | GitHub star | Company     | Language |
| -------------------------------------------------------- | ---- | ----------- | ----------- | -------- |
| [Notary](https://github.com/theupdateframework/notary)   | 2015 | 1.6         |             | Go       |
| [Cloud Custodian](https://cloudcustodian.io/)            | 2016 | 1.8         | Open Source | Python   |
| [Sonobuoy](https://heptio.com/products/#heptio-sonobuoy) | 2018 | 1.0         | Heptio      | Go       |



## Security

| Name                                              | Year | GitHub star | Company   | Language | Description                  |
| ------------------------------------------------- | ---- | ----------- | --------- | -------- | ---------------------------- |
| [TUF](https://theupdateframework.github.io/)      | 2010 | 0.8         | n/a       | n/a      | Specification/CNCF           |
| [Vault](https://www.vaultproject.io/)             | 2015 | 10.5        | HashiCorp | Go       |                              |
| [Clair](https://coreos.com/clair/docs/latest/)    | 2016 | 4.4         | CoreOS    | Go       |                              |
| [Anchore](https://anchore.com/)                   | 2016 | 0.3         | Anchore   | Python   |                              |
| [kube2iam](https://github.com/jtblin/kube2iam) | 2016 | 0.9    |        | Go |Per Pod AWS policy|
| [Sysdig Falco](https://sysdig.com/opensource/falco/) | 2016 | 0.0 | Sysdig | C++ ||
| [Spiffe](https://spiffe.io/)                      | 2017 | 0.3         |           | Go       | Specification                |
| [Guard](https://github.com/appscode/guard)        | 2017 | 0.2         | Appscode  | Go       | K8s auth via Google & GitHub |
| [kubeaudit](https://github.com/Shopify/kubeaudit) | 2017 | 0.2         | Shopify   | Go       |                              |
| [kiam](https://github.com/uswitch/kiam)        | 2017 | 0.3    |        | Go |Per Pod AWS policy|



## Observability

### Debugger

| Name                                                     | Year | GitHub star | Company                      | Language |
| -------------------------------------------------------- | ---- | ----------- | ---------------------------- | -------- |
| [Squash](https://github.com/solo-io/squash)              | 2017 | 0.7         | [Solo](https://www.solo.io/) | Go       |
| [Sysdig Inspect](https://sysdig.com/opensource/inspect/) | 2017 | 0.5         | Sysdig                       | JS       |
| [KubeSquash](https://github.com/solo-io/kubesquash)      | 2018 | 0.1         | [Solo](https://www.solo.io/) | Go       |




### Tracer

| Name                                  | Year | GitHub star | Company  | Language |
| ------------------------------------- | ---- | ----------- | -------- | -------- |
| [NewRelic](https://newrelic.com/)     | 2008 | n/a | NewRelic |          |
| [Sentry](https://github.com/getsentry/sentry) | 2010 | 19.0 | Sentry | Python |
| [DataDog](https://www.datadoghq.com/) | 2010 | n/a | DataDog  | Go       |
| [Opentracing](https://opentracing.io) | 2016 | n/a         | CNCF     | Various |
| [OpenCensus](https://opencensus.io/) | 2017 | n/a | Google | Various |
| [Rookout](https://www.rookout.com/solution/microservices/) | 2018 | n/a | Rookout |  |




### Processor

| Name                                   | Year | GitHub star | Company  | Language |
| -------------------------------------- | ---- | ----------- | -------- | -------- |
| [NewRelic](https://newrelic.com/)      | 2008 | n/a         | NewRelic |          |
| [DataDog](https://www.datadoghq.com/)  | 2010 | n/a         | DataDog  | Go       |
| [Zipkin](https://zipkin.io/)           | 2016 | 9.6         | Twitter  | Go       |
| [Jaeger](https://www.jaegertracing.io) | 2017 | 6.2         | Uber     | Go       |



### Prometheus exporters

| Name                                                         | Year | GitHub star | Support  |
| ------------------------------------------------------------ | ---- | ----------- | -------- |
| [ElasticSearch exporter](https://github.com/justwatchcom/elasticsearch_exporter) | 2015 | 0.4         | ES       |
| [BlackBox](https://github.com/prometheus/blackbox_exporter)  | 2016 | 0.8         | TCP/HTTP |




## Metric collecting agents

| Name                                                         | Year | GitHub star | Company     | Language          |
| ------------------------------------------------------------ | ---- | ----------- | ----------- | ----------------- |
| [CollectD](https://collectd.org/)                            | 2005 | 2.0         | Open Source | C                 |
| [Riemann](http://riemann.io/)                                | 2012 | 3.6         | Open Source | Clojure           |
| [StatsD](https://github.com/etsy/statsd)                     | 2012 | 13.4        | Etsy        | Javascript/NodeJS |
| [Netdata](https://my-netdata.io/)                            | 2013 | 33.0        |             | C                 |
| [OSQuery](https://osquery.io/)                               | 2014 | 13.3        | Facebook    | C++               |
| [Note Exporter](https://github.com/prometheus/node_exporter) | 2014 | 2.1         | Prometheus  | Go                |
| [Kube State Metrics](https://github.com/kubernetes/kube-state-metrics) | 2016 | 0.9         | Google      | Go                |




## Logging

| Name                                                       | Year | GitHub star | Company       | Language | Description                      |
| ---------------------------------------------------------- | ---- | ----------- | ------------- | -------- | -------------------------------- |
| [Fluentd](https://www.fluentd.org/)                        | 2011 | 6.8         | Treasure Data | C, Ruby  | Log collecting                   |
| [Logstash](https://www.elastic.co/products/logstash)       | 2013 | 9.5         | ElasticCo     | Ruby     | Log collecting                   |
| [FluentBit](https://fluentbit.io/)                         | 2015 | 0.9         | CNCF          | C        | Log collecting                   |
| [Filebeat](https://www.elastic.co/products/beats/filebeat) | 2015 | n/a         | ElasticCo     | Go       | Log collecting                   |
| [Zap](https://github.com/uber-go/zap)                      | 2017 | 5.5         | Uber          | Go       | High performance logging library |



## Notification

| Name                                                        | Year | GitHub star | Company    | Language |
| ----------------------------------------------------------- | ---- | ----------- | ---------- | -------- |
| [PagerDuty](https://www.pagerduty.com/)                     | 2009 |             | PagerDuty  |          |
| [Alert Manager](https://github.com/prometheus/alertmanager) | 2015 | 1.6         | Prometheus | Go       |



## Time Series Databases

| Name                                               | Year | GitHub star | Company     | Language |                     |
| -------------------------------------------------- | ---- | ----------- | ----------- | -------- | ------------------- |
| [Graphite](https://github.com/graphite-project)    | 2008 | 20.0        | Open Source | Python   |                     |
| [InfluxDB](https://github.com/influxdata/influxdb) | 2013 | 14.7        | InfluxData  | Go       |                     |
| [Prometheus](https://prometheus.io/)               | 2014 | 20.0        | CNCF        | Go       |                     |
| [Timescale](https://www.timescale.com/)            | 2017 | 6.2         | Timescale   | C        | Postgres extension  |
| [Thanos](https://github.com/improbable-eng/thanos) | 2018 | 2.2         | Improbable  | Go       | Scalable Prometheus |
| [Cortex](https://www.weave.works/oss/cortex/)      | 2018 | 0.7         | Weave       | Go       | Scalable Prometheus |
| [M3](https://eng.uber.com/m3/)                     | 2018 | 1.2         | Uber        | Go       | Scalable Prometheus |



## Data visualization / Dashboard

| Name                                                   | Year | GitHub | Company        | Language   |
| ------------------------------------------------------ | ---- | ------ | -------------- | ---------- |
| [Graphite](https://github.com/graphite-project)        | 2008 | 20.0   | Open Source    | Python     |
| [Sysdig Monitor](https://sysdig.com/products/monitor/) | 2014 | 5.4    | Sysdig         | C++        |
| [Grafana](https://github.com/grafana/grafana)          | 2014 | 24.7   | Grafana Labs   | Typescript |
| [Weave Scope](https://www.weave.works/oss/scope/)      | 2015 | 3.0    | Weave Works    | Go         |
| [Cloudcraft](https://cloudcraft.co/)                   | 2016 | n/a    | Cloudcraft Inc | Service    |



## Persistent storage

| Name                     | Year | GitHub | Company | Language |
| ------------------------ | ---- | ------ | ------- | -------- |
| [Rook](https://rook.io/) | 2016 | 4.1    | Upbound | Go       |



## SQL Database

| Name                                          | Year | GitHub | Company    | Language |                |
| --------------------------------------------- | ---- | ------ | ---------- | -------- | -------------- |
| [Patroni](https://github.com/zalando/patroni) | 2015 | 2.1    | Zalando    | Python   | HA Postgres    |
| [Vitess](https://vitess.io/)                  | 2015 | 7.0    | The Vitess | Go       | Scalable MySQL |
| [TIDB](https://github.com/pingcap/tidb)       | 2016 | 16.2   | PingCap    | Go       | Scalable MYSQL |



## Messaging

| Name                                      | Year | GitHub | Company     | Language |
| ----------------------------------------- | ---- | ------ | ----------- | -------- |
| [NATS](https://github.com/nats-io/gnatsd) | 2014 | 4.9    | Open Source | Go       |



## CLI

| Name                                        | Year | GitHub | Language | Description           |
| ------------------------------------------- | ---- | ------ | -------- | --------------------- |
| [stern](https://github.com/wercker/stern)   | 2016 | 1.4    | Go       | Multi-pod logs        |
| [kubens](https://github.com/ahmetb/kubectx) | 2017 | 2.9    | Shell    | set kubectl namespace |



# External Tools

| Name                                                         | Company |
| ------------------------------------------------------------ | ------- |
| [Kubernetes apps](https://docs.google.com/spreadsheets/d/1FCgqz1Ci7_VCz_wdh8vBitZ3giBtac_H8SBw4uxnrsE/edit?usp=drive_web) | Google  |
| [CNCF Landscape](https://landscape.cncf.io/)                 | CNCF    |
