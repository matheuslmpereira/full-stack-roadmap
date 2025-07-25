# DevOps & Infrastructure Roadmap

## 1. Foundations

* Linux fundamentals

  * File system, permissions, processes
  * Systemd and init systems
* Networking basics

  * IP addressing
  * DNS, DHCP
  * TCP, UDP, ICMP
  * NAT, firewalls
* Shell scripting

  * Bash
  * Command-line tools (grep, awk, sed, etc.)
* Version control

  * Git fundamentals
  * GitOps basics

---

## 2. Containerization

* Docker

  * Images, containers, volumes, networks
  * Dockerfiles and multi-stage builds
* Container Orchestration

  * Kubernetes

    * Pods, deployments, services
    * ConfigMaps and secrets
    * Helm
    * Operators
  * Docker Compose

---

## 3. CI/CD

* Pipelines

  * YAML-based definitions
  * Build/test/deploy stages
* Tools

  * GitHub Actions
  * GitLab CI/CD
  * Jenkins / CircleCI / ArgoCD
* Strategies

  * Rolling deployments
  * Blue/green deployments
  * Canary releases

---

## 4. Infrastructure as Code (IaC)

* Terraform

  * Providers and modules
  * State management
  * Workspaces and variables
* Alternatives

  * Pulumi
  * AWS CDK
* Configuration Management

  * Ansible
  * Chef / Puppet (legacy)

---

## 5. Cloud Platforms

* Core services across providers (AWS, GCP, Azure)

  * Compute (EC2, GCE, Azure VMs)
  * Storage (S3, Blob, GCS)
  * Networking (VPC, subnets, load balancers)
  * IAM (roles, policies)
* Serverless

  * AWS Lambda / GCP Functions / Azure Functions
  * Event-driven architecture basics

---

## 6. Observability

* Monitoring

  * Prometheus
  * Cloud-native metrics (CloudWatch, Stackdriver)
* Logging

  * ELK Stack (Elasticsearch, Logstash, Kibana)
  * Loki / Fluent Bit / Vector
* Alerting

  * Alertmanager
  * Opsgenie / PagerDuty / Grafana Alerts

---

## 7. Security

* Secrets management

  * HashiCorp Vault
  * AWS Secrets Manager / GCP Secret Manager
* Network security

  * Firewalls
  * Zero-trust architecture basics
* Infrastructure hardening

  * CIS benchmarks
  * SSH best practices

---

## 8. Reliability Engineering

* SLOs and SLIs
* Chaos Engineering
* Load testing and stress tools (k6, JMeter)
* Incident response

  * Runbooks
  * Postmortems
