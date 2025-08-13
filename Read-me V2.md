# PRO-FOCAL  - workflows qualité automatisé pour une conformité embarquée, au service de la propulsion technologique VFrance_Parachute
22.19 Ko •441 lignes
•
Le formatage peut être différent de la source

### 1. Manifeste PRO-FOCAL : Conformité agile pour propulsion de l'âme technologique

1️⃣ **L'âme technologique est le guide de la boussole.** La qualité suit l’innovation.  
2️⃣ **La R&D initie la qualité, sans bureaucratie inutile.**  
3️⃣ **Les Zones Chaudes guident l’action.** Chaque problème résolu renforce le produit.  
4️⃣ **GitOps + CI/CD garantissent une traçabilité continue et transparente.**  
5️⃣ **Automatisation des tâches répétitives, discernement humain sur les décisions tactiques.**  
6️⃣ **Les bots sont en soutien, jamais intrusifs.**  
7️⃣ **La conformité se fond dans les workflows, sans freiner l’innovation.**


Tu souhaites être l'officier de terrain en charge de déployer cette démarche ? OSE déployer ton [évolution professionelle ](https://www.api-society.com/fr/certifications/technologies-numeriques/developpement-logiciel/fondamentaux-python). Deviens Lead Utils simplement par ton volontarisme ! (nous recommandons un lien fonctionnel avec un directeur technologique, R&D, ou Logiciel)



## 2. Objectif

La PRO-FOCAL propose un cadre structuré pour intégrer les exigences de qualité et de conformité dans les projets technologiques à composante scientifique ou réglementée (dispositifs médicaux, deeptech, IA critique, hardware) au travers de :

- Chatbots maîtrisés en interne,
- Workflows qualité intégrés,
- Suivi de projet par zones à risque,
- Et une approche GitOps CI/CD documentaire.
    

---

## 3. Outils intégrés dans la procédure

### 3.1 Outils classiques

- **Qualitiso** : Plateforme de conformité qualité et veille réglementaire
- **GitOps** : Automatisation CI/CD et gestion versionnée
- **Obsidian** (optionnel) : une plateforme centralisée documentaire open-source
    

### 3.2 Chatbots

- **FOCAL-ISO** : Agent IA intégré pour rappels contextuels et détection de dérives qualité
- **QualitiBot** : Agent IA pour veille réglementaire et assistance procédure
- **BotAudit** : Robot assistant pour audits internes et externes
    

---

## 4. Fonctionnement et intégration

- Intégration native dans les outils de travail (GitHub, CI/CD, Obsidian)
- Rappels et feedback continus sur les exigences qualité et conformité
- Détection précoce de non-conformités et alertes ciblées
- Préparation automatique des audits internes et externes
- Reporting simplifié avec export data analytics via scripts Python et dashboard Obsidian
    

---

## 5. Normes concernées par secteur

| Catégorie                             | Dispositif médical                                                                                                   | Robotique intelligente & mobilité autonome grand public | E-santé de gestion                | Smart Grid               |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | --------------------------------- | ------------------------ |
| **Système qualité**                   | ISO 13485, ISO 14971, ISO 17025                                                                                      | IEC 60335-2-29, UL 2272, UL 4600, UL 3300               | ISO 13485, ISO 14971              | ISO 55001, ISO 27001     |
| **Électro-mécanique**                 | IEC 60601-1, IEC 61010                                                                                               | IEC 60335-1, IEC 61508, UL 2272                         | IEC 60601-1                       | IEC 61850                |
| **Risque**                            | ISO 14971                                                                                                            | IEC 61508, UL 4600                                      | ISO 14971                         | ISO 31000                |
| **Logiciel**                          | IEC 62304, prIEC 62304 ed2 * prIEC 63521 ed1 * prIEC 63450 ed1 *prEN 63621 ed1PNW 62-540 ed1AAMI TIR 45, IEC 82304-2 | OD 2045, UL 3300, UL 4600                               | IEC 62304, IEC 82304-2, ISO 27001 | IEC 62351                |
| **Cybersécurité & confidentialité**   | IEC 62443, ISO/IEC 27001                                                                                             | IEC 62443, ISO/IEC 27001                                | IEC 62443, ISO/IEC 27001          | IEC 62443, ISO/IEC 27001 |
| **Interopérabilité & communications** | –                                                                                                                    | IEEE 802.11, 3GPP (5G)                                  | HL7, FHIR                         | IEC 61850, DNP3, Modbus  |

---

## 6. Traçabilité et versionning

- Chaque document ou livrable est versionné avec UUID ou hash
- Versionning par Git pour assurer l’historique et la transparence
- Métadonnées associées à chaque élément : conformité, risques, état thermique
- Export des données via scripts Python
- Visualisation dynamique dans Obsidian ou dashboards automatisés
    

---

## 7. Management et prise de décision

- Le management reçoit des synthèses objectives et automatisées
- Dashboard de pilotage avec KPIs conformité, qualité, maturité projet
- Les bots fournissent des résumés exploitables sans surcharge documentaire
- Base décisionnelle sur état réel du terrain (non déclaratif)
    

---

## 8. Suivi thermique et Zones Chaudes

### 8.1 Objectif

Identifier visuellement les composants critiques du projet à travers une approche thermique légère :

> 🔥 Une **Zone Chaude** est un élément technique ou réglementaire instable ou non conforme, à traiter en priorité, sans blâme.

### 8.2 Code thermique

|Thermique|Signification|
|---|---|
|💣 Zone Bombe|Problème identifié, instabilité forte à traiter en priorité|
|🔴 Zone Chaude|Risque bloquant, instabilité critique|
|🟡 Zone Tiède|Endettement connu, conformité partielle|
|🟢 Zone Froide|Conforme, stable, auditable|

### 8.3 Suivi dans les livrables

Les états thermiques sont intégrés dans :

- Les **tickets GitHub** ou issues projets
- Les **fiches modules Obsidian**
- Les **tableaux de suivi projet et plans d’action internes**
    

**Exemple :**

```markdown
# Suivi thermique – Module : Power Supply Unit
- Zone Tiède : 🟡 validée par équipe R&D (pare-feu activé)
- Maturité : prototype intermédiaire, phase pré-bêta
- Risque identifié : Certification IEC 60601-1 en attente – isolation à confirmer
- Décision qualité : intervention différée post vérification diélectrique
- Suivi prévu : Sprint 30
- is_ame_tech_true : false  # Pas un élément critique d’âme technologique
```

---

## 9. Dashboard Projet GitOps – Vue synthétique Hardware

### 9.1 Objectif

Structurer le projet en arborescence Git pour refléter les exigences normatives, le suivi des preuves, et la gestion des risques.

### 9.2 Arborescence type (IEC 60601-1)

```
hardware/
├── design/
│   ├── block_diagram.svg
│   ├── schematic.pdf
│   └── bom.csv
├── safety/
│   ├── requirements_60601.md
│   ├── risk_assessment.xlsx
│   ├── compliance_matrix_60601.md
│   └── test_plan_60601.md
├── tests/
│   ├── lab_certificates/
│   │   ├── TÜV_report_1234.pdf
│   │   └── Intertek_certificate.pdf
│   ├── internal_tests/
│   │   └── insulation_test_log_2024.csv
├── evidence/
│   ├── oscilloscope_readings/
│   ├── thermal_images/
│   └── label_photos/
```

### 9.3 Métadonnées exemple

```yaml
---
module: battery_firmware_v2
thermal_status: 💣
risk: "Crash aléatoire – non conforme à ISO 14971"
linked_norms: [IEC 62304, ISO 14971]
audit_ready: false
last_reviewed: 2025-07-21
is_ame_tech_true: true
parefeu_RD_activé: false  # Le pare-feu est levé : intervention qualité nécessaire immédiatement
---
```

---

## 10. Temporisation qualité et maturité prototype : rôle du pare-feu R&D

Dans PRO-FOCAL, la gestion des non-conformités s’appuie sur un principe fondamental :

> **Seules les non-conformités avérées, validées et priorisées par l’équipe R&D déclenchent une requête d'intervention qualité.**

Ce mécanisme agit comme un **pare-feu activé par la R&D**, garantissant que la fonction
qualité ne soit impliquée que dans des cas où son expertise est réellement nécessaire.


## 🔥 **Exemples synthétiques PRO-FOCAL**

#### Exemple 1 : Ticket #1234

```markdown
# Ticket #1234 – Non-conformité : Isolation insuffisante câble données externe
- Zone Chaude : 🟡 validée par équipe R&D (pare-feu activé)  
- Maturité : itération alpha en cours  
- Risque identifié : Certification IEC 60601-1 en attente – isolation à confirmer  
- Décision qualité : intervention différée pour prioriser stabilisation technique avant documentation complète  
- Suivi prévu : post phase bêta, Sprint 40  
- is_ame_tech_true: false  # Pas un élément critique d’âme technologique  
- pare_feu_RD_activé: false  # L'intervention qualité est différée jusqu'au prochain sprint
```

> **Interprétation** : Ici, la non-conformité est reconnue par la R&D et priorisée pour permettre une progression technique. La documentation sera finalisée après validation de la stabilité.

#### Exemple 2 : Ticket #1256

```markdown
# Ticket #1256 – Non-conformité : Crash système critique sur module batterie firmware
- Zone Chaude : 🔴 validée par équipe R&D (pare-feu levé)  
- Maturité : prototype avancé, phase bêta  
- Risque identifié : Crash aléatoire – non conforme à ISO 14971  
- Décision qualité : intervention immédiate pour correctif, documentation partielle déjà auditée en interne à reprendre et à revalider  
- Suivi prévu : Sprint 32, audit interne anticipé  
- is_ame_tech_true: true  # Élément critique d’âme technologique pour garantir la fiabilité  
- pare_feu_RD_activé: true  # Le pare-feu est levé, l’intervention qualité est immédiate
```

> **Interprétation** : Dans ce cas, la R&D déclenche l’intervention qualité immédiate en raison du risque bloquant. L'objectif est de corriger rapidement le problème tout en garantissant la conformité sans compromis sur la stabilité du produit.

---

### **Annexes**

#### **Métadonnées PRO-FOCAL**

Les métadonnées sont un élément clé pour assurer une bonne gestion documentaire et une traçabilité continue des projets :

```yaml
metadata:
  document_type: "PRO-FOCAL"
  version: "1.1"
  author: "Nom de l’auteur"
  date_created: "YYYY-MM-DD"
  last_modified: "2025-07-22"
  validated_by: "Nom du validateur"
  validation_date: "YYYY-MM-DD"
  related_norms: [ISO 13485, IEC 62304, IEC 60601-1, ISO 14971, IEC 60335-2-29, UL4600, UL2272, IEC 62133, OD 2045, IEC 62443, ISO 27001]
  traceability_id: "UUID ou hash unique"
```

#### **Liste des outils et liens**

- **Qualitiso** – Plateforme de conformité qualité pour l'industrie du dispositif médical.
- **GitOpsxQualitiso repository** – CI/CD documentaire pour l’intégration continue et le suivi des documents.
    

### **Chatbots**

- **FOCAL-ISO** : Agent IA pour rappels contextuels et détection de dérives qualité.
- **QualitiBot** : Agent IA pour veille réglementaire et assistance procédure.
- **BotAudit** : Robot assistant pour audits internes et externes.
    
### **HeatMap**



<table style="border-collapse: collapse; font-family: sans-serif; font-size: 0.9em; width: 100%; text-align: center; border: 1px solid #ccc;"> <thead> <tr style="background-color: #f2f2f2;"> <th style="border: 1px solid #ccc; padding: 6px;">💣</th> <th style="border: 1px solid #ccc; padding: 6px;">Code TU</th> <th style="border: 1px solid #ccc; padding: 6px;">Activité terrain</th> <th style="border: 1px solid #ccc; padding: 6px;">FW</th> <th style="border: 1px solid #ccc; padding: 6px;">ELEC</th> <th style="border: 1px solid #ccc; padding: 6px;">INT</th> <th style="border: 1px solid #ccc; padding: 6px;">SYS</th> </tr> </thead> <tbody> <tr> <td></td> <td>ELEC-JBD-Design-r1</td> <td>Design HW (schéma, PCB, contraintes)</td> <td style="background-color: #85C1E9;">2</td> <td style="background-color: #E67E22; color: white;">8</td> <td style="background-color: #3498DB; color: white;">4</td> <td style="background-color: #F7DC6F;">5</td> </tr> <tr> <td></td> <td>ELEC-JBD-TestUnitaire-r1</td> <td>Test carte en banc</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F39C12; color: white;">7</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F39C12; color: white;">7</td> </tr> <tr> <td style="font-size: 1.5em;"></td> <td>ELEC-JBD-RiskAssessment-r1</td> <td>Analyse de risque technique multi-domaine</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #E74C3C; color: white;">9</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #E67E22; color: white;">8</td> </tr> <tr> <td style="font-size: 1.5em;"></td> <td>ELEC-JBD-DocNormative-r1</td> <td>Justification technique (preuves HW)</td> <td style="background-color: #E74C3C; color: white;">9</td> <td style="background-color: #CB4335; color: white;">8</td> <td style="background-color: #F5B041;">5</td> <td style="background-color: #D35400; color: white;">7</td> </tr> <tr> <td style="font-size: 1.5em;">💣</td> <td>ELEC-JBD-IntegrationSupport-r1</td> <td>Debug carte avec FW et IHM</td> <td style="background-color: #3498DB; color: white;">4</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #E67E22; color: white;">8</td> <td style="background-color: #E67E22; color: white;">8</td> </tr> <tr> <td></td> <td>ELEC-JBD-ComplianceReporting-r1</td> <td>Reporting conformité / suivi des écarts</td> <td style="background-color: #85C1E9;">2</td> <td style="background-color: #AED6F1;">3</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F39C12; color: white;">7</td> </tr> <tr> <td style="font-size: 1.5em;">💣</td> <td>ELEC-JBD-BringUp-r1</td> <td>Première mise sous tension & validation comportementale</td> <td style="background-color: #F39C12; color: white;">7</td> <td style="background-color: #E67E22; color: white;">8</td> <td style="background-color: #E74C3C; color: white;">9</td> <td style="background-color: #F39C12; color: white;">7</td> </tr> <tr> <td style="font-size: 1.5em;">💣</td> <td>ELEC-JBD-EMC-Debug-r1</td> <td>Résolution problème CEM / bruits</td> <td style="background-color: #3498DB; color: white;">4</td> <td style="background-color: #E74C3C; color: white;">9</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #E67E22; color: white;">8</td> </tr> <tr> <td></td> <td>ELEC-JBD-FWUpgradeSupport-r1</td> <td>Support update FW sur système cible</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #AED6F1;">3</td> <td style="background-color: #F39C12; color: white;">7</td> <td style="background-color: #F39C12; color: white;">7</td> </tr> <tr> <td></td> <td>ELEC-JBD-ReviewCross-r1</td> <td>Revue croisée HW / FW / INT</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F4D03F;">6</td> </tr> <tr> <td></td> <td>ELEC-JBD-ExplorationAlim-r1</td> <td>Analyse instabilités & optimisation régulateurs</td> <td style="background-color: #F4D03F;">6</td> <td style="background-color: #E74C3C; color: white;">9</td> <td style="background-color: #F7DC6F;">5</td> <td style="background-color: #F4D03F;">6</td> </tr> </tbody> </table>



###  Squelette complet conceptuel du Repository
SMQ-focal-PARA
├── README.md                     # Présentation du projet, manifeste & principes fondateurs
├── manifestes/                   # Manifestes et principes fondateurs
│   ├── manifeste_pro_focal.md    # Manifeste du projet
│   ├── principes_clefs.md        # Principes clés du projet
│   ├── fusion_conceptuelle.md    # Spécifications de la fusion des approches
├── docs/                          # Documentation technique et guides
│   ├── normes/                   # Liste des normes et checklists
│   │   ├── liste_normes.md       # Liste des normes applicables
│   │   ├── tableau_conformite_secteurs.md  # Conformité par secteur
│   │   ├── checklists/           # Listes de vérification par norme
│   │   │   ├── 14971_2019.md
│   │   │   ├── 62304_2015_class_a.md
│   │   │   ├── FDA_CYBER_2018.md
│   │   │   └── ...               # Autres variantes normatives
│   ├── integration/              # Guides d'intégration CI/CD et outils
│   │   ├── workflow_ci_cd.md     # Pipeline d'intégration continue et déploiement
│   │   ├── integration_Docker.md # Intégration avec Docker
│   │   └── guides_outils.md      # Autres outils d'intégration
│   ├── modèles_docs/             # Modèles de documentation pour Pandoc
│   │   ├── template_pandoc_docx.md
│   │   ├── template_pandoc_pdf.md
│   │   └── template_audit.md     # Modèle de rapport d'audit
│   ├── extension_markdown/       # Extensions markdown spécifiques
│   │   └── md_extensions.md      # Liste des extensions Markdown utilisées
├── .github/                      # GitHub workflows et templates
│   ├── workflows/                # Fichiers de configuration pour les actions GitHub
│   │   ├── ci_cd_pipeline.yml
│   │   ├── quality_check.yml
│   │   ├── heatmap_auto_gen.yml
│   │   └── chatbot_dispatch.yml
│   ├── ISSUE_TEMPLATE/           # Templates pour la gestion des issues GitHub
│   │   ├── non_conformite.md
│   │   └── suivi_thermique.md
│   └── PULL_REQUEST_TEMPLATE.md  # Template pour les pull requests
├── quality/                      # Outils de gestion de la qualité
│   ├── suivi_thermique/          # Suivi des températures et analyse thermique
│   │   ├── heatmap_table.html
│   │   ├── zones_chaudes.md
│   │   ├── analytics_dashboards/ # Tableaux de bord d'analyse thermique
│   │   │   └── heatmap_live.json
│   │   └── exemples_tickets.md   # Exemples de tickets pour anomalies thermiques
│   ├── audits/                   # Audits internes et externes
│   │   ├── audit_interne_xx.md
│   │   └── audit_externe_checklist.md
│   ├── kpi_conformite.md         # Indicateurs de conformité
│   ├── risk_management_plan.md   # Plan de gestion des risques
│   └── gaps_analysis.md          # Analyse des manques (gaps)
├── hardware/                     # Conception matérielle
│   ├── design/                   # Diagrammes électroniques et schémas
│   │   ├── block_diagram.svg
│   │   ├── schematic.pdf
│   │   └── bom.csv               # Liste des matériaux (BOM)
│   ├── safety/                   # Sécurité des équipements
│   │   ├── requirements_60601.md # Exigences de sécurité 60601
│   │   ├── risk_assessment.xlsx  # Évaluation des risques
│   │   ├── compliance_matrix_60601.md # Matrice de conformité 60601
│   │   └── test_plan_60601.md    # Plan de test 60601
│   ├── tests/                    # Tests et certificats
│   │   ├── lab_certificates/     # Certificats des laboratoires
│   │   │   ├── TUV_report.pdf
│   │   │   └── Intertek_certificate.pdf
│   │   ├── internal_tests/       # Tests internes
│   │   │   └── insulation_test_log.csv
│   └── evidence/                 # Preuves de conformité
│       ├── oscilloscope_readings/
│       ├── thermal_images/
│       └── label_photos/
├── software/                     # Développement logiciel
│   ├── src/                      # Code source et firmware
│   │   └── module_batterie_firmware/
│   │       ├── main.c
│   │       ├── drivers/
│   │       └── tests/
│   ├── docs/                     # Conformité logicielle
│   │   └── IEC_62304_compliance_matrix.md
│   └── metadata/                 # Méta-données du logiciel
│       ├── crash_report.yaml
│       └── thermal_status.yaml
├── init/                         # Fichiers d'initialisation du projet
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── Makefile
│   ├── .gitignore
│   ├── config/
│   ├── data/
│   ├── images/
│   ├── documents/
│   └── template/
├── hooks/                        # Git hooks pour garantir la conformité
│   ├── commit-msg
│   ├── pre-commit
│   ├── pre-push
│   └── ...                       # Autres hooks de conformité
├── scripts/                      # Scripts utilitaires
│   ├── export_data.py
│   ├── generate_heatmap.py
│   ├── sync_obsidian.py
│   ├── auto_versioning.py
│   ├── collect.py
│   ├── gaps.py
│   ├── render.py
│   ├── translate.py
│   └── util.py
├── ai_agents/                    # Agents d'intelligence artificielle
│   ├── focal_iso_agent.py        # Rappels contextuels IA
│   ├── qualitibot_agent.py       # Veille réglementaire IA
│   ├── botaudit_agent.py         # Audit interne/externe IA
│   └── integration_tests.py
├── data/                         # Données du projet
│   ├── thermal_states.json
│   ├── project_kpis.json
│   ├── risk_register.csv
│   ├── evidence/
│   └── compliance_reports/
├── test_formatters/              # Formatage des tests
│   └── format_tests.py
├── project_management/           # Gestion de projet
│   ├── roadmaps/
│   ├── milestones/
│   └── tickets/
├── version/                      # Suivi de version
│   ├── version.md
│   ├── changelog.md
│   └── metadata.yaml
└── LICENSE                       # Licence du projet


Notices:
1. Documentation & Manifeste
README.md : Vision d’ensemble, quickstart, philosophie.
manifestes/ : Manifeste, principes, engagement direction, gestion des risques.

2. Documentation technique & conformité
docs/normes/ : Catalogue normatif, matrices de conformité sectorielles, dossiers de checklists paramétriques (ISO, IEC, FDA…).
docs/integration/ :Documentation CI/CD, Docker, guides outils.
docs/modeles_docs/ :Templates (Pandoc, audits, rapports).
docs/extension_markdown/ : Extensions Markdown pour automatiser et enrichir la documentation technique.

3. Automatisation qualité & audit
.github/workflows/ : Pipelines CI/CD, checks qualité, génération Heatmap, dispatch IA.
.github/ISSUE_TEMPLATE/ :Templates d’issues non-conformité, suivi thermique.

4. Qualité, suivi thermique et reporting
quality/suivi_thermique/ : Suivi visuel des zones à risques.
quality/audits/, quality/kpi_conformite.md, quality/risk_management_plan.md : Rapports audits, KPIs, gestion des risques, analyse des gaps réglementaires.

5. Secteur matériel et logiciel
hardware/ : Dossiers design, safety, preuves, tests pour conformité IEC (60601, 62304, etc.).
software/ : Code, matrices de conformité logicielle, métadonnées d’incident ou statut thermique.

6. Initialisation environnement projet
init/ : Dockerfile, configs, templates, données bases, images, documents. Démarrage rapide et reproductible.

7. Hooks & automatisations locales
hooks/ : Scripts d’automatisation à chaque étape Git (commit, push…), contrôle qualité et conformité dès l’origine.

8. Scripts d’exploitation & IA
scripts/ : Export data, génération heatmap, synchronisation, versioning, collecte, détection des gaps, traduction, rendu de documentation.

ai_agents/ : Agents IA spécialisés (rappels, conformité, audits automatiques).

9. Données et rapports
data/ : States thermiques, KPIs, registre des risques, preuves, rapports de conformité.

10. Outils de test et gestion projet
test_formatters/, project_management/, version/ : Mise en forme des tests, gestion milestones & tickets, versionning précis et métadonnées.

11. LICENCE
Licence commerciale adaptée à tes besoins (99€ option annuel en plus de l'abo Qualitiso)

### Vue Obsidian

![[74784403-962c-4510-8976-730a08ae723c_cool2.png]]
