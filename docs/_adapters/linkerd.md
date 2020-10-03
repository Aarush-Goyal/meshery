---
layout: page
title: Linkerd Adapter
name: Meshery Adapter for Linkerd
mesh_name: Linkerd
version: v2.5.0
port: 10001/tcp
project_status: stable
github_link: https://github.com/layer5io/meshery-linkerd
image: /docs/assets/img/service-meshes/linkerd.svg
---
# {{ page.name }}

| Service Mesh   | Adapter Status | Latest Supported Mesh Version |
| :------------: | :------------:   | :------------:              |
| {{page.title}} | [{{ page.project_status }}]({{ page.github_link }}) | {{page.version}}  |

### Lifecycle management

The {{page.name}} can install **{{page.version}}** of {{page.mesh_name}}. A number of sample applications can be installed using the {{page.name}}.

### Features
1. Lifecycle management of {{page.mesh_name}}
1. Lifecycle management of sample applications
1. Performance testing

### Sample Applications

The {{ page.name }} includes a handful of sample applications. Use Meshery to deploy any of these sample applications.

- [Emojivoto](https://github.com/BuoyantIO/emojivoto)
    - A microservice application that allows users to vote for their favorite emoji, and tracks votes received on a leaderboard.

- [Istio Bookinfo](https://github.com/istio/istio/tree/master/samples/bookinfo) 
    - This application is a polyglot composition of microservices are written in different languages and sample BookInfo application displays information about a book, similar to a single catalog entry of an online book store.

- [Linkerd Books](https://github.com/BuoyantIO/booksapp)
    - Application that helps you manage your bookshelf.

- [HTTPbin](https://httpbin.org/)
    - A simple HTTP Request & Response Service.

Identify overhead involved in running {{page.mesh_name}}, various {{page.mesh_name}} configurations while running different workloads and on different infrastructure. The adapter facilitates data plane and control plane performance testing.

1. Prometheus integration
1. Grafana integration

The [Meshery adapter for Linkerd]({{ page.github_link }}) will connect to Linkerd's Prometheus and Grafana instances running in the control plane.
