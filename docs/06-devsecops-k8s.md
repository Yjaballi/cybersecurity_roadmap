# ☸️ DevSecOps & Kubernetes Security

Esta trilha aborda **segurança integrada ao ciclo de entrega de software e à camada de plataforma**, com foco em **Infrastructure as Code (IaC), containers, Kubernetes, supply chain e runtime security**.

> ⚠️ **Importante**  
> DevSecOps **não é** um cargo isolado nem apenas “rodar SAST no CI”.  
> DevSecOps é a **prática de integrar segurança ao fluxo de engenharia**, enquanto **Platform / Kubernetes Security** trata da **proteção da infraestrutura, do cluster e do runtime**, onde o impacto é real.

---

## 👥 Carreiras

- **DevSecOps Engineer**  
  Atua no **ponto de interseção entre desenvolvimento, infraestrutura e segurança**, integrando controles ao SDLC, pipelines CI/CD, IaC e supply chain.

- **Platform / Kubernetes Security Engineer**  
  Responsável por **garantir que a plataforma seja segura por padrão**, cobrindo clusters, workloads, identidade, rede, políticas e runtime.

---

## 🧠 Domínios Técnicos Essenciais

### 📦 IaC Security (Infrastructure as Code)

> Em cloud e Kubernetes, **infraestrutura é código** — e código inseguro escala rápido.

- Segurança de Terraform, Helm, CloudFormation e ARM
- Validação de configurações **antes do deploy**
- Detecção de misconfiguration replicável
- Enforcement de padrões técnicos (policy as code)
- Prevenção de drift entre código e ambiente real

Ferramentas open source:
- **Checkov** – https://github.com/bridgecrewio/checkov  
- **tfsec** – https://github.com/aquasecurity/tfsec  
- **Terrascan** – https://github.com/accurics/terrascan  
- **KICS** – https://github.com/Checkmarx/kics  

---

### 🐳 Container Image Security

> Uma imagem insegura vira **mil containers inseguros**.

- Scanning de imagens em build e registry
- Vulnerabilidades em SO base e dependências
- Uso de imagens mínimas e imutáveis
- Assinatura, verificação e confiança de imagens
- Controle de origem (base images confiáveis)

Ferramentas open source:
- **Trivy** – https://github.com/aquasecurity/trivy  
- **Grype** – https://github.com/anchore/grype  
- **Syft** – https://github.com/anchore/syft  
- **Docker Scout (community)** – https://docs.docker.com/scout/  

---

### ☸️ Kubernetes Security (Cluster & Workloads)

> Kubernetes **não é seguro por padrão** — ele é flexível por padrão.

- Hardening de cluster (control plane e nodes)
- RBAC, service accounts e identidade
- Network Policies e isolamento de tráfego
- Pod Security Standards
- Segregação de namespaces e ambientes
- Proteção e acesso seguro ao etcd

Ferramentas open source:
- **kube-bench** – https://github.com/aquasecurity/kube-bench  
- **kube-hunter** – https://github.com/aquasecurity/kube-hunter  
- **Kubescape** – https://github.com/kubescape/kubescape  
- **Kyverno** – https://kyverno.io/  
- **OPA Gatekeeper** – https://github.com/open-policy-agent/gatekeeper  

---

### 🧠 Admission Control & Policy as Code

> Segurança declarativa é **controle escalável**.

- Validação de manifests no momento do deploy
- Bloqueio automático de configurações inseguras
- Enforcement técnico (não só guideline)
- Compliance contínuo e versionável
- Redução de erro humano em escala

Ferramentas:
- **OPA / Gatekeeper** – https://www.openpolicyagent.org/  
- **Kyverno** – https://kyverno.io/  

---

### 🧬 Runtime Security

> O pipeline falha. O ataque **acontece em runtime**.

- Detecção de comportamento anômalo
- Monitoramento de syscalls e eventos do kernel
- Detecção de container escape
- Visibilidade de processos e chamadas suspeitas
- Resposta em tempo real

Ferramentas open source:
- **Falco** – https://falco.org/  
- **Tetragon (eBPF)** – https://github.com/cilium/tetragon  
- **Tracee** – https://github.com/aquasecurity/tracee  

---

### 🔗 Supply Chain Security

> O atacante agora entra **antes do deploy**.

- Proteção de pipelines CI/CD
- Integridade de artefatos e builds
- Assinatura e verificação criptográfica
- Proveniência e rastreabilidade (SLSA)
- Redução de dependência não confiável

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
- **CKS – Certified Kubernetes Security Specialist**  
- **AWS Security – Specialty**

---

## 📚 Livros Técnicos Essenciais (DevSecOps & Kubernetes)

### Kubernetes Security  
**Autor:** Liz Rice, Michael Hausenblas  
> Referência moderna e prática sobre **segurança real em Kubernetes**.

### Container Security  
**Autor:** Liz Rice  
> Base sólida sobre containers, namespaces, cgroups e runtime.

### Practical Cloud Native Security  
**Autor:** Mark Coleman, Dan Nemeth  
> Segurança aplicada a ambientes cloud native, do build ao runtime.

### Securing DevOps  
**Autor:** Julien Vehent  
> Clássico sobre **segurança em pipelines, automação e cultura DevSecOps**.

### Software Supply Chain Security  
**Autores:** Seth Vargo et al.  
> Base moderna sobre ataques à cadeia de suprimentos e mitigação.

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


---

# 🏭 Fabricantes & Plataformas — DevSecOps & Kubernetes Security

Este documento lista **fabricantes e plataformas amplamente usados no mercado** para **DevSecOps, Kubernetes Security, Cloud Native Security e Supply Chain Security**.

> ⚠️ **Importante**  
> Fabricantes **não substituem fundamentos**.  
> Eles **implementam controles**, mas **quem garante segurança é arquitetura + processo + engenharia**.

A lista está organizada **por domínio técnico**, refletindo **uso real em ambientes maduros**.

---

## 📦 IaC Security & Policy as Code

Ferramentas focadas em **segurança de infraestrutura como código**, validação preventiva e enforcement técnico.

### Fabricantes / Plataformas
- **Palo Alto Networks – Prisma Cloud (IaC Security)**
- **Check Point – CloudGuard**
- **Snyk IaC**
- **Bridgecrew (Checkov)**
- **Aqua Security (IaC & Cloud Native)**
- **HashiCorp Sentinel** (policy as code)
- **Sysdig Secure (IaC context)**
- **Tenable Cloud Security** (IaC + misconfiguration + exposure context)

---

## 🐳 Container Image Security & Registry Protection

Proteção de imagens, dependências, registries e pipelines de build.

### Fabricantes / Plataformas
- **Aqua Security**
- **Sysdig Secure**
- **Anchore**
- **Snyk Container**
- **JFrog Xray**
- **Docker Scout**
- **Palo Alto Prisma Cloud (Container Security)**
- **Trend Micro Cloud One – Container Security**
- **Tenable Container Security** (vulnerabilities + exposure)

---

## ☸️ Kubernetes Security (Cluster, Workloads & Configuração)

Segurança de clusters, namespaces, RBAC, policies e hardening.

### Fabricantes / Plataformas
- **Aqua Security**
- **Sysdig Secure**
- **Palo Alto Prisma Cloud**
- **Check Point CloudGuard**
- **ARMO / Kubescape**
- **Red Hat Advanced Cluster Security (ACS)**
- **VMware Tanzu Security**
- **Google GKE Security / Anthos Security**
- **Microsoft Defender for Containers**
- **Tenable Cloud Security (K8s posture + risk)**

---

## 🧠 Admission Control & Policy Enforcement

Validação e bloqueio de configurações inseguras **no momento do deploy**.

### Fabricantes / Plataformas
- **OPA / Gatekeeper**
- **Kyverno**
- **HashiCorp Sentinel**
- **Red Hat Advanced Cluster Security**
- **Palo Alto Prisma Cloud (policy engine)**

---

## 🧬 Runtime Security (Detecção & Resposta)

Detecção comportamental, syscalls, eBPF e resposta em tempo real.

### Fabricantes / Plataformas
- **Aqua Security**
- **Sysdig Secure**
- **Falco (CNCF)**
- **Cilium / Tetragon**
- **Trend Micro Cloud One**
- **CrowdStrike Falcon Cloud Security**
- **Palo Alto Prisma Cloud (Runtime Protection)**

---

## 🌐 Microsegmentação & Zero Trust Leste–Oeste

Proteção de **tráfego interno**, workloads, containers e VMs, com foco em **Zero Trust** e **redução de blast radius**.

> 📌 Essencial em Kubernetes, cloud híbrida e ambientes distribuídos.

### Fabricantes / Plataformas
- **Akamai Guardicore (Microsegmentation)**
- **Illumio**
- **VMware NSX**
- **Cisco Secure Workload (Tetration)**
- **Palo Alto Prisma Cloud (Microsegmentation features)**
- **Cilium (eBPF-based networking & security)**

---

## 🔗 Supply Chain Security (CI/CD & Proveniência)

Proteção do pipeline, integridade de artefatos e ataques à cadeia de suprimentos.

### Fabricantes / Plataformas
- **GitHub Advanced Security**
- **GitLab Ultimate (DevSecOps)**
- **Snyk**
- **JFrog Xray**
- **Sigstore (cosign)**
- **in-toto**
- **Google SLSA**
- **Chainguard**

---

## 📊 CNAPP / Exposure Management (Visão Unificada)

Plataformas que correlacionam **configuração, vulnerabilidade, identidade e exposição real**.

### Fabricantes / Plataformas
- **Palo Alto Networks – Prisma Cloud**
- **Aqua Security Platform**
- **Sysdig Secure**
- **Check Point CloudGuard**
- **Wiz**
- **Orca Security**
- **Lacework**
- **Microsoft Defender for Cloud**
- **Tenable Cloud Security / Tenable One**

> 📌 Aqui entra **exposure management**, não só posture.

---

## 🔐 Identidade & Secrets (Plataforma & Pipelines)

Gestão de identidade, segredos e acesso em ambientes cloud native.

### Fabricantes / Plataformas
- **HashiCorp Vault**
- **CyberArk**
- **AWS Secrets Manager**
- **Azure Key Vault**
- **Google Secret Manager**
- **Doppler**
- **Akeyless**

---

## 🧭 Como Usar Esta Lista

- 📌 **Não escolha ferramenta antes do problema**
- 📌 Avalie seu **nível de maturidade**
- 📌 Priorize **prevenção + visibilidade + runtime**
- 📌 Entenda onde entra **microsegmentação**
- 📌 Evite sobreposição de ferramentas

> 💡 Ambientes maduros usam **menos ferramentas, melhor integradas**.

---

## ⚠️ Observação Final

- Fabricantes mudam
- Features migram
- Produtos se fundem

👉 **Fundamentos, arquitetura e método permanecem.**

DevSecOps e Kubernetes Security **não são tool-driven**.  
São **engineering-driven**.

