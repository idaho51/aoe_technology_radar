---
title:      "Docker"
ring:       scale
quadrant:   infrastructure-and-operational-technology

---

![state](./../assets/images/item_state_under_review.png)

## Why? ##

[Docker](https://www.docker.com/) is a technology to implement the [**infrastructure as code**](https://martinfowler.com/bliki/InfrastructureAsCode.html) principle.
It allows automated and reproducible builds and deployments. Automated deployments are a must have when migrating solutions to the cloud.

Docker is currently the most-used solution for creating and managing container-based infrastructures and deployments.

Essentially, Docker is a platform to build container images, distribute them and run them as an isolated process (using Linux kernel cgroups, network namespaces and custom mounts).

In a DevOps environment, this helps a lot as we can run the exact same software and runtime (such as PHP) on both production and locally while developing. This enables us to debug our software much easier.

Also, Docker allows us to keep our development setup much smaller and faster; instead of VirtualBox setups on a per-project base, we can compose our project development setup out of small containers. A CI environment building the containers allows us to package and test the whole environment instead of different software components on different runtimes in a much more stable way.

Backed by services such as [Kubernetes](https://kubernetes.io/), we can deploy Docker containers on a flexible infrastructure and enable our developers to test their software more easily in different environments.

Here at Haufe, we assess Docker in different projects to become more flexible and faster, which increases our focus on development of even better and more stable software.

## Our projects ##

- [Docker guidelines](https://haufe-lexware.gitbooks.io/haufe-group-docker-book-startup-guide/content/) - Thomas Schüring <thomas.schuering@haufe-lexware.com>

All application that run on AWS or Azure use docker. This is an incomplete list of projects.
- Foundation Services
- iDesk
- Panama
- OnBoarding App
and many more

## Contact ##

Thomas Schüring <thomas.schuering@haufe-lexware.com>

