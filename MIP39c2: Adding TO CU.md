# MIP39c2: Adding TechOps Core Unit

## Preamble

```
MIP39c2-SP#: #21
Author(s): @eskp
Contributors:
Status:
Date Applied: <yyyy-mm-dd>
Date Ratified: <yyyy-mm-dd>
```

## Sentence Summary

MIP39c2-SP21 adds TechOps Core Unit to handle all of the System Adminstration and Technical Support needs of Maker Protocol and its Core Units.

## Paragraph Summary

Striving to improve communication and collaboration between the developers, end users and other stakeholders by applying DevOps principles to software delivery and first class technical support. Getting things done safer and faster in an automated and repeatable way with the help from some of the modern Infrastructure Administration tools. While continuously monitoring and improving the process throughout.

## Specification

### Motivation

TechOps Core Unit (TO CU) is passionately supporting secure, reliable and transparent infrastructure in order to continue and improve Maker DAO’s collaboration, agility and resilience. Stakeholders in the Maker Ecosystem, such as existing CUs and new participants, know that they can rely on an experienced TO CU to set up and securely maintain their infrastructure.

### Mission

Provide technical support services to MakerDAO Ecosystem stakeholders and liaison with external service providers; while ensuring the effectiveness, reliability and security of the MakerDAO infrastructure layer.

### Vision

TO CU is a team of passionate professionals with quality first attitude, extensive experience in the Maker Ecosystem and a heavy interest in the always developing Web3 space.

The infrastructure we deliver is reinforced by:

- *Reliability* - Secure and reliable operations, resulting in high service availability, robust monitoring and regular safe deployments
- *Support* - 24/7 detection and incident response with high level of redundancy between critical components and the team members
- *Transparency* - Accessibility and transparency to other CUs and the DAO community. With the stakeholders mentioned above, regularly informed about the state of the infrastructure, its cost structure and the tradeoffs involved

TO CU closely collaborates with the stakeholders of the Maker Ecosystem, facilitating:

- *Education* - TO CU properly educates other CUs about operational security best practices and regularly reviews them for improvements
- *Point of contact* - TO CU facilitates incident response and acts as a first line of support for external security researchers and Maker Ecosystem participants
- *Integration* - New participants in Maker Ecosystem and 3rd party integrators can access and reuse infrastructure scripts and recipes from the service catalogue created and maintained by TO CU

### Core Unit Name

TechOps Core Unit

### Proposed Core Unit Facilitator(s)

@eskp and @dizzy

### Core Unit Team

#### Core Unit Facilitator(s) - 2

- Communications with Governance and Community
- Agile workload management
- Managing budget and business strategy
- 24 hour availability due to time zones coverage
- No single point of failure

#### Engineering - currently 5

Will be looking to hire another 2 Techops Engineers in the near future.

#### Account manager / project manager

Will be looking to hire in the near future. The main objective is to relieve the Facilitators.

### Core Unit Mandate (Responsibilities)

#### Maker Protocol Focus

- Infrastructure hosting and collaboration with other CUs

  - *Protocol Engineering CU* for Eth nodes provisioning, administration and monitoring
  - *Oracle CU* for Administration, Monitoring and new Collateral onboarding
  - *DUX CU* - hosting of the Governance portal
  - Other critical Maker protocol components such as various *Keepers*

- Infrastructure Monitoring & Alerts

  - Dashboards, response to alerts and Reports

- Development & QA

  - Infrastructure design, CI/CD pipelines, staging environments

- Technical Support

  - Support other CUs with setting up accounts, helping with infrastructure setup and configuration, security best practices education, and so on
  - 24/7 follow the sun support, assessment and remediation

- Tools administration

  - 3rd party services administration and management

#### General System Administration

- Documentation

- Cloud providers management

  - Multiple cloud providers to prevent lock-in, add pricing options and introduce fault tolerance. Automated with Terraform.

- Network & Security

  - VPC and Firewall management

- Load balancing

  - Dynamic upstreams/certificates automation

- Testing (services and infrastructure)

- Database administration

- Secrets and service credentials management

- Backups & Restore

  - Database
  - Stateful services filesystem
  - Regular automated restore tests of the backups


#### DevOps Services

- Infrastructure as Code Automation

  * Cloud Environment provisioning with [Terraform](https://www.terraform.io/)
  * Cost management & Optimizations

- Source control and artifacts management

  * Github repositories
  * Docker repositories

- CI/CD - Setting up automated delivery and testing pipelines to deploy Maker services to various environments with confidence

  * Github Actions and other systems

- Monitoring, Metrics & Alerts

  * Various server metrics
  * Service availability and performance

- Log Aggregation

  - Centralize log data storage for easy developer access, analysis and optional alerting

- Knowledge Sharing and Training

  * Expected to be continuously learning
  * Provide environment for safe experimentation
  * Regular knowledge sharing presentations within the team and outside

#### Research & Development

- Eth2 nodes administration
- Container orchestration on Kubernetes
- Chaos Engineering implementation
- Mapping and establishing SLIs and SLOs (SLOs are a tool to help determine what engineering work to prioritize. Striking the right balance between investing in functionality that will win new customers or retain current ones, versus investing in the reliability and scalability that will keep those customers happy.)