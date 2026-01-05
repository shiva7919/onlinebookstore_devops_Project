# onlinebookstore_devops_Project

## Project Overview
This project implements an end-to-end CI/CD platform using industry-standard DevOps tools.
The goal is to automate code quality checks, builds, artifact management, containerization,
and image distribution with full traceability.

## Toolchain
- GitHub – Source control & trigger
- Terraform – Infrastructure provisioning
- Ansible – Configuration management
- Jenkins – CI/CD orchestration
- SonarQube – Static code analysis & quality gates
- Nexus Repository – Artifact storage
- Docker & Docker Compose – Containerization
- Docker Hub – Image registry

## Architecture Flow
GitHub → Jenkins → SonarQube → Maven/NPM → Nexus → Docker → Docker Hub

## Design Principles
- No manual server configuration
- No UI-based infrastructure creation
- No secrets in code
- Everything is reproducible and automated

## Kubernetes Decision
Kubernetes is intentionally excluded from this project.
Docker Compose is used for service orchestration to keep the platform simple,
cost-effective, and aligned with the project scope.

## Ownership & Standards
Each tool has a clear responsibility:
- Terraform provisions infrastructure
- Ansible configures software
- Jenkins orchestrates pipelines
- Docker packages applications

## Repository Structure
terraform/  – Infrastructure as Code  
ansible/    – Configuration management  
jenkins/    – CI/CD pipeline definitions  
app/        – Sample application  
docs/       – Documentation & evidence  

## Screenshots 
<img width="1591" height="766" alt="Screenshot 2026-01-05 060913" src="https://github.com/user-attachments/assets/250f9ed7-69ba-4c3d-9223-5f4c334151d6" />
<img width="1594" height="758" alt="Screenshot 2026-01-05 060932" src="https://github.com/user-attachments/assets/c41d66e7-30ce-4001-a56e-d0d6f4bba33a" />
<img width="1592" height="775" alt="Screenshot 2026-01-05 060949" src="https://github.com/user-attachments/assets/aa21a051-d7d4-453c-8a0c-7a03c8b91292" />
<img width="1585" height="761" alt="Screenshot 2026-01-05 061007" src="https://github.com/user-attachments/assets/e7883e25-ed01-4f65-ae33-d350d32095f4" />
<img width="1545" height="596" alt="Screenshot 2026-01-05 061036" src="https://github.com/user-attachments/assets/23ab2947-5145-40e1-bb90-533004826947" />
<img width="1604" height="765" alt="Screenshot 2026-01-05 061052" src="https://github.com/user-attachments/assets/5e7a9795-0187-4aa7-ba32-52ab4d294664" />
<img width="1209" height="746" alt="Screenshot 2026-01-05 061107" src="https://github.com/user-attachments/assets/1dadee02-bfc2-41fe-a238-60e4c83145b5" />
<img width="1602" height="778" alt="Screenshot 2026-01-05 061123" src="https://github.com/user-attachments/assets/04f339a5-e58f-4a18-a342-78281e09d110" />
<img width="1601" height="842" alt="Screenshot 2026-01-05 061209" src="https://github.com/user-attachments/assets/3ff44847-9f10-40cd-a6a6-a8649bd56552" />
<img width="1572" height="865" alt="Screenshot 2026-01-05 061227" src="https://github.com/user-attachments/assets/38d61d7f-1ede-4de1-b028-c0ad32286b60" />
<img width="1576" height="824" alt="Screenshot 2026-01-05 061251" src="https://github.com/user-attachments/assets/2b3ef8d7-8cfb-4836-9fd4-861fc036bc69" />
<img width="1583" height="653" alt="Screenshot 2026-01-05 061327" src="https://github.com/user-attachments/assets/01c7b723-8221-4fe8-84af-d67216df1e98" />

<img width="1519" height="711" alt="Screenshot 2026-01-05 062100" src="https://github.com/user-attachments/assets/4369e312-c026-42c1-9a08-ade74d494f44" />
<img width="1920" height="1080" alt="10" src="https://github.com/user-attachments/assets/e6c6426f-cceb-4077-8880-e9cc66bbea03" />
<img width="1920" height="1080" alt="9" src="https://github.com/user-attachments/assets/df0b460f-289b-48bb-823f-47a3c2226143" />
<img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/e285d657-de4b-4a9b-a113-641059735ec7" />

<img width="1594" height="531" alt="Screenshot 2026-01-05 093705" src="https://github.com/user-attachments/assets/a1bf819b-1028-4a91-8e3b-805b00525b81" />
<img width="1611" height="496" alt="Screenshot 2026-01-05 093720" src="https://github.com/user-attachments/assets/47c2adb2-f970-45e9-a118-32b4ffc51320" />
<img width="1615" height="585" alt="Screenshot 2026-01-05 093740" src="https://github.com/user-attachments/assets/60993d68-5f98-4f75-a0f1-19042834659b" />
<img width="1591" height="692" alt="Screenshot 2026-01-05 093757" src="https://github.com/user-attachments/assets/0ac88016-226b-40ff-995b-cb4231d74c48" />
<img width="1616" height="672" alt="Screenshot 2026-01-05 093812" src="https://github.com/user-attachments/assets/54c6422b-e3b6-4a6e-b945-a04602172cdd" />


<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/9fa5f3f6-cc4d-4316-a4c1-8d06880710e2" />
