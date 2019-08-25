---
layout: post
title: OpenShift Cluster – How to Drain or Evacuate a Node for Maintenance
subtitle: OpenShift Notes for Cluster Admins
tags: openshift, Kubernetes, docker
image: "img/openshift-cluster-how-to-drain-or-evacuate-a-node-for-maintenance.jpg"
bigimg: "/img/openshift-cluster-how-to-drain-or-evacuate-a-node-for-maintenance.jpg"
show-avatar: false
---

As we know OpenShift clusters are bundled with multiple compute nodes, master nodes, infra nodes etc, it’s not a big deal to manage node maintenance for OS patching kind of activities. But we need to ensure we have enough capacity on other nodes to balance the workload.

When there is a maintenance work – eg: Kernel patching – we need to exercise this without impacting those pods and application running on cluster.

**[See Full Article](https://www.techbeatly.com/2018/11/openshift-cluster-how-to-drain-or-evacuate-a-node-for-maintenance.html/)**
