# ⛓️ Segurança de Blockchain & Web3

Esta trilha aborda **segurança de ecossistemas blockchain e Web3**, com foco em **smart contracts, protocolos, infraestrutura descentralizada, carteiras, bridges, governança e risco sistêmico**.

Blockchain Security **não é só auditar smart contract**.  
É **criptografia, economia, código, arquitetura distribuída e governança**, tudo ao mesmo tempo.

> ⚠️ Em Web3, **bug vira perda financeira direta**.  
> Não existe rollback, não existe “patch depois”.

---

## 🎯 Objetivos da Trilha

- Entender **como blockchains realmente funcionam**
- Identificar **vetores reais de ataque em Web3**
- Aplicar **controles técnicos, econômicos e arquiteturais**
- Preparar profissionais para **auditoria, defesa e arquitetura segura**
- Conectar **segurança técnica, risco financeiro e governança**

---

## 👥 Carreiras em Blockchain Security

- **Blockchain Security Engineer**
- **Smart Contract Auditor**
- **Web3 Security Researcher**
- **Protocol Security Architect**
- **DeFi Risk Analyst**
- **Security Lead (Web3 / Crypto)**

> Em Web3, segurança é **core business**, não suporte.

---

## 🧱 Fundamentos Técnicos (Obrigatórios)

### 🔗 Conceitos de Blockchain
- Ledger distribuído
- Consenso (PoW, PoS, variantes)
- Imutabilidade e finality
- Chaves públicas e privadas
- Transações, blocos e estados
- On-chain vs off-chain

---

### 🔐 Criptografia Aplicada
- Hash functions
- Assinaturas digitais
- Merkle Trees
- Zero-Knowledge Proofs (ZKPs)
- Threshold signatures
- Multi-sig

> Falha criptográfica = falha sistêmica.

---

### 🧠 Economia & Incentivos (Crítico)
- Tokenomics
- Game theory
- Incentive alignment
- MEV (Maximal Extractable Value)
- Ataques econômicos

> Muitos ataques **não são bugs**, são **incentivos mal desenhados**.

---

## 🧨 Principais Ameaças em Blockchain / Web3

### 🔓 Smart Contracts
- Reentrancy
- Integer overflow / underflow
- Access control flaws
- Oracle manipulation
- Flash loan attacks
- Logic bugs
- Unsafe upgradeability

---

### 🌉 Infraestrutura & Protocolos
- Bridge exploits
- Consensus manipulation
- Validator compromise
- RPC abuse
- Node poisoning
- DNS hijacking

---

### 💼 Carteiras & Usuários
- Private key leakage
- Phishing e wallet drainers
- Malicious dApps
- Approval abuse
- Seed phrase compromise

---

### 🧠 Governança & DAO
- Governance capture
- Vote manipulation
- Sybil attacks
- Economic majority attacks

---

## 🧩 Superfícies de Ataque Web3

- Smart contracts
- Wallets (hot / cold)
- RPC endpoints
- Bridges
- Oracles
- Frontends Web3
- Governance mechanisms
- Off-chain services

---

## 🛡️ Controles de Segurança em Blockchain

### 🔧 Técnicos
- Secure smart contract patterns
- Formal verification
- Static & dynamic analysis
- Fuzzing
- On-chain monitoring
- Rate limiting de RPC
- Multisig e timelocks

---

### 🧪 Secure Web3 SDLC
- Threat modeling para Web3
- Auditorias independentes
- Testes econômicos
- Bug bounty programs
- Monitoramento contínuo on-chain

---

### 🧠 Governança & Risco
- Defense-in-depth em protocolos
- Circuit breakers
- Emergency pause
- Risk committees
- Disclosure responsável

---

## 📘 Frameworks, Normas e Referências

### 🔗 Frameworks Técnicos
- **OWASP Smart Contract Top 10**  
  https://owasp.org/www-project-smart-contract-top-10/

- **Ethereum Smart Contract Best Practices**  
  https://consensys.github.io/smart-contract-best-practices/

- **Trail of Bits – Blockchain Security Resources**  
  https://github.com/trailofbits/blockchain-security

---

### 🧭 Governança & Risco
- **DeFi Risk Framework (Gauntlet / Community)**  
  https://gauntlet.network/

- **Crypto Risk Framework (WEF)**  
  https://www.weforum.org/

---

## 🧪 Labs Práticos (Blockchain / Web3)

> Blockchain security **se aprende explorando exploits reais**.

### Labs e Ambientes
- **Damn Vulnerable DeFi**  
  https://github.com/SunWeb3Sec/DeFiHackLabs

- **Ethernaut (OpenZeppelin)**  
  https://ethernaut.openzeppelin.com/

- **Capture The Ether**  
  https://capturetheether.com/

- **Paradigm CTF (Blockchain)**  
  https://ctf.paradigm.xyz/

- **Foundry / Hardhat Test Labs**  
  https://book.getfoundry.sh/

---

## 🧰 Ferramentas Importantes

### 🔍 Análise & Auditoria
- **Slither** – https://github.com/crytic/slither
- **Mythril** – https://github.com/ConsenSys/mythril
- **Manticore** – https://github.com/trailofbits/manticore
- **Echidna (fuzzing)** – https://github.com/crytic/echidna

---

### 🧠 Desenvolvimento Seguro
- **Hardhat** – https://hardhat.org/
- **Foundry** – https://github.com/foundry-rs/foundry
- **OpenZeppelin Contracts** – https://openzeppelin.com/contracts/

---

### 🔎 Monitoramento On-chain
- **Tenderly** – https://tenderly.co/
- **Forta (Detection Network)** – https://forta.org/

---

## 📘 Cursos e Formação

### Blockchain Security
- **Secureum Bootcamp**  
  https://secureum.xyz/

- **Trail of Bits – Blockchain Security Training**  
  https://www.trailofbits.com/training/

- **Ethernaut CTF (OpenZeppelin)**  
  https://ethernaut.openzeppelin.com/

---

### Complementares
- **Cryptography I – Stanford (Dan Boneh)**  
  https://crypto.stanford.edu/~dabo/courses/onlinecrypto/

---

## 🏅 Certificações (Contexto Web3)

> Ainda **não existe certificação universal** como CISSP em Web3.  
Avaliar sempre **reputação técnica**, não marketing.

- Secureum Certifications (Skill-based)
- Auditor programs de plataformas (Ethereum, Solana, etc.)

---

## 📚 Livros Essenciais de Blockchain & Web3 Security

### Mastering Ethereum  
**Autor:** Andreas M. Antonopoulos  
> Base técnica obrigatória para entender Ethereum e smart contracts.

---

### Blockchain Security from the Ground Up  
**Autor:** George K. Thiruvathukal  
> Visão estrutural de segurança em blockchains.

---

### Building Secure and Reliable Smart Contracts  
**Organização:** Trail of Bits  
> Guia técnico usado em auditorias reais.

---

### DeFi and the Future of Finance  
**Autores:** Campbell R. Harvey et al.  
> Entendimento profundo de riscos econômicos em DeFi.

---

### Hands-On Smart Contract Development with Solidity  
**Autor:** Kevin Solorio  
> Desenvolvimento com foco em segurança prática.

---

## 🔗 Integração com Outras Trilhas

- **AppSec** – lógica, código e testes
- **Cloud Security** – RPC, nodes e infra
- **IAM & Zero Trust** – identidade e chaves
- **GRC / Risco** – impacto financeiro e compliance
- **CTI** – campanhas e ataques Web3

---

## 📌 Princípios-Chave de Blockchain Security

- Código é dinheiro
- Bug é perda financeira
- Incentivo mal desenhado é vulnerabilidade
- Auditoria não elimina risco
- Governança importa tanto quanto criptografia

---

> Blockchain muda rápido.  
> **Criptografia, arquitetura e risco continuam sendo a base.**
