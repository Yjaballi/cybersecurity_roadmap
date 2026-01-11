# 🟥 Red Team / Pentest

Esta trilha cobre **testes de intrusão, simulação de adversários e operações ofensivas**, com foco em **descoberta de falhas reais, exploração, pós-exploração e evasão**, sempre com **escopo autorizado**.

Red Team **não é ferramenta**: é **processo, técnica e disciplina**.

---

## 👥 Progressão de Carreira

> A progressão não é linear.  
> Muitos profissionais alternam entre **pentest tradicional** e **red team** conforme o tipo de projeto.

- Pentester Jr  
- Pentester  
- Red Team Operator  
- Exploit Developer  

---

## 🧠 Habilidades Técnicas Essenciais

### 🔍 Enumeração & Reconhecimento
- Reconhecimento passivo e ativo
- Enumeração de serviços, usuários e permissões
- Enumeração web, rede e identidade
- Descoberta de superfície de ataque

**Ferramentas open source:**
- `nmap`
- `masscan`
- `amass`
- `dnsx`
- `whatweb`
- `enum4linux`
- `ldapsearch`

---

### 💥 Exploração
- Exploração de falhas conhecidas (CVEs)
- Exploração lógica e falhas de negócio
- Exploração web e infraestrutura
- Exploração manual (não só framework)

**Ferramentas open source:**
- `metasploit`
- `sqlmap`
- `nikto`
- `ffuf`
- `nuclei`
- `searchsploit`

---

### 🪪 Active Directory Attacks
- Enumeração de AD
- Abuso de permissões
- Kerberoasting / AS-REP Roasting
- Pass-the-Hash / Pass-the-Ticket
- Abuso de GPO e delegações
- Lateral movement

**Ferramentas open source:**
- `BloodHound`
- `SharpHound`
- `CrackMapExec`
- `Impacket`
- `Rubeus`
- `Mimikatz`
- `Responder`

---

### 🔓 Pós-Exploração
- Escalada de privilégios
- Lateral movement
- Persistência
- Pivoting
- Exfiltração controlada

**Ferramentas open source:**
- `linpeas / winpeas`
- `pspy`
- `chisel`
- `ligolo-ng`
- `netcat`

---

### 🕵️‍♂️ Evasão & OpSec
- Evasão de EDR/AV
- Living off the Land (LOLBins)
- Payload obfuscation
- Controle de ruído operacional
- OPSEC em operações longas

**Ferramentas open source:**
- `Covenant`
- `Sliver`
- `Mythic`
- `PowerSploit`
- `Donut`
- `ScareCrow`

---

### 🧬 Exploit Development (Avançado)
- Análise de binários
- Buffer overflow
- Heap exploitation
- Exploração de memória
- Bypass de mitigations (DEP, ASLR)

**Ferramentas open source:**
- `pwntools`
- `Ghidra`
- `radare2`
- `pwndbg`
- `gef`

---

## 📘 Cursos e Documentação (Formação)

### Pentest / Red Team
- **Offensive Security – Training Catalog**  
  https://www.offsec.com/courses/

- **Pentester Academy (INE)**  
  https://ine.com/learning/paths/penetration-testing

- **PortSwigger Web Security Academy (Gratuito)**  
  https://portswigger.net/web-security

---

### Active Directory
- **Red Team Operator AD Labs (TryHackMe)**  
  https://tryhackme.com/

- **AD Security & Attacks (Hack The Box Academy)**  
  https://academy.hackthebox.com/

---

### Exploit Development
- **OpenSecurityTraining**  
  https://opensecuritytraining.info/

- **LiveOverflow Binary Exploitation (YouTube)**  
  https://www.youtube.com/c/LiveOverflow

---

## 🧪 Labs Práticos (Ofensivos)

> Red Team **se aprende errando em lab** antes de errar em cliente.

### Plataformas
- **Hack The Box (HTB)**  
  https://www.hackthebox.com/

- **Hack The Box Academy**  
  https://academy.hackthebox.com/

- **TryHackMe**  
  https://tryhackme.com/

- **PentesterLab**  
  https://pentesterlab.com/

- **VulnHub (VMs locais)**  
  https://www.vulnhub.com/

---

## 🏅 Certificações (Validação de Conhecimento)

### 🔰 Entry / Intermediate
- **eJPT – Junior Penetration Tester**  
  https://elearnsecurity.com/product/ejpt-certification/

- **PNPT – Practical Network Penetration Tester**  
  https://certifications.tcm-sec.com/pnpt/

- **CEH – Certified Ethical Hacker**  
  https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/

- **GPEN – GIAC Penetration Tester**  
  https://www.giac.org/certifications/penetration-tester-gpen/

---

### 🔥 Advanced
- **OSCP – Offensive Security Certified Professional**  
  https://www.offsec.com/certifications/oscp/

- **OSWA – Web Assessor**  
  https://www.offsec.com/certifications/oswa/

- **OSWE – Web Expert**  
  https://www.offsec.com/certifications/oswe/

- **OSEP – Experienced Pentester**  
  https://www.offsec.com/certifications/osep/

- **OSED – Exploit Developer**  
  https://www.offsec.com/certifications/osed/

- **GXPN – GIAC Exploit Researcher**  
  https://www.giac.org/certifications/exploit-researcher-gxpn/

- **CREST CRT / CCT**  
  https://www.crest-approved.org/

---

## 🔗 Integração com Outras Trilhas

- **Purple Team** – validação de detecção
- **Blue Team / SOC** – melhoria de alertas
- **AppSec** – correção estrutural
- **CTI** – simulação de adversários reais
- **GRC / Jurídico** – escopo e autorização

---

## 📌 Princípios-Chave da Trilha Red Team

- Ferramenta não substitui técnica
- Enumeração vale mais que exploit
- OPSEC é parte do ataque
- Relatório é tão importante quanto o acesso
- Red Team bom melhora o Blue Team

---
