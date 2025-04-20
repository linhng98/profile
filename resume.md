# Linh Nguyen - Site Reliability Engineer

## Contacts

- Ho Chi Minh city, Viet Nam
- Mobile: (+84) 70-446-8256
- Email: linhnguyen.workspace@gmail.com
- GitHub: [https://github.com/linhng98](https://github.com/linhng98)
- Linkedin: [https://www.linkedin.com/in/nvlinh98](https://www.linkedin.com/in/nvlinh98/)

## About Me
I favor automation, have a technology-driven attitude, and am constantly looking for ways to complete tasks more efficiently. Additionally, I invest a lot of time in learning new things out of pure curiosity about how things work under the hood. I also view new challenges as great opportunities to expand my knowledge and expertise

## Skills
- **Platforms**: Google Cloud, AWS, Azure, Kubernetes
- **Tools**: GitLab CI/CD, GitHub Actions, CircleCI, ArgoCD, Atlantis, Docker, Terraform, Terragrunt, Ansible, Prometheus, Grafana, Loki, Tempo, Opentelemetry, Helm, Cortex, Thanos, Istio, Rook, Kafka, Vault, KEDA
- **Programming Languages**: Go, Python
- **Framework**: Gin, Gorm, FastAPI, SQLAlchemy

## Experiences
- **DevSecOps Engineer (May 2022 - Present) – Cinnamon AI**
  - Migrated CI/CD processes from CircleCI to GitHub Actions to reduce company expenses and improve control and structure of templates
  - Collaborated with multiple cloud providers (Azure, AWS, GCP) to design and implement various deployment models tailored to client needs
  - Bootstrapped infrastructure accross multiple cloud providers using Atlantis, Terraform and Terragrunt, enabling a GitOps workflow for managing infrastructure as code
  - Enforced keyless authentication for all cloud providers, eliminating the need for static credentials and enhancing security via federated oidc workload identity
  - Centralized secret management with HashiCorp Vault, enforcing fine-grained access control permissions using OIDC roles and policies, and integrated with github actions and Azure AD
  - Implemented GPU sharing with Nvidia time-slicing technology to reduce infrastructure costs, enabling scheduling of multiple AI pipelines on the same GPU node and optimizing cloud resource usage
  - Developed a GPU usage exporter to expose VRAM usage metrics per container, providing greater insight into resource utilization
  - Seamlessly scale Kubernetes clusters with KEDA and graceful termination sidecar, enabling automatic scaling of workloads based on number of pending jobs in the queue
  - Managed versioning with semantic-release, supporting both single and mono repositories, to automatically generate release tags, messages, and changelogs based on commit messages while adhering to SemVer conventions and best practices
  - Designed and implemented disaster recovery architecture for enterprise clients
  - Introduced tracing concepts and closely collaborated with developers to implement OpenTelemetry in the complex AI pipelines orchestrator product

- **Startup Co-Founder/DevOps (March 2021 - March 2024) - HubTech**
  - Set up infrastructure for development and production using a modern tech stack, including Google Kubernetes Engine, GitLab CI/CD, Kaniko, ArgoCD, Terraform, and GitHub Actions
  - Developed chat and notification services utilizing Gorilla WebSocket and NATS Pub-Sub
  - Created an identity service for user authentication, authorization, and management, including Google Single Sign-On
  - Built an upload service with integrated image processing features using the bimg library
  - Migrated infrastructure from GCP to an on-premises environment to reduce costs

- **Site Reliability Engineer (September 2021 - May 2022) – Teko**
  - Tuned and bootstrapped Kubernetes clusters for on-premises infrastructure using Rancher Kubernetes Engine
  - Provisioned and operated Rook Ceph clusters for object storage and persistent volume solutions
  - Migrated from a standalone Prometheus setup to Prometheus Operator, enabling sharding and replicas to enhance high availability and scalability
  - Centralized Prometheus metrics using Cortex to provide a single point of observability
  - Created and maintained OpenSearch and Kafka clusters for data analytics
  - Customized Helm charts to support multiple workload resources with flexible options

- **DevOps Engineer (September 2020 - August 2021) – Yeah1**
  - Collaborated closely with developers to diagnose, containerize applications, and optimize cache layers
  - Utilized Terraform/Terragrunt to provision Google Cloud Platform (GCP) resources through infrastructure as code
  - Migrated the continuous delivery system from Spinnaker to ArgoCD
  - Experimented with the Istio service mesh system
  - Built Cloudflare RBAC wrapper tool using Golang and React
  - Used Fluentd and Elasticsearch to centralize application logs
  - Monitored infrastructure using Prometheus, Grafana, and OpsGenie

- **Backend Developer (June 2020 - September 2020) - Halocom**
  - Develop marketing platform using fastAPI and gin framework
  - Get used to kurbernetes

## Open-source Projects
- **Dynamic Secret Operator [linhng98/dynamic-secret-operator](https://github.com/linhng98/dynamic-secret-operator)**: a Kubernetes operator written in Go (Operator Framework) which generates secrets dynamically
- **MessAround [linhng98/mess-around](https://github.com/linhng98/mess-around)**: playground to demonstrate many awesome devops tools, enforce gitops pattern, build scalable and sustainable application cluster

## Education
- [Ho Chi Minh City University of Science](https://en.hcmus.edu.vn) (HCMUS) - Bachelor of Science in Information Technology
