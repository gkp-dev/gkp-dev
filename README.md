### Bonjour, je suis Jean-Loris Gankpe 👋

## 🚀 GTM Engineer · AI Applied Engineer
**Développeur fullstack passé par les Sales Ops : je construis les agents IA et les systèmes qui font tourner les équipes Sales et CS.**

Deux casquettes, un même métier : partir d'un vrai problème d'équipe (un CRM mal rempli, des appels perdus, des heures de saisie), et livrer un système en production qui le règle, puis le mesurer.

---

### ⚡ En ce moment
* 🔭 **Poste actuel :** Sales Ops & AI dans une startup française d'IA conversationnelle
* 🤖 **AI Engineer :** un agent Slack en production qui lit et écrit dans HubSpot (Python, Google ADK, Gemini avec repli sur Claude, Cloud Run, Vertex AI Agent Engine), suite d'évaluation rejouable de 36 scénarios, confirmation obligatoire avant chaque écriture
* 📈 **GTM Engineer :** marché adressable de ~16 700 entreprises construit avec Clay et des sous-agents de recherche ; appels Fathom versés automatiquement dans HubSpot avec n8n ; référentiel Supabase synchronisé chaque nuit depuis le CRM
* 🌱 **Je creuse :** déploiement d'agents sur Google Cloud, sécurité des agents (moindre privilège, prompt injection), évaluations

---

### 🛠️ Stack

**IA & agents**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" />
</p>

**GTM & automatisation**
<p>
  <img src="https://img.shields.io/badge/HubSpot-FF7A59?style=for-the-badge&logo=hubspot&logoColor=white" />
  <img src="https://img.shields.io/badge/Clay-000000?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Pipedrive-017737?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" />
</p>

**Ingénierie & cloud**
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
</p>

---

### 🏆 Projets

**🤖 Agents IA en production**

| Projet | Stack | Ce que ça fait |
| :--- | :--- | :--- |
| **Agent CRM dans Slack** | `Python` `Google ADK` `Gemini` `Claude` `Cloud Run` `Vertex AI` | Toute l'entreprise (32 personnes) crée et met à jour contacts, leads, deals et tâches HubSpot en langage naturel, avec enrichissement Clay. Confirmation obligatoire avant chaque écriture, aucun outil de suppression, repli entre modèles, 36 scénarios d'évaluation rejoués avant chaque mise en production. |
| **Agent de lecture des contrats** | `n8n` `Claude` `HubSpot` | Lit les contrats signés et remplit 44 champs du deal et de ses lignes de produits dans le CRM. |
| **Voicebots et chatbots clients** | `IA vocale` `API` `Salesforce` | Agents vocaux et écrits branchés aux outils du client (Salesforce, API, n8n), avec passage de relais à un humain. Chez Les Sherpas : 500+ appels hors horaires par mois. |
| **Agents de veille** | `n8n` `Gemini` `WhatsApp API` | Veille RH, juridique et économique résumée automatiquement, et note vocale IA hebdomadaire envoyée sur WhatsApp. |

**📈 Agents GTM et gestion du CRM**

| Projet | Stack | Ce que ça fait |
| :--- | :--- | :--- |
| **Plateforme CRM interne** | `Next.js` `FastAPI` `Supabase` | Audit du CRM HubSpot, documentation des champs et formation des équipes, en français, anglais et arabe. Référentiel Supabase synchronisé chaque nuit depuis HubSpot, avec historique des changements. |
| **Marché adressable** | `Clay` `sous-agents de recherche` | ~16 700 entreprises identifiées et enrichies pour la prospection. |
| **Appels vers le CRM** | `n8n` `Fathom` `Aircall` `Gemini` | Chaque appel commercial est résumé et rattaché à la bonne fiche, dans HubSpot ou Pipedrive. 328 appels versés dans HubSpot. |
| **Lecture de factures** | `n8n` `OpenAI` `PandaDoc` | Agent qui lit les factures d'un client du BTP et génère ses documents. |
| **Hygiène du CRM** | `HubSpot` `n8n` | 50 000+ fiches restructurées, routage des leads, relances et synchronisation automatisés. |

**🔧 Open source et outillage**

| Projet | Stack | Ce que ça fait |
| :--- | :--- | :--- |
| **[pipedrive-mcp-server](https://github.com/gkp-dev/pipedrive-mcp-server)** | `TypeScript` `MCP` | Serveur MCP open source pour piloter Pipedrive depuis un assistant IA. |
| **Skills Claude Code partagés** | `Claude Code` | Skills de prospection, de gestion du CRM et de création de démos pour les équipes Sales et CS, présentés en atelier à 11 personnes. |
| **Migration Zapier → n8n** | `n8n` `Docker` | 50+ workflows migrés, environ 25 % de coûts d'exécution en moins. |

👉 **[Démos et détails sur mon portfolio](https://portfolio.gkp-dev.com/)**

---

### 📫 Me contacter

[<img align="left" alt="Portfolio" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/googlechrome.svg" />][portfolio]
[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="Email" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />][email]

<br />

[portfolio]: https://portfolio.gkp-dev.com/
[linkedin]: https://www.linkedin.com/in/jean-loris-gankpe-b421921b2/
[email]: mailto:gkprofessionel@gmail.com
