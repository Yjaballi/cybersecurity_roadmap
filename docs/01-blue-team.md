# 🟦 Blue Team / SOC / Security Operations

Esta trilha aborda **operações de segurança defensiva**, com foco em **monitoramento, detecção, resposta a incidentes e engenharia de detecção**, tendo o **SIEM como núcleo operacional**, integrado a outras fontes de telemetria (**EDR, Cloud, Apps e CTI**).

---

# 🧩 PARTE 1 — BLUE TEAM  
## Capacidades Defensivas

## 🔵 O que é Blue Team

Blue Team **não é apenas o SOC reagindo a alertas**.  
É o conjunto de **capacidades preventivas, detectivas e responsivas** que atuam **antes, durante e depois do ataque**.

---

## 📊 Domínios Operacionais do Blue Team

### Enquadramento de Atividades, Ferramentas e Responsabilidades

| Domínio Blue Team | Atividades Principais | Tecnologias / Ferramentas | Perfis Envolvidos |
|------------------|----------------------|---------------------------|-------------------|
| **Detection & Response (Core)** | Monitoramento, correlação, resposta inicial | SIEM, EDR/XDR, NDR, UEBA | SOC N1 / N2 / N3 |
| **Exposure Management (Gevul)** | Scans, priorização por risco, correlação com CTI | Vulnerability / Exposure Management | SecOps, AppSec |
| **Network Security Controls** | Segmentação, regras, bloqueios | Firewall / NGFW, IDS, IPS | Network Security |
| **Application Perimeter** | Proteção de aplicações e APIs | WAF, API Security, Bot Protection | AppSec + SOC |
| **Endpoint Protection** | Detecção comportamental e contenção | EDR / XDR | SOC N1 / N2 |
| **Threat-Informed Defense** | Contextualização e priorização | CTI, MITRE ATT&CK | Threat Hunter |
| **Automation & Orchestration** | Playbooks e resposta automática | SOAR, Scripts | SOC N3 |
| **Logging & Telemetry** | Coleta e normalização de logs | Agents, Syslog, APIs | SecOps |
| **Hardening & Preventive Controls** | Redução da superfície de ataque | Patch, Baselines, CIS | Infra / SecOps |
| **Cloud & Platform Security** | Telemetria e controles em nuvem | CSPM, CNAPP, Cloud Logs | Cloud + SOC |

---

## 🔍 Controles Importantes no Blue Team

### 🟠 Gestão de Vulnerabilidades (Gevul)
- Atua **antes do incidente**
- Reduz superfície de ataque
- Alimenta o SOC com contexto real de exploração
- Deve ser correlacionada com **CTI e SIEM**

> Gevul é **Blue Team preventivo**, não ofensivo e não apenas GRC.

---

### 🟠 Firewall / NGFW
- Controle **preventivo e detectivo**
- Permite contenção rápida
- Gera logs críticos para correlação

> Firewall é **sensor e atuador** do Blue Team.

---

### 🟠 IDS / IPS / NDR
- Detecção de scans, exploits e C2
- Complementa EDR (rede ≠ endpoint)
- Fundamental para threat hunting

---

### 🟠 WAF / API Security
- Interseção entre **AppSec e Blue Team**
- SOC responde, AppSec define regra

---

### 🟠 EDR / XDR
- Núcleo da resposta inicial
- Detecção comportamental
- Contenção local imediata

---

# 🏢 PARTE 2 — SOC  
## Security Operations Center (Modelo Operacional)

O **SOC (Security Operations Center)** é a **estrutura operacional** responsável por **executar o Blue Team no dia a dia**, funcionando como o **centro nervoso da detecção e resposta**.

Enquanto **Blue Team** define **capacidades**, o **SOC organiza pessoas, processos e tecnologia** para executá-las continuamente.

---

## 🎯 Objetivos do SOC
- Monitorar eventos em tempo quase real
- Detectar atividades suspeitas ou maliciosas
- Executar contenções rápidas
- Coordenar resposta inicial a incidentes
- Reduzir impacto técnico e de negócio

---

## 🧱 Componentes Fundamentais do SOC

| Pilar | Descrição |
|----|---------|
| **Pessoas** | SOC N1, N2, N3, Detection Engineers, Threat Hunters |
| **Processos** | Playbooks, SLAs, escalonamento, comunicação |
| **Tecnologia** | SIEM, EDR/XDR, NDR, SOAR, CTI |
| **Governança** | Métricas, KPIs, melhoria contínua |

---

## 👥 Papéis Operacionais no SOC

### 🟢 SOC N1 — Monitoramento & Triagem
- Monitoramento contínuo
- Triagem e classificação inicial
- Execução de playbooks simples
- Escalonamento adequado

### 🟡 SOC N2 — Análise & Contenção
- Análise técnica aprofundada
- Correlação entre múltiplas fontes
- Contenção básica (isolamento, bloqueios)
- Apoio técnico ao N1

### 🔴 SOC N3 — Especialista / Engenharia
- Investigação de incidentes complexos
- Criação e tuning de regras
- Threat hunting
- Automação e melhoria contínua

---

## 🟥 CSIRT — Computer Security Incident Response Team

O **CSIRT pode ou não ser separado do N3**

### Responsabilidades do CSIRT
- Coordenação de incidentes relevantes
- Análise técnica aprofundada
- Interface com DFIR, TI, Jurídico e Negócio
- Comunicação executiva
- Lições aprendidas e recomendações estruturais

---

## 🔁 O que o SOC faz (e não faz)

### O SOC faz
- Triagem e validação de alertas
- Correlação de eventos
- Contenção inicial
- Escalonamento técnico e gerencial
- Comunicação durante incidentes

### O SOC não faz (por padrão)
- Forense profunda
- Análise detalhada de malware
- Recuperação de ambientes
- Decisões estratégicas de risco

---

## 📊 Métricas de um SOC Maduro
- MTTD
- MTTR
- Taxa de falsos positivos
- Cobertura MITRE ATT&CK
- Incidentes contidos vs escalados

---

# 👥 Progressão de Carreira

> Não existe progressão linear obrigatória.  
> Em ambientes reais, **nível ≠ senioridade**.

Papéis comuns:
- SOC Analyst N1  
- SOC Analyst N2  
- SOC Analyst N3  
- Detection Engineer  
- Threat Hunter  
- SecOps Engineer  

---

# 🧠 Threat Hunting

Threat Hunting é a atividade **proativa** do Blue Team para identificar ameaças **não detectadas automaticamente**, baseada em **hipóteses e comportamento**.

Fontes usadas:
- SIEM
- EDR / XDR
- NDR
- Logs de Cloud, Firewall, Identity
- MITRE ATT&CK
- CTI

Entregáveis:
- Novas detecções
- Ajustes de regras
- Playbooks aprimorados
- Relatórios de achados

---

# 🧠 Habilidades Técnicas Essenciais

## SIEM & Detecção
- Ingestão de dados
- Normalização e enriquecimento
- Correlação
- Tuning de regras
- Métricas de detecção

## Engenharia de Detecção
- Detecção comportamental
- Uso correto de fontes por TTP
- Integração **SIEM ↔ EDR ↔ CTI**

---

# 🚨 Resposta a Incidentes (SOC)

Resposta no SOC **não é forense profunda**, é **contenção, decisão rápida e coordenação**.

---

# 🤖 Playbooks & Automação
- Playbooks operacionais
- Scripts (Bash, PowerShell, Python)
- SOAR

---

# 📚 Livros Essenciais — Blue Team, SOC & DFIR

## Fundamentos
- **The Practice of Network Security Monitoring** — Richard Bejtlich
- **Applied Network Security Monitoring** — Chris Sanders

## Logs & SIEM
- **Logging and Log Management** — Anton Chuvakin
- **Security Operations Center** — Joseph Muniz

## Incident Response & DFIR
- **Incident Response & Computer Forensics** — Mandia et al.
- **The Art of Memory Forensics**

## Threat Hunting
- **The Threat Hunter’s Handbook**
- **Practical Threat Intelligence and Data-Driven Threat Hunting**

---

# 🧪 Labs Práticos
- TryHackMe (Blue Team)
- CyberDefenders
- LetsDefend
- DetectionLab
- Wazuh Labs

---

# 🏅 Certificações
- CompTIA CySA+
- ISC2 SSCP
- GIAC (GSEC, GCIA, GCIH, GCED, GMON)
- Microsoft SC-200 / SC-100
- CompTIA Security+

---

## 📌 Regra de Ouro

Blue Team não é só reagir.  
É **reduzir a chance do ataque dar certo** e **responder rápido quando ele acontece**.


---

## 🧱 Exemplos de Fabricantes por Domínio (Referência de Mercado)

> 📌 Esta lista é **ilustrativa**, não prescritiva.  
> O objetivo é ajudar a **entender o mercado**, não definir stack.

### 🧠 Detection & Response (Core SOC)
- SIEM: Splunk, Elastic, IBM QRadar, Microsoft Sentinel, Wazuh, ManageEngine, Trio e-Safer
- EDR / XDR: CrowdStrike, Microsoft Defender, SentinelOne, Sophos, Trend Micro
- NDR: Vectra AI, Darktrace, ExtraHop, Lumu

---

### 🧩 Exposure Management / Gevul
- Vulnerability Management: Tenable, Qualys, Rapid7, Ecotrust
- Exposure Management / ASM: Tenable, XM Cyber, Microsoft Defender EASM, SOCRadar
- Suporte a priorização por risco: Tenable, Rapid7, XM Cyber

---

### 🌐 Network Security Controls
- Firewall / NGFW: Palo Alto Networks, Check Point, Cisco
- IDS / IPS: Suricata, Snort, Cisco, Palo Alto Networks
- NDR / Network Analytics: ExtraHop, Vectra AI, Darktrace, Lumu

---

### 🔐 Application Perimeter (WAAP)
- WAF / WAAP: Akamai, Cloudflare, Imperva, Cequence
- API Security: Cequence, Akamai, Salt Security
- Bot Management: Akamai, Cloudflare, Imperva, Cequence

---

### 🖥️ Endpoint Protection
- EDR: CrowdStrike, Microsoft Defender, SentinelOne, Sophos, Trend Micro
- XDR: Palo Alto Cortex, Microsoft, Sophos, Trend Micro

---

### 🤖 Automation & Orchestration
- SOAR: Splunk SOAR, Cortex XSOAR, Swimlane, ManageEngine
- Automação Corporativa: ManageEngine, ServiceNow
- Scripts: Python, PowerShell, Bash

---

### 📊 Logging & Telemetry
- Agentes e coleta: Wazuh, Elastic Agent, Splunk UF, ManageEngine
- Cloud Logs: AWS CloudTrail, Azure Monitor, GCP Logging
- APIs e integrações: nativas de vendors + custom

---

### 🛡️ Hardening & Preventive Controls
- Patch Management: ManageEngine, Microsoft, Tenable
- Baselines / CIS: CIS Benchmarks, Microsoft Security Baselines
- Compliance técnico: scripts, GPOs, IaC security

---
