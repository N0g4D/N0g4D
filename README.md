# 👋 Hi, I'm Alessio Malerba

🚀 **Senior Power Platform Solution Architect (PL-600) | Pro-Dev Security Specialist**

I design and deliver enterprise solutions in the **Microsoft Cloud ecosystem**, bringing **software engineering discipline, ALM governance, and security** to low-code. Most of my client work today is **legacy modernization in banking**: moving aging RPA and desktop databases onto governed Power Platform architectures.

I operate as an **Independent Consultant**, helping B2B organizations (Banking, Energy, Enterprise) retire technical debt and extend the platform through Pro-Dev integration. My open-source work sits where that world meets two others: **AI agents** (Model Context Protocol) and **verifiable, privacy-preserving systems on EVM chains**.

🎓 PL-600 Solution Architect Expert · PL-400 Developer Associate · BSc Computer Science (University of Genoa) · CyberChallenge.IT 2022

---

## 🛠️ What I'm Currently Working On

### 🏦 Client work: legacy modernization and enterprise automation

- **Blue Prism → Power Automate Desktop.** Migration of back-office processes for two Italian banks: a monthly securities-statement control, checked for parity against production Blue Prism logs, and a set of account and cheque inquiry flows built once for both banks.
- **Microsoft Access → Power Apps + SQL Server.** Re-platforming of a legacy Access line-of-business application: Power Apps front end, SQL Server on-premises through the data gateway, stored procedures instead of a custom API layer, Power Automate cloud flows for orchestration, and desktop robots only where a legacy system exposes no API.
- **Production support** for an enterprise BPO automation solution built on Power Platform.

### 🤖 Open source: MCP tool connections for AI agents

Two integrations for [Omega](https://github.com/singnet/Omega), SingularityNET's open-source agent framework, both built on the Model Context Protocol (MCP):

- **[omega-connect](https://github.com/N0g4D/omega-connect)**: an OmegaHive app that lets the minds (agents) in a hive use outside tools through MCP servers, with Microsoft 365 as the first showcase. A tool counts as a read only after a person has reviewed it, every write waits for a named person's approval, and a tool whose definition changes drops back to "write". Demoed end to end on a live hive against a Microsoft 365 tenant: Teams channel read, approved post.<br>
  <sub>Python · MCP · Microsoft Entra OAuth · Microsoft Graph · Apache-2.0</sub>
- **[omega-mcp](https://github.com/N0g4D/omega-mcp)**: an MCP client plugin for an Omega that runs on its own. The agent gets three tools to list, inspect, and call the MCP servers its operator configures; a tool that changes data is refused unless the operator allows it.<br>
  <sub>Python · MeTTa · MCP · Apache-2.0</sub>

### 🔐 Web3: verifiable and confidential by design

- **[Ancorhash](https://github.com/N0g4D/azure-web3-notarizer)**: B2B document notarization on EVM chains with zero data leakage. The SHA-256 hash is computed in the browser, so the document never leaves the device; a relayer pays the gas, and billing is fiat-ready. At ETHRome 2026 I prototyped a [Confidential RWA Vault](https://github.com/N0g4D/azure-web3-notarizer/tree/ethrome-2026) on top of it: encrypted storage on Swarm, a queryable index with expiry on Arkiv, an ERC-721 anchor on Avalanche Fuji. Next: a hosted deployment on Azure Functions and an end-to-end demo driven by a Power Automate Desktop flow.<br>
  <sub>.NET 10 · Azure Functions (isolated worker) · Nethereum · React · TypeScript</sub>
- **[Atlantysm](https://github.com/N0g4D/atlantysm)**: a fully on-chain game. The MVP runs on MUD v2: every crystal is an ERC-6551 account that plays on its own behalf, combat is commit–reveal, and 152 Foundry tests cover the contracts. Now designing Season 0 on Sepolia: a single immutable contract where each crystal's element, level, and mana stay encrypted with Zama's FHEVM, and a duel publishes only who won.<br>
  <sub>Solidity · Foundry · MUD v2 · FHEVM · React · viem</sub>
- **Research:** security review tooling for confidential (FHE) smart contracts.

---

## 🧩 Core Tech Stack

- **Architecture & Governance:** Power Platform Solution Architecture (PL-600), Dataverse Security, DLP Policies, Center of Excellence (CoE), ALM and CI/CD with GitHub Actions and Azure DevOps.
- **Automation & Legacy Modernization:** Power Automate (Cloud & Desktop), Blue Prism migration, Power Apps, Power Pages, SQL Server (T-SQL, stored procedures), on-premises data gateway.
- **Pro-Dev Extensibility:** C# / .NET 10, Azure Functions, React, TypeScript, Custom Connectors, Power Apps Component Framework (PCF; see [PCF Mega Library](https://github.com/N0g4D/pcf-mega-library)).
- **AI & Agents:** Model Context Protocol (MCP), Microsoft Graph, Microsoft Entra ID, Copilot Studio, Azure AI Document Intelligence, Python.
- **Web3 & Security:** Solidity, Foundry, Slither, MUD v2, ERC-6551, FHE (Zama FHEVM), Nethereum, viem, Applied Cryptography.

---

## 💼 Professional Experience

- **Independent Solution Architect & Tech Lead** *(Freelance)*<br>
  *Focus: Legacy modernization in banking (Blue Prism → Power Automate Desktop, Access → Power Apps + SQL Server), Architectural Refactoring, Pro-Dev integrations.*
- **Microsoft Solution Architect** @ **Protiviti**<br>
  *Focus: Custom ERP systems, Power Pages, React/PCF development.*
- **Power Platform Engineer** @ **Cluster Reply**<br>
  *Focus: Enterprise solutions for Tier-1 Energy & Banking clients, Agile delivery.*

---

📬 **Get in Touch**<br>
✉️ [info@alessiomalerba.it](mailto:info@alessiomalerba.it)<br>
💼 [LinkedIn](https://www.linkedin.com/in/alessio-malerba-969088204/)

---

> *"Low-code doesn’t replace development — it enhances it. Architecture governs them both."*
