# 06 — Industrialisation, COGS, ROI et arbitrage marque blanche vs formulation propre

## 1. Points de vigilance production

### 1.1 Matériaux du process

| Élément | Matériau | Justification |
|---------|----------|----------------|
| Cuve de fabrication | **Inox 316L** ou **PEHD haute densité** | Résiste aux QUATs cationiques + silane oligomère + GLDA. **Ne pas utiliser inox 304** (pH > 7 + chlorures = piqûration possible à long terme). Aluminium proscrit. |
| Agitateur | Pales inclinées 4 lobes, vitesse variable 50–300 tr/min | Cisaillement modéré nécessaire (PolyDADMAC sensible au cisaillement élevé : > 600 tr/min → coupure de chaîne polymère et perte de fonctionnalité) |
| Pompe de transfert | Pompe à membrane PTFE ou pompe centrifuge inox 316L | Éviter pompes à roue dentée (cisaillement) |
| Tuyauteries | PEHD, PTFE, ou inox 316L | Pas de PVC souple plastifié (extraction phtalates par les QUATs) |
| Filtration finale | Filtre 50 µm cartouche polypropylène | Avant conditionnement, retenir agglomérats résiduels |
| Bidon final | **PEHD noir** 5 L et 20 L, bouchon DIN 51 | Anti-UV, étanche QUATs, étanche silane (vérifier joint EPDM ou Viton) |

### 1.2 Ordre d'incorporation strict (cf. [`01_FORMULATION.md`](./01_FORMULATION.md) §1)

Récapitulatif :

```
Eau déminéralisée 26,3 %                          [Cuve, T° 20-25 °C, 200 tr/min]
      ↓
+ GLDA 47 % (0,5 %)                               [Dissolution complète, 5 min]
      ↓
+ BKC 50 % (40 %), addition lente sur 10 min      [Agitation 150 tr/min, mousse possible]
      ↓
+ DDAC 50 % (16 %), addition lente sur 10 min     [Agitation maintenue]
      ↓
+ PolyDADMAC 40 % (2,5 %), addition très lente    [Agitation 250 tr/min, 15 min — pas
   sur 15 min                                       de coup de cisaillement]
      ↓
+ Lutensol AO9 (4 %)                              [Préchauffer à 30 °C si solide, addition régulière]
      ↓
+ Glucopon 215 UP (2,5 %)                         [Après dispersion complète n°6]
      ↓
+ SILRES BS 1306 (6 %), addition lente sur 20 min [Agitation 300 tr/min, contrôle limpidité]
      ↓
[Contrôle pH : viser 7,5-8,5. Si < 7,0 → NaOH 30 % goutte à goutte]
      ↓
+ BIT 20 % (0,1 %)                                [Agitation 100 tr/min, 5 min]
      ↓
+ Colorant pré-dilué (0,01 %)                     [Agitation, contrôle teinte vert clair]
      ↓
[Contrôle moussage. Si nécessaire : antimousse 0,05 %]
      ↓
+ Eau QSP 100 %                                   [Ajustement masse]
      ↓
[Homogénéisation finale 30 min à 150 tr/min]
      ↓
[Prélèvement contrôle qualité : aspect, pH, densité, viscosité]
      ↓
[Filtration 50 µm + conditionnement bidon PEHD noir]
```

### 1.3 Paramètres process critiques

| Paramètre | Valeur | Conséquence si dérive |
|-----------|--------|----------------------|
| T° fabrication | 20–25 °C | > 30 °C : accélération condensation silanol → gélification ; < 15 °C : viscosité Lutensol gênante |
| Vitesse max d'agitation | 300 tr/min | > 500 tr/min : coupure PolyDADMAC, perte rémanence |
| Temps d'addition silane | ≥ 20 min | < 10 min : choc d'incorporation, opalescence persistante |
| pH avant ajout silane | 7,2–8,5 | Hors plage : condensation accélérée |
| Stockage en bidon | 5–35 °C, à l'abri lumière | > 40 °C prolongé : dérive viscosité |
| Délai mise en bidon après fabrication | < 24 h | Au-delà : risque sédimentation à confirmer |

### 1.4 Contrôles libération de lot

Sur prélèvement post-homogénéisation (avant conditionnement) :

| Contrôle | Méthode | Critère |
|----------|---------|---------|
| Aspect | Visuel | Limpide vert clair, pas de séparation |
| pH | Électrode | 7,5–8,5 |
| Densité | Densimètre | 1,015–1,030 |
| Viscosité | Brookfield LV sp.1 60 tr/min | 25–50 mPa·s |
| Dosage BKC + DDAC | Titrage NF EN ISO 2871 | Σ QUAT actif 27–29 % |
| Test moussage à dilution 1:7 | Tube + agitation 30 s | Mousse persiste < 5 min |

---

## 2. COGS détaillé (coût matière par L de concentré)

Hypothèses :
- Volumes annuels 5 000 L (cas central)
- Prix MP **indicatifs négoce France 2026 — à actualiser au sourcing réel**
- Conditionnement = bidon PEHD 5 L + étiquettes + bouchon

### 2.1 Coût matière (hors conditionnement)

| Composant | % m/m | g/L | €/kg MP indicatif | €/L formule |
|-----------|-------|-----|--------------------|--------------|
| Eau déminéralisée + QSP | 28,2 % | 287 | 0,002 | 0,001 |
| GLDA Na4 47 % | 0,5 % | 5,1 | 3,50 | 0,018 |
| BKC C12-16 50 % | 40,0 % | 408 | 2,80 | 1,142 |
| DDAC 50 % | 16,0 % | 163 | 4,20 | 0,685 |
| PolyDADMAC 40 % | 2,5 % | 25,5 | 3,50 | 0,089 |
| Lutensol AO9 | 4,0 % | 40,8 | 2,80 | 0,114 |
| Glucopon 215 UP | 2,5 % | 25,5 | 3,80 | 0,097 |
| SILRES BS 1306 | 6,0 % | 61,2 | 7,50 | 0,459 |
| NaOH 30 % | 0,1 % | 1,0 | 0,80 | 0,001 |
| BIT 20 % | 0,1 % | 1,0 | 14,00 | 0,014 |
| Colorant E142 / Acid Green | 0,01 % | 0,1 | 35,00 | 0,004 |
| Antimousse silicone | 0,05 % | 0,5 | 12,00 | 0,006 |
| **Total matières premières** | **100 %** | **~1020** | | **2,63 €/L** |

> **Incertitudes** : prix BKC/DDAC fluctuent ±15 % selon sourcing (Lonza vs Stepan vs KAO vs sourcing chinois agréé Article 95). PolyDADMAC ±10 %. Silane ±10 %. **Recalibrer COGS au lancement** après appels d'offres MP fermes.

### 2.2 Coût conditionnement (bidon 5 L)

| Élément | €/bidon 5 L | €/L |
|---------|--------------|------|
| Bidon PEHD 5 L noir DIN 51 | 0,90 | 0,18 |
| Bouchon scellé + témoin d'intégrité | 0,15 | 0,03 |
| Étiquette face + dos + collage | 0,25 | 0,05 |
| Carton + palette + filmage | 0,30 | 0,06 |
| **Total conditionnement** | **1,60** | **0,32** |

### 2.3 Coût façonnage (sous-traité)

| Poste | Coût €/L (lot 1000–2000 L) |
|-------|------------------------------|
| Façonnage (pesée + fabrication + filtration) | 0,40 |
| Conditionnement | 0,15 |
| Contrôle qualité libération | 0,08 |
| **Total façonnage** | **0,63** |

> Pour lots ≥ 5000 L, le coût façonnage descend à **0,45 €/L**. À 10 000 L, ~0,38 €/L.

### 2.4 COGS total par L de concentré

| Poste | €/L (5000 L/an) | €/L (10 000 L/an) |
|-------|-----------------|---------------------|
| Matières premières | 2,63 | 2,55 (effet prix volume MP) |
| Conditionnement bidon 5 L | 0,32 | 0,28 |
| Façonnage sous-traité | 0,63 | 0,38 |
| Logistique entrée + sortie | 0,15 | 0,12 |
| **COGS sortie usine** | **3,73 €/L** | **3,33 €/L** |

> Si on conditionne en 20 L au lieu de 5 L, le poste "Conditionnement" passe à 0,15 €/L → COGS 20 L ≈ **3,20 €/L à 10 000 L/an**. C'est le format à pousser pour les applicateurs gros volume.

### 2.5 Synthèse COGS

| Format | COGS €/L (5000 L/an) | COGS €/L (10 000 L/an) |
|--------|----------------------|--------------------------|
| Bidon 5 L | 3,73 | 3,33 |
| Bidon 20 L | 3,55 | 3,20 |

> **Note vs synthèse exécutive du README** : la fourchette 1,80–2,30 €/L mentionnée dans le pitch initial correspondait au **coût matière sec** (poste 2.1) hors conditionnement et façonnage. **Le COGS sortie usine réel est 3,20–3,73 €/L** selon volume et format. À utiliser pour les calculs de marge.

---

## 3. Recommandation prix de vente et marge

### 3.1 Prix de vente cible

| Format | Prix sortie usine HT recommandé | COGS €/L | Marge brute % | Marge brute €/L |
|--------|----------------------------------|-----------|---------------|------------------|
| **Bidon 5 L** | **8,50 €/L (42,50 € le bidon)** | 3,33 | **61 %** | 5,17 |
| **Bidon 20 L** | **7,00 €/L (140 € le bidon)** | 3,20 | **54 %** | 3,80 |
| Moyenne pondérée gamme (60/40 5L/20L) | ~7,90 €/L | 3,28 | **58 %** | 4,62 |

### 3.2 Positionnement vs concurrents

| Produit | Prix pro €/L 5 L estimé | PROTECT+ écart |
|---------|---------------------------|----------------|
| Dalep 2100 5 L | 9,00–11,00 | **-6 % à -22 %** (PROTECT+ moins cher) |
| Algimouss 5 L | 8,00–9,50 | **+0 % à +6 %** (PROTECT+ équivalent à légèrement plus cher) |
| Guard Industrie 5 L | 9,50–12,00 | **-10 % à -29 %** |
| Sika AntiMousse 5 L | 6,50–8,50 | **+0 % à +30 %** (PROTECT+ plus cher mais concentré supérieur) |

> Positionnement clair : **prix Dalep -10 à -20 %**, perfs supérieures (binaire QUAT + booster + hydrofuge), positionné **au-dessus** de Sika et **en-dessous** de Dalep/Guard. Algumouss est le concurrent direct sur le prix.

### 3.3 Volumes et chiffre d'affaires prévisionnel

| Année | Volume L/an | CA HT (à 7,90 €/L moyen) | Marge brute (58 %) |
|-------|-------------|----------------------------|----------------------|
| Y1 (lancement S2) | 3 000 | 23 700 € | 13 700 € |
| Y2 | 6 000 | 47 400 € | 27 500 € |
| Y3 | 10 000 | 79 000 € | 45 800 € |

### 3.4 Amortissement R&D

R&D Phase 1 à 6 = **56–60 k€** (cf. [`04_PROTOCOLE_RD.md`](./04_PROTOCOLE_RD.md))
+ Frais réglementaires (FDS pro + dossier BPR si nécessaire) ≈ **15 k€**
+ Outillage marquage / packaging ≈ **5 k€**
**Investissement total : ~80 k€**

→ **Amorti en ~22 mois sur la projection ci-dessus** (cumul marge Y1+Y2+Y3 = 87 k€).

---

## 4. Arbitrage **formulation propre vs marque blanche**

### 4.1 Option A — Marque blanche chez OEM existant (Idegis, Owatrol OEM, façonniers PACA)

| Critère | Évaluation |
|---------|------------|
| Délai mise sur le marché | **3 à 6 mois** (formule existante adaptée) |
| Investissement R&D | 0 €. Achat MP fini. |
| Marge brute applicable | 30–40 % (l'OEM prend la marge industrielle) |
| Différenciation produit | **Faible.** Formule générique partagée potentiellement avec d'autres marques. Aucune des 3 leviers (binaire BKC+DDAC, PolyDADMAC, silane intégré) ne se trouve facilement chez les OEM grand public. |
| Maîtrise réglementaire FDS | **Limitée.** L'OEM gère, REVALYS ne peut pas optimiser pour battre Algumouss (H332). |
| Argument commercial "Made in REVALYS" | **Affaibli** : le client pro applicateur sait reconnaître une formule générique. |
| Risque dépendance fournisseur | **Élevé.** Si l'OEM augmente ses prix ou arrête une référence, REVALYS subit. |
| **Verdict** | **Acceptable comme produit d'attente / produit défensif**, mais **incompatible avec un positionnement premium différencié**. |

### 4.2 Option B — Formulation propre sous-traitée chez façonnier inox 316L ★ RETENU

| Critère | Évaluation |
|---------|------------|
| Délai mise sur le marché | **12–18 mois** (R&D Phase 1 à 6 + dossiers réglementaires) |
| Investissement R&D | **~80 k€** (chiffré §3.4) |
| Marge brute applicable | **54–61 %** (la marge industrielle reste chez REVALYS) |
| Différenciation produit | **Forte.** Combinaison BKC+DDAC binaire + PolyDADMAC + silane oligomère, positionnement exclusif marché. |
| Maîtrise FDS et étiquetage | **Totale.** Optimisation H315/H319/H412 sur dilution chantier (différenciateur sécurité applicateur). |
| Argument commercial | **Renforcé.** "Formule REVALYS exclusive 2026" est défendable et juridiquement protégeable (savoir-faire + secret formule). |
| Risque dépendance | **Modéré et géré.** 2 façonniers qualifiés (PACA + IDF/Loire), recettes documentées, MP multi-sources. |
| **Verdict** | **★ Recommandé.** Le surplus de marge (≈ +20 points) couvre largement l'investissement R&D dès Y2. |

### 4.3 Décision finale recommandée

**Go formulation propre, sous-traitance façonnage chez prestataire inox 316L français.**

Justification synthétique :

1. **Marge brute 54–61 % vs 30–40 % en marque blanche** → différentiel de profit de **15 à 20 k€/an dès 5 000 L vendus**, qui amortit le R&D en 18 mois et finance la rente concurrentielle ensuite.
2. **Différenciation technique réelle et défendable** sur 3 leviers (binaire BKC+DDAC, PolyDADMAC, silane intégré, sans acide). Aucun OEM grand public n'offre cette combinaison clé en main.
3. **Maîtrise FDS et argument sécurité applicateur** (H315/H319 dilué vs H332 Algimouss) impossible à faire en marque blanche car nécessite reformulation complète.
4. **Cohérence de gamme** REVALYS FLASH → PROTECT+ → SHIELD : la formulation propre permet d'aligner pH, base solvant et chimie pour qu'il n'y ait pas d'incompatibilité chantier inter-étapes.
5. **Risque industriel maîtrisé** : pas d'investissement usine (façonnage sous-traité), pas de stocks lourds (lots 1000–2000 L à la commande), 2 façonniers qualifiés.

### 4.4 Plan d'exécution 12 mois

| Mois | Jalon |
|------|-------|
| M0 | Validation formule cible + sourcing MP (3 fournisseurs qualifiés par MP critique) |
| M1–M3 | Phase 1 essais labo (compatibilité, clarté, pH) |
| M3–M6 | Phase 2 stabilité accélérée 12 sem 40 °C |
| M3–M5 | Phase 3 essais biocide laboratoire COFRAC |
| M5–M9 | Phase 4 banc d'essai chantier 7 supports (rémanence M+18 = poursuite) |
| M5–M6 | Phase 5 tests corrosion 7 matériaux |
| M7–M8 | Sélection façonnier final, contractualisation |
| M9–M11 | Phase 6 lots pilotes 100 kg (3 lots) |
| M9–M11 | Production FDS + dossier réglementaire + inscription ANSES + lancement étiquettes/bidons |
| M11–M12 | Lancement commercial Y1 (S2) — formation force de vente, démos chantier applicateurs clé |

### 4.5 Conditions de remise en cause (No-Go)

Stopper le projet et basculer sur Option A marque blanche **si et seulement si** :
- Phase 1 invalide la stabilité de l'hydrofuge **et** le repli (silane à 3 % ou retrait hydrofuge en bidon SHIELD séparé) n'est pas commercialement viable
- **OU** un compétiteur sort un produit équivalent BKC+DDAC+hydrofuge intégré avant M+9 (peu probable, à surveiller)
- **OU** restriction BPR du DDAC en TP10 annoncée sous 12 mois (à monitorer ECHA en continu)
