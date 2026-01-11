# ☸️ DevSecOps & Kubernetes Security

Esta trilha aborda **segurança integrada ao ciclo de entrega de software e à camada de plataforma**, com foco em **IaC, containers, Kubernetes, supply chain e runtime security**.

> ⚠️ **Importante:**  
> DevSecOps **não é** um cargo isolado nem apenas “rodar SAST no CI”.  
> DevSecOps é a **prática de integrar segurança ao fluxo de engenharia**, enquanto **Platform / Kubernetes Security** trata da **proteção da infraestrutura e do runtime**.

---

## 👥 Carreiras

- **DevSecOps Engineer**  
  Integra controles de segurança ao SDLC, pipelines CI/CD e IaC, trabalhando junto a DevOps e AppSec.

- **Platform Security Engineer**  
  Responsável pela segurança da plataforma (Kubernetes, containers, runtime, identidade, rede e políticas).

---

## 🧠 Habilidades Técnicas Essenciais

### 📦 IaC Security (Infrastructure as Code)
- Segurança de Terraform, Helm, CloudFormation, ARM
- Validação de configuração antes do deploy
- Detecção de misconfiguration
- Enforcement de padrões (policy as code)

Ferramentas open source:
- **Checkov** – https://github.com/bridgecrewio/checkov
- **tfsec** – https://github.com/aquasecurity/tfsec
- **Terrascan** – https://github.com/accurics/terrascan
- **KICS** – https://github.com/Checkmarx/kics

---

### 🐳 Container Image Security
- Image scanning
- Vulnerabilidades e dependências
- Imagens imutáveis
- Assinatura e verificação de imagens

Ferramentas open source:
- **Trivy** – https://github.com/aquasecurity/trivy
- **Grype** – https://github.com/anchore/grype
- **Syft** – https://github.com/anchore/syft
- **Docker Scout (community)** – https://docs.docker.com/scout/

---

### ☸️ Kubernetes Security (Cluster & Workloads)
- Hardening de cluster
- RBAC e identidade
- Network Policies
- Pod Security Standards
- Segregação de namespaces
- Segurança de etcd

Ferramentas open source:
- **kube-bench** – https://github.com/aquasecurity/kube-bench
- **kube-hunter** – https://github.com/aquasecurity/kube-hunter
- **Kubescape** – https://github.com/kubescape/kubescape
- **Kyverno** – https://kyverno.io/
- **OPA Gatekeeper** – https://github.com/open-policy-agent/gatekeeper

---

### 🧠 Admission Control & Policy as Code
- Validação de manifests
- Bloqueio de configurações inseguras
- Enforcement automático
- Compliance contínuo

Ferramentas:
- **OPA / Gatekeeper** – https://www.openpolicyagent.org/
- **Kyverno** – https://kyverno.io/

---

### 🧬 Runtime Security
- Detecção de comportamento anômalo
- Monitoramento de syscalls
- Detecção de escape de container
- Proteção em tempo real

Ferramentas open source:
- **Falco** – https://falco.org/
- **Tetragon (eBPF)** – https://github.com/cilium/tetragon
- **Tracee** – https://github.com/aquasecurity/tracee

---

### 🔗 Supply Chain Security
- Proteção do pipeline CI/CD
- Integridade de artefatos
- Assinatura e verificação
- Proveniência de builds (SLSA)

Ferramentas open source:
- **Sigstore (cosign)** – https://www.sigstore.dev/
- **in-toto** – https://in-toto.io/
- **SLSA Framework** – https://slsa.dev/
- **GitHub Actions Security Hardening** – https://docs.github.com/actions/security-guides

---

## 🧪 Labs Práticos (DevSecOps & Kubernetes)

> Essa trilha **só funciona com laboratório**.

### Plataformas de Labs
- **Katacoda / Killercoda (Kubernetes labs)**  
  https://killercoda.com/

- **Kubernetes Goat (OWASP)**  
  https://github.com/madhuakula/kubernetes-goat

- **Cloud Native Security Labs (Aqua / community)**  
  https://github.com/aquasecurity/cloud-native-security-labs

- **TryHackMe – DevSecOps & Kubernetes Labs**  
  https://tryhackme.com/

- **Kubescape Labs**  
  https://hub.armo.cloud/docs/tutorials

---

## 📘 Cursos Oficiais (Formação)

### Kubernetes & Cloud Native
- **Linux Foundation – Kubernetes Security Fundamentals (LFS460)**  
  https://training.linuxfoundation.org/training/kubernetes-security-fundamentals-lfs460/

- **Kubernetes Documentation – Security Concepts**  
  https://kubernetes.io/docs/concepts/security/

---

### DevSecOps
- **DevSecOps Foundation (DOFD)**  
  https://devopsinstitute.com/certifications/devsecops-foundation/

- **Google SLSA & Supply Chain Security Training**  
  https://slsa.dev/

- **AWS DevSecOps Learning Path**  
  https://aws.amazon.com/training/devsecops/

---

### Cloud Native Security
- **CNCF Security Whitepapers & Docs**  
  https://www.cncf.io/projects/

---

## 🏅 Certificações

### Kubernetes
- **CKA – Certified Kubernetes Administrator**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/

- **CKS – Certified Kubernetes Security Specialist**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/

---

### DevSecOps / Cloud Native (Complementares)
- **AWS Security – Specialty**  
  https://aws.amazon.com/certification/certified-security-specialty/

- **AZ-500 – Azure Security Engineer**  
  https://learn.microsoft.com/credentials/certifications/azure-security-engineer/

---

## 🔗 Integração com Outras Trilhas

- **AppSec** – segurança de código e pipelines
- **Cloud Security** – identidade, rede e governança
- **SOC / Blue Team** – detecção e resposta em runtime
- **GRC** – políticas, risco e compliance

---

## 📌 Princípios-Chave de DevSecOps & K8s Security

- Segurança começa **antes do deploy**
- Kubernetes expande o impacto do erro
- Policy as Code é controle real
- Runtime é onde o ataque acontece
- Supply chain é o novo alvo

---
