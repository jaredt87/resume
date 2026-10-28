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

Staff Systems Engineer focused on cloud platforms, infrastructure automation, secure access, and cost control. I design and build systems that make infrastructure safer to change and easier to operate, replacing manual work and one-off processes with repeatable platforms.

## Selected Impact

- Replaced legacy SSH, bastion, and third-party access workflows with a Go-based platform using AWS Systems Manager, IAM, and Okta SSO; estimated to reduce licensing costs by more than $100,000 per year.
- Built governed access workflows across multiple AWS accounts for infrastructure and databases, with auditing and a design that supports hundreds of users.
- Co-architected automated monthly patching and infrastructure image-build pipelines to make recurring maintenance more consistent and less manual.
- Helped teams move toward dynamic, self-service infrastructure patterns, including Cloudflare Workers routing and adoption by frontend engineers.

## Experience

`December 2020 - Present`
__BambooHR - Staff Systems Engineer__

- **Platform architecture and secure access:** Architected and built a Go-based internal access platform that replaced legacy SSH, bastion, and third-party tooling. Integrated AWS Systems Manager, IAM, and Okta SSO to provide governed access to infrastructure and services across multiple AWS accounts.
- **Security and auditability:** Built workflows for database proxying, role-based access, administrative escalation, and activity auditing. The platform supports access to services including EC2, RDS, ECS, EKS, and Redis, with a design built to support hundreds of users.
- **Cost reduction:** Helped eliminate more than $100,000 per year in estimated infrastructure-access licensing costs by replacing the previous access approach with an internally owned platform.
- **Operational automation:** Co-architected monthly patching with Semaphore and Ansible, including Aptly snapshots, task sequencing, and coordination with related RDS updates.
- **Repeatable infrastructure:** Built and improved Auto Scaling Group image-build pipelines and infrastructure automation, reducing reliance on manual, one-off operational steps.
- **Cloud edge and developer enablement:** Served as a Cloudflare Workers subject-matter resource. Helped shape URI-based routing through Cloudflare Load Balancers and Workers to regional services, and mentored frontend engineers adopting repository-based Workers workflows.
- **Cost and reliability operations:** Investigate infrastructure cost anomalies and work through the causes and fixes, alongside ongoing production monitoring and troubleshooting with Grafana, ELK, Loggly, and Datadog.
- **Technical leadership:** Guide architecture and implementation, break larger initiatives into workable engineering steps, and help teams move static infrastructure toward more dynamic, maintainable systems.

`March 2020 - November 2020`
__O.C. Tanner - Software Engineer in Test__

- Built and maintained API and UI test automation using Ruby and Capybara for applications backed by GraphQL, Kafka, and PostgreSQL.
- Worked with a 5–6 developer Scrum team to align test coverage with feature work and changes as code was checked in.
- Used Bamboo, Docker, and Puppet Bolt to support repeatable development and test workflows.

`May 2019 - March 2020`
__Solutionreach, Inc. - Software Development Engineer in Test__

- Built UI test automation using Java and Selenium, working with developers to keep coverage aligned with product changes.
- Supported build and test workflows using Bamboo, Docker, Git, and PostgreSQL.

`September 2016 - May 2019`
__3M - DevOps Engineer__

- Supported an environment of nearly 3,000 virtual machines running on Hyper-V and vSphere.
- Built software installation and configuration automation using Python, PowerShell, and AngularJS.
- Helped shape automation architecture for Health Information Systems software and worked across development and QA teams to improve deployment consistency and troubleshoot issues.

`January 2016 - September 2016`
__Zions Bancorporation - Business Systems Analyst__

- Supported production, staging, test, and disaster-recovery environments; coordinated requirements, releases, change requests, and post-change validation.
- Investigated application issues and worked with technical teams and vendors to resolve incidents.

`May 2015 - January 2016`
__Zions Bancorporation - Technical Support Specialist__

- Supported local and remote staff across Windows, Mac, mobile devices, networking, Citrix XenApp, and Active Directory.
- Diagnosed user issues, explained solutions clearly, and identified opportunities to improve support.

## Selected Projects

**ackOS** — [github.com/jaredt87/ackOS](https://github.com/jaredt87/ackOS)

Building a Go-based control kernel that separates authorization, execution, verification, recovery, and state commitment. The goal is to make automated changes safer by checking that the state being changed still matches the state that was authorized.

**Wingman** — [github.com/jaredt87/wingman](https://github.com/jaredt87/wingman)

Building an AI engineering partner that works with team context and established workflows. Integrating it with ackOS keeps the AI's ability to propose infrastructure changes separate from the system that authorizes, executes, and verifies those changes.

## Skills

AWS, GCP, Cloudflare Workers, Linux, networking, IAM, EC2, S3, RDS, ECS, EKS, Redis, Terraform, Puppet, Ansible, Semaphore, Docker, Kubernetes, Go, Python, Ruby, Java, PowerShell, Bash, GitHub Actions, CircleCI, Bamboo, Grafana, Prometheus, ELK, Datadog, PostgreSQL, MSSQL, MongoDB, GraphQL, Kafka, Selenium, Capybara.

## Education

**University of Phoenix** — B.S. Information Technology; Advanced Software Developer Certificate, 2019.
