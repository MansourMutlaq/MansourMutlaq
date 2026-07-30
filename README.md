<div align="right">
<a href="README.md"><img src="https://flagcdn.com/w20/us.png" width="16" alt="English"> <b>English</b></a>
&nbsp; | &nbsp;
<a href="README-ar.md"><img src="https://flagcdn.com/w20/sa.png" width="16" alt="Arabic"> <b>العربية</b></a>
</div>

<div align="center">
<img src="assets/banner.svg" alt="Mansour Alharbi Banner" width="100%">
</div>

<br>

<div align="center">
<h3>$ whoami | grep "Cloud Infrastructure, Security & Network Automation" <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="30" alt="Developer GIF"></h3>
<p>
Hi, I am <b>Mansour</b>, an Information Technology graduate and certified <b>AWS Solutions Architect – Associate</b>, <b>HashiCorp Terraform Associate (004)</b>, and <b>Cisco CCNA</b> professional focused on cloud infrastructure, Infrastructure as Code, networking, automation, and security engineering.
<br><br>
I build documented engineering projects using AWS, Terraform, Python, Linux, Cisco IOS, Docker, GitHub Actions, and OpenSearch, with an emphasis on secure architecture, reusable automation, automated validation, and operational readiness.
</p>
</div>

<br>

<div align="center">
<p><b>How to reach me</b></p>
<a href="https://www.linkedin.com/in/mansour-mu-alharbi" target="_blank"><img src="https://api.iconify.design/simple-icons:linkedin.svg?color=%230077b5" width="35" alt="LinkedIn"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://x.com/iirtac" target="_blank"><img src="https://api.iconify.design/simple-icons:x.svg?color=%23ffffff" width="35" alt="X"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://outlook.live.com/mail/0/deeplink/compose?to=mansour-alharbi@outlook.com" target="_blank"><img src="https://api.iconify.design/simple-icons:microsoftoutlook.svg?color=%230078d4" width="35" alt="Outlook"></a>
</div>

<br>

---

### Core Technical Skills

<div align="center">
<p><strong>Cloud Infrastructure & Infrastructure as Code</strong></p>
<img src="https://img.shields.io/badge/AWS_Architecture-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Architecture">&nbsp;
<img src="https://img.shields.io/badge/Terraform_IaC-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform IaC">&nbsp;
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">&nbsp;
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</div>

<div align="center">
<p><strong>Networking & Automation</strong></p>
<img src="https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco IOS">&nbsp;
<img src="https://img.shields.io/badge/Python_Automation-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Automation">&nbsp;
<img src="https://img.shields.io/badge/Netmiko-4B275F?style=for-the-badge" alt="Netmiko">&nbsp;
<img src="https://img.shields.io/badge/Jinja2-B41717?style=for-the-badge&logo=jinja&logoColor=white" alt="Jinja2">&nbsp;
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
</div>

<div align="center">
<p><strong>Infrastructure Security & Observability</strong></p>
<img src="https://img.shields.io/badge/AWS_CloudTrail-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS CloudTrail">&nbsp;
<img src="https://img.shields.io/badge/Security_Analytics-0B253A?style=for-the-badge" alt="Security Analytics">&nbsp;
<img src="https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white" alt="OpenSearch">&nbsp;
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest">&nbsp;
<img src="https://img.shields.io/badge/Secure_CI-2EA44F?style=for-the-badge&logo=githubactions&logoColor=white" alt="Secure CI">
</div>

---

### Technical Focus & Roadmap

- Designing secure AWS architectures with reusable Terraform modules, environment separation, private networking, and least-privilege access controls.
- Building automation and observability across cloud, Linux, and network infrastructure.
- Developing a Secure Multi-AZ AWS Application Platform with Terraform to demonstrate high availability, secure delivery, monitoring, and cost-aware operations.
- Planning an enterprise hybrid infrastructure home lab covering virtualization, Windows Server, Linux administration, Active Directory, DNS, DHCP, network segmentation, monitoring, backup, and hybrid AWS connectivity.
---

<div align="center">
<strong>Portfolio Status:</strong>
3 completed and documented projects · 1 AWS and Terraform platform in active development
</div>

<br>

## Featured Technical Projects

### [Cisco IOS Network Automation Toolkit](https://github.com/MansourMutlaq/Cisco-Network-Automation)

A modular Python network automation toolkit built and validated against a live six-device Cisco IOS environment in EVE-NG. The project provides YAML-based device inventory, secure runtime credential loading, Netmiko SSH validation, timestamped running-configuration backups, Jinja2 configuration rendering, tested deployment and rollback components, structured logging, and operational reporting.

**Validated Results**

- Netmiko SSH connectivity: **6/6 devices**
- Running-configuration backups: **6/6 devices**
- Automated pytest suite: **30/30 passed**

**Technologies:** Python · Netmiko · YAML · Jinja2 · pytest · Cisco IOS · EVE-NG<br>
**Status:** Completed

---

### [Infrastructure Security Analytics](https://github.com/MansourMutlaq/infrastructure-security-analytics)

A multi-source infrastructure security analytics pipeline that ingests AWS CloudTrail, Linux authentication, and Cisco IOS telemetry. It normalizes heterogeneous events into an ECS-inspired security model, executes deterministic detection rules, assigns risk scores, correlates related activity, and generates investigation-ready HTML, JSON, CSV, and optional OpenSearch outputs.

**Validated Results**

- Automated test suite: **47/47 passed**
- Statement coverage: **92.98%**
- Multi-version GitHub Actions CI: **Python 3.12, 3.13, and 3.14**
- Ruff static analysis and Bandit security scanning: **Passed**
- Live OpenSearch validation: **15 normalized events and 10 correlated alerts indexed**
- AWS, Linux, and Cisco detections documented with reproducible evidence

**Technologies:** Python · AWS CloudTrail · Linux Authentication · Cisco IOS · OpenSearch · Docker Compose · GitHub Actions · pytest · Ruff · Bandit · Jinja2<br>
**Status:** Completed

---

### [IoT-Enabled Solar-Powered Smart Wheelchair](https://github.com/MansourMutlaq/IoT-Smart-Wheelchair)

A capstone engineering project integrating embedded software, IoT connectivity, obstacle detection, health monitoring, GPS-based location support, and solar-powered operation to improve user safety and independence. The system uses ESP32-based control, multiple sensors, real-time alerts, and energy-aware design.

**Project Contributions**

- Led the project architecture and team delivery
- Integrated embedded control, IoT communication, and sensor-based safety functions
- Implemented multi-sensor obstacle detection and alerting logic
- Documented system architecture, hardware integration, and operational behavior

**Technologies:** ESP32 · C/C++ · IoT Sensors · GPS · Embedded Systems · Solar Energy<br>
**Status:** Completed · Capstone Project

---

## Cloud Infrastructure Project in Development

### [Secure Multi-AZ AWS Application Platform with Terraform](https://github.com/MansourMutlaq/aws-secure-multi-az-platform)

<div align="center">
<img src="https://img.shields.io/badge/Project_Status-In_Development-yellow?style=for-the-badge" alt="Project Status: In Development">
</div>

A production-oriented AWS reference platform designed to demonstrate secure cloud infrastructure, reusable Infrastructure as Code, high availability, observability, federated CI/CD, and cost-aware operations.

The application layer remains intentionally lightweight so the project can focus on infrastructure architecture, security controls, automated delivery, validation, and operational readiness.

**Target Architecture**

- Multi-AZ VPC with public, private application, and isolated database subnets
- Application Load Balancer distributing traffic to private ECS Fargate tasks
- Amazon RDS PostgreSQL deployed without public access
- Amazon ECR and Docker-based application packaging
- Secrets Manager and AWS KMS for secrets and encryption controls
- AWS WAF protecting the public application entry point
- CloudWatch monitoring, SNS notifications, and VPC Flow Logs
- Encrypted S3 Terraform state with versioning and native state locking
- Reusable Terraform modules with separate development and production configurations

**Technical & Operational Controls**

- GitHub Actions authentication to AWS through OIDC and temporary credentials
- Separate Terraform plan and controlled apply workflows
- Terraform formatting, validation, TFLint, and Checkov scanning in CI
- Least-privilege IAM roles and security-group chaining between ALB, ECS, and RDS
- AWS Budgets, deployment evidence, failure testing, and documented teardown

**Planned Technologies:** AWS VPC · Terraform · ECS Fargate · Application Load Balancer · Amazon RDS PostgreSQL · Amazon ECR · Docker · IAM · AWS KMS · Secrets Manager · AWS WAF · CloudWatch · SNS · VPC Flow Logs · S3 Remote State · GitHub Actions OIDC · TFLint · Checkov<br>
**Status:** In Development<br>
**Started:** July 2026<br>
**Target Window:** Early August 2026

---

### Verified Professional Certifications

<table width="100%">
<tr>
<td width="33%" align="center" valign="top">
<h4>AWS Certified</h4>
<hr>
<a href="https://www.credly.com/badges/dc16e4e2-440d-4ae5-a1af-97329eef6867/public_url" target="_blank">
<img src="assets/aws-saa-badge.png" width="120" alt="AWS Certified Solutions Architect Associate">
</a>
<br><br>
<strong>AWS Certified Solutions Architect – Associate</strong>
<br><br>
<a href="https://www.credly.com/badges/dc16e4e2-440d-4ae5-a1af-97329eef6867/public_url" target="_blank">Verify Credential</a>
</td>
<td width="33%" align="center" valign="top">
<h4>HashiCorp Certified</h4>
<hr>
<img src="assets/terraform-associate-004.svg" width="110" alt="HashiCorp Certified Terraform Associate 004">
<br><br>
<strong>HashiCorp Certified:<br>Terraform Associate (004)</strong>
</td>
<td width="33%" align="center" valign="top">
<h4>Cisco Certified</h4>
<hr>
<a href="https://www.credly.com/badges/926aefcd-e73c-46cc-99fd-5a865908ab21/public_url" target="_blank">
<img src="assets/ccna_med.jpg" width="120" alt="Cisco Certified Network Associate">
</a>
<br><br>
<strong>Cisco Certified Network Associate</strong>
<br><br>
<a href="https://www.credly.com/badges/926aefcd-e73c-46cc-99fd-5a865908ab21/public_url" target="_blank">Verify Credential</a>
</td>
</tr>
</table>
