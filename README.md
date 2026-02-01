# emoji-library.

---

📁 1. /docs/README.md

`

# GitDigital Emoji Library

The GitDigital Emoji Library is the visual language of the GitDigital ecosystem.  
It defines the emojis used for repositories, teams, roles, badges, workflows, and contributor‑economy systems.

This library acts as the source of truth for:
- Emoji taxonomy  
- Repo prefix mapping  
- Contributor badges  
- Governance roles  
- Protocol categories  
- Design system rules  
- Machine‑readable registry for bots  

Every GitDigital organization, repo, and product should reference this library to ensure consistency, clarity, and contributor‑friendly UX.

---

Why Emojis?

Emojis provide:
- Instant cognitive recognition  
- A universal visual language  
- A friendly, modern contributor experience  
- A consistent identity across 300+ repositories  
- A foundation for gamification and contributor rewards  

---

## Repository Structure

`
emoji-library/
│
├── taxonomy/
├── sets/
├── mappings/
├── design-system/
├── badges/
├── docs/
└── registry.json
`

Each folder contains a specific part of the emoji operating system.

---

## How to Use This Library

1. Choose emojis from the taxonomy or sets.  
2. Apply mappings to repos, teams, or workflows.  
3. Follow design-system rules for consistency.  
4. Use badges for contributor recognition.  
5. Reference registry.json for automation and bots.

---

## Proposing New Emojis

All new emoji proposals must include:
- Category  
- Purpose  
- Justification  
- Example usage  
- Suggested mappings  

Submit proposals via emoji-proposal.md template (coming soon).

---

## License

Open-source, permissive, and contributor-friendly.
`

---

## 📁 2. /docs/philosophy.md

`

### Emoji Philosophy

The GitDigital Emoji System is more than decoration — it is a functional design language.

It exists to:
- Reduce cognitive load  
- Improve contributor onboarding  
- Make repo scanning effortless  
- Reinforce GitDigital’s identity  
- Support gamification and recognition  
- Provide a universal visual vocabulary  

Emojis act as micro‑logos.  
They make the ecosystem feel alive, intuitive, and welcoming.

This philosophy guides every decision in this library.
`

---

## 📁 3. /docs/integration-guide.md

`

### Integration Guide

This guide explains how to integrate the emoji system into GitDigital repos, teams, bots, and workflows.

---

### Repository Naming

Prefix repos with emojis based on their category:

- 🧱 Infrastructure → 🧱-infra-*
- 🤖 Automation → 🤖-bot-*
- 🔐 Security → 🔐-sec-*
- 📚 Documentation → 📚-docs-*
- 🧪 Experimental → 🧪-exp-*

---

### Team Naming

Teams should use emojis that reflect their domain:

- 🛡 Governance Team  
- 🧙 Protocol Architects  
- 🛠 Builder Team  
- 🤖 Automation Team  

---

### Documentation

Use emojis to mark sections:

- 📘 Overview  
- 🧩 Components  
- ⚙️ Setup  
- 🧪 Testing  
- 🛡 Security Notes  

---

### Bots & Automation

Bots consume registry.json to:
- Validate repo naming  
- Enforce emoji usage  
- Generate badges  
- Apply contributor XP  
- Tag PRs with emoji categories  

---

### UI/UX

Emojis should appear in:
- Repo titles  
- Issue templates  
- PR templates  
- Wiki navigation  
- Contributor profiles  
`

---

## 📁 4. /docs/naming-conventions.md

`

### Naming Conventions

This document defines how emojis are used in naming across the GitDigital ecosystem.

---

#### Repository Prefixes

Format:
<emoji>-<category>-<name>

##### Examples:
- 🧱-infra-core
- 🤖-bot-sync-engine
- 🔐-sec-audit-runner
- 📚-docs-style-guide
- 🧪-exp-prototype-01

---

#### Team Names

Format:
<emoji> <Team Name>

##### Examples:
- 🛡 Governance Team
- 🧙 Protocol Architects
- 🛠 Builder Squad
- 🤖 Automation Crew

---

#### Badge Names

Format:
<emoji> <Badge Title>

##### Examples:
- 🧙 Expert Architect
- 🦾 Automation Master
- 🛠 Builder Tier 2
- 🧭 Navigator Maintainer

---

#### Workflow Names

Format:
<emoji> <Workflow Title>

##### Examples:
- 🔁 Sync Repos
- ⚡ Fast Merge
- 🛡 Security Scan
`

---

## 📁 5. /taxonomy/categories.md

`

### Emoji Categories

This file defines the core emoji categories used across the GitDigital ecosystem.

---

#### Infrastructure
🧱 Infrastructure  
⚙️ Systems  
🛠 Tools  
🧩 Modules  
📦 Packages  

#### Automation
🤖 Automation  
🔁 Sync  
⚡ Fast Actions  
🧠 Smart Logic  

#### Security & Compliance
🔐 Security  
🛡 Governance  
📜 Compliance  
🧾 Audits  

#### Protocol Layers
🧬 Core Protocol  
🔗 On‑chain  
🌐 API  
📡 Gateway  
🛰 Network  

#### Documentation
📚 Docs  
📝 Notes  
📖 Guides  
🧠 Knowledge  

#### Contributor Economy
🥇 Gold  
🥈 Silver  
🥉 Bronze  
🧙 Expert  
🛠 Builder  
🧭 Navigator  
🐣 New Contributor  
🦾 Automation Master  

#### Experimental
🧪 Lab  
🚧 WIP  
🔥 Hot  
⚠️ Risky  
`

---

## 📁 6. /taxonomy/protocols.md

`

### Protocol Emoji Taxonomy

Defines emojis for protocol layers.

- 🧬 Core Protocol  
- 🔗 On‑chain Logic  
- 🌐 API Layer  
- 📡 Gateway Layer  
- 🛰 Network Layer  
- 🧩 Modules  
- 🛠 Extensions  
`

---

## 📁 7. /taxonomy/teams.md

`

### Team Emoji Taxonomy

- 🛡 Governance Team  
- 🧙 Protocol Architects  
- 🛠 Builder Team  
- 🤖 Automation Team  
- 📚 Documentation Team  
- 🧪 Research & Lab Team  
`

---

## 📁 8. /taxonomy/roles.md

`

### Role Emoji Taxonomy

- 🧭 Navigator (Maintainer)  
- 🛠 Builder  
- 🧙 Architect  
- 🛡 Guardian (Security)  
- 🦾 Automation Specialist  
- 🐣 New Contributor  
`

---

## 📁 9. /taxonomy/badges.md

`

### Badge Emoji Taxonomy

XP Tiers
🐣 Beginner  
🛠 Builder  
🧙 Expert  
🦾 Automation Master  
🧠 Architect  

### Achievements
🔥 Streak  
⚡ Fast Merge  
🛡 Governance Guardian  
🧩 Modular Master  
📚 Documentation Hero  
`

---

## 📁 10. /taxonomy/lanes.md

`

### Contributor Lanes

- 🛠 Builder Lane  
- 🧙 Expert Lane  
- 🧭 Maintainer Lane  
- 🦾 Automation Lane  
- 📚 Documentation Lane  
- 🧪 Research Lane  
`

---

## 📁 11. /taxonomy/repo-types.md

`

### Repository Types

- 🧱 Infrastructure  
- 🤖 Automation  
- 🔐 Security  
- 📚 Documentation  
- 🧪 Experimental  
- 🧩 Modules  
- 🛠 Tools  
`

---

## 📁 12. /taxonomy/governance.md

`

### Emoji Governance Rules

1. Emojis must be consistent with taxonomy.  
2. New emojis require proposal + approval.  
3. Repo prefixes must match category.  
4. Badges must use approved emoji sets.  
5. Bots enforce naming and usage.  
`

---

## 📁 13. /sets/core-set.md

`

### Core Emoji Set

This is the primary emoji set used across GitDigital.

🧱 🤖 🔐 📚 🧪 🛠 🧙 🧭 🦾 🧬 🔗 🌐 📡 🛰  
`

---

## 📁 14. /sets/extended-set.md

`

### Extended Emoji Set

Used for optional or specialized contexts.

🔥 ⚠️ 🚧 🧾 📦 🧩 📝 📖  
`

---

## 📁 15. /sets/seasonal-set.md

`

### Seasonal Emoji Set

Used for events, holidays, and special releases.

🎉 🎁 🎃 🎄 ✨  
`

---

## 📁 16. /sets/experimental-set.md

`

### Experimental Emoji Set

Used for prototypes, labs, and early-stage ideas.

🧪 🚧 🔥  
`

---

## 📁 17. /mappings/repo-prefix-map.md

`

### Repository Prefix Mapping

🧱 → infra-*  
🤖 → bot-*  
🔐 → sec-*  
📚 → docs-*  
🧪 → exp-*  
🛠 → tools-*  
🧩 → module-*  
`

---

## 📁 18. /mappings/org-map.md

`

### Organization Emoji Map

GitDigital Products → 🧱  
GitDigital Solana → 🔗  
OpenGrantStack → 🎯  
Compliance Registry → 🔐  
Automation Suite → 🤖  
`

---

## 📁 19. /mappings/product-map.md

`

### Product Emoji Map

Proof-of-Contribution Protocol → 🧬  
Compliance Registry → 🔐  
RepoSync AI → 🤖  
AutoDocs Generator → 📚  
Governance Validator → 🛡  
`

---

## 📁 20. /mappings/workflow-map.md

`

### Workflow Emoji Map

🔁 Repo Sync  
⚡ Fast Merge  
🛡 Security Scan  
📚 Docs Build  
🧪 Test Suite  
`

---

## 📁 21. /mappings/automation-map.md

`

### Automation Emoji Map

🤖 Automation  
🔁 Sync  
⚡ Speed  
🧠 Smart Logic  
🛡 Safety Checks  
`

---

## 📁 22. /design-system/usage-guidelines.md

`

### Emoji Usage Guidelines

1. Use emojis consistently.  
2. Use only approved emojis.  
3. Place emojis at the start of names.  
4. Avoid mixing categories.  
5. Keep meanings stable over time.  
`

---

## 📁 23. /design-system/do-dont.md

`

### Do & Don't

#### Do
- Use emojis as prefixes  
- Use emojis to clarify meaning  
- Use emojis in docs and workflows  

#### Don't
- Use random emojis  
- Change meanings without approval  
- Overload names with multiple emojis  
`

---

## 📁 24. /design-system/accessibility.md

`

### Accessibility Guidelines

- Always pair emojis with text  
- Avoid relying on emoji alone  
- Ensure screen readers can interpret names  
`

---

## 📁 25. /design-system/color-pairings.md

`

### Color Pairings

Recommended UI color pairings for emoji categories.

🧱 Infrastructure → Gray / Blue  
🤖 Automation → Purple / Neon  
🔐 Security → Red / Black  
📚 Docs → Blue / White  
🧪 Experimental → Yellow / Orange  
`

---

## 📁 26. /design-system/typography-pairings.md

`

### Typography Pairings

Use clean, readable fonts with emojis.

Recommended:
- Inter  
- Roboto  
- SF Pro  
- Open Sans  
`

---

## 📁 27. /badges/contributor-badges.md

`

### Contributor Badges

- 🐣 New Contributor  
- 🛠 Builder  
- 🧙 Expert  
- 🧭 Maintainer  
- 🦾 Automation Master  
`

---

## 📁 28. /badges/xp-tiers.md

`

### XP Tiers

Tier 1 → 🐣  
Tier 2 → 🛠  
Tier 3 → 🧙  
Tier 4 → 🦾  
Tier 5 → 🧠  
`

---

## 📁 29. /badges/achievement-badges.md

`

### Achievement Badges

🔥 Streak  
⚡ Fast Merge  
🛡 Governance Guardian  
🧩 Modular Master  
📚 Documentation Hero  
`

---

## 📁 30. /badges/governance-badges.md

`

### Governance Badges

🛡 Security Guardian  
🧭 Navigator  
🧙 Protocol Architect  
`

---

## 📁 31. /registry.json

`
{
  "categories": {
    "infrastructure": "🧱",
    "automation": "🤖",
    "security": "🔐",
    "docs": "📚",
    "experimental": "🧪"
  },
  "badges": {
    "builder": "🛠",
    "expert": "🧙",
    "automation_master": "🦾"
  },
  "repo_prefixes": {
    "infra": "🧱",
    "bot": "🤖",
    "sec": "🔐",
    "docs": "📚",
    "exp": "🧪"
  }
}
`

---

