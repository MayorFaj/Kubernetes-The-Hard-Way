# Kubernetes the hard way

**Diclaimer:** The following setup should be used for learning purpose only, and not to be considered for production. Kubernetes the hard way is optimized for learning, which means taking the long route to ensure eash task required to bootstrap a highly available Kubernetes cluster is understood.

## **Tools**

- VM: AWS EC2
- OS: Ubuntu 20.04 lts+
- Docker Engine
- kubectl console utility
- cfssl and cfssljson utilities
- Kubernetes cluster

You will create 3 EC2 Instances, and in the end, we will have the following parts of the cluster properly configured:

- Kubernetes Control Nodes
- Kubernetes Worker Nodes
- Configured SSL/TLS certificates for Kubernetes components to communicate securely
- Configured Node Network
- Configured Pod Network

## **Labs**

- [Installing Client tools](./docs/01-Installing%20client%20tools)

- [Provisioning Compute Resources](./docs/02-Provisioning%20compute%20resources)

- [Preparing self-signed CA and Generating TLS Certificates](./docs/03-Preparing%20a%20self-signed%20CA%20and%20Generating%20TLS%20Certificates)

- [Distributing the Client and Server Certificates](./docs/04-Distributing%20the%20client%20and%20server%20certificates)

- [Generating Kubernetes Configurations Files For Authentication](./docs/05-Generating%20kubernetes%20configuration%20files%20for%20authentication)

- [Preparing the ETCD Database For Encryption at Rest](./docs/06-Prepare%20the%20ETCD%20database%20for%20encryption%20at%20rest)

- [Bootstrapping The ETCD cluster](./docs/07-Bootstrapping%20the%20etcd%20cluster)

- [Bootstrapping The Control Plane](./docs/08-Bootstraping%20the%20control%20plane)

- [Boostraping Kubernetes Worker Node](./docs/09-Bootstrapping%20the%20kubernetes%20worker%20nodes)

- [Configuring Kubelet](./docs/10-Configuring%20kubelet)
