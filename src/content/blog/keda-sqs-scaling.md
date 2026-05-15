---
title: "How to Scale Your Pods Based on a Queue"
description: "KEDA in Kubernetes Part 2/3 — Scale workloads in Amazon EKS based on an AWS SQS Queue using two IAM identity models: Pod Identity Owner and Operator Identity Owner."
publishedAt: 2023-06-26
tags: ["kubernetes", "autoscaling", "keda", "aws", "containers"]
externalUrl: "https://medium.com/@carlocolumna/keda-in-amazon-eks-part-2-scale-based-on-aws-sqs-queue-1dbd13fa5384"
draft: false
---

# How to Scale Your Pods Based on a Queue (KEDA Part 2/3)

This part of the series demonstrates scaling a Kubernetes workload in Amazon EKS based on the depth of an AWS SQS Queue. Two identity models are covered in depth — Pod Identity Owner and Operator Identity Owner — including their security tradeoffs, Terraform IAM setup, and live scaling tests.
