# 05 — Réglementaire BPR / CLP / FDS et risques 24-36 mois

> **À retenir** : tous les statuts BPR ci-dessous doivent être **revérifiés au lancement** auprès de la liste Article 95 ECHA (ECHA Biocidal Active Substances) et du registre des décisions BPR de la Commission. Les dates butoirs et reclassements évoluent.

## 1. Cadre réglementaire applicable

| Texte | Périmètre | Impact PROTECT+ |
|-------|-----------|-----------------|
| Règlement BPR UE 528/2012 | Mise sur le marché des produits biocides | Autorisation par TP, fournisseurs MP en Article 95 |
| Règlement CLP UE 1272/2008 (+ ATP en cours) | Classification, étiquetage, emballage | Concentré H302/H314/H400/H410, dilution chantier H315/H319/H412 |
| Règlement REACH UE 1907/2006 | Enregistrement, évaluation, autorisation des MP | Toutes MP en > 1 t/an ou pré-enregistrées |
| Règlement FDS UE 2020/878 | Format des fiches de données de sécurité | Obligation depuis 1er janvier 2023 |
| Règlement détergent UE 648/2004 | (Pas applicable — produit biocide, pas détergent) | Hors scope sauf revendication nettoyage |
| ADR (transport routier matières dangereuses) | Transport bidons | UN 3082 / Classe 9 selon classification environnement |
| Décret biocides FR (Code environnement art. L522 et R522) | Obligations nationales France | Inventaire ANSES, redevance, déclaration utilisation pro |

## 2. Statut BPR par actif (à vérifier ECHA Article 95 au lancement)

| Substance | CAS | Statut BPR pour TP02 (désinfection surfaces non-alimentaires usage public) | Statut TP10 (matériaux de construction) | Source à vérifier | Risque 24–36 mois |
|-----------|-----|----------------------------------------------------------------------------|------------------------------------------|-------------------|---------------------|
| BKC C12-16 (ADBAC) | 68424-85-1 | Approuvé, voir décisions Commission UE | TP10 inscrit dans le programme d'examen, **statut à vérifier** | echa.europa.eu/regulations/biocidal-products-regulation | Faible. Très installé sur le marché, très utilisé hôpital + agro. Pas de signaux retrait. |
| DDAC | 7173-51-5 | Approuvé pour TP02, TP04, TP08, TP10, TP11, TP12 | Approuvé TP10 | echa.europa.eu | Faible. Intérêt confirmé par Commission. |
| PolyDADMAC | 26062-79-3 | **Non-biocide.** Polymère traitement. Pas soumis à autorisation BPR. | Idem | REACH uniquement | Très faible — risque limité à reclassification REACH éventuelle. |
| Octyltriéthoxysilane (substance dans BS 1306) | 2943-75-1 | Non-biocide. Auxiliaire formulation. | Non-biocide. | REACH — vérifier dossier enregistrement Wacker | Très faible. |
| GLDA Na4 | 51981-21-6 | Non-biocide. | Idem | REACH | Très faible. Profil éco favorable, biodégradable. |
| Lutensol AO9 (alcool gras éthoxylé C12-14 EO9) | 68439-50-9 | Non-biocide. | Idem | REACH | Faible. Surveillance générique éthoxylates mais usage cosmétique/détergent confirmé. |
| Glucopon 215 UP (APG C8-10) | 68515-73-1 | Non-biocide. | Idem | REACH | Très faible. Biosourcé, biodégradable. |
| BIT (Acticide BIT 20) | 2634-33-5 | Approuvé TP06 (préservation produits in-can), peut être utilisé comme conservateur formulation | Pas TP10, mais autorisé comme conservateur in-can | echa.europa.eu | **Surveillance.** Sensibilisant cutané (H317), sous surveillance UE pour reclassement éventuel. À 0,1 %, très loin du seuil de classification du mélange. |
| NaOH 30 % | 1310-73-2 | Non-biocide. | Idem | REACH | Aucun. |

### 2.1 Substances **écartées** de la formulation, justification BPR

| Substance | Raison de l'écartement |
|-----------|--------------------------|
| **Terbutryn** (CAS 886-50-0) | Approuvée TP07/TP09/TP10 mais sous **surveillance forte UE pour persistance environnementale** (PBT borderline). Probabilité non négligeable de restriction d'usage à 24-36 mois sur produits façade. **Décision : ne pas inclure**, malgré sa rémanence intéressante. Repli si jamais nécessaire : **Diuron** (mais idem PBT, rejeté), **Octylisothiazolinone (OIT)** plutôt qu'un triazine. |
| **OIT** (CAS 26530-20-1) | Pertinence TP10 modeste, sensibilisant cutané (H317), coût élevé, ratio bénéfice/risque défavorable face à un binaire BKC+DDAC déjà très efficace. |
| **Acide glycolique** (CAS 79-14-1) | Apporte **H332 (nocif inhalation)** sur le concentré → différenciation perdue vs Algimouss. Apporte aussi pH bas → corrosion métaux. **Contrainte client client validée : aucun acide.** |
| **Hypochlorite de sodium** | Hors scope cahier des charges. Action choc, pas curatif progressif. |
| **MIT, CMIT, BIT/MIT mélange** | Risque sensibilisant cutané supérieur au BIT seul, MIT particulièrement scruté UE. **BIT seul** retenu pour la conservation in-can. |

## 3. Classification CLP du concentré et de la solution chantier

### 3.1 Concentré (bidon 5/20 L applicateur pro)

| Paramètre | Valeur calculée |
|-----------|-----------------|
| Σ BKC + DDAC actif | 28,0 % m/m |
| BKC seul | 20,0 % → > 5 % → déclenche **Skin Corr. 1B / H314** |
| Σ M-factor M(aigu) Aquatic | BKC × M=10 + DDAC × M=10 → fortement classant |
| **Classification finale concentré** | **Acute Tox. 4 (oral) H302** + **Skin Corr. 1B H314** + **Eye Dam. 1 H318 (englobé H314)** + **Aquatic Acute 1 H400** + **Aquatic Chronic 1 H410** |
| **Pictogrammes** | **SGH05** (corrosif) + **SGH07** (point exclamation) + **SGH09** (environnement) |
| **Mention d'avertissement** | **Danger** |
| **Mentions de danger** | H302, H314, H400, H410 |
| **Conseils de prudence** | P234, P260, P264, P273, P280, P301+P312+P330, P303+P361+P353, P305+P351+P338+P310, P391, P501 |
| **Identique à Dalep et Algimouss ?** | OUI sur SGH05/07/09 + H302/H314/H400/H410. **DIFFÉRENT d'Algimouss : pas de H332** (suppression acide glycolique). |

### 3.2 Solution chantier diluée 1:7

| Paramètre | Valeur calculée |
|-----------|-----------------|
| BKC dans solution chantier | 2,86 % m/m → **entre 1 % et 5 % → Skin Irrit. 2 / H315 + Eye Irrit. 2 / H319** (passe sous le seuil corrosif 5 %) |
| DDAC dans solution chantier | 1,14 % → idem H315/H319 |
| Σ QUAT actif solution chantier | 4,0 % → **sous le seuil 5 %**, classification irritante uniquement |
| Aquatic après dilution × 7 | Aquatic Chronic 3 H412 |
| **Classification finale solution chantier** | **Skin Irrit. 2 H315 + Eye Irrit. 2 H319 + Aquatic Chronic 3 H412** |
| **Pictogramme** | **SGH07 seul** |
| **Mention d'avertissement** | **Attention** |

> **C'est un avantage commercial fort** : l'applicateur travaille avec une solution non-corrosive (juste irritante), gants nitrile + lunettes suffisent. Pas d'EPI niveau corrosif.

## 4. Checklist FDS format UE 2020/878

À produire pour le concentré PROTECT+ avant mise sur le marché. Format strict 16 sections.

| Section | Titre | Contenu spécifique PROTECT+ 2026 |
|---------|-------|------------------------------------|
| 1 | Identification substance/mélange et société | Nom commercial : REVALYS PROTECT+ ; usage : biocide TP02 et TP10 (à confirmer autorisation) ; fournisseur : REVALYS, Sablé-sur-Sarthe ; tél. urgence : ORFILA +33 1 45 42 59 59 |
| 2 | Identification des dangers | Classification CLP cf. §3.1 ; éléments d'étiquetage ; autres dangers (PBT/vPvB : non) ; perturbateurs endocriniens : non |
| 3 | Composition / informations sur les composants | Mélange. Liste : BKC C12-16 (CAS 68424-85-1, 20 %, H302/H314/H400/H410 M=10/M=1) ; DDAC (CAS 7173-51-5, 8 %, H302/H314/H400/H410 M=10/M=1) ; PolyDADMAC (CAS 26062-79-3, 1 %, non classé) ; OTES oligomère (mention BS 1306, ~3 %, non classé) ; APG C8-10 (CAS 68515-73-1, 2,5 %, H318) ; Lutensol AO9 (CAS 68439-50-9, 4 %, H302/H318) ; GLDA Na4 (CAS 51981-21-6, 0,2 %, non classé) ; BIT (CAS 2634-33-5, 0,02 %, H317 — sous seuil) |
| 4 | Premiers secours | Inhalation : air libre ; peau : retirer vêtements souillés, laver à grande eau 15 min ; yeux : rincer 15 min, ophtalmologiste ; ingestion : ne pas faire vomir, eau, médecin |
| 5 | Mesures de lutte contre l'incendie | Non inflammable. Eau pulvérisée, CO₂, mousse polyvalente, poudre ABC. EPI pompiers. Évacuer eaux d'extinction (toxique aquatique). |
| 6 | Mesures en cas de dispersion accidentelle | EPI gants nitrile, lunettes, combinaison. Endiguer, absorber sable/terre/vermiculite, ne pas rejeter à l'égout/cours d'eau. Bidons étanches pour élimination DIS. |
| 7 | Manipulation et stockage | T° 5–35 °C, à l'abri du gel et du soleil direct. PEHD étanche. Loin acides forts (déstabilisation silane), oxydants forts, anioniques. |
| 8 | Contrôles d'exposition / protection individuelle | VLEP : pas de VLEP réglementaire France pour BKC/DDAC. EPI : gants nitrile (épaisseur ≥ 0,4 mm, EN 374-3), lunettes EN 166, combinaison Cat. III type 6. Rinçage oculaire à proximité. |
| 9 | Propriétés physiques et chimiques | État : liquide ; couleur : vert clair ; odeur : faible légèrement aminée ; pH : 7,5–8,5 ; densité : ~1,02 ; viscosité : 25–50 mPa·s ; point d'éclair : > 100 °C (non inflammable) ; solubilité eau : totale ; coeff. partage : NA mélange |
| 10 | Stabilité et réactivité | Stable conditions normales. Incompatibilités : tensioactifs anioniques (précipitation), oxydants forts, acides forts. Décomposition thermique > 200 °C : NOx, HCl, COx. |
| 11 | Informations toxicologiques | DL50 orale rat (BKC) ~795 mg/kg ; DL50 orale rat (DDAC) ~325 mg/kg → Cat. 4 oral (mélange ETA calculé) ; corrosion peau (BKC > 5 %) ; lésions oculaires graves ; pas de cancérogène/mutagène/reprotoxique connu ; pas de sensibilisant respiratoire ; sensibilisant cutané : non au seuil de la formule |
| 12 | Informations écologiques | Très toxique organismes aquatiques effets long terme (M=10 aigu, M=1 chronique). Biodégradabilité : BKC partielle 60-80 % en 28 j, DDAC partielle, APG totale, GLDA totale. Pas de bioaccumulation significative. |
| 13 | Considérations relatives à l'élimination | Déchets dangereux. Code déchet 07 04 01 (solvants/liquides de lavage) ou 16 03 05 (déchets organiques contenant substances dangereuses) — à confirmer DREAL. Filière agréée DIS. |
| 14 | Informations relatives au transport | UN 3082 — MATIÈRE DANGEREUSE DU POINT DE VUE DE L'ENVIRONNEMENT, LIQUIDE, N.S.A. (chlorure d'alkylbenzyldiméthylammonium et chlorure de didécyldiméthylammonium) — Classe 9, Groupe d'emballage III, code danger 90, transport routier ADR : étiquette 9 + poisson mort. Quantité limitée 5 L. |
| 15 | Informations réglementaires | BPR UE 528/2012 : produit biocide — actifs en programme d'examen TP02/TP10 ; CLP UE 1272/2008 : classé ; REACH UE 1907/2006 : pas de SVHC > 0,1 % ; Inventaire France ANSES SIMMBAD : à déclarer |
| 16 | Autres informations | Phrases H complètes ; références bibliographiques ; date de révision ; n° version ; mention "FDS conforme au règlement UE 2020/878" |

> Délai de production FDS : **2 à 4 semaines** selon disponibilité données fournisseurs. Sous-traiter si besoin chez un consultant FDS expérimenté biocides (Carl ROTH consulting, ChemSafe, Toxalys).

## 5. Étiquetage France à produire

| Bidon 5 L et 20 L | Contenu obligatoire |
|-------------------|---------------------|
| Face avant | Nom commercial REVALYS PROTECT+ ; volume nominal ; mention "Antimousse concentré professionnel" ; mention "Usage strictement professionnel" ; logo navy/or |
| Face arrière (étiquette CLP) | Pictogrammes SGH05+SGH07+SGH09 ; mention DANGER ; H302+H314+H400+H410 ; conseils P (cf. §3.1) ; identité fournisseur + adresse + tél. urgence ORFILA |
| Mentions biocides (Décret n°2019-643) | "TP02 — Désinfectants pour les surfaces en contact avec les denrées alimentaires et l'alimentation animale" : NON applicable ici. Mention TP02 général ou TP10 selon autorisation accordée. **Numéro d'autorisation France** à intégrer dès délivrance. Mention obligatoire "Utilisez les produits biocides avec précaution. Avant toute utilisation, lisez l'étiquette et les informations concernant le produit." |
| Inscription ANSES | À effectuer via SIMMBAD avant mise sur le marché. Prélèvement redevance forfaitaire annuelle. |

## 6. Risques réglementaires 24–36 mois et plans de repli

| Risque | Probabilité | Impact si réalisé | Plan de repli identifié |
|--------|-------------|---------------------|--------------------------|
| BKC C12-16 reclassement / restriction TP10 | Faible | Reformulation partielle obligatoire | Augmenter DDAC à 12-14 %, abaisser BKC à 14-16 %, total QUAT actif maintenu |
| DDAC restriction supplémentaire | Très faible | Idem | Substituer par chlorure de dialkylméthylbenzylammonium (CAS 68391-01-5) |
| BIT classement plus strict (sensibilisation forte) | Modérée | Reformulation conservateur | Substituer par DMDM hydantoin ou Bronopol (sous réserve compatibilité QUATs) |
| Octyltriéthoxysilane reclassement REACH | Faible | Reformulation hydrofuge | Substituer par méthyltriéthoxysilane oligomère ou siloxane PDMS-OH micro-émulsion (cf. [`02_HYDROFUGE_STRATEGIE.md`](./02_HYDROFUGE_STRATEGIE.md) repli) |
| Restriction éthoxylates Lutensol AO9 (chaînes EO sous surveillance) | Modérée à long terme | Reformulation tensioactif | Augmenter Glucopon (APG biosourcé déjà présent) à 5-6 %, supprimer Lutensol |
| Évolution des seuils CLP M-factor aquatique | Faible | Étiquetage potentiellement plus restrictif | Suivi veille ECHA, ajustement étiquette |
| Inscription SVHC d'un additif (colorant, antimousse silicone) | Très faible | Reformulation mineure | Substitution colorant E142 → autre vert hydrosoluble alimentaire ; antimousse Wacker ↔ Dow trivial |

**Principe général** : toutes les MP retenues sont multi-fournisseur (≥ 2 sources qualifiables Article 95 ECHA), substitution possible sans refonte de la philosophie de la formule.
