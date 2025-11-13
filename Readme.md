# Quarkus Petoboto

A sample quarkus application demonstrating "enterprise-grade" features and configuration scenarios.

The domain is a simple pet center, the goal is to help you get your project working with Quarkus and AWS.

## Full-stack Reference Implementation

Provide a realistic reference implementation for a modern application operation, including stateful components ("shopping cart"), user interface, backend framework, cloud deployment, and so on.

## Multi-module

The organization is composed of several modules ("management", "adoption", "medical", "shipping", ...) developed independently.

- svc-index: Facade frontend Renarde app service served at /
- svc-mgmt: Management frontend Vaadin app service served at /app/mgmt
- mod-core: Shared entities and configuration
- cdk-infra: Cloud deployment using AWS CDK for Java

## Authentication

- Cross-module seamless single sign-on

- Integrate with Google Sign In and other identity providers.

- Integrate with Amazon Cognito Federated User Pools

- Integrate with AWS Application Load Balancer

- Integrate with custom corporate users table

- Logout

## Authorization

- Define and assign custom roles per-module

## Frontend Integration

Demonstrate integration with popular UI frameworks.

- Renarde, Roq, Vaadin (first)
- JSF, React, ... (later)

## Infrastructure as code

Automated deployment with AWS CDK for Java
