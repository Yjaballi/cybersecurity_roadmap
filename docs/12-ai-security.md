# 🤖 Segurança de Inteligência Artificial (AI Security)

Este documento descreve os **fundamentos, riscos, controles e carreiras** relacionados à **segurança de sistemas de Inteligência Artificial**, incluindo **Machine Learning (ML), LLMs, GenAI e AI-enabled systems**.

A segurança de IA deve ser tratada como uma **extensão natural da segurança de aplicações, dados e infraestrutura**, com riscos próprios.

---

## 🎯 Objetivo

- Entender **como sistemas de IA funcionam**
- Identificar **vetores reais de ataque**
- Definir **controles técnicos e organizacionais**
- Integrar segurança de IA ao **SDLC, DevSecOps e GRC**
- Preparar profissionais para **AI Security / AI Governance**

---

## 🧱 Fundamentos Técnicos de IA (Obrigatórios)

### Conceitos de IA e ML
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning
- Modelos supervisionados vs não supervisionados
- Treinamento, validação e inferência
- Overfitting e underfitting

### LLMs e GenAI
- Large Language Models (LLMs)
- Prompt, contexto e tokens
- Fine-tuning vs RAG (Retrieval-Augmented Generation)
- Modelos fechados vs open source
- APIs de inferência

---

## 🧨 Principais Ameaças em Segurança de IA

### Ataques ao Modelo
- **Prompt Injection**
- **Jailbreak de LLM**
- Model Inversion
- Model Extraction
- Membership Inference

### Ataques aos Dados
- **Data Poisoning**
- Training Data Leakage
- Dataset Bias e manipulação intencional

### Ataques à Infraestrutura de IA
- Comprometimento de pipelines de ML
- Abuso de APIs de inferência
- Falhas de autenticação e autorização
- Exposição de chaves e tokens

### Ataques de Uso Indevido
- Geração de código malicioso
- Geração de phishing e engenharia social
- Abuso de automações baseadas em IA

---

## 🧩 Superfícies de Ataque em Sistemas de IA

- Prompts e entradas do usuário
- APIs de inferência
- Pipelines de dados
- Ambientes de treinamento
- Artefatos de modelo (weights, checkpoints)
- Integrações com sistemas corporativos
- Plugins e ferramentas conectadas ao modelo

---

## 🛡️ Controles de Segurança para IA

### Controles Técnicos
- Validação e sanitização de prompts
- Rate limiting e autenticação forte
- Segregação de ambientes (train / test / prod)
- Monitoramento de inferência
- Logging e auditoria de prompts e respostas
- Proteção de modelos e artefatos
- Isolamento de execução (containers / sandbox)

### Controles de Aplicação
- Secure AI SDLC
- Threat Modeling específico para IA
- Testes de segurança em prompts
- Red teaming de IA (AI Red Teaming)
- Guardrails e filtros de saída

### Controles de Dados
- Classificação de dados
- Minimização de dados
- Mascaramento e anonimização
- Controle de acesso a datasets
- Auditoria de datasets usados em treinamento

---

## 🧠 Frameworks e Referências Técnicas

### Frameworks
- **NIST AI Risk Management Framework (AI RMF)**
- **OWASP Top 10 for LLM Applications**
- **MITRE ATLAS (Adversarial Threat Landscape for AI Systems)**
- ISO/IEC 23894 (AI Risk Management – quando aplicável)
- ISO/IEC 27001 / 27701 (controles transversais)

### Conceitos Importantes
- AI Risk Management
- Explainable AI (XAI)
- Responsible AI
- AI Governance
- Human-in-the-loop

---

## 🔁 Integração com DevSecOps e GRC

### DevSecOps
- Segurança desde o design (shift-left)
- Pipelines de ML seguros
- Validação automática de modelos
- Monitoramento contínuo de uso indevido

### GRC e Conformidade
- Avaliação de riscos de IA
- Políticas de uso aceitável de IA
- Governança de modelos
- LGPD e proteção de dados em IA
- Preparação para regulações de IA

---

## 👥 Carreiras em Segurança de IA

### Papéis Técnicos
- AI Security Engineer
- AppSec com foco em IA
- ML Engineer com foco em segurança
- AI Red Team / AI Blue Team

### Papéis de Governança
- AI Risk Analyst
- AI Governance Specialist
- Security Architect (AI-enabled systems)
- CISO com responsabilidade sobre IA

---

## 🎓 Cursos e Certificações (Referência)

### Cursos
- Secure AI / AI Security (vendor e open)
- Cursos de ML básico (fundamentais)
- OWASP LLM Security Labs
- NIST AI RMF Training

### Certificações (quando aplicável)
- Certificações de AppSec / Cloud / GRC aplicadas a IA
- Certificações emergentes específicas de AI Security (avaliar maturidade)

---
