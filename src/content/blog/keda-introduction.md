---
title: "How to Level Up Your Kubernetes Scaling"
description: "KEDA in Kubernetes Part 1/3 — Why Horizontal Pod Autoscaler falls short, and how KEDA (Kubernetes Event-driven Autoscaling) solves scale-to-zero, event-based triggers, and the external metrics API limitation."
publishedAt: 2023-06-12
tags: ["kubernetes", "autoscaling", "keda", "aws", "containers"]
externalUrl: "https://medium.com/@carlocolumna/eda-in-amazon-eks-install-keda-82849cf31f01"
draft: false
---

# How to Level Up Your Kubernetes Scaling (KEDA Part 1/3)

This article explains the limitations of Kubernetes HPA (cannot scale to zero, limited to CPU/memory metrics, dependent on metric aggregators), introduces KEDA as the solution, and walks through installing KEDA on Amazon EKS using Helm and Terraform with IAM roles for service accounts.
