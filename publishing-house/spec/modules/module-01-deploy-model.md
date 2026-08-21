# Module 01 — Deploy a Model on Red Hat AI Enterprise

### Brief Overview

This module introduces the lab environment and walks attendees through deploying a model for inference on Red Hat AI Enterprise. Attendees select a model, configure a model server, and deploy it to the platform. By the end of this module, the model is running and ready to accept inference requests.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Basic OpenShift/Kubernetes concepts; familiarity with AI model concepts (training vs. inference)
- **Duration:** 10 min

### Learning Objectives

- Deploy a model for inference on Red Hat AI Enterprise
- Verify that the deployed model is running and accepting inference requests

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Explore the lab environment | 3 min |
| 2 | Deploy the model for inference | 5 min |
| 3 | Verify the deployment | 2 min |

### Detailed Steps

1. Log in to the Red Hat AI Enterprise console.
2. Navigate to the model serving area within OpenShift AI.
3. Review the available model server runtimes.
4. Select the model to deploy.
5. Configure the model server parameters (runtime, replicas, resource limits).
6. Deploy the model to the platform.
7. Observe the deployment status and wait for the model pod to become ready.
8. Send a test inference request to confirm the model is responding.

### Key Takeaways

- Red Hat AI Enterprise provides a streamlined workflow for deploying models to inference endpoints.
- A deployed model must be verified before it can be evaluated or exposed to consumers.
- Model server configuration (runtime, replicas, resource limits) determines how the model serves inference requests.

### Infrastructure Notes

- No models are pre-deployed; attendees deploy from scratch.
- The model and runtime used in this module carry forward to all subsequent modules.
