# Nginx Helm Chart Deployment

This repository contains a Helm chart for deploying an Nginx web server on a Kubernetes cluster using Minikube. The project demonstrates various configurations and customizations with Kubernetes, showcasing foundational skills relevant to DevOps roles.

## Project Overview
The Helm chart enables a customizable Nginx deployment, allowing users to experiment with Kubernetes features such as labels, annotations, resource requests and limits, node affinity, tolerations, and environment variables.

## Key Features
- **Custom Environment Variables**: Configurable environment variables are passed into the deployment for dynamic behavior and flexible configurations.
- **Labels and Annotations**: Custom labels and annotations were added to pods for metadata and service discovery enhancements.
- **Node Affinity and Tolerations**: Demonstrates controlling pod scheduling based on node labels and toleration rules.
- **Resource Management and Probes**: Configured resource requests and limits, as well as liveness and readiness probes, to ensure efficient resource usage and robust health checks.

## Learning Objectives Achieved
- Deployed a working Nginx server using Helm and Kubernetes.
- Gained experience configuring and customizing Helm charts.
- Applied advanced Kubernetes features such as node affinity, tolerations, custom annotations, and resource constraints.

## Future Improvements
Potential next steps include integrating this setup into a CI/CD pipeline, exploring additional Kubernetes configurations, and optimizing the deployment further.
