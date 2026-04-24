# REVALYS PROTECT+ 2026 — Dossier de formulation

**Antimousse concentré professionnel toiture, façade et supports minéraux extérieurs**
**Effet curatif progressif — rémanence ≥ 18 mois — micro-effet hydrofuge intégré**

> Document de travail R&D — branche `claude/revalys-protect-formulation-OtArd`
> Statut : v0 — formulation cible avant essais labo
> Auteur : Direction R&D REVALYS, Sablé-sur-Sarthe
> Date : avril 2026

---

## 1. Synthèse exécutive (10 lignes)

REVALYS PROTECT+ 2026 est un **antimousse cationique binaire BKC + DDAC à 28 % d'actif total**, boosté par un polymère cationique (PolyDADMAC) pour la rémanence et complété par un **silane hydrosoluble pré-hydrolysé (octyltriéthoxysilane oligomérique)** délivrant un micro-effet hydrofuge invisible sans film. Le système tensioactif est **100 % non-ionique** (alcool gras éthoxylé C12-14 EO9 + APG C8-10) pour préserver la cationicité des biocides. La formule est **sans acide** (pas d'acide lactique, glycolique ni citrique), ce qui élimine la contribution H332 d'Algimouss et tout risque corrosif sur métaux légers en cas de contact accidentel. pH spontané attendu 7,5–8,5, densité ~1,02, viscosité fluide pulvérisable. Concentré classé **H302 / H314 / H400 / H410** (équivalent Dalep et Algimouss, inévitable au-dessus de 5 % BKC), **mais solution chantier à dilution 1:7 retombe en H315 / H319 / H412** (SGH07 seul). COGS estimé 1,80–2,30 €/L concentré, **prix de vente cible 7,50 €/L HT** sortie d'usine, marge brute 65–70 %. Go industriel recommandé en **formulation propre sous-traitée chez façonnier inox 316L** plutôt qu'en marque blanche : la rente concurrentielle vient de la combinaison QUAT binaire + PolyDADMAC + silane oligomère, qu'aucun OEM grand public ne maîtrise et qui ne se retrouve pas chez Dalep, Parex, Algimouss ni Sika.

---

## 2. Index des livrables

| # | Fichier | Contenu |
|---|---------|---------|
| 1 | [`01_FORMULATION.md`](./01_FORMULATION.md) | Tableau formulation finale, mécanismes d'action, paramètres physicochimiques cibles |
| 2 | [`02_HYDROFUGE_STRATEGIE.md`](./02_HYDROFUGE_STRATEGIE.md) | Stratégies d'intégration hydrofuge évaluées, choix retenu, justification |
| 3 | [`03_BENCHMARK.md`](./03_BENCHMARK.md) | Analyse complète Dalep / Parex / Algimouss / Sika / ATM / Guard, argumentaire différenciation |
| 4 | [`04_PROTOCOLE_RD.md`](./04_PROTOCOLE_RD.md) | Plan d'essais labo, stabilité accélérée, performance biocide, tests chantier, corrosion |
| 5 | [`05_REGLEMENTAIRE_FDS.md`](./05_REGLEMENTAIRE_FDS.md) | Statut BPR par actif, classification CLP concentré + dilué, checklist FDS 2020/878, risques 24–36 mois |
| 6 | [`06_INDUSTRIALISATION_ROI.md`](./06_INDUSTRIALISATION_ROI.md) | Vigilances production, COGS détaillé, prix de vente, marge, arbitrage formulation propre vs marque blanche |

---

## 3. Décisions structurantes (résumé)

| Décision | Choix | Pourquoi |
|---|---|---|
| Architecture biocide | Binaire BKC + DDAC (20 % + 8 % m/m actifs) | Synergie membrane + rémanence, dépasse le mono-actif Dalep |
| Booster rémanence | PolyDADMAC 1 % actif | Accroche cationique multipoint sur supports anioniques minéraux |
| Acidification | **AUCUNE** (contrainte client) | Préservation métaux + suppression H332 vs Algimouss |
| Tensioactifs | 100 % non-ioniques (Lutensol AO9 + Glucopon 215 UP) | Compatibilité QUATs cationiques, biosourçage partiel |
| Hydrofuge | Octyltriéthoxysilane pré-hydrolysé hydrosoluble (Wacker SILRES BS 1306) à 6 % | Pas d'émulsifiant, pas de film visible, compatible cation |
| Séquestrant | GLDA Na4 (Dissolvine GL-47-S) | Biodégradable, profil éco supérieur EDTA |
| Conservateur | BIT 20 % à 0,1 % | Hors MIT/CMIT, faible risque sensibilisation |
| Régulateur pH | NaOH 30 % en **réserve uniquement** | pH spontané déjà en spec |
| Conditionnement | PEHD noir 5 L et 20 L | Anti-UV, étanche aux QUATs |

---

## 4. Hors scope confirmé

Non utilisés conformément au cahier des charges :
- Hypochlorite, chlore actif, eau de Javel
- **Aucun acide** (lactique, citrique, glycolique, sulfonique, phosphorique)
- Tensioactifs anioniques (LAS, SLES, sulfates, sulfonates)
- Solvants organiques classants COV
- Terbutryn (voir [`05_REGLEMENTAIRE_FDS.md`](./05_REGLEMENTAIRE_FDS.md) pour justification)
- OIT (peu pertinent TP10, ratio coût/bénéfice défavorable)
- Copie directe d'une formule concurrente
