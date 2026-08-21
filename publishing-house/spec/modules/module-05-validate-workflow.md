# Module 05 — Validate the End-to-End Workflow

### Brief Overview

The model is deployed, evaluated, exposed as a service, and connected to an application. This module brings those pieces together by validating the end-to-end request flow. Attendees trace a request from the application through the MaaS endpoint to the model and back, verifying that every component in the serving chain is functioning correctly.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Module 04 completed (application deployed and connected to the model service)
- **Duration:** 20 min

### Learning Objectives

- Verify end-to-end request flow from application request to model response
- Troubleshoot common issues in the serving chain between the application and the model

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Trace a request through the serving chain | 5 min |
| 2 | Verify each component in the workflow | 5 min |
| 3 | Troubleshoot a simulated failure | 5 min |
| 4 | Confirm end-to-end reliability | 5 min |

### Detailed Steps

1. Send a request from the application interface and note the response.
2. Trace the request path: application to MaaS endpoint to model server to model.
3. Inspect the application logs to confirm the outbound request was sent.
4. Inspect the model server logs to confirm the inference request was received and processed.
5. Verify the response returned through each layer matches expectations.
6. Introduce a simulated failure (for example, invalid credentials or an unreachable endpoint).
7. Observe the error behavior in the application and in the model server logs.
8. Troubleshoot the failure by identifying the broken component.
9. Restore the correct configuration.
10. Send another request and confirm end-to-end reliability is restored.

### Key Takeaways

- End-to-end validation confirms that deployment, serving, access control, and application integration are all working together.
- Tracing a request through the serving chain reveals where failures occur when something breaks.
- Structured troubleshooting (check logs at each layer) is essential for maintaining production AI services.

### Infrastructure Notes

- Attendees need access to application logs and model server logs.
- The simulated failure scenario must be reversible without disrupting the environment for subsequent modules.
