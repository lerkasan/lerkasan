## Hi, I'm Valeriia, an aspiring DevOps Engineer.

I have about a year of hands-on experience in DevOps engineering acquired while implementing pet projects and participating in various training programs. I am knowledgeable about provisioning infrastructure as code on AWS, building and optimizing CI/CD pipelines for automated deployment of containerized applications in AWS ECS and Kubernetes clusters using AWS CodeDeploy and GitOps approach.

### TECHNICAL SKILLS

- Systems Administration: Linux, Bash Scripting, Apache Httpd, Nginx, reverse-proxy, DNS
- Cloud: Amazon Web Services (AWS) – EC2, ECS, ALB, Autoscaling,  S3, VPC, IAM, RDS, CodeDeploy
- Continuous Integration and Continuous Deployment (CI/CD): Github Actions, ArgoCD, GitOps
- Infrastructure as Code (IaC) and Configuration Management: Terraform, Ansible, Packer
- Containerization and Orchestration: Docker, Docker Compose, Kubernetes, Helm
- Monitoring and Observability: Prometheus, Loki, Grafana
- Software Development: Java, Spring Boot, JUnit, Mockito, RESTful API, SQL, Git
- Databases and Migration tools: MySQL, PostgreSQL, Flyway, Liquibase
- Build Tools and Artifacts: Maven, Gradle, npm, JFrog Artifactory
- Static Code Analysis and Security Scanners: SonarQube, Trivy, Grype, Checkov		

### PET PROJECTS

#### 1. An automated deployment of a full-stack website
*Project description:* Terraform code provisions a Kubernetes cluster and installs External Secrets and External DNS operators, AWS Loadbalancer Controller, ArgoCD, Prometheus+Grafana+Loki stack, SonarQube, and JFrog Artifactory. As soon as ArgoCD is installed, it automatically deploys frontend and backend as Helm charts. CI/CD was implemented using GitHub Actions workflows and ArgoCD GitOps approach. 

Continuous integration includes checks for security best practices:
- static code analysis via self-hosted SonarQube
- analysis of Terraform code via Checkov
- checking Docker image for size efficiency using Dive
- scanning Docker images for vulnerabilities with Trivy and Grype

Techonologies:
- Orchestration: Kubernetes (AWS EKS) for backend and frontend services
- Infrastructure: AWS (EKS, ECR, ALB, Route53, RDS, SSM, IAM, VPC)
- IaC: Terraform
- CI/CD: Github Actions, ArgoCD
- Artifact Management: jFrog Artifactory, Helm charts
- Monitoring: Prometheus, Loki, Grafana, Datadog
- Security: SonarQube, Trivy, Grype, Checkov
- Database: PostgreSQL
- Backend: Java, Spring Boot, JUnit, Maven
- Frontend: Angular

https://github.com/stars/lerkasan/lists/greencity-devops-project
##

#### 2. A full-stack website with automated deployment
*Project description:* AI-driven interactive platform to assist job seekers in honing technical interview skills. The project leverages ChatGPT API to generate technical questions based on selected topics. Platform provided a voice interface before OpenAI delivered a similar feature for ChatGPT. Implementation leverages AWS Polly service to transform the ChatGPT-generated text questions into synthesized speech; uses Deepgram API to transcribe users' responses in real time; analyzes each response via ChatGPT, providing users with constructive feedback about answers.

Key features of the project:
- AI-Powered Question Generation: Leverages the capabilities of the ChatGPT API to autonomously present technical questions based on selected topics
- Seamless Voice Integration: Incorporates AWS Polly service to transform the ChatGPT-generated text questions into synthesized speech, offering a more immersive experience
- Real-Time Speech Transcription: Uses Deepgram API to transcribe user's responses in real time
- Intelligent Feedback System: Analyzes each response via ChatGPT, providing users with constructive feedback on their answers

Technologies:
- Orchestration: Docker Compose for backend and frontend services
- Infrastructure: AWS (EC2 Autoscaling, ALB, Route53, RDS, S3, Polly, CodeDeploy, CloudWatch, SSM, STS, IAM)
- IaC: Terraform
- CI/CD: Github Actions, AWS CodeDeploy
- Artifact Management: GitHub Packages, GitHub Container Registry
- Monitoring: AWS CloudWatch
- Database: MySQL, Flyway migrations
- Backend: Java, Spring Boot, JUnit, Mockito, Maven
- Frontend: Vue.js, JavaScript, HTML, CSS, Tailwind CSS

https://github.com/lerkasan/boanerges

##

#### 3. An automated deployment of a dummy Django website
Technologies:
- Orchestration: Docker Compose for backend services
- Infrastructure: AWS (EC2 Autoscaling, S3, CloudFront, ALB, Route53, RDS, Elasticache, ECR, CodeDeploy, SSM, IAM, VPC)
- IaC: Terraform
- CI/CD: Github Actions, AWS CodeDeploy
- Database and Cache: PostgreSQL, Redis
- Backend: Python, Django
- Frontend: HTML
 
https://github.com/stars/lerkasan/lists/yefp1