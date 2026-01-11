# ☸️ DevSecOps & Kubernetes Security

Esta trilha aborda **segurança integrada ao ciclo de entrega de software e à camada de plataforma**, com foco em **Infrastructure as Code (IaC), containers, Kubernetes, supply chain e runtime security**.

> ⚠️ **Importante**  
> DevSecOps **não é** um cargo isolado nem apenas “rodar SAST no CI”.  
> DevSecOps é a **prática de integrar segurança ao fluxo de engenharia**, enquanto **Platform / Kubernetes Security** trata da **proteção da infraestrutura, do cluster e do runtime**.

---

## 👥 Carreiras

- **DevSecOps Engineer**  
  Integra segurança ao SDLC, pipelines CI/CD, IaC e supply chain, atuando junto a DevOps e AppSec.

- **Platform / Kubernetes Security Engineer**  
  Responsável pela segurança da plataforma: **clusters, workloads, identidade, rede, políticas e runtime**.

---

## 🧠 Domínios Técnicos Essenciais

### 📦 IaC Security (Infrastructure as Code)

> Erros de IaC **escalam rápido e replicam falhas**.

- Segurança de Terraform, Helm, CloudFormation e ARM
- Validação antes do deploy
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

> Kubernetes **não é seguro por padrão**.

- Hardening de cluster
- RBAC e identidade
- Network Policies
- Pod Security Standards
- Segregação de namespaces
- Segurança do etcd

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

> O ataque **acontece em runtime**, não no pipeline.

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

> O pipeline virou alvo.

- Proteção do CI/CD
- Integridade de artefatos
- Assinatura e verificação
- Proveniência de builds (SLSA)

Ferramentas open source:
- **Sigstore / cosign** – https://www.sigstore.dev/  
- **in-toto** – https://in-toto.io/  
- **SLSA Framework** – https://slsa.dev/  

---

## 🧪 Labs Práticos (Essenciais)

> Essa trilha **não funciona sem laboratório**.

- **Killercoda (Kubernetes Labs)**  
  https://killercoda.com/

- **OWASP Kubernetes Goat**  
  https://github.com/madhuakula/kubernetes-goat

- **Cloud Native Security Labs**  
  https://github.com/aquasecurity/cloud-native-security-labs

- **TryHackMe – DevSecOps & Kubernetes**  
  https://tryhackme.com/

---

## 📘 Cursos Oficiais (Formação)

### Kubernetes & Cloud Native
- Linux Foundation – Kubernetes Security Fundamentals (LFS460)  
  https://training.linuxfoundation.org/training/kubernetes-security-fundamentals-lfs460/

- Kubernetes Docs – Security Concepts  
  https://kubernetes.io/docs/concepts/security/

---

### DevSecOps & Supply Chain
- DevSecOps Foundation (DOFD)  
  https://devopsinstitute.com/certifications/devsecops-foundation/

- Google SLSA & Supply Chain Security  
  https://slsa.dev/

---

## 🏅 Certificações

- **CKA – Certified Kubernetes Administrator**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/

- **CKS – Certified Kubernetes Security Specialist**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/

- **AWS Security – Specialty**  
  https://aws.amazon.com/certification/certified-security-specialty/

---

## 📚 Livros Técnicos Essenciais (DevSecOps & Kubernetes)

### Kubernetes Security
**Autor:** Liz Rice, Michael Hausenblas  
> Referência moderna e prática sobre **segurança real em Kubernetes**.

---

### Container Security
**Autor:** Liz Rice  
> Fundamentos de containers, namespaces, cgroups e runtime security.

---

### Practical Cloud Native Security
**Autor:** Mark Coleman, Dan Nemeth  
> Segurança aplicada a ambientes cloud native, do build ao runtime.

---

### Securing DevOps
**Autor:** Julien Vehent  
> Clássico sobre **segurança em pipelines, automação e cultura DevSecOps**.

---

### Software Supply Chain Security
**Autores:** Seth Vargo et al.  
> Base conceitual moderna sobre **supply chain attacks e mitigação**.

---

## 🔗 Integração com Outras Trilhas

- **AppSec** – segurança de código e pipelines
- **Cloud Security** – identidade, rede e governança
- **SOC / Blue Team** – detecção e resposta em runtime
- **GRC** – políticas, risco e compliance

---

## 📌 Princípios-Chave de DevSecOps & Kubernetes Security

- Segurança começa **antes do deploy**
- Kubernetes amplifica erros
- Policy as Code é controle real
- Runtime é onde o ataque acontece
- Supply chain é o novo alvo
