# 04 — Protocole R&D complet

## Phasage global

| Phase | Objectif | Durée | Go/No-Go |
|-------|----------|-------|---------|
| **Phase 1 — Faisabilité chimique** | Compatibilité MP, clarté, pH, stabilité 48 h sur 6 variantes | 3 sem | Choisir variante de référence |
| **Phase 2 — Stabilité accélérée** | Vieillissement 40 °C 12 sem + cycles gel/dégel | 12 sem | Pas de séparation, ΔpH ≤ 0,5, perte d'actif ≤ 5 % |
| **Phase 3 — Performance biocide** | EN 1276, EN 13697, test mousse réelle | 4 sem | Réduction log ≥ 5 |
| **Phase 4 — Tests chantier 7 supports** | Efficacité curative + rémanence + esthétique | 8 sem visuel + 18 mois rémanence | Visible J+30, persistance M+18 |
| **Phase 5 — Tests corrosion 7 matériaux** | Sécurité contact accidentel | 1 sem | Aucune dégradation |
| **Phase 6 — Validation industrielle** | Reproductibilité 3 lots pilotes 100 kg | 4 sem | CV ≤ 3 % sur paramètres clés |

**Durée totale** : 6 mois calendaires + 12 mois suivi rémanence terrain = lancement commercial T+18 mois si Phase 1 à 6 OK.

---

## Phase 1 — Essais labo miniatures (20–50 g)

### 1.1 Matrice d'essais

6 variantes à tester en parallèle, base 30 g chacune, en flacons verre 50 mL hermétiques :

| Variante | BKC | DDAC | PolyDADMAC | Silane BS 1306 | Notes |
|----------|-----|------|------------|----------------|-------|
| V1 (référence cible) | 40 % | 16 % | 2,5 % | 6 % | Formule cible |
| V2 (sans silane) | 40 % | 16 % | 2,5 % | 0 % | Témoin biocide pur |
| V3 (sans PolyDADMAC) | 40 % | 16 % | 0 % | 6 % | Test contribution polymère |
| V4 (silane élevé) | 40 % | 16 % | 2,5 % | 8 % | Test seuil de stabilité |
| V5 (BKC seul) | 56 % | 0 % | 2,5 % | 6 % | Témoin mono-actif type Dalep |
| V6 (DDAC seul) | 0 % | 56 % | 2,5 % | 6 % | Témoin mono-actif rémanence |

Tous les ratios % m/m identiques sur les autres composants (eau, GLDA, Lutensol, Glucopon, BIT, colorant).

### 1.2 Critères Phase 1 (J+0 et J+2)

| Critère | Méthode | Critère Go |
|---------|---------|-----------|
| Aspect visuel | Lumière du jour, fond noir et fond blanc | Limpide ou très légèrement opalescent, monophasique |
| pH | Électrode combinée | 7,2–8,8 |
| Conductivité | Conductimètre | 35–50 mS/cm (témoin process) |
| Centrifugation 4000 tr/min × 30 min | Centri benchtop | Pas de séparation huileuse |
| Compatibilité PEHD (24 h contact) | Échantillon PEHD + visuel | Pas de décoloration, pas de gonflement |
| Test dilution 1:7 dans eau dure 30 °f | Mélange + observation 1 h | Solution claire, pas de précipitation |

**Décision** : retenir la variante V1 si tous critères OK. Sinon arbitrer entre V1/V3/V4.

---

## Phase 2 — Stabilité accélérée

Sur la variante retenue, lots 500 mL en bidon PEHD 1 L (gabarit fournisseur final).

### 2.1 Conditions

| Condition | Durée | Échantillonnage |
|-----------|-------|-----------------|
| Étuve 40 °C ± 1 °C | 12 semaines | T0, T+2 sem, T+4 sem, T+8 sem, T+12 sem |
| Frigo 4 °C ± 1 °C | 4 semaines | T0, T+1 sem, T+4 sem |
| Cycles gel/dégel –5 °C / +25 °C | 3 cycles × 24 h | Avant/après chaque cycle |
| Ambiante laboratoire 20 °C | 24 mois (suivi long) | T0, M+3, M+6, M+12, M+18, M+24 |

### 2.2 Mesures à chaque échantillonnage

- Aspect visuel + photo
- pH
- Densité
- Viscosité Brookfield LV sp.1 60 tr/min
- **Dosage BKC** par titrage potentiométrique au laurylsulfate de sodium (NF EN ISO 2871-2) — perte tolérée ≤ 5 % à T+12 sem 40 °C
- **Dosage DDAC** par HPLC-CAD (sous-traiter analyse externe si pas de matériel)
- Test biocide rapide EN 1276 contre *Pseudomonas aeruginosa* (témoin cinétique)

**Critère Go Phase 2** : aucun déphasage permanent, ΔpH ≤ 0,5, perte d'actif total ≤ 5 % à T+12 sem 40 °C, viscosité variation ≤ ± 30 %.

---

## Phase 3 — Performance biocide

### 3.1 Tests normatifs

| Norme | Souche / cible | Concentration test | Critère Go |
|-------|---------------|---------------------|-----------|
| **EN 1276** (bactéricide quantitatif phase suspension) | *Pseudomonas aeruginosa, Escherichia coli, Staphylococcus aureus, Enterococcus hirae* | Solution à 1:7 (concentration chantier) | Réduction log ≥ 5 en 5 min, 20 °C, conditions saleté basse |
| **EN 13697** (bactéricide / fongicide surface non-poreuse) | Idem + *Candida albicans*, *Aspergillus brasiliensis* | 1:7 et 1:10 | Réduction log ≥ 4 (bactérie), ≥ 3 (levure/moisissure), 5 min |
| **EN 1650** (fongicide / levuricide quantitatif suspension) | *Candida albicans*, *Aspergillus brasiliensis* | 1:7 | Réduction log ≥ 4 en 15 min |

### 3.2 Tests internes spécifiques mousses/algues/lichens

| Test | Substrat | Conditions | Critère |
|------|---------|------------|---------|
| Algue verte *Klebsormidium flaccidum* en culture | Boîte de Pétri agar Bristol | Application solution 1:7, observation J+1 / J+3 / J+7 / J+14 | Décoloration totale J+14, absence de reprise J+30 |
| Cyanobactérie *Nostoc commune* | Idem | Idem | Décoloration ≥ 80 % J+14 |
| Lichen sur tuile (terrain) — *Xanthoria parietina* | Tuile prélevée façade nord, 25 × 25 cm, ancienneté ≥ 10 ans | Application 200 mL/m² dilution 1:4, exposition extérieure réelle | Décoloration visible J+10, élimination J+60 |
| Mousse *Bryum capillare* / *Hypnum cupressiforme* | Tuile prélevée terrain | Application 200 mL/m² dilution 1:7 | Décoloration J+7, élimination J+30 |

### 3.3 Comparatif performance vs concurrents

Sur le **même protocole tuile lichen + mousse terrain**, comparer en parallèle :
- PROTECT+ 2026 V1
- Dalep 2100
- Algimouss Algimix
- Sika ParexLanko Net Vert (à dilution recommandée fabricant)

Évaluation aveugle par 3 opérateurs à J+10, J+30, J+90, M+12, M+18 (rémanence).

---

## Phase 4 — Tests chantier 7 supports

### 4.1 Supports retenus

| N° | Support | Provenance |
|----|---------|------------|
| 1 | Tuile terre cuite vieillie (ancienneté ≥ 15 ans, exposition nord) | Récupération chantier |
| 2 | Ardoise naturelle (Angers/Trélazé) vieillie | Récupération chantier |
| 3 | Plaque fibrociment ondulée vieillie | Récupération chantier |
| 4 | Enduit hydraulique chaux ciment (banchée labo, 28 j séchage) | Fabrication labo |
| 5 | Enduit monocouche minéral (type Parex/PRB, banchée labo) | Fabrication labo |
| 6 | Béton brut C25/30 (dalle banchée 90 j) | Fabrication labo |
| 7 | Pierre calcaire tendre (Anstrude / Lavoux) | Carrière |

Format échantillon : 30 × 30 cm, 3 réplicas par support × 4 produits comparés (PROTECT+, Dalep, Algimouss, témoin eau).

### 4.2 Application

- Dilution 1:7 (cas standard)
- Volume : 200 mL/m² (correspondant aux préconisations applicateurs façade)
- Pulvérisation basse pression 6 bar
- Exposition extérieure plein vent banc d'essai sud-ouest, station météo Sablé-sur-Sarthe
- Suivi photo + colorimétrie (Konica Minolta CM-700d) à J+0, J+7, J+30, J+90, M+6, M+12, M+18

### 4.3 Critères

| Critère | Méthode | Cible PROTECT+ |
|---------|---------|----------------|
| Décoloration mousse/algue | Visuel + colorimétrie ΔE | ΔE ≥ 15 à J+30 |
| Élimination complète | Visuel + brossage doux | OK à J+60 |
| Rémanence (recolonisation) | Visuel comparé témoin eau | Pas de reprise à M+18 sur 80 % surface |
| Aspect support post-traitement | Visuel : film, brillance, virage couleur | Aucun film visible, pas de virage > ΔE 3 |
| Effet hydrofuge | Mesure angle de contact gouttelette eau (10 µL) sur zone traitée vs zone témoin | ΔAngle ≥ +15° à J+7 et M+12 |

---

## Phase 5 — Test corrosion 7 matériaux

### 5.1 Matériaux

| N° | Matériau | Format échantillon |
|----|----------|---------------------|
| 1 | Aluminium brut 1050A H14 | Plaque 50 × 100 mm, 1 mm |
| 2 | Aluminium laqué thermolaqué blanc RAL 9010 | Idem |
| 3 | PVC blanc rigide menuiserie | Idem 3 mm |
| 4 | Zinc naturel laminé 0,65 mm | Idem |
| 5 | Cuivre M1 0,6 mm | Idem |
| 6 | Verre flotté float 4 mm | Idem |
| 7 | Bois pin sylvestre peint primaire + finition acrylique 2 couches | Idem |

### 5.2 Protocole

- Application concentré pur **et** dilution 1:4 (cas le plus agressif chantier)
- Contact 2 h à 20 °C (simulation projection accidentelle non rincée immédiatement)
- Rinçage eau du robinet, séchage 24 h
- Inspection visuelle + microscopie 10× : piqûres, virage couleur, dépôt blanc, cloquage peinture, perte de brillance

### 5.3 Critères Go/No-Go

| Matériau | Critère Go |
|----------|-----------|
| Alu brut | Pas de piqûre visible 10×, ΔE ≤ 3 |
| Alu laqué | Pas de cloquage, pas de virage, ΔE ≤ 2 |
| PVC | Pas de blanchiment, pas de fissuration |
| Zinc | Pas de tache blanche, pas de corrosion brune |
| Cuivre | Pas de virage vert vif, oxydation naturelle tolérée |
| Verre | Aucune trace de gravure ni de dépôt insoluble |
| Bois peint | Pas de cloquage, pas de pelage |

> Le pH 7,5–8,5 et l'absence d'acide protègent normalement Al/Zn/Cu. Le risque résiduel vient des QUAT à haute concentration (28 %) qui peuvent en théorie tacher Al brut par adsorption. À tester impérativement.

---

## Phase 6 — Validation industrielle

### 6.1 Lots pilotes

3 lots successifs de 100 kg chez le façonnier sous-traitant (cf. [`06_INDUSTRIALISATION_ROI.md`](./06_INDUSTRIALISATION_ROI.md)) :
- Lot 1 : recette nominale, opérateur A
- Lot 2 : recette nominale, opérateur B (test reproductibilité opérateur)
- Lot 3 : recette nominale, MP issue d'un fournisseur secondaire qualifié (test robustesse fournisseurs)

### 6.2 Mesures

Sur chaque lot, prélèvements à T0 + T+30 j + T+90 j + T+12 mois :
- Aspect, pH, densité, viscosité, dosage BKC + DDAC
- CV inter-lots ≤ 3 % sur paramètres principaux
- Stabilité cumulée 12 mois

### 6.3 Critère Go pour lancement commercial

3 lots conformes + dossier FDS + dossier réglementaire BPR validé + premiers tests rémanence terrain M+12 OK.

---

## Récapitulatif moyens à mobiliser

| Ressource | Phase concernée | Coût estimatif |
|-----------|-----------------|----------------|
| Pilote labo interne (chimiste + technicien) | 1, 2 | 20 k€ |
| Sous-traitance EN 1276 / 13697 / 1650 (laboratoire accrédité COFRAC) | 3 | 8–12 k€ |
| Banc d'essai exposition extérieure (location + suivi 18 mois) | 4 | 6 k€ |
| Tests corrosion (1 sem laboratoire) | 5 | 2 k€ |
| Lots pilotes industriels (3 × 100 kg, façonnier) | 6 | 15 k€ |
| Analytiques externes (HPLC-CAD DDAC, dosages spéciaux) | 1, 2, 6 | 5 k€ |
| **TOTAL R&D Phase 1 → 6** | | **56–60 k€** |

Coût R&D amorti dès **8 000 L commercialisés** au prix cible (cf. ROI [`06_INDUSTRIALISATION_ROI.md`](./06_INDUSTRIALISATION_ROI.md)).
