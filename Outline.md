# Introduction 
## About the course
This course focuses on the skills and knowledge required to become a fully functioning Kubernetes Administrator. 

You’ll begin with basic administration tasks and understanding the capabilities that the Kubernetes platform provides. You’ll cover each segment of knowledge needed to fully administer everything you’ll need as a Kubernetes administrator.

You will learn foundational knowledge needed to install, configure and deploy applications in a Kubernetes cluster. First, you will learn about Kubernetes’ architecture, looking closely at each of the cluster’s components and their roles. Next, you will discover how to install and configure a Kubernetes cluster: you’ll look at how to perform installations on-premises with kubeadm, and in cloud scenarios such as Azure Kubernetes Services and Google Kubernetes Engine

You will gain the ability to deploy, manage, and troubleshoot container-based workloads in Kubernetes. First, you will learn how to use the Kubernetes API and API Server internals. Next, you will discover how to use labels, annotations, and namespaces to organize the largest workloads and how Kubernetes uses labels internally for its own operations.
Dives into the primary building block of Kubernetes-based applications: Controllers. In this course you will learn the critical skills for deploying and maintaining your self-healing applications in Kubernetes. The course covers Deployments, DaemonSets, StatefulSets, Jobs, and CronJobs.

You will take a deep dive into these cluster administration topics. First, you will learn how to configure persistent storage for your Pods. Next, you will explore using configuration as data to configure your Pod-based applications.

You will learn Kubernetes networking fundamentals and how to access applications deployed in your cluster. First, you will learn how the Kubernetes network model enables simple and consistent networking for applications and Services deployed in Kubernetes Clusters. Next, you will discover how to use Services for access to applications deployed in Kubernetes.

You’ll learn core cluster maintenance tasks such as etcd backup and restore operations, upgrading an existing Kubernetes Cluster, and facilitating for Worker Node maintenance and high availability cluster topologies. Next, you’ll discover how to quickly find and analyze performance monitoring and logging data in your cluster

You’ll explore Kubernetes security fundamentals, learning how authentication and authorization work to control access to the Kubernetes API. Then, you’ll learn how certificates are used in Kubernetes and how to create and manage certificates in your cluster. Next, you’ll learn how to create and manage kubeconfig files for accessing clusters and then configure cluster access for a new user.

You’ll learn how to install applications in Kubernetes with Helm version 3. First, you’ll learn how to build a Helm Chart. Next, you’ll explore how to customize it with Helm templates.

You’ll learn how to automate and control application deployments using the ArgoCD operator and complementary tools. First, you’ll discover how ArgoCD can be configured to automate a deployment using Git as a single source of truth

You’ll learn to use Lens as your central management tool for all your Kubernetes Clusters. First, you’ll explore what Lens is and how to install it. Next, you’ll discover how to integrate your existing Kubernetes Cluster with your Lens installation
Additionally, the content in this path aligns with the objectives for the Certified Kubernetes Administrator exam and can help you prepare for the test.

## Outcome 
You will explore how to interact with your cluster, deploying Pods, Services, and Deployments. When you’re finished with this course, you will have the skills and knowledge of Kubernetes needed to administer a Kubernetes cluster and deploy applications in Kubernetes.

You will explore how to create, manage, and maintain healthy container-based applications with the primary Kubernetes workload construct, the Pod. When you’re finished with this course, you will have the skills and knowledge of creating and maintaining container-based workloads in Kubernetes.

You will learn the critical skills for deploying and maintaining your self-healing applications in Kubernetes. The course covers Deployments, DaemonSets, StatefulSets, Jobs, and CronJobs. You’ll also learn how to select a Controller type for your workload, and how to deploy and maintain your container-based application in your Kubernetes cluster.

You will discover how Pod scheduling works and how to influence scheduling in your cluster. When you are finished with this course, you will have a foundational knowledge of storage and scheduling that will help you as you move forward to being a skilled Kubernetes cluster Administrator.

You will explore how to expose applications outside your cluster with Ingress using several different Ingress patterns. When you’re finished with this course, you will have the skills and knowledge of Kubernetes networking needed to configure and manage your cluster network and access to your Kubernetes based applications.

You’ll explore core tools and techniques for troubleshooting your cluster. When you’re finished with this course, you’ll have the skills and knowledge of maintaining, monitoring, and troubleshooting needed to operate and manage Kubernetes Clusters.

You’ll learn how to control access to the Kubernetes API with role based access controls. When you’re finished with this course you will have the skills needed to operate and manage security in Kubernetes clusters.

You’ll discover how to manage dependencies between charts and use a Helm repository. By the end of this course, you’ll be able to build your own Helm chart and install any application release in Kubernetes with Helm.

You’ll learn how ArgoCD and the Helm Operator can be combined to automate deployments for your applications configured as Helm charts. Finally, you’ll explore progressive deployments, and how to use Flagger to automate a canary deployment. When you’re finished with this course, you’ll have the requisite knowledge of GitOps workflows, and the technical skills needed to reliably automate continuous delivery of your applications.

You’ll learn how to deploy and monitor workloads to Kubernetes through Lens. When you’re finished with this course, you’ll have the skills and knowledge of managing Kubernetes clusters with Lens needed to control your entire Kubernetes estate through one single tool.

## Outline 

### Topic 1 - Kubernetes Installation and Configuration Fundamentals
-   Overview
-   Explore the Kubernetes Architecture
-   Installing and Configuring Kubernetes
-   Working with Your Kubernetes Cluster

### Topic 2 - Managing the Kubernetes API Server and Pods
-   Overview
-   Using the Kubernetes API
-   Managing Objects with Labels, Annotation and Namespace
-   Running and Managing Pods

### Topic 3 - Managing Kubernetes Controllers and Deployment
-   Overview
-   Using Controllers to Deploy Applications and Deployment
-   Basics
-   Maintaining Applications with Deployments
-   Deploying and Maintaining Applications with DaemonSets and Jobs

### Topic 4 - Configuring and Managing Kubernetes Storage and Scheduling
-   Overview
-   Configuring and Managing Storage in Kubernetes
-   Configuration as Data-Environment Variables, Secrets, ConfigMap

### Topic 5 - Configuring and Managing Kubernetes Networking Services, and Ingress
-   Overview
-   Kubernetes Networking Fundamentals
-   Configuring and Managing Application Access with Services
-   Configuring and Managing Application Access with Ingress

### Topic 6 - Maintaining, Monitoring and Troubleshooting Kubernetes
-   Overview
-   Maintaining Kubernetes Clusters
-   Logging and Monitoring in Kubernetes Clusters
-   Troubleshooting Kubernetes Clusters

### Topic 7 - Configuring and Managing Kubernetes Security
-   Overview
-   Kubernetes Security Fundamentals
-   Managing Certificates and kubeconfig Files
-   Managing Role Based Access Controls

### Topic 8 - Packaging Applications with Helm for Kubernetes
-   Overview
-   Introduction Helm
-   Discovering Helm
-   Installing a Local Kubernetes Cluster with Helm
-   Building Helm Charts
-   Customizing Charts with Helm Templates
-   Managing Dependencies
-   Using Existing Helm Chart

### Topic 9 - Automating Kubernetes Deployments Using a GitOps Workflow
-   Overview
-   Understanding the Challenges of Automating Deployments
-   Using the GitOps Approach for Automating Deployments
-   Configuring ArgoCD for Automated Deployments
-   Automating Packaged Releases with the Helm Operator

### Topic 10 - Istio Service Mesh 

-   Overview
-   Introducing Istio
-   Traffic Management With Istio
-   Managing Service Traffic
-   Securing Communication with Mutual TLS
-   Observing the Service Network
-   Running Istio in Production


### Topic 11 - Managing Kubernetes Clusters with Lens
-   Overview
-   Managing Kubernetes Clusters with Lens
-   Adding Kubernetes Clusters to Lens
-   Deploying and Managing Workloads through Lens

### Bonus Section 

- Introduction SealSecret 
- Play With Cert Manager 
- Creating quickly kubernetes with KinD
- Management Cluster With K9s
.... 