# From Model to Model as a Service: Building Scalable AI Inference

## Overview

AI platform setup doesn't stop with model deployment. Teams need to understand how a model performs, how that performance changes over time, and how to make the model reliably available to multiple users and applications.

In this hands-on lab, attendees take a model through the full serving lifecycle on Red Hat AI Enterprise. Starting with model deployment, they benchmark and evaluate inference performance, then expose the model through a Model-as-a-Service approach for shared, scalable consumption. From there, attendees connect the model to an application and see how serving, access, and usage come together in a production workflow.

## Target Audience

- **Role:** AI engineers, platform engineers, AI operations teams
- **Experience level:** Intermediate
- **What they already know:** Basic OpenShift/Kubernetes concepts, familiarity with AI model concepts (training vs. inference)
- **What they don't know:** How to move from a deployed model to a production-grade, shared AI service on Red Hat AI Enterprise

## Prerequisites

- Basic understanding of containers and Kubernetes/OpenShift
- Familiarity with generative AI model concepts (what a model is, what inference means)

## Learning Objectives

1. Deploy a model for inference on Red Hat AI Enterprise
2. Analyze model inference performance using EvalHub for evaluations
3. Configure a repeatable evaluation workflow for tracking model performance over time
4. Configure a deployed model as a Model-as-a-Service for shared, scalable consumption
5. Integrate a model service into an application using standard API patterns
6. Verify end-to-end request flow from application request to model response
7. Monitor model serving metrics through the observability dashboard

## Content Type

Lab (hands-on)

## Products & Technologies

- Red Hat AI Enterprise (includes OpenShift and OpenShift AI)

## Module Map

| Module | Title | Duration |
|--------|-------|----------|
| 1 | Deploy a Model on Red Hat AI Enterprise | 10 min |
| 2 | Evaluate and Benchmark Model Performance with EvalHub | 20 min |
| 3 | Expose the Model as a Model-as-a-Service | 20 min |
| 4 | Integrate the Model into an Application | 20 min |
| 5 | Validate the End-to-End Workflow | 20 min |
| 6 | Monitor Model Performance through Observability | 20 min |
| — | **Total hands-on** | **1 hour and 50 minutes** |
| — | Intro / presentation | ~10 min |
| — | **Total lab** | **~2 hours** |

## Difficulty Level

Intermediate

## Environment

**Learner view:** A Red Hat AI Enterprise environment. No models are pre-deployed — attendees start from scratch and build up through the serving lifecycle.

**Automation needed:** TBD — confirmed in infrastructure phase

## Infrastructure Requirements

- **Cloud provider:** CNV
- **Cluster type:** Multinode — 3 control plane (16 vCPU, 64GB RAM), 2 workers (16 vCPU, 64GB RAM, 100GB disk)
- **OCP version:** 4.22
- **Topology:** Per-student
- **Sizing:** 3 control plane nodes + 2 worker nodes + 1 GPU node (NVIDIA L40)
- **Automation approach:** GitOps (Helm + ArgoCD)
- **AI/MaaS:** GPU — attendees deploy and serve a model on-cluster; open-source model (TBD)
- **External services:** registry.redhat.io, quay.io
- **Non-GA products:** None (all products are GA)
