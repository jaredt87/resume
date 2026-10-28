---
layout: cv
title: Jared Thomson's Resume
---
# __Jared Thomson__

<div id="webaddress">
<a href="mailto:jaredt37@gmail.com">Email</a>
| <a href="https://www.linkedin.com/in/jaredthomson1987/">LinkedIn</a>
| <a href="https://github.com/jaredt87">GitHub</a>
</div>

## Summary

Cloud and infrastructure engineer with a software engineering background. I build and support the systems that let development teams ship and operate software reliably, from cloud infrastructure and automation to internal platforms and access controls. Most of my work has been about making complicated systems easier to run, safer to change, and less dependent on manual work.

## Skills

- **Cloud and infrastructure:** AWS, GCP, Linux, EC2, S3, RDS, ECS, EKS, Redis
- **Infrastructure as code and automation:** Terraform, Puppet, Ansible, Semaphore, Docker
- **Programming and scripting:** Go, Python, Ruby, Java, PowerShell, Bash
- **CI/CD and testing:** GitHub Actions, CircleCI, Bamboo, Selenium, Capybara
- **Monitoring and logging:** Grafana, Prometheus, ELK, Datadog, Loggly
- **Data and application technologies:** PostgreSQL, MSSQL, MongoDB, GraphQL, Kafka

## Relevant Experience

`December 2020 - Present`
__BambooHR - Systems Engineer__

- Build and maintain cloud infrastructure and automation across AWS and GCP using Terraform, Puppet, and related tools.
- Architected and built a Go-based internal access platform to replace the old SSH and bastion workflow. It uses AWS Systems Manager, IAM, and Okta SSO to give engineers controlled access to infrastructure and services.
- Built access workflows across multiple AWS accounts, including database proxying and auditing, with a design that supports hundreds of users.
- Helped reduce infrastructure access costs by more than $100,000 per year.
- Co-architected an automated monthly patching system using Semaphore and Ansible. The workflow coordinates patching, uses Aptly snapshots, sequences tasks, and accounts for related RDS updates.
- Monitor and troubleshoot production systems using Grafana, ELK, Loggly, and Datadog.
- Work with developers and other teams to turn infrastructure needs into systems that are repeatable, supportable, and easier to operate.

`March 2020 - November 2020`
__O.C. Tanner - Software Engineer in Test__

- Built and maintained automated API and UI tests using Ruby and Capybara.
- Worked with ReactJS applications and services using GraphQL, Kafka, PaperTrail, and PostgreSQL.
- Worked on a Scrum team of 5-6 developers and coordinated test coverage as new code was checked in.
- Used Bamboo, Docker, and Puppet Bolt as part of the development and test workflow.

`May 2019 - March 2020`
__Solutionreach, Inc. - Software Development Engineer in Test__

- Designed and implemented UI tests using Java and Selenium.
- Worked with developers to keep test coverage aligned with new features and code changes.
- Used Bamboo, Docker, Git, and PostgreSQL in the build and test environment.

`September 2016 - May 2019`
__3M - DevOps Engineer__

- Supported nearly 3,000 virtual machines running on Hyper-V and vSphere.
- Built automation for software installation and configuration using Python, PowerShell, and AngularJS.
- Helped guide the architecture of installation and configuration automation for Health Information Systems software.
- Worked with developers and QA engineers across teams and locations to automate deployments and troubleshoot problems.
- Used MSSQL and MongoDB and coordinated work within a Scrum team.

`January 2016 - September 2016`
__Zions Bancorporation - Business Systems Analyst__

- Supported infrastructure and applications in production, staging, test, and disaster-recovery environments.
- Worked with business and technical teams to gather requirements, plan changes, test releases, and validate implementations.
- Troubleshot application issues and coordinated with vendors and internal teams to resolve incidents.
- Helped manage change requests, upgrades, and post-change validation.

`May 2015 - January 2016`
__Zions Bancorporation - Technical Support Specialist__

- Supported local and remote staff across Windows, Mac OS, mobile devices, browsers, networking, Citrix XenApp, and Active Directory.
- Investigated support issues, resolved problems, and explained solutions to users.
- Identified opportunities to coach users and improve support through calls, chats, tickets, and email.

## Selected Engineering Projects

**ackOS - [github.com/jaredt87/ackOS](https://github.com/jaredt87/ackOS)**

- Building an execution-control system that puts authorization, execution lifecycle, verification, recovery, and commit decisions in a clear boundary.
- Developed a plugin-host/provider architecture and typed Git read and write primitives.
- Focused on making changes against real repositories safely, including checking that the state being changed still matches the state that was authorized.

**Wingman - [github.com/jaredt87/wingman](https://github.com/jaredt87/wingman)**

- Building an AI engineering partner designed to work with a team's context and ways of working, rather than treating every request as a one-off prompt.
- Integrating Wingman with ackOS so infrastructure changes can be requested through an AI workflow while execution authority and verification stay in a separate control system.
- Working toward an end-to-end test against a real Terraform repository.

## Education

`2014 - 2019`
__University of Phoenix__

- Bachelor of Science in Information Technology
- Advanced Software Developer Certificate
- National Society of Collegiate Scholars

## Certifications and Training

- Kubernetes
- Git
- Python
- DevOps
- Software Quality Assurance
