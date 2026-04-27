# 03 — Audit critique REVALYS PROTECT+ 2026 — Formule v1.1

> Source : `00_CAHIER_DES_CHARGES_V1_REFERENCE.md` et `01_FORMULE_V1_1.md`.
> Document factuel, à compléter par les rapports d'essais paillasse, stabilité, biocidie et terrain.

## 0. Corrections intégrées suite audit

Les trois corrections ci-dessous sont actées et reportées dans le protocole paillasse `02_PROTOCOLE_PAILLASSE.md`.

| # | Correction | Action |
|---|------------|--------|
| 1 | Test « Stabilité dilution 1:7 en eau dure 30 °f stockée 48 h » | **Ajouté au protocole** — observation à T+24 h et T+48 h : précipité, voile, ΔpH. Critère : limpide, ΔpH ≤ 0,3. |
| 2 | Test « Pulvérisabilité réelle » | **Ajouté au protocole** — pulvérisateur 6–8 bar + motopompe 15–18 bar, buse 1,2 mm, lot 5 L. Observer débit, cône, régularité, absence de bouchage. |
| 3 | Critère sédiment | **Modifié** — sédiment redispersable en moins de 30 s d'agitation = acceptable (était : aucun sédiment toléré). Évite des No-Go faussement bloquants. |

Simplifications associées :
- Tension superficielle mesurée uniquement sur la variante de référence V1 (au lieu de toutes).
- Densité mesurée uniquement sur les top 3 variantes après pré-sélection (au lieu de toutes).

## 1. Contexte & objectif

REVALYS développe la version 2026 de l'antimousse concentré professionnel PROTECT+ pour toiture, façade et supports minéraux extérieurs. Le produit s'inscrit dans la gamme entre FLASH (Step 1 Clean) et un futur SHIELD (Step 3 Protect, hydrofugation dédiée). Cible applicateur professionnel France, conditionnement bidons PEHD noir 5 L et 20 L, application motopompe 15–18 bar ou pulvérisateur 6–8 bar. Concurrents directs : Dalep 2100, Algimouss Algimix, Sika AntiMousse, ParexLanko Net Vert, ATM Algifluid, Guard Industrie.

Objectif fonctionnel : antimousse concentré à effet curatif progressif (4–8 semaines) et rémanence longue durée. **Cible rémanence ≥ 18 mois sous réserve validation banc d'essai — non revendicable commercialement à ce stade.** Sans chlore actif, sans acide, sans tensioactif anionique, sans solvant COV classant. Dilutions chantier 1:4 / 1:7 / 1:10. Stabilité bidon visée 24 mois à 5–30 °C. pH spontané maîtrisé 7,5–8,5.

## 2. Formule v1.1 retenue

| # | Composant | CAS | % m/m | % actif réel |
|---|-----------|-----|-------|--------------|
| 1 | Eau déminéralisée (totale, charge + QSP) | 7732-18-5 | 46,25 | — |
| 2 | GLDA Na4 sol. mère 47 % | 51981-21-6 | 1,00 | 0,47 |
| 3 | BKC C12-16 sol. mère 50 % | 68424-85-1 | 24,00 | 12,00 |
| 4 | DDAC sol. mère 50 % | 7173-51-5 | 20,00 | 10,00 |
| 5 | PolyDADMAC sol. mère 40 %, Mw 100–150 kDa | 26062-79-3 | 2,50 | 1,00 |
| 6 | Lutensol AO9 (alcool gras C12-14 EO9) | 68439-50-9 | 3,00 | 3,00 |
| 7 | Glucopon 215 UP (APG C8-10) | 68515-73-1 | 2,50 | 2,50 |
| 8 | Amine oxyde lauryl-DMAO sol. mère 30 % | 1643-20-5 | 0,50 | 0,15 |
| 9 | NaOH 30 % (réserve pH process) | 1310-73-2 | 0–0,1 | — |
| 10 | BIT sol. mère 20 % (conservateur in-can) | 2634-33-5 | 0,10 | 0,02 |
| 11 | Antimousse silicone process (réserve) | variable | 0–0,05 | — |
| **Total** | | | **100,00** | **Σ QUAT actif = 22,00** |

Architecture aqueuse monophasique. **Sans silane. Sans acide.** Densité cible ~1,02 g/mL.

## 3. Justification technique

### 3.1 Couple BKC + DDAC (Σ 22 % actif, ratio 1,2/1)

- BKC C12-16 (12 % actif) : biocide cationique à pénétration rapide (groupe benzyle), action curative cinétique sur algues, mousses et lichens.
- DDAC (10 % actif) : biocide cationique double-chaîne C10, adsorption multi-points sur substrats anioniques, désorption lessivage ralentie, tolérance eau dure supérieure.
- Total 22 % couvre les besoins biocides aux trois dilutions chantier (5,5 % / 3,1 % / 2,2 % en pulvé) ; les sites d'adsorption du substrat saturent au-delà de cette gamme, ce qui rend un dosage supérieur inutile et coûteux.
- Ratio 1,2/1 favorise la rémanence vs un mono-actif BKC ou un ratio BKC dominant.

### 3.2 PolyDADMAC (1 % actif, Mw 100–150 kDa)

- Polyélectrolyte cationique non biocide servant de booster d'accroche multi-points sur supports minéraux anioniques.
- Mw modéré pour limiter la sensibilité au cisaillement process et le bond de viscosité.
- Effet attendu de renforcement de la rétention des QUATs sur substrat ; ampleur réelle à valider en banc d'essai terrain.

### 3.3 Tensioactifs non-ioniques (Σ 6 %)

- Lutensol AO9 (3 %) : mouillant principal pour cuticules cireuses (lichens) ; HLB 13,3.
- Glucopon 215 UP (2,5 %) : APG biosourcé, mouillage poreux, profil éco favorable.
- Amine oxyde lauryl-DMAO (0,5 %) : booster wetting + régulateur de mousse pour application motopompe.
- Aucun tensioactif anionique (incompatibilité directe avec QUATs cationiques).

### 3.4 GLDA Na4 (0,47 % actif)

- Séquestrant biodégradable Ca²⁺/Mg²⁺/Fe³⁺ ; doublé vs v0 pour absorber les eaux de chantier dures jusqu'à 30–35 °f sans déstabiliser le système.

## 4. Écarts v0 → v1.1

| Élément | v0 | v1.1 | Raison |
|---------|----|------|--------|
| Σ QUAT actif | 28 % (BKC 20 + DDAC 8) | 22 % (BKC 12 + DDAC 10) | Saturation adsorption substrat, suppression surdosage, COGS optimisé |
| Ratio BKC / DDAC | 2,5 / 1 | 1,2 / 1 | Rééquilibrage vers la rémanence |
| Silane oligomère (BS 1306) | 6 % | 0 % (retiré) | Effet hydrofuge non mesurable à dose intégrable, risque gélification, antagonisme PolyDADMAC |
| GLDA séquestrant | 0,5 % sol. mère | 1,0 % sol. mère | Sécurise comportement en eau dure |
| Amine oxyde lauryl-DMAO | absent | 0,5 % | Booster wetting + régulateur de mousse |
| Colorant E142 / Acid Green | 0,01 % | 0 % (retiré v1 → v1.1) | Bidon PEHD noir + étiquetage suffisent ; simplifie la FDS |
| Positionnement hydrofuge | Intégré PROTECT+ | Reporté sur SHIELD séparé | Permet un dosage hydrofuge correct et préserve la stabilité du PROTECT+ |

## 5. Performances attendues (avec limites)

> **Toutes les performances ci-dessous sont attendues sur base de raisonnement chimique et d'antériorité matières premières. Aucune n'est validée à ce stade.**

- Action curative biocide sur algues, mousses, cyanobactéries et lichens : attendue, à confirmer en EN 1276 / EN 13697 / EN 1650 sur formule complète à 1:7 et 1:10.
- Rémanence : **objectif ≥ 18 mois non démontré** ; suivi banc d'essai 12 à 18 mois requis avant toute revendication commerciale.
- Stabilité bidon 24 mois à 5–30 °C : attendue, à confirmer en stabilité accélérée 40 °C 12 sem + cycles gel/dégel + suivi temps réel 24 mois.
- Compatibilité matériaux à préserver (alu, PVC, zinc, cuivre, vitrage, bois peint) : attendue grâce au pH 7,5–8,5 et à l'absence d'acide ; à confirmer par tests sur 12 matériaux.
- Compatibilité supports à traiter (tuile, ardoise, fibrociment, enduit, béton, pierre calcaire) : attendue ; tests colorimétriques préalables nécessaires sur enduits teintés et peintures façade existantes.
- Mousse à l'application motopompe : attendue maîtrisée par amine oxyde + antimousse process en réserve ; à confirmer en test moussage Ross-Miles + lot pilote.

## 6. Risques & incertitudes

- Stabilité bidon long terme à valider expérimentalement (interactions QUAT + polymère + non-ioniques).
- Rémanence terrain réelle à valider sur 7 supports en banc d'essai (donnée littérature PolyDADMAC transposée d'autres applications).
- Comportement en eau de chantier dure (> 30 °f) à confirmer malgré le GLDA renforcé.
- Sourcing PolyDADMAC européen Mw 100–150 kDa à confirmer (SNF, Solenis, Kemira identifiés ; à qualifier).
- Phytotoxicité ruissellement sur sols végétalisés : risque modéré, géré par notice technique applicateur (bâchage + rinçage).
- Sensibilité réglementaire à 24–36 mois : éthoxylates (Lutensol AO9), BIT, statut TP10 du DDAC à monitorer.

## 7. Cadre réglementaire (à valider par consultant spécialisé)

- **Règlement BPR UE 528/2012** : produit biocide ; types TP02 et TP10 à confirmer selon usages revendiqués.
- **Substances actives BKC (CAS 68424-85-1) et DDAC (CAS 7173-51-5)** : statut Article 95 ECHA à reverifier au lancement (fournisseur producteur ou importateur autorisé).
- **AMM France non obtenue à ce stade.** Inscription ANSES via SIMMBAD obligatoire avant commercialisation, numéro d'autorisation à intégrer sur étiquette dès délivrance.
- **FDS conforme REACH 1907/2006 + CLP 1272/2008 + format UE 2020/878** : à produire en 16 sections, FR + EN minimum.
- **Étiquetage H/P** : classification du concentré attendue SGH05 + SGH07 + SGH09 (Acute Tox. 4 / Skin Corr. 1B / Aquatic Acute 1 / Aquatic Chronic 1) ; classification de la solution diluée 1:7 attendue plus légère, SGH07 seul. À reclasser officiellement après formulation finale.
- **Validation par consultant réglementaire spécialisé biocides obligatoire avant lancement** (point critique du projet).

## 8. Plan de validation

| Phase | Objet | Durée | Critère Go |
|-------|-------|-------|------------|
| 1 | Paillasse : compatibilité MP, aspect, pH spontané, dilution eau dure 30 °f, centrifugation, compatibilité PEHD | 3 sem | Aspect limpide, pH 7,5–8,5, pas de précipitation |
| 2 | Vieillissement accéléré 40 °C 12 sem + cycles gel/dégel + suivi temps réel 24 mois | 12 sem | ΔpH ≤ 0,5, perte actif ≤ 5 %, viscosité ± 30 % |
| 3 | Tests biocides EN 1276 / EN 13697 / EN 1650 (laboratoire COFRAC) + tests internes algues/lichens | 4 sem | Réduction log ≥ 5 (bactéricide), ≥ 4 (surface, fongicide) |
| 4 | Essais terrain 7 supports, comparatifs vs Dalep / Algimouss / témoin, suivi M+3 / M+6 / M+12 | 12–18 mois | Décoloration J+30, élimination J+60, équivalence ou supériorité concurrents M+12 |
| 5 | 3 lots pilotes 100 kg + dossier réglementaire + Go/No-Go formel | 4 sem | CV inter-lots ≤ 3 %, dossier complet, validation consultant réglementaire |

Budget global indicatif : programme R&D ~55 k€ + réglementaire/packaging/lancement ~20 k€ = **~75–90 k€**. Délai T0 → lancement commercial : ~11 mois.

## 9. Conclusion opérationnelle

La formule v1.1 est **opérationnelle pour démarrage de la validation paillasse**. Les choix techniques (binaire BKC+DDAC à 22 %, ratio 1,2/1, PolyDADMAC 1 %, trio non-ionique, GLDA renforcé, sans silane, sans acide, sans colorant) sont cohérents et tracés vers les contraintes du cahier des charges.

À ce stade :
- Aucune performance n'est validée expérimentalement.
- La revendication rémanence ≥ 18 mois ne doit pas être utilisée commercialement avant validation banc d'essai.
- Le dossier réglementaire (BPR / ANSES / AMM / FDS / CLP) est un point critique à faire valider par un consultant spécialisé biocides avant toute mise sur le marché.
- Les écarts vs v0 sont justifiés par l'audit en 8 étapes consolidé dans le cahier des charges v1 (`00_CAHIER_DES_CHARGES_V1_REFERENCE.md`).

Décision recommandée : **engager Phase 1 (essais paillasse miniatures) et le sourcing des matières premières critiques en parallèle**. Réévaluer la décision Go/No-Go industriel à l'issue de la Phase 2 (12 sem de stabilité accélérée).
