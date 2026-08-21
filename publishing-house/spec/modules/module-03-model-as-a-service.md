# Module 03 — Expose the Model as a Model-as-a-Service

### Brief Overview

A deployed model that only one team can reach is not enough for production use. This module walks attendees through configuring the deployed model as a Model-as-a-Service (MaaS), making it available for shared, scalable consumption across teams and applications. Attendees configure access controls, API endpoints, and scaling policies to prepare the model for broader use.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Module 01 completed (model deployed); Module 02 completed (model evaluated)
- **Duration:** 20 min

### Learning Objectives

- Configure a deployed model as a Model-as-a-Service for shared, scalable consumption
- Manage access controls and API endpoint configuration for the model service

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Review the Model-as-a-Service approach | 3 min |
| 2 | Configure the model as a shared service | 7 min |
| 3 | Configure access controls and API endpoints | 5 min |
| 4 | Configure scaling policies | 5 min |

### Detailed Steps

1. Navigate to the model serving configuration for the deployed model.
2. Review the Model-as-a-Service approach and how it differs from a single-team deployment.
3. Configure the model as a shared service by exposing it through a stable API endpoint.
4. Configure access controls to define which users and teams can consume the model service.
5. Generate or retrieve API credentials for consuming the service.
6. Configure scaling policies to handle multiple concurrent consumers.
7. Verify the API endpoint is externally reachable.
8. Send a test inference request through the MaaS endpoint to confirm the service is operational.

### Key Takeaways

- Model-as-a-Service transforms a single-team model deployment into a shared, scalable resource available across the organization.
- Access controls and API credentials govern who can consume the model service.
- Scaling policies ensure the service can handle concurrent requests from multiple consumers.

### Infrastructure Notes

- The MaaS endpoint must be externally accessible from the application deployed in Module 04.
- Scaling configuration set here carries forward to the monitoring module.
