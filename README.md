# awesome-kubernetes
A collection of tools for [Kubernetes](https://kubernetes.io/).

## Table Of Contents
* [Tools](#tools)
* [Peformance](#performance)
* [Tutorials](#tutorials)
* [More Resources](#more-resources)

## Tools
* [Kubernetes Auto-Ingress](https://github.com/hxquangnhat/kubernetes-auto-ingress) - Dynamically create an ingress for an associated service for Kubernetes, works with NGNIX ingress controller.
* [Kubernetes LEMP Stack](https://github.com/chepurko/k8s-lemp) - Kubernetes LEMP Stack is a distributed LEMP stack built on top of a Kubernetes cluster. It enables anyone to deploy multiple CMSs (currently WordPress) for any number of websites. We built it to be secure and very fast by default.
* [NGNIX WordPress Docker](https://github.com/raulr/nginx-wordpress-docker) - The official WordPress image has a PHP-FPM variant, but it still needs a web server to handle HTTP requests. This image provides an Nginx server ready to use as a wordpress:fpm front-end.
* [Minikube](https://github.com/kubernetes/minikube) - Minikube is a tool that makes it easy to run Kubernetes locally. Minikube runs a single-node Kubernetes cluster inside a VM on your laptop for users looking to try out Kubernetes or develop with it day-to-day.
* [Kube Lego](https://github.com/jetstack/kube-lego) - Kube Lego automatically requests certificates for Kubernetes Ingress resources from Let's Encrypt.
* [ExternalDNS](https://github.com/kubernetes-incubator/external-dns) - ExternalDNS synchronizes exposed Kubernetes Services and Ingresses with DNS providers.
* [Kubespray Wrapper](https://github.com/kubespray/kubespray-cli) - Easy to use command line tool for kubernetes deployment with kubespray.
* [Kubespray](https://github.com/kubernetes-incubator/kubespray) - Setup a kubernetes cluster.
* [Cluster capacity analysis framework](https://github.com/kubernetes-incubator/cluster-capacity) - Cluster capacity analysis.
* [Kubeadm](https://github.com/kubernetes/kubeadm) - Kubernetes installation with kubeadm really simplifies deployment procedure and it is easy to use.
* [Kubernetes Elasticsearch Cluster](https://github.com/pires/kubernetes-elasticsearch-cluster) - Elasticsearch cluster on top of Kubernetes made easy.
* [Spread](https://github.com/redspread/spread) - Spread is a command line tool that makes it easy to version Kubernetes clusters, deploy to Kubernetes clusters in one command, and set up a local Kubernetes cluster.
* [Teresa](https://github.com/luizalabs/teresa-api) - Teresa is an extremely simple platform as a service that runs on top of Kubernetes.The API needs a database backend and access to Amazon S3 for storage.
* [Kube Latency](https://github.com/simonswine/kube-latency) - This is a simple little tool, that helps to measure bandwidth and latency in a kubernetes Pod Network.
* [Kubernetes Vault Integration](https://github.com/Boostport/kubernetes-vault) - The Kubernetes-Vault project allows pods to automatically receive a Vault token using Vault's AppRole auth backend.
* [K8sec](https://github.com/dtan4/k8sec) - CLI tool to manage Kubernetes Secrets easily.
* [Redis Cluster on Kubernetes](https://github.com/sobotklp/kubernetes-redis-cluster) - This k8s module is intended to simplify the creation and operation of a Redis Cluster deployment in Kubernetes.https://logz.io/blog/prometheus-monitoring/
* [KubeNow](https://github.com/kubenow/KubeNow) - KubeNow is a cloud agnostic platform for microservices, based on Docker and Kubernetes. Other than lighting-fast Kubernetes operations, KubeNow helps you in lifting your final application configuring DNS records and distributed storage.
* [NGINX for Kubernetes Reloaded](https://github.com/rosskukulinski/nginx-kubernetes-reload) - Containerized NGINX that watches for configuration file changes from Kubernetes Secrets or ConfigMaps.
* [Kubernetes Dashboard](https://github.com/kubernetes/dashboard) - General-purpose web UI for Kubernetes clusters.
* [Reference doc of hyperkube](https://github.com/fdebonneval/docker8s) - Reference doc of hyperkube.
* [mobydig](https://github.com/fdebonneval/mobydig) - Image to run Sysdig on Docker for mac (but not only, it should work on a docker engine on a linux host) #Why ? Why a particular image for Docker for mac ? Sysdig provides a Docker image to run sysdig/csysdig on Docker but on a Linux host.
* [Quartermaster](https://github.com/coreos/quartermaster) - Quartermaster is a framework for managing containerized storage systems like Ceph, GlusterFS, NFS-Ganesha, Rook and others on top of Kubernetes. 

## Performance
* [Prometheus on Kubernetes](https://github.com/grobie/prometheus-on-kubernetes) - An example setup of Prometheus inside of Kubernetes, monitoring the Kubernetes infrastructure itself as well as services running in Kubernetes.
* [Prometheus Monitoring with Grafana](https://logz.io/blog/prometheus-monitoring/) - The combination of Prometheus and Grafana is becoming a more and more common monitoring stack used by DevOps teams for storing and visualizing time series data. 
* [Varnish exporter for Prometheus](https://github.com/jonnenauha/prometheus_varnish_exporter) - Scrapes the varnishstat -j JSON output on each Prometheus collect and exposes all reported metrics.
* [Prometheus metric library for Nginx](https://github.com/knyar/nginx-lua-prometheus) - This is a Lua library that can be used with Nginx to keep track of metrics and expose them on a separate web page to be pulled by Prometheus.
* [Cluster-level Kubernetes Logging with Honeycomb](https://github.com/honeycombio/honeycomb-kubernetes-agent) - Honeycomb's Kubernetes agent aggregates logs across a Kubernetes cluster. Stop managing log storage in all your clusters and start tracking down real problems.
* [Estafette Cloudflare DNS](https://github.com/estafette/estafette-cloudflare-dns) - This small Kubernetes application configures dns and proxy settings in Cloudflare for any public service with the correct annotations.

## Tutorials
* [Kubernetes Nginx Ingress controller](https://crondev.com/kubernetes-nginx-ingress-controller/) - Ingress is the built‑in Kubernetes load‑balancing framework for HTTP traffic. With Ingress, you control the routing of external traffic.
* [Kubernetes installation with kubeadm](https://crondev.com/kubernetes-installation-kubeadm/) - Please note that kubeadm is still in Alpha and not ready for production use, but it is good enough to play with on development environments.
* [Kubernetes upgrade – kubeadm](https://crondev.com/kubernetes-upgrade-kubeadm/) - Kubeadm is still in beta, but if you already deployed a Kubernetes cluster on some environment using it and now want to upgrade, you can do that manually.
* [Distributed Load Testing Using Kubernetes](https://cloud.google.com/solutions/distributed-load-testing-using-kubernetes) - Load testing is key to the development of any backend infrastructure because load tests demonstrate how well the system functions when faced with real-world demands.
* [Monitoring Your Kubernetes Infrastructure With Prometheus](https://www.weave.works/blog/monitoring-kubernetes-infrastructure/) - Monitoring Your Kubernetes Infrastructure With Prometheus.
* [Code Cooking: Kubernetes](https://medium.com/google-cloud/code-cooking-kubernetes-e715728a578c) - Using Google CDN with Kubernetes.
* [WordPress in Kubernetes: The Perfect Setup](https://sysdig.com/blog/wordpress-kubernetes-perfect-setup/) -This tutorial shows how to prepare and deploy WordPress with all required dependencies (MySQL, etc) in Kubernetes.
* [Sysdig Install: Kubernetes](https://support.sysdig.com/hc/en-us/articles/206770633-Sysdig-Install-Kubernetes-) - Sysdig Monitor is the first and only monitoring, alerting, and troubleshooting solution designed from the ground up to provide unprecedented visibility into containerized infrastructures.
* [How to monitor Nginx on Kubernetes](https://sysdig.com/blog/monitor-nginx-kubernetes/) - In this article we are going to show how to monitor Nginx on Kubernetes, describing different use cases, peculiarities of running on this platform, relevant metrics and dashboards.

## More Resources
* [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - You can find more awesome resources for Kubernetes here.
