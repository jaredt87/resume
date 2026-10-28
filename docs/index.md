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

Staff Systems Engineer focused on cloud platforms, infrastructure automation, secure access, and cost control. I design and build forward-thinking systems that make infrastructure safer to change and easier to operate, replacing manual work and one-off processes with repeatable platforms.

## Selected Impact

- Built and operate a Go-based internal access platform that replaces legacy SSH, bastion, and third-party access workflows; estimated licensing savings exceed $100,000 per year.
- Co-architected a trusted monthly patching system that has run reliably for four years, automating recurring maintenance and reducing the manual effort required from the infrastructure team.
- Serve as the Cloudflare SME while helping teams own their Workers and routing workflows independently, supporting a broader move toward Cloudflare as the front door for company traffic.
- Help improve the infrastructure behind revenue-generating services, including a fleet of roughly 300 legacy static servers, while teams evaluate a path toward Kubernetes.

## Experience

`December 2020 - Present`
__BambooHR - Staff Systems Engineer__

- **Infrastructure strategy and technical leadership:** Help guide the evolution of infrastructure supporting revenue-generating business services, including roughly 300 legacy static servers. Work with engineers and stakeholders to redesign systems, improve how they operate, and evaluate migration paths toward Kubernetes. Provide day-to-day technical guidance and help the team make sound engineering decisions.
- **Secure access platform and cost reduction:** Architected and built a Go-based internal access platform replacing legacy SSH, bastion, and third-party tooling. Integrated AWS Systems Manager, IAM, and Okta SSO across multiple AWS accounts, with database proxying, role-based access, administrative escalation, and activity auditing for services including EC2, RDS, ECS, EKS, and Redis. Designed to support hundreds of users; estimated licensing savings exceed $100,000 per year.
- **Reliable patching and image maintenance:** Co-architected the Semaphore and Ansible system that has run monthly patching reliably for four years. It coordinates maintenance tasks and Aptly snapshots, with RDS coordination, and now includes Auto Scaling Group AMI patching. Based on the team's estimate, it avoids roughly a week of work for a five-engineer team per monthly cycle.
- **Cloudflare architecture and enablement:** Serve as the Cloudflare SME and help move traffic toward Cloudflare as a common front door. Created Cloudflare Load Balancer routing and supported Workers-based paths for APIs and the marketing application. Help teams set up repositories and Wrangler workflows so they can deploy and own Workers independently rather than depending on a central specialist.
- **Cost investigation and mitigation:** Investigated a multi-AZ traffic change associated with an approximately $600-per-day cost increase and helped the team work out how to address it. Continue investigating infrastructure cost anomalies and identifying practical fixes.
- **Operational engineering:** Improve Auto Scaling Group image-build pipelines and use Grafana, ELK, Loggly, and Datadog for monitoring and troubleshooting. Promote reusable patterns, mentor engineers, and provide direct, constructive feedback to help the team improve.

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
