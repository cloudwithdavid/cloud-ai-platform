# Roadmap

## 1. Application & Local AI

- [ ] Select the application use case and define its core workflows.
- [ ] Build a Python/FastAPI application with a suitable database.
- [ ] Implement API endpoints, data operations, and automated tests.
- [ ] Integrate the OpenAI Responses API with validated structured outputs, timeouts, retries, and error handling.
- [ ] Validate the complete application locally.

## 2. Cloud & DevOps

- [ ] Design and deploy the application on AWS with HTTPS, private networking, and appropriate access controls.
- [ ] Integrate Amazon Bedrock and validate the application's AI functionality.
- [ ] Provision infrastructure with Terraform using Amazon S3 for remote state, versioning, encryption, and state locking.
- [ ] Containerize the application with Docker and publish images to Amazon ECR.
- [ ] Deploy with Amazon ECS on AWS Fargate, including health checks, rolling updates, and appropriate scaling.
- [ ] Implement GitHub Actions CI/CD for automated testing, container builds, Trivy security scanning, and deployment.
- [ ] Implement IAM least privilege, AWS Secrets Manager, and secure workload access.
- [ ] Instrument the application with OpenTelemetry and integrate Amazon CloudWatch and AWS X-Ray for logs, metrics, and tracing.
- [ ] Use GitHub MCP and AWS MCP to inspect deployments, investigate failures, and review infrastructure and operational telemetry.
- [ ] Validate AI-assisted engineering findings and actions against actual infrastructure and operational evidence.
- [ ] Test application resilience, deployment failures, infrastructure recovery, and operational troubleshooting.
- [ ] Validate infrastructure reproducibility, teardown, and cost controls.

## 3. Cloud AI Systems

- [ ] Extend the application with document-grounded RAG using Amazon Bedrock Knowledge Bases.
- [ ] Implement 3–4 meaningful tool actions with appropriate validation and error handling.
- [ ] Establish secure access to data and enforce permissions across retrieval, model interactions, and tool execution.
- [ ] Implement Amazon Bedrock Guardrails and validate safety controls.
- [ ] Extend tracing across model interactions, retrieval, and tool execution.
- [ ] Evaluate retrieval quality, tool behavior, task outcomes, and relevant failure cases.

## 4. Platform as Code

- [ ] Identify reusable infrastructure patterns and extract configurable Terraform modules.
- [ ] Define application-specific configuration and isolate resources, permissions, and Terraform state as appropriate.
- [ ] Develop reusable GitHub Actions workflows for infrastructure provisioning and application deployment.
- [ ] Implement AWS OIDC authentication, validation, deployment approvals, and standardized security controls.
- [ ] Enable self-service deployment through predefined application and environment inputs.
- [ ] Standardize appropriate logging, monitoring, health checks, and cost controls.
- [ ] Create an Agent Skill for repeatable deployment preflight checks where useful.
- [ ] Build and deploy a second minimal AI application using the same infrastructure and deployment workflow.
- [ ] Validate repeatability, application isolation, failure handling, recovery, and teardown.
- [ ] Document architectural decisions, tradeoffs, operational evidence, and demonstrated reuse.