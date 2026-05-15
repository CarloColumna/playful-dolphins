---
title: "How to Scale Your Pods Based on HTTP Traffic"
description: "KEDA in Kubernetes Part 3/3 — Scale HTTP workloads to and from zero using the KEDA HTTP Add-on on Amazon EKS, covering three real-world ingress scenarios."
publishedAt: 2023-08-12
tags: ["kubernetes", "autoscaling", "keda", "cloud-native", "aws"]
externalUrl: "https://medium.com/@carlocolumna/how-to-scale-your-pods-based-on-http-traffic-d58221d5e7f1"
draft: false
---

# How to Scale Your Pods Based on HTTP Traffic (KEDA Part 3/3)

The final part of the KEDA series covers scaling Kubernetes workloads to and from zero based on live HTTP traffic using the KEDA HTTP Add-on on Amazon EKS. Three scenarios are covered: ClusterIP-only access, Ingress + NGINX controller, and cross-namespace routing using an ExternalName Service.
