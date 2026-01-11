# ☁️ Cloud Security

Esta trilha cobre **segurança em ambientes de computação em nuvem**, com foco em **arquitetura, identidade, rede, visibilidade, postura de segurança e resposta a incidentes**, considerando **AWS, Azure e Google Cloud** em cenários **single-cloud e multi-cloud**.

Cloud Security **não é firewall na nuvem**.  
É **design correto, identidade bem governada, telemetria completa e automação contínua**.

---

## 👥 Carreiras

- **Cloud Security Engineer**  
  Implementa controles, hardening, logging, detecção e resposta a incidentes em ambientes cloud.

- **Cloud Security Architect**  
  Desenha **arquiteturas seguras e escaláveis**, define padrões, governa riscos e conecta segurança ao negócio.

---

## 🧠 Domínios Técnicos de Cloud Security

### 🔐 Identidade como Perímetro (IAM)

> Em cloud, **quem manda é a identidade**.

- Identidades humanas e não humanas (users, roles, services, workloads)
- Princípio do menor privilégio aplicado na prática
- RBAC, ABAC e políticas condicionais
- MFA, autenticação forte e access policies
- Federation, SSO e identidade híbrida
- Gestão de segredos e credenciais

📌 **Erro de IAM = comprometimento total do ambiente**

---

### 🌐 Segurança de Rede em Cloud

> Rede em cloud é **controle lógico**, não físico.

- VPC / VNet / Subnets
- Security Groups, NSGs e Firewalls
- Segmentação e microsegmentação
- Tráfego norte-sul e leste-oeste
- Exposição segura de serviços (LB, APIs, ingress)
- Integração com WAF e proteções de borda

---

### 📊 Logging, Telemetria & Visibilidade

> Sem logs, **não existe segurança nem DFIR em cloud**.

- Centralização de logs
- Logs de identidade, API, rede e workload
- Auditoria de ações administrativas
- Integração com SIEM
- Detecção de comportamento anômalo
- Retenção, integridade e rastreabilidade

📌 Logs em cloud **não são opcionais**.

---

### 🛡️ Cloud Security Posture Management (CSPM)

> O maior risco em cloud é **misconfiguration**, não exploit.

- Avaliação contínua de postura
- Hardening de serviços nativos
- Detecção de configurações inseguras
- Benchmarks CIS
- Priorização baseada em risco
- Integração com governança e compliance

---

### ⚙️ Segurança ao Longo do Ciclo Cloud

Cloud Security precisa existir **antes, durante e depois do deploy**.

- Design seguro (Landing Zones)
- Provisionamento seguro (IaC)
- Segurança em runtime
- Resposta a incidentes em cloud
- Governança contínua

📌 Segurança que entra só no runtime **chega tarde**.

---

### 🌍 Multicloud Security

> Multicloud sem padrão vira **caos operacional**.

- Normalização de controles entre clouds
- Visibilidade centralizada
- Identidade unificada
- Logging padronizado
- Governança e políticas comuns
- Risco de shadow IT

---

## 🧪 Labs Práticos (Essenciais)

> Cloud Security **se aprende configurando, errando e corrigindo**.

- AWS Well-Architected Labs (Security Pillar)  
  https://wellarchitectedlabs.com/security/

- AWS CloudGoat  
  https://github.com/RhinoSecurityLabs/cloudgoat

- Azure Security Labs  
  https://learn.microsoft.com/security/

- GCP Security Foundations  
  https://cloud.google.com/security

- TryHackMe – Cloud Security  
  https://tryhackme.com/

- DetectionLab – Cloud  
  https://github.com/clong/DetectionLab

---

## 📘 Cursos Oficiais (Formação)

### AWS
- AWS Security Fundamentals  
  https://aws.amazon.com/training/digital/aws-security-fundamentals/

- AWS Well-Architected – Security Pillar  
  https://aws.amazon.com/architecture/well-architected/

### Microsoft Azure
- Secure Your Cloud Data  
  https://learn.microsoft.com/training/paths/secure-your-cloud-data/

- AZ-500 – Azure Security Engineer  
  https://learn.microsoft.com/training/paths/design-implement-azure-security/

### Google Cloud
- Google Cloud Security Foundations  
  https://cloud.google.com/training/security

### Vendor Neutral
- Cloud Security Alliance – Training  
  https://cloudsecurityalliance.org/education/

- MITRE ATT&CK for Cloud  
  https://attack.mitre.org/matrices/enterprise/cloud/

---

## 🧰 Ferramentas Open Source Importantes

### CSPM / Auditoria
- ScoutSuite – https://github.com/nccgroup/ScoutSuite
- Prowler – https://github.com/prowler-cloud/prowler
- CloudMapper – https://github.com/duo-labs/cloudmapper

### IaC Security
- Checkov – https://github.com/bridgecrewio/checkov
- tfsec – https://github.com/aquasecurity/tfsec
- Terrascan – https://github.com/accurics/terrascan

### Runtime & Detecção
- Falco – https://falco.org/
- OpenSearch Security Analytics – https://opensearch.org/docs/latest/security-analytics/

### Identidade
- Keycloak – https://www.keycloak.org/
- Open Policy Agent (OPA) – https://www.openpolicyagent.org/

---

## 🏅 Certificações

- AWS Certified Security – Specialty  
- AZ-500 – Azure Security Engineer  
- Google Professional Cloud Security Engineer  
- CCSK – Cloud Security Alliance  
- CCSP – ISC2  

---

## 🔗 Integração com Outras Trilhas

- **SOC / Blue Team** – detecção e resposta em cloud
- **DFIR** – investigação e evidências cloud
- **AppSec** – segurança de workloads e APIs
- **DevSecOps** – IaC e pipelines
- **GRC** – risco, compliance e governança

---

## 📚 Livros Técnicos Essenciais de Cloud Security

### Cloud Security and Privacy  
**Autores:** Tim Mather, Subra Kumaraswamy, Shahed Latif  
> Base conceitual de segurança em nuvem, responsabilidade compartilhada e governança.

---

### Practical Cloud Security  
**Autor:** Chris Dotson  
> Livro extremamente prático sobre IAM, rede, logging e incident response em cloud.

---

### Designing Secure Cloud Architecture  
**Autor:** Michael S. Smith  
> Foco em **arquitetura segura**, não em ferramenta.

---

### Incident Response in the Cloud  
**Autor:** Chris Dotson  
> Resposta a incidentes específica para ambientes cloud.

---

### Zero Trust Networks  
**Autores:** Evan Gilman, Doug Barth  
> Fundamentos de Zero Trust aplicáveis diretamente a cloud.

---

### Security and Privacy in Cloud Computing  
**Autores:** Siani Pearson, George Yee  
> Visão acadêmica e estratégica sobre risco e privacidade em cloud.

---

## 📌 Princípios-Chave de Cloud Security

- Identidade é o novo perímetro
- Misconfiguration é o risco dominante
- Logs são obrigatórios
- Segurança precisa escalar automaticamente
- Multicloud exige governança forte

> Cloud muda rápido.  
> **Fundamentos bons duram décadas.**

---

## 🏢 Fabricantes (Exemplos) – Cloud Security no Mundo Real

> Exemplos de fabricantes/plataformas comuns por domínio (não é lista exaustiva).

### CSPM / CNAPP / Postura & Exposição
- Wiz
- Palo Alto Prisma Cloud
- Microsoft Defender for Cloud
- Orca Security
- Lacework
- Check Point CloudGuard
- Crowdstrike

### Workload / Container Runtime / Cloud Workload Protection
- CrowdStrike (Falcon Cloud Security)
- Sysdig
- Aqua Security
- Trend Micro (Cloud One)
- Palo Alto Prisma (CWPP)

### Identidade / CIEM / Access Governance (cloud/híbrido)
- Microsoft Entra ID (Azure AD)
- Okta
- Ping Identity
- SailPoint
- CyberArk (PAM)
- ManageEngine

### Logs / SIEM / Detecção (cloud + enterprise)
- Microsoft Sentinel
- Splunk
- Google Chronicle (Security Operations)
- Elastic Security
- Datadog Security (quando aplicável)
- ManageEngine

### WAAP / WAF / Proteção de borda para apps e APIs
- Akamai
- Cloudflare
- F5
- Imperva
- Cequence

---
