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
- [ ] Deploy to Amazon EKS with Kubernetes, including health probes, rolling updates, and scaling.
- [ ] Implement GitHub Actions CI/CD for automated testing, container builds, Trivy security scanning, and deployment.
- [ ] Implement IAM least privilege, AWS Secrets Manager, and secure workload access.
- [ ] Instrument the application with OpenTelemetry and integrate Amazon CloudWatch and AWS X-Ray for logs, metrics, and distributed tracing.
- [ ] Test application resilience, deployment failures, infrastructure recovery, and operational troubleshooting.
- [ ] Validate infrastructure reproducibility, teardown, and cost controls.

## 3. AI-Augmented DevOps

- [ ] Use GitHub MCP to inspect GitHub Actions workflows, investigate failures, and review deployments.
- [ ] Use AWS MCP to inspect cloud resources, query telemetry, and assist troubleshooting.
- [ ] Create an Agent Skill for repeatable deployment preflight checks.
- [ ] Validate AI-assisted findings and actions against actual infrastructure and operational evidence.

## 4. Cloud AI Systems

- [ ] Extend the application with document-grounded RAG using Amazon Bedrock Knowledge Bases.
- [ ] Implement application-facing MCP tool integrations, evaluating AgentCore Runtime and Gateway for the required architecture.
- [ ] Establish secure access to data and enforce permissions across retrieval, model interactions, and tool execution.
- [ ] Implement Amazon Bedrock Guardrails and validate safety controls.
- [ ] Extend distributed tracing across