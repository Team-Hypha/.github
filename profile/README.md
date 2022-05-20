# Hypha

## What is Hypha?
Hypha is an open-source observability framework that makes debugging distributed systems easier by correlating logs and traces and combining them in a single tool.
Hypha automates the set up of distributed tracing, aggregation of existing logs, and deployment of a telemetry pipeline to handle all of the data.

![Hypha architecture diagram](https://github.com/Team-Hypha/hypha-website/blob/main/src/images/architecture/Hypha-Architecture.jpg)

Hypha's simple yet powerful UI allows users to move between logs and traces, giving them both the high-level context of traces and detailed view of logs in the same tool.

![Screenshot of Hypha's UI showing traces and logs](https://github.com/Team-Hypha/hypha-website/blob/main/src/images/screenshots/trace-and-logs.png)

## Learn more
[Read the case study](httsp://teamhypha.com/case-study) to learn more.

## Hypha Components:
1. The [Hypha Backend](https://github.com/Team-Hypha/hypha-backend) allows users to deploy backend compnents to AWS Elastic Container Service or via Docker Compose.
2. The [Hypha Agent](https://github.com/Team-Hypha/hypha-agent) sets up instrumentation for tracing, log aggregation, and emits telemetry to the backend.
3. The [Hypha UI](https://github.com/Team-Hypha/hypha-ui) wraps Grafana to give a simple, focused entry point for users.
