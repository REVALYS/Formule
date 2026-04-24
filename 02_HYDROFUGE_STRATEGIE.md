# 02 — Stratégie d'intégration de l'hydrofuge en milieu cationique concentré

## Le problème technique en une ligne

Mettre un hydrofuge silicone dans une formule à 28 % de QUAT sans détruire l'émulsion, sans précipiter, sans laisser de film visible et sans antagonisme cation/silanol — c'est **le point dur n°1** de la formulation. Les solutions standard du marché de la silicone-water sont émulsifiées par des **tensioactifs anioniques ou non-ioniques basse HLB**, incompatibles avec un milieu QUAT haut.

## Trois stratégies évaluées

### Stratégie A — Micro-émulsion 100 % non-ionique + siloxane réactif < 2 %

Fabriquer notre propre micro-émulsion à partir d'un siloxane à fonction silanol terminal (PDMS-OH, viscosité 50–100 cSt) émulsifié dans un système Lutensol AO9 / Glucopon haut HLB.

| Critère | Évaluation |
|---------|------------|
| Faisabilité industrielle | Moyenne. Nécessite un homogénéisateur haute pression (HPH ≥ 200 bar) ou un rotor-stator type Silverson. Investissement 30–80 k€ ou sous-traitance façonnier. |
| Stabilité prévisionnelle | Risquée. Les micro-émulsions PDMS sont métastables ; en présence de QUAT 28 %, l'écran tensioactif non-ionique est progressivement déplacé par adsorption compétitive du cation → coalescence sous 3–9 mois. |
| Coût matière | 1,40–1,80 €/L (PDMS-OH ≈ 8 €/kg + tensioactifs supplémentaires) |
| Risque film visible | Faible si dosage < 2 %, **mais hydrofugation faible** dans ces conditions. |
| **Verdict** | **Rejeté** — instabilité long terme + investissement homogénéisation + perfs hydrofuges médiocres à dosage compatible cation. |

### Stratégie B — Alkylalcoxysilane pré-hydrolysé hydrosoluble, sans émulsifiant ★ RETENU

Utiliser un **concentré aqueux d'octyltriéthoxysilane (OTES) ou propyltriéthoxysilane (PTES) pré-hydrolysé**, vendu prêt à diluer. Le silane est sous forme **oligomère silanol-siloxane** dispersé moléculairement dans un mélange eau / petit alcool / co-solvant glycol, sans tensioactif émulsifiant. Référence type : **Wacker SILRES BS 1306**, BS 290, ou Evonik Protectosil aqua.

| Critère | Évaluation |
|---------|------------|
| Faisabilité industrielle | **Excellente.** Simple addition liquide-liquide sous agitation modérée à 20–25 °C, pas d'équipement spécifique. |
| Stabilité prévisionnelle | **Bonne**, conditionnée au pH stabilisé 7,0–8,5. À pH < 6 ou > 9, condensation accélérée des silanols → gélification possible en bidon. C'est exactement pourquoi on a banni l'acidification (cf. contrainte client). |
| Compatibilité cation | **Bonne.** Les oligomères silanol portent une charge négative résiduelle faible, mais leur petite taille et leur dispersion moléculaire évitent le pontage QUAT-silane qui détruirait les deux. À tester impérativement (compatibilité mère + 90 j 40 °C). |
| Coût matière | 1,10–1,40 €/L de formule pour 6 % de BS 1306 (≈ 18–22 €/kg de concentré silane) |
| Risque film visible | **Très faible.** Les silanes oligomères pénètrent dans la porosité avant condensation → greffage interne, pas de film de surface. C'est exactement ce que les fabricants de béton et façades ITE utilisent depuis 20 ans. |
| Risque condensation prématurée en bidon | À surveiller. Mitigation : pH 7,5–8,5 strict + bidon PEHD étanche + stabilité 12 sem 40 °C. |
| **Verdict** | **★ Retenu** — meilleur compromis stabilité/coût/perfs/simplicité industrielle. |

### Stratégie C — Silicate de potassium / sodium modifié

Utiliser un **silicate alcalin dilué** (K₂SiO₃ ou Na₂SiO₃) pour minéraliser légèrement la surface et apporter une consolidation hydrophilique pseudo-hydrofuge.

| Critère | Évaluation |
|---------|------------|
| Faisabilité industrielle | Bonne, MP courante peinture silicate. |
| Effet hydrofuge réel | **Faible voire nul.** Le silicate est hydrophile, il consolide la surface mais n'apporte pas l'angle de contact +15° recherché. À la limite il **diminue** l'hydrophobie. |
| Compatibilité cation | **Mauvaise.** Le silicate alcalin est très basique (pH 11–13) et chargé négativement → précipitation immédiate en présence de QUAT cationique. |
| **Verdict** | **Rejeté** — antagonisme chimique direct + ne répond pas au cahier des charges hydrofuge. |

### Stratégie D — Kit 2 composants (biocide + hydrofuge séparés)

Vendre PROTECT+ comme **2 bidons séparés** (un bidon biocide concentré + un bidon hydrofuge) à mélanger au chantier.

| Critère | Évaluation |
|---------|------------|
| Faisabilité industrielle | Triviale, 2 produits bien connus. |
| Acceptation chantier | **Mauvaise.** Les applicateurs façade/toiture refusent le mélange chantier (perte de temps, risque erreur dosage, double logistique, double coût conditionnement). C'est la raison pour laquelle Dalep, Parex et Algimouss vendent en mono-produit. |
| Différenciation marketing | **Négative.** Vendre 2 bidons en 2026 est un retour en arrière vs concurrents mono-produit. |
| **Verdict** | **Rejeté** — perdrait l'argument "tout-en-un" qui est précisément le positionnement premium voulu. |

## Décision retenue

**Stratégie B — silane oligomère hydrosoluble pré-hydrolysé sans émulsifiant.**

Référence cible : **Wacker SILRES BS 1306** (concentré aqueux d'alkyl-alcoxy-silanes, pré-hydrolysé, hydrosoluble, ~50 % MA, prévu pour formulation aqueuse alcaline jusqu'à pH 11). Alternatives **identifiées et qualifiables** : Wacker BS 290, Evonik Protectosil aqua, Dow XIAMETER OFS-6403.

**Conditions de réussite** (à valider par essais labo Phase 1) :
1. pH du concentré stabilisé 7,5–8,5 (sans acidification — la contrainte client renforce ce choix car pas d'acide = pas de risque d'accélérer la condensation silanol).
2. Ordre d'incorporation strict : **silane en avant-dernier**, après les QUATs et le PolyDADMAC, pour limiter le temps de contact à haut potentiel cationique.
3. Agitation modérée mais prolongée (30 min minimum) pour homogénéisation moléculaire.
4. Stockage bidon PEHD étanche, **interdiction de transvaser dans bidon ouvert** (l'air et le CO₂ acidifient et déstabilisent à long terme).

## Risques résiduels à mitiger

| Risque | Probabilité | Mitigation |
|--------|-------------|------------|
| Condensation silanol sous 12 mois → gélification en bidon | Faible-modérée | Test stabilité accélérée 40 °C 12 sem, contrôle viscosité tous les 14 j ; si dérive > 50 %, repli sur stratégie A |
| Antagonisme silanol-QUAT (perte d'actif biocide) | Faible | Test EN 1276 avant/après vieillissement 12 sem, contrôle activité résiduelle ≥ 95 % |
| Effet hydrofuge insuffisant à 0,4 % silane sur support | Modérée | Test angle de contact sur tuile/béton/calcaire à dilution chantier ; si < +10°, augmenter à 8 % BS 1306 dans concentré |
| Film visible/brillance sur tuile vernissée ou ardoise polie | Faible | Test visuel post-application 7 j sur 7 supports (cf. [`04_PROTOCOLE_RD.md`](./04_PROTOCOLE_RD.md)) |

## Plan B (repli)

Si Phase 1 labo invalide la stratégie B (gélification en bidon ou perte d'efficacité biocide > 10 %) :
- **Repli 1** : abaisser silane à 3 % m/m de BS 1306 → moindre hydrofugation mais stabilité garantie.
- **Repli 2** : passer en émulsion Wacker SILRES BS 1701 (siloxane émulsion non-ionique conçu pour formulations aqueuses), à valider compatibilité QUAT par étude de phase préliminaire.
- **Repli 3** : retirer l'hydrofuge du concentré et le commercialiser comme **option SHIELD séparée** (Step 3 de la gamme), recentrer PROTECT+ sur biocide pur amélioré (binaire BKC+DDAC+PolyDADMAC). Reste différencié vs Dalep/Algimouss par la rémanence supérieure.
