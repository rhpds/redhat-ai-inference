# Module 04 — Integrate the Model into an Application

### Brief Overview

With the model exposed as a service, attendees now connect it to a consuming application. This module demonstrates how to integrate the Model-as-a-Service endpoint into an application using standard API patterns. Attendees configure the application to call the model service, send requests, and observe responses flowing through the integration.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Module 03 completed (model exposed as a Model-as-a-Service with a reachable API endpoint)
- **Duration:** 20 min

### Learning Objectives

- Integrate a model service into an application using standard API patterns
- Configure application-side settings to consume the Model-as-a-Service endpoint

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Review the sample application | 3 min |
| 2 | Configure the application to use the model service | 7 min |
| 3 | Deploy the application | 5 min |
| 4 | Send requests and observe responses | 5 min |

### Detailed Steps

1. Review the sample application and its architecture.
2. Identify where the application makes inference calls.
3. Configure the application with the MaaS API endpoint URL.
4. Configure the application with the API credentials generated in Module 03.
5. Deploy the application to the OpenShift cluster.
6. Wait for the application pod to become ready.
7. Open the application interface.
8. Send a request through the application that triggers an inference call to the model service.
9. Observe the response returned from the model through the application interface.
10. Confirm that the application is successfully consuming the Model-as-a-Service endpoint.

### Key Takeaways

- Standard API patterns (REST/OpenAI-compatible endpoints) make model services consumable by any application without custom integration code.
- Application-side configuration requires the MaaS endpoint URL and valid API credentials.
- The integration pattern used here is reusable for connecting any application to a model service on Red Hat AI Enterprise.

### Infrastructure Notes

- A sample application is provided in the lab environment.
- The application must be deployed to the same cluster or have network access to the MaaS endpoint.
