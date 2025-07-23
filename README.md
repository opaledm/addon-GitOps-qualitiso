# PRO-FOCAL

**Procédure de mise en œuvre de chatbots internes de focalisation et workflow qualité CI/CD pour la conformité pérenne**

 Procédure au sein d'un système qualité qui utilise Add-on GitOps aux templates Qualitiso pour automatisation et traçabilité Git via GitHub, Scripts CI/CD & Obsidian

---

## 1. Contexte

Dans les secteurs de la deeptech, des dispositifs médicaux, de l’intelligence artificielle critique et des systèmes hardware complexes, la conformité aux normes qualité et réglementaires est un enjeu majeur. Les approches traditionnelles peuvent freiner l’innovation par leur lourdeur.

**PRO-FOCAL** vise à allier rigueur scientifique, transparence, traçabilité et agilité, grâce à l’intégration native de la conformité dans les outils et processus quotidiens, notamment via des chatbots spécialisés et l’automatisation CI/CD.

---

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

### 3.2 Chatbots

- **FOCAL-ISO** : Agent IA intégré pour rappels contextuels et détection de dérives qualité
- **QualitiBot** : Agent IA pour veille réglementaire et assistance procédure
- **BotAudit** : Robot assistant pour audits internes et externes


## 4. Fonctionnement et intégration

- Intégration native dans les outils de travail (GitHub, CI/CD, Obsidian)
- Rappels et feedback continus sur les exigences qualité et conformité
- Détection précoce de non-conformités et alertes ciblées
- Préparation automatique des audits internes et externes
- Reporting simplifié avec export data analytics via scripts Python et dashboard Obsidian
    

---

## 5. Normes concernées par secteur

|Catégorie|Dispositif médical|Robotique intelligente & mobilité autonome grand public|E-santé de gestion|Smart Grid|
|---|---|---|---|---|
|**Système qualité**|ISO 13485, ISO 14971, ISO 17025|IEC 60335-2-29, UL 2272, UL 4600, UL 3300|ISO 13485, ISO 14971|ISO 55001, ISO 27001|
|**Électro-mécanique**|IEC 60601-1, IEC 61010|IEC 60335-1, IEC 61508, UL 2272|IEC 60601-1|IEC 61850|
|**Risque**|ISO 14971|IEC 61508, UL 4600|ISO 14971|ISO 31000|
|**Logiciel**|IEC 62304, prIEC 62304 ed2, IEC 82304-2|OD 2045, UL 3300, UL 4600|IEC 62304, IEC 82304-2, ISO 27001|IEC 62351|
|**Cybersécurité & confidentialité**|IEC 62443, ISO/IEC 27001|IEC 62443, ISO/IEC 27001|IEC 62443, ISO/IEC 27001|IEC 62443, ISO/IEC 27001|
|**Interopérabilité & communications**|–|IEEE 802.11, 3GPP (5G)|HL7, FHIR|IEC 61850, DNP3, Modbus|

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

---

### 8.2 Code thermique

|Thermique|Signification|
|---|---|
|🔴 Zone Chaude|Risque bloquant, instabilité critique|
|🟡 Zone Tiède|Endettement connu, conformité partielle|
|🟢 Zone Froide|Conforme, stable, auditable|

---

### 8.3 Suivi dans les livrables

Les états thermiques sont intégrés dans :

- Les **tickets GitHub** ou issues projets
- Les **fiches modules Obsidian**
- Les **tableaux de suivi projet et plans d’action internes**
    

**Exemple** :

```markdown
# Suivi thermique – Module : Power Supply Unit
- Zone Tiède : 🟡 validée par équipe R&D (pare-feu activé)
- Maturité : prototype intermédiaire, phase pré-bêta
- Risque identifié : Certification IEC 60601-1 en attente – isolation à confirmer
- Décision qualité : intervention différée post vérification diélectrique
- Suivi prévu : Sprint 30
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
thermal_status: 🔴
risk: "Crash aléatoire – non conforme à ISO 14971"
linked_norms: [IEC 62304, ISO 14971]
audit_ready: false
last_reviewed: 2025-07-21
---
```

### 9.4 Rôle des chatbots dans le dashboard

- **FOCAL-ISO** : détecte les Zones Chaudes à partir des commits ou fichiers
- **BotAudit** : génère alertes à chaque modification critique non couverte
- **QualitiBot** : suggère normes manquantes ou incohérences réglementaires

---

## 10. Temporisation qualité et maturité prototype : rôle du pare-feu R&D

Dans PRO-FOCAL, la gestion des non-conformités s’appuie sur un principe fondamental :

**Seules les non-conformités avérées, validées et priorisées par l’équipe R&D déclenchent une intervention qualité.**

Ce mécanisme agit comme un **pare-feu activé par la R&D**, garantissant que la fonction qualité intervient de manière ciblée, sans freiner la dynamique d’innovation ni la progression technique. Cette approche pragmatique permet d’aligner exigences réglementaires et contraintes réelles du développement.

### 🔥 Exemples synthétiques PRO-FOCAL

```markdown
# Ticket #1234 – Non-conformité : Isolation insuffisante câble données externe  
- Zone Chaude : 🟡 validée par équipe R&D (pare-feu activé)  
- Maturité : itération alpha en cours  
- Décision qualité : intervention différée pour prioriser stabilisation technique avant documentation complète  
- Suivi prévu : post phase bêta, Sprint 40  
```

> Ici, la non-conformité est reconnue et priorisée par la R&D, qui retarde l’intervention qualité pour permettre une progression technique fluide. La documentation sera complétée une fois la stabilité atteinte.

```markdown
# Ticket #1256 – Non-conformité : Crash système critique sur module batterie firmware  
- Zone Chaude : 🔴 validée par équipe R&D (pare-feu levé)  
- Maturité : prototype avancé, phase bêta  
- Décision qualité : intervention immédiate pour correctif, documentation partielle déjà auditée en interne à reprendre et à revalider  
- Suivi prévu : Sprint 32, audit interne anticipé  
```

> Dans ce cas critique, la R&D priorise la levée du pare-feu et sollicite une prise en charge qualité rapide, garantissant la conformité réglementaire sans compromis sur la stabilité du produit.

Cette démarche favorise un équilibre entre agilité R&D et rigueur qualité, soutenue par les chatbots PRO-FOCAL, qui facilitent la transparence, le suivi et l’aide à la décision sans surcharge documentaire.

## 11. Annexes

### Métadonnées PRO-FOCAL

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

### Liste des outils et liens

- **Qualitiso** – Plateforme de conformité qualité pour l'industrie du dispositif médical
- **GitOps** – CI/CD documentaire

- **FOCAL-ISO** : Agent IA intégré pour rappels contextuels et détection de dérives qualité
- **QualitiBot** : Agent IA pour veille réglementaire et assistance procédure
- **BotAudit** : Robot assistant pour audits internes et externes
