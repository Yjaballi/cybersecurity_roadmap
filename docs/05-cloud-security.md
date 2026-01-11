# ☁️ Cloud Security

Esta trilha cobre **segurança em ambientes de computação em nuvem**, com foco em **identidade, rede, visibilidade, postura de segurança e resposta a incidentes**, considerando **AWS, Azure e Google Cloud** em cenários **single-cloud e multi-cloud**.

Cloud Security **não é firewall na nuvem**.  
É **arquitetura, identidade, telemetria, automação e governança contínua**.

---

## 👥 Carreiras

- **Cloud Security Engineer**  
  Atua na implementação de controles, monitoramento, hardening, detecção e resposta a incidentes em ambientes cloud.

- **Cloud Security Architect**  
  Responsável por **desenhar arquiteturas seguras**, definir padrões, governar riscos e alinhar segurança com negócio e escala.

---

## 🧠 Domínios Técnicos de Cloud Security

### 🔐 Identidade como Perímetro (IAM)

> Em cloud, **identidade é o novo firewall**.

- Identidades humanas e não humanas (users, roles, workloads)
- Princípio do menor privilégio aplicado de forma prática
- RBAC, ABAC e políticas baseadas em contexto
- MFA, autenticação forte e conditional access
- Federation, SSO e identidade híbrida
- Gestão de segredos e credenciais

📌 **Falha de IAM = comprometimento total do ambiente**

---

### 🌐 Segurança de Rede em Cloud

> Rede em cloud é **controle lógico**, não cabo.

- VPC / VNet / Subnets
- Security Groups, NSGs e Firewalls
- Segmentação e microsegmentação
- Tráfego norte-sul e leste-oeste
- Exposição segura de serviços (LB, API, ingress)
- Integração com WAF e proteções de borda

---

### 📊 Logging, Telemetria & Monitoramento

> Sem logs, **não existe segurança nem forense em cloud**.

- Centralização de logs
- Logs de identidade, rede, API e workload
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
- Gestão de risco e priorização
- Integração com governança e compliance

---

### ⚙️ Segurança no Ciclo de Vida Cloud

Cloud Security precisa existir **antes, durante e depois do deploy**.

- **Design seguro (Landing Zones)**
- **Provisionamento seguro (IaC)**
- **Segurança em runtime**
- **Resposta a incidentes em cloud**
- **Governança contínua**

📌 Segurança que entra só no runtime **chega tarde**.

---

### 🌍 Multicloud Security

> Multicloud sem padrão vira **caos operacional**.

- Normalização de controles entre clouds
- Visibilidade centralizada
- Gestão unificada de identidade
- Padronização de logging
- Governança e políticas comuns
- Risco de shadow IT

---

## 🧪 Labs Práticos (Essenciais para Cloud Security)

> Cloud Security **se aprende configurando, errando e corrigindo**.

- **AWS Well-Architected Labs (Security Pillar)**  
  https://wellarchitectedlabs.com/security/

- **AWS CloudGoat (Vulnerable by Design)**  
  https://github.com/RhinoSecurityLabs/cloudgoat

- **Azure Security Labs (Microsoft Learn)**  
  https://learn.microsoft.com/security/

- **GCP Security Foundations Labs**  
  https://cloud.google.com/security

- **TryHackMe – Cloud Security Labs**  
  https://tryhackme.com/

- **DetectionLab – Cloud**  
  https://github.com/clong/DetectionLab

---

## 📘 Cursos Oficiais (Formação)

### ☁️ AWS
- AWS Security Fundamentals  
  https://aws.amazon.com/training/digital/aws-security-fundamentals/

- AWS Well-Architected – Security Pillar  
  https://aws.amazon.com/architecture/well-architected/

---

### ☁️ Microsoft Azure
- Secure Your Cloud Data  
  https://learn.microsoft.com/training/paths/secure-your-cloud-data/

- Azure Security Engineer (AZ-500)  
  https://learn.microsoft.com/training/paths/design-implement-azure-security/

---

### ☁️ Google Cloud
- Google Cloud Security Foundations  
  https://cloud.google.com/training/security

---

### 🌍 Vendor Neutral
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

## 🏅 Certificações (Validação de Conhecimento)

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

## 📌 Princípios-Chave de Cloud Security

- Identidade é o novo perímetro
- Misconfiguration é o risco dominante
- Logs são obrigatórios
- Segurança precisa escalar automaticamente
- Multicloud exige governança forte

> Cloud muda rápido.  
> **Fundamentos bons duram décadas.**
