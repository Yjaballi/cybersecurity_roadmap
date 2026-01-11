# 🤖 Segurança de Inteligência Artificial (AI Security)

Este documento descreve os **fundamentos, riscos, controles e carreiras** relacionados à **segurança de sistemas de Inteligência Artificial**, incluindo **Machine Learning (ML), LLMs, GenAI e AI-enabled systems**.

Segurança de IA **não é uma disciplina isolada**.  
Ela é uma **extensão natural de AppSec, Data Security, Cloud, DevSecOps e GRC**, com **novas superfícies de ataque**.

---

## 🎯 Objetivos da Trilha

- Entender **como sistemas de IA realmente funcionam**
- Identificar **vetores reais de ataque (não teóricos)**
- Aplicar **controles técnicos e organizacionais**
- Integrar segurança de IA ao **SDLC, DevSecOps e GRC**
- Preparar profissionais para **AI Security e AI Governance**

---

## 🧱 Fundamentos Técnicos de IA (Obrigatórios)

### Conceitos de IA e ML
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning
- Modelos supervisionados, não supervisionados e por reforço
- Pipeline de ML: coleta → treinamento → validação → inferência
- Overfitting, underfitting e data leakage

Conteúdos base:
- https://developers.google.com/machine-learning/crash-course
- https://www.coursera.org/learn/machine-learning

---

### LLMs e GenAI
- Large Language Models (LLMs)
- Tokens, contexto e embeddings
- Prompting e prompt chaining
- Fine-tuning vs **RAG (Retrieval-Augmented Generation)**
- Modelos fechados vs open source
- APIs de inferência e agentes

Conteúdos:
- https://platform.openai.com/docs
- https://huggingface.co/docs
- https://lilianweng.github.io/posts/2023-06-23-agent/

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
- Training data leakage
- Dataset bias intencional
- Manipulação de datasets externos (RAG)

### Ataques à Infraestrutura de IA
- Comprometimento de pipelines de ML
- Abuso de APIs de inferência
- Exposição de tokens e chaves
- Falhas de IAM em serviços de IA
- Escalada via plugins/agentes

### Ataques de Uso Indevido
- Geração de malware
- Phishing e engenharia social em escala
- Abuso de automações baseadas em IA
- Bypass de controles humanos

---

## 🧩 Superfícies de Ataque em Sistemas de IA

- Prompts e entradas do usuário
- APIs de inferência
- Pipelines de dados
- Ambientes de treinamento
- Artefatos de modelo (weights, checkpoints)
- Integrações com sistemas corporativos
- Plugins, agentes e ferramentas externas

---

## 🛡️ Controles de Segurança para IA

### 🔧 Controles Técnicos
- Validação e sanitização de prompts
- Rate limiting e autenticação forte
- Isolamento de ambientes (train / test / prod)
- Monitoramento de inferência
- Logging e auditoria de prompts e respostas
- Proteção de modelos e artefatos
- Sandbox / containers para execução

---

### 🧪 Controles de Aplicação (Secure AI SDLC)
- Threat Modeling específico para IA
- Testes de segurança em prompts
- Red Teaming de IA
- Guardrails de entrada e saída
- Human-in-the-loop para decisões críticas

---

### 🧬 Controles de Dados
- Classificação e rotulagem de dados
- Minimização de dados
- Mascaramento e anonimização
- Controle de acesso a datasets
- Auditoria de datasets de treinamento

---

## 🧠 Frameworks e Referências Técnicas

### Frameworks Oficiais
- **NIST AI Risk Management Framework (AI RMF)**  
  https://www.nist.gov/itl/ai-risk-management-framework

- **OWASP Top 10 for LLM Applications**  
  https://owasp.org/www-project-top-10-for-large-language-model-applications/

- **MITRE ATLAS – Adversarial Threat Landscape for AI Systems**  
  https://atlas.mitre.org/

- **ISO/IEC 23894 – AI Risk Management**  
  https://www.iso.org/standard/77304.html

- **ISO/IEC 27001 / 27701** (controles transversais)

---

## 🧰 Ferramentas Open Source Importantes

### 🔍 AI / LLM Security
- **PromptFoo** – https://github.com/promptfoo/promptfoo
- **Garak (LLM Vulnerability Scanner)** – https://github.com/leondz/garak
- **LLM Guard** – https://github.com/protectai/llm-guard
- **Rebuff (Prompt Injection Defense)** – https://github.com/protectai/rebuff

---

### 🧪 Red Teaming de IA
- **Microsoft PyRIT** – https://github.com/Azure/PyRIT
- **OpenAI Evals (framework)** – https://github.com/openai/evals
- **AI Red Teaming Resources (NIST)**  
  https://airc.nist.gov/

---

### 🔐 Data & Pipeline Security
- **MLflow** – https://mlflow.org/
- **Great Expectations (Data Quality)** – https://greatexpectations.io/
- **OpenLineage** – https://openlineage.io/

---

## 🧪 Labs Práticos (AI Security)

> Segurança de IA **se aprende explorando modelos reais**.

### Labs e Ambientes
- **OWASP LLM Security Labs**  
  https://github.com/OWASP/www-project-top-10-for-large-language-model-applications

- **Prompt Injection Playground**  
  https://github.com/evilrobot01/prompt-injection-playground

- **TryHackMe – AI & LLM Rooms (em evolução)**  
  https://tryhackme.com/

- **HuggingFace Spaces (model testing)**  
  https://huggingface.co/spaces

---

## 🔁 Integração com DevSecOps e GRC

### DevSecOps
- Segurança desde o design
- Pipelines de ML seguros
- Versionamento de modelos
- Monitoramento contínuo de inferência
- Integração com CI/CD

---

### GRC & Conformidade
- Avaliação de risco de IA
- Políticas de uso aceitável de IA
- Governança de modelos
- LGPD / GDPR e dados usados em IA
- Preparação para regulações de IA (EU AI Act)

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
- CISO responsável por IA

---

## 🎓 Cursos e Capacitação

### Cursos Oficiais
- **NIST AI RMF Training**  
  https://www.nist.gov/itl/ai-risk-management-framework

- **OWASP LLM Security Workshops**  
  https://owasp.org/

- **Microsoft – Secure Generative AI**  
  https://learn.microsoft.com/security/engineering/secure-ai

- **Google – Responsible AI**  
  https://ai.google/responsibility/

---

### 🤖 Certificação em Segurança de Inteligência Artificial (AI Security)

- **CompTIA SecAI+ (CY0-001)**  
  https://www.comptia.org/en-us/certifications/secai/

Recomenda-se combinar:
- **AppSec (OSWE, CSSLP)**
- **Cloud Security (CCSP, AWS Security)**
- **GRC / Risk (CISSP, CRISC)**
- **Privacidade (CDPSE, ISO 27701)**

Certificações emergentes devem ser avaliadas com cautela.

---

## 📌 Princípios-Chave de Segurança de IA

- IA é software + dados + infra
- Prompt é superfície de ataque
- Modelo sem governança vira risco
- Automação amplia impacto do erro
- Segurança de IA é contínua, não projeto

---
## 📚 Livros Essenciais de Segurança em Inteligência Artificial (AI Security)

Esta lista reúne **livros amplamente reconhecidos** por profissionais, pesquisadores e órgãos reguladores para entender **segurança, risco, abuso e governança de sistemas de IA**, incluindo **ML, LLMs, GenAI e sistemas autônomos**.

São leituras usadas por:
- AI Security Engineers
- Security Architects
- CISOs e GRC
- Pesquisadores de ML Security
- Times de Red Team / Blue Team focados em IA

---

## 🧱 Fundamentos de IA, Risco e Segurança

### Artificial Intelligence Safety and Security  
**Autores:** Roman Yampolskiy  

📌 **Livro referência acadêmica** sobre riscos reais de IA.

Cobre:
- Falhas de segurança em sistemas de IA
- Ataques adversariais
- Risco sistêmico e uso indevido
- Segurança de IA além do hype de GenAI

> Muito citado em pesquisas e debates regulatórios.

---

### Machine Learning Security  
**Autores:** Ling Huang, Anthony D. Joseph  

📌 Base técnica sólida em **ML Security**.

Cobre:
- Data poisoning
- Model extraction
- Model inversion
- Ataques adversariais
- Defesa em pipelines de ML

---

## 🧨 Ataques, Abusos e Adversarial ML

### Adversarial Machine Learning  
**Autores:** Anthony D. Joseph, Blaine Nelson  

📌 Referência clássica em **ataques contra modelos de ML**.

Cobre:
- Ataques de evasão
- Poisoning
- Robustez de modelos
- Limitações reais das defesas

---

### The Hundred-Page Machine Learning Book  
**Autor:** Andriy Burkov  

📌 Não é livro de segurança, mas é **leitura obrigatória** para qualquer profissional de AI Security.

Cobre:
- Como ML realmente funciona
- Onde erros e riscos surgem
- Base necessária para threat modeling em IA

> Segurança sem entender ML vira achismo.

---

## 🤖 LLMs, GenAI & Sistemas Modernos

### Generative AI Security  
**Autor:** Ben Potter  

📌 Um dos primeiros livros focados **exclusivamente em segurança de GenAI**.

Cobre:
- Prompt injection
- Jailbreaks
- Abuso de LLMs
- Riscos de automação com IA
- Controles técnicos e organizacionais

---

### Securing Machine Learning Systems  
**Autores:** Chris Wysopal et al.  

📌 Abordagem prática conectando **AppSec + ML**.

Cobre:
- Secure ML pipelines
- Threat modeling de IA
- Integração com DevSecOps
- Segurança de dados e modelos

---

## 🧭 Governança, Ética e Regulação de IA

### The Alignment Problem  
**Autor:** Brian Christian  

📌 Fundamental para entender **risco sistêmico e desalinhamento de IA**.

Cobre:
- Decisões automatizadas
- Impacto social
- Falhas não técnicas que viram incidentes reais

---

### Weapons of Math Destruction  
**Autora:** Cathy O’Neil  

📌 Não é técnico, mas é **essencial para GRC e liderança**.

Cobre:
- Risco de modelos opacos
- Decisões automatizadas em escala
- Falhas éticas que viram risco legal e reputacional

---

### Ethics of Artificial Intelligence and Robotics  
**Autor:** Vincent Müller (Editor)

📌 Referência acadêmica usada em **governança e regulação de IA**.

---

## 🧠 Arquitetura, Segurança & Decisão

### Security Engineering (Applied to AI Systems)  
**Autor:** Ross Anderson  

📌 Embora não seja específico de IA, é **fundamental para arquitetar sistemas de IA seguros**.

Por quê?
- IA é sistema distribuído
- Confiança, identidade, dados e governança continuam valendo
- Ataques exploram arquitetura, não só modelo

---

### Designing Secure Systems  
**Autores:** Liran Tal, Adar Weidman  

📌 Aplicável diretamente a **AI-enabled systems**.

Cobre:
- Design seguro
- Threat modeling
- Integração de segurança desde o início

---

## 🎯 Como Usar Esta Lista

- 📌 **Técnicos:** comece por *Machine Learning Security* e *Adversarial ML*
- 📌 **AppSec / DevSecOps:** *Securing Machine Learning Systems*
- 📌 **Executivo / GRC:** *Alignment Problem* + *Weapons of Math Destruction*
- 📌 **Arquitetura:** *Security Engineering* + *Designing Secure Systems*

> 🔎 **AI Security não é mágica**  
> É **engenharia, dados, risco e decisão — só que em escala maior**.

---

## ⚠️ Observação Importante

Esses livros:
- ❌ não ensinam prompt bonito
- ❌ não prometem “IA segura por design”
- ❌ não vendem ferramenta

Mas:
- ✅ constroem pensamento crítico
- ✅ ajudam a antecipar incidentes
- ✅ preparam para decisões difíceis sobre IA

---

> IA amplia capacidade.  
> **Segurança de IA amplifica responsabilidade.**

