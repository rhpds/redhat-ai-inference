# Module 02 — Evaluate and Benchmark Model Performance with EvalHub

### Brief Overview

With a model deployed, attendees need to measure how well it performs before exposing it to consumers. This module introduces EvalHub, a feature of Red Hat AI Enterprise for running evaluations against deployed models. Attendees run benchmark evaluations, analyze the results, and configure a repeatable evaluation workflow that can track performance over time.

### Audience and Time

- **Personas:** AI engineers, platform engineers, AI operations teams
- **Prerequisites:** Module 01 completed (model deployed and serving inference requests)
- **Duration:** 20 min

### Learning Objectives

- Analyze model inference performance using EvalHub for evaluations
- Configure a repeatable evaluation workflow for tracking model performance over time

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Explore EvalHub in the Red Hat AI Enterprise console | 3 min |
| 2 | Run a benchmark evaluation against the deployed model | 7 min |
| 3 | Analyze evaluation results | 5 min |
| 4 | Configure a repeatable evaluation workflow | 5 min |

### Detailed Steps

1. Navigate to EvalHub within the Red Hat AI Enterprise console.
2. Review the available evaluation types and benchmark datasets.
3. Select the deployed model as the evaluation target.
4. Choose a benchmark dataset and configure evaluation parameters.
5. Run the benchmark evaluation against the deployed model.
6. Wait for the evaluation run to complete.
7. Analyze the evaluation results: review latency, throughput, and quality metrics.
8. Compare results against baseline thresholds.
9. Configure a repeatable evaluation workflow by saving the evaluation configuration.
10. Verify that the saved workflow can be triggered again to track performance changes over time.

### Key Takeaways

- EvalHub provides a structured way to benchmark and evaluate model inference performance directly within Red Hat AI Enterprise.
- Evaluation results surface latency, throughput, and quality metrics that inform serving decisions.
- A repeatable evaluation workflow enables teams to track model performance over time as configurations or models change.

### Infrastructure Notes

- EvalHub must be available in the Red Hat AI Enterprise environment.
- The benchmark dataset used for evaluation is pre-loaded in the environment.
