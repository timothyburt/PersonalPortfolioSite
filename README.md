# The Relic Forge: Architectural Blueprint

This repository provides the high-level **Architectural Blueprint** for **The Relic Forge**—a personal full-stack Django application that serves as a unique professional portfolio.

**Core Thesis:** The project is designed to prove the **melding of human experience (emotional resilience) with technical experience (system building)**. It transforms creative, cathartic outputs (poetry, reflection) into demonstrable, gamified achievements (**Relics**) via a robust, custom-built framework.

***

## 🗺️ System Overview

The application is structured around a high-status, **Tribal/Raw** aesthetic and a **gamified progression system**.

### 1. Thematic Pillars (Content Structure)

All content is categorized and tracked across four pillars:

| Pillar | Content Type | Core Function | IP Reward |
| :--- | :--- | :--- | :--- |
| **VERSE** | Fragment (Poetry) | Log Resonance | +25 IP |
| **SOUND** | The Soundtrack (Music) | Log Immersion | +25 IP |
| **JOURNEY** | The Discourse (Prompt) | Log Reflection | +50 IP |
| **NARRATIVE** | The Vault/Scroll (Fiction) | Validate Artifact Key | +500 IP |

### 2. The Gamified Progression Track

The user's journey is tracked via a customized leveling system that gates high-value content and features:

| Mechanic | Description |
| :--- | :--- |
| **Insight Points (IP)** | Earned by logging activity across all four pillars. |
| **Ranks** | IP thresholds grant Ranks (Initiate $\rightarrow$ Archivist), providing **status and influence**. |
| **Relics & Blueprint** | **Relics** are high-status digital achievements unlocked by completing a **Chronicle** (a collection of **Fragments**). The member's progress is visualized on **The Ancestral Blueprint** armor schematic. |
| **Dual Gating** | Access to new content requires meeting *both* a **Rank (IP) threshold** and forging a specific **Relic**. |

### 3. Key Technical Components

* **Django Backend:** Python framework used for structure, security, and the custom relational database (Models).
* **The CMS:** Utilized for managing all content types (Saga, Chronicle, Fragment) and defining their relationship to the gamification layer.
* **Rune Cloud:** A custom tagging system (**Many-to-Many relationship**) that filters content based on thematic/emotional concepts (Runes), enhancing content discovery.

***

## ⚠️ Note to Reviewers

This repository contains the high-level models and structural files intended for **architectural review only**. Core application files necessary for deployment (e.g., sensitive settings, database files, main entry points) are omitted for security and privacy. The code is not runnable in this public environment.