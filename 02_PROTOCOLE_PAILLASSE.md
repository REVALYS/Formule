# 02 — Protocole paillasse REVALYS PROTECT+ 2026 v1.1

> Source formule : `01_FORMULE_V1_1.md`.
> Phase 1 du programme de validation (cf. `00_CAHIER_DES_CHARGES_V1_REFERENCE.md` §9).
> Intègre les 3 corrections critiques validées en audit (cf. `03_AUDIT_CRITIQUE.md`).

## 1. Objectif

Valider la formulabilité de la v1.1 en essais miniatures (30–50 g par variante) avant lancement de la stabilité accélérée 12 sem 40 °C. Sélection de la variante de référence.

## 2. Variantes à tester

| Variante | BKC actif | DDAC actif | Σ QUAT actif | Objet |
|----------|-----------|------------|---------------|-------|
| V1 (référence) | 12,0 % | 10,0 % | 22,0 % | Formule v1.1 actée |
| V2 | 14,0 % | 8,0 % | 22,0 % | Ratio BKC dominant (témoin cinétique) |
| V3 | 10,0 % | 12,0 % | 22,0 % | Ratio DDAC dominant (témoin rémanence) |

Tous les autres composants identiques à la v1.1.

## 3. Tests obligatoires

### 3.1 Aspect, pH, conductivité

| Test | Méthode | Critère |
|------|---------|---------|
| Aspect visuel | Lumière du jour, fond noir et fond blanc | Limpide à très légèrement opalescent, monophasique |
| pH (25 °C) | Électrode combinée NF EN 1262 | 7,5–8,5 spontané |
| Conductivité | Conductimètre | 35–50 mS/cm (témoin process) |

### 3.2 Centrifugation

| Test | Méthode | Critère |
|------|---------|---------|
| Centrifugation immédiate | 4000 tr/min × 30 min | Pas de séparation huileuse, pas de phase libre |
| **Sédiment éventuel** | Agitation manuelle 30 s | **Sédiment redispersable en < 30 s = acceptable** *(critère validé audit)* |

### 3.3 Compatibilité PEHD

| Test | Méthode | Critère |
|------|---------|---------|
| Contact 24 h flacon PEHD | Échantillon + visuel | Pas de décoloration, pas de gonflement, pas d'opacification |

### 3.4 Dilution eau dure

| Test | Méthode | Critère |
|------|---------|---------|
| Dilution 1:7 dans eau dure 30 °f, observation 24 h à 20 °C | Eau synthétique 30 °f | Solution limpide, aucune précipitation, aucun voile |
| **Stabilité dilution 1:7 en eau dure 30 °f stockée 48 h** | **Eau synthétique 30 °f, observation à T+24 h et T+48 h** | **Aucun précipité, aucun voile, ΔpH ≤ 0,3** *(test ajouté audit)* |

### 3.5 Tension superficielle

| Test | Méthode | Critère |
|------|---------|---------|
| Tension superficielle solution 1:7 **sur variante V1 (référence) uniquement** | Tensiomètre Du Noüy | ≤ 32 mN/m *(simplification audit : 1 seule variante)* |

### 3.6 Densité

| Test | Méthode | Critère |
|------|---------|---------|
| Densité 20 °C **sur top 3 variantes uniquement** (après pré-sélection sur §3.1 à §3.4) | Densimètre Anton Paar ou pycnomètre | 1,015–1,030 g/mL *(simplification audit : top 3)* |

### 3.7 Pulvérisabilité réelle *(test ajouté audit)*

| Test | Méthode | Critère |
|------|---------|---------|
| **Pulvérisateur basse pression 6–8 bar** | Solution 1:7, buse 1,2 mm, 5 L | Débit régulier, cône homogène, absence de pulsation, absence de bouchage |
| **Motopompe 15–18 bar** | Solution 1:7, buse 1,2 mm, lot 5 L | Débit régulier, cône homogène, absence de pulsation, absence de bouchage |

### 3.8 Test moussage

| Test | Méthode | Critère |
|------|---------|---------|
| Test moussage Ross-Miles ou agitation 30 s | Solution 1:7, observation 1 min repos | Mousse résiduelle < 30 % du volume initial |

## 4. Critères Go/No-Go Phase 1

| Critère | Cible |
|---------|-------|
| Aspect concentré | Limpide à légèrement opalescent, monophasique |
| pH spontané | 7,5–8,5 |
| Centrifugation | Pas de phase libre |
| **Sédiment éventuel** | **Redispersable en < 30 s d'agitation = acceptable** |
| Dilution 1:7 eau dure 30 °f, 24 h | Limpide, sans précipitation |
| **Dilution 1:7 eau dure 30 °f, 48 h** | **Limpide, sans précipitation, ΔpH ≤ 0,3** |
| Tension superficielle (V1) | ≤ 32 mN/m |
| Densité (top 3) | 1,015–1,030 g/mL |
| Pulvérisabilité 6–8 bar | Débit et cône réguliers |
| Pulvérisabilité 15–18 bar | Débit et cône réguliers |
| Mousse 1 min repos | < 30 % volume initial |

## 5. Décision Phase 1

- **Go** : variante V1 (référence) retenue pour Phase 2 (stabilité accélérée 12 sem 40 °C). V2 et V3 servent de comparatifs et peuvent être conservés en réserve.
- **No-Go partiel** : si V1 échoue mais V2 ou V3 passent, basculer la variante de référence en conséquence et réviser `01_FORMULE_V1_1.md`.
- **No-Go total** : retour audit, révision du ratio QUAT ou du système de séquestration.

## 6. Livrable de phase

Rapport de paillasse comportant :
- Photos T0 et T+48 h des concentrés et dilutions 1:7
- Tableaux de mesures (aspect, pH, conductivité, centrifugation, eau dure 24 h et 48 h, pulvérisabilité 6–8 bar et 15–18 bar)
- Tension superficielle V1, densité top 3
- Décision Go/No-Go formelle signée
