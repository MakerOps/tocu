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

Striving to improve communication and collaboration between the developers, end users and other professionals (that is all participants creating a product or system, not just Dev and Ops teams) by applying DevOps principles. Getting things done faster - in an automated and repeatable way with the help from some of the modern System Administration tools. While continuously monitoring and improving the process throughout.

## Specification

### Motivation

What is different about DevOps?
1. IT industry evolved - added complexity and fragility
2. Ops recognition of Agile - applying Software Engineering practices to manage infrastructure
3. The tools and technologies that have become available as a result of the above and their fairly complex implementation


### Core Unit Name

TechOps Core Unit

### Proposed Core Unit Facilitator(s)

@eskp and @dizzy

### Core Unit Team

#### Core Unit Facilitator(s) - 2

- Communications with Governance and Community
- Agile workload management
- Managing budget and business strategy
- 24 hour availability due to time zone coverage
- No single point of failure

#### Engineering - currently 5

Will be looking to hire another Techops Engineer in the near future. #TODO Include this in the budget.

#### Account manager / project manager

Will be looking to hire in the near future - can be quite junior. The main objective is to relieve the Facilitators.


### Core Unit Mandate (Responsibilities)

#### Specific to Maker Protocol

- Collaborate with Protocol Engineering CU for Eth nodes provisioning, administration and monitoring

- Collaborate with Oracle CU for Administration, Monitoring and new Collateral onboarding

- 3rd party services built on Maker protocol provisioning and administration

- ...

- TODO the below are general Sysadmin tasks - relate back to MakerDAO specific tasks more

#### System Administration

- Documentation

- Cloud providers management

Multiple cloud providers to prevent lock-in, add pricing options and introduce fault tolerance.
Automated with Terraform.

- Network & Security

VPC and Firewall management.

- Load balancing

Dynamic upstreams/certificates automation.

- Testing (services and infrastructure)

- Database management

- Secrets and service credentials management

- Backups & Restore

* Database
* Stateful services filesystem
* Regular automated restore tests of the backups



#### DevOps Services

- Infrastructure as Code Automation

* Cloud Environment provisioning with [Terraform](https://www.terraform.io/)
* Cost management & Optimizations

- Source control and artifacts management

* Github repositories
* Docker repositories

- CI/CD - Services Deployment Automation

* Github Actions and other systems

Setting up automated delivery and testing pipelines to deploy Maker services to various environments with confidence.

- Monitoring, Metrics & Alerts
* Various Hosts' metrics
* Service availability

24/7 response due to geographical distribution of Engineers.

- Log Aggregation
Centralize log data storage for easy developer access, analysis and optional alerting.

- Knowledge Sharing and Training

* Expected to be continuously learning
* Provide environment for safe experimentation
* Attend conferences + budget for training
* Presentations within the team


#### Technical Support

Provide technical support to the Core Units in the Maker DAO with setting up accounts, helping with infrastructure setup and configuration, answering security questions, and so on. 


#### Research & Development

- Eth2 nodes administration
- Container orchestration on Kubernetes
- Chaos Engineering implementation
- Mapping and establishing SLIs and SLOs
SLOs are a tool to help determine what engineering work to prioritize. Striking the right balance between investing in functionality that will win new customers or retain current ones, versus investing in the reliability and scalability that will keep those customers happy.