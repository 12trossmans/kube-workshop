# Kubernetes Workshop

This is a hands-on, technical workshop intended to get comfortable working with Kubernetes and deploying & configuring applications. It should hopefully take roughly 5~6 hours. This workshop is intended partial as a companion to this [Kubernetes Technical Primer](https://github.com/benc-uk/kube-primer) which can be read or used to get an initial grounding on the concepts.

This workshop is very much designed for software engineers & developers with little or zero Kubernetes experience, but wish to get hands on and learn how to deploy and manage applications. It is not focused on the adminstration, network configuration & day-2 operations of Kubernetes itself, so some aspects may not be relevant to dedicated platform/infrastructure engineers.

The application used will be one that has already been written and built, so no application code will need to be written.

The workshop will use Azure Kubernetes Service (AKS) and assumes a relative degree of comfort in using Azure for sections 2 and 3.

Sections / modules:

- [⚒️ Workshop Pre Requisites](00-pre-reqs/readme.md) - Covering the pre set up and tools that will be needed.
- [🚦 Deploying Kubernetes](01-cluster/readme.md) - Deploying AKS, setting up kubectl and accessing the cluster.
- [📦 Container Registry & Images](02-container-registry/readme.md) - Deploying the registry and importing images.
- [❇️ Overview Of The Application](03-the-application/readme.md) - Details of the application to be deployed.
- [🚀 Deploying The Backend](04-deployment/readme.md) - Laying down the first two components and introduction to Deployments and Pods.
- [🌐 Basic Networking](05-network-basics/readme.md) - Introducing Services to provide network access.
- [💻 Adding The Frontend](06-frontend/readme.md) - Deploying the frontend to the app and wiring it up.
- [✨ Improving The Deployment](07-improvements/readme.md) - Adding resource limits, probes and secrets.
- [🌎 Ingress & Helm](08-helm-ingress/readme.md) - Finalizing the application using ingress.
- [🤯 Stretch & Bonus Topics](09-extra-advanced/readme.md) - Bonus advanced topics, stretch goals and other exercises.
