---
layout: default
title: "Formation de la Lune par Triple Transition de Phase dans la Proto-Terre en cours de différenciation : Un mécanisme falsifiable aux prédictions quantifiées"
---

# Formation de la Lune par Triple Transition de Phase dans la Proto-Terre en cours de différenciation : Un mécanisme falsifiable aux prédictions quantifiées

**Michel Debailleul** — Géophysicien, Université libre de Bruxelles (ULB)
ORCID: [0009-0003-1222-1433](https://orcid.org/0009-0003-1222-1433)
Email: michel.debailleul@yahoo.fr
Licence : CC BY 4.0

[![DOI](https://img.shields.io/badge/DOI-Zenodo-blue)](https://doi.org/10.5281/zenodo.20760018)
[![EarthArXiv](https://img.shields.io/badge/EarthArXiv-preprint-orange)](https://doi.org/10.31223/X5XB6H)
[![OSF](https://img.shields.io/badge/OSF-mirror-green)](https://doi.org/10.17605/OSF.IO/XTN4Q)

🇬🇧 [Read in English](README.md)

---

> *"L'improbabilité n'est pas un argument. La Lune existe. L'improbable s'est produit. Mon travail consiste à identifier comment il s'est produit, pas à calculer s'il était probable qu'il se produise. Le seul test valable est de savoir si les prédictions que j'en tire sont vérifiées ou non par l'observation."*

---

## Résumé

D'où vient la Lune ?

Plusieurs **caractéristiques bien établies** du **système Terre–Lune** — l'**identité isotopique quasi parfaite Terre–Lune**, la **dichotomie crustale lunaire**, le **délai d'environ 350 Ma** de la **dynamo terrestre**, et les **olivines riches en fer** récemment rapportées par **Chang'e-6** — **restent sans explication pleinement satisfaisante**.

Ce travail présente une **alternative quantitative** : **la Lune s'est formée à partir de la proto-Terre elle-même**, par l'**instabilité interne** d'un corps **entièrement fondu et en rotation rapide** — et non par une **collision externe**.

Le point de départ est une **borne thermodynamique**, non une hypothèse : l'**énergie d'accrétion** excède l'énergie nécessaire pour **fondre l'intégralité du manteau silicaté** d'un facteur **≈121**, directement lié à l'**énergie de liaison gravitationnelle** connue de la Terre (Solomatov 2000 ; Elkins-Tanton 2012 ; Rubie et al. 2015). La **proto-Terre** était donc un **corps magmatique tournant en ≈3,5 h** — une valeur tirée de la **littérature sur l'accrétion des planètes telluriques** (Agnor et al. 1999 ; Kokubo & Genda 2010), et non un **paramètre libre non contraint** — sans **Lune** encore existante pour **stabiliser son axe de rotation**.

En l'**absence de tout plan de référence externe** dans le Système solaire à cette époque, seul l'**angle entre l'axe de rotation et l'axe principal d'inertie du corps lui-même** a un sens physique. Cet angle **oscille chaotiquement** dans l'intervalle **[40°, 70°]** et **ne se stabilise jamais** : le **bombardement continu**, l'**activité T-Tauri**, et l'**absence de stabilisateur de marée** maintiennent le système **en permanence hors équilibre**.

Un **moteur unique** — la **ségrégation progressive du fer-nickel** vers le **noyau en formation** — entraîne **trois transitions couplées** : l'émergence d'un **Tore Magmatique Cohérent** dans la **bande intertropicale**, **deux à trois épisodes d'éjection hypersonique** qui construisent la Lune **couche par couche**, et une **transition magnétique** dont le **délai d'environ 350 Ma** découle de **trois durées contraintes indépendamment**, **sans paramètre libre**.

Le **mécanisme d'éjection** est dérivé explicitement, équation par équation, à partir d'une **analyse de stabilité de Solberg–Høiland**, et sa sensibilité à chaque paramètre d'entrée majeur — **obliquité**, **gradient de densité**, **efficacité de capture**, **masse éjectée** — est **testée plutôt que supposée**. **Dix-huit hypothèses** sont **classées par niveau de confiance**, et **seize limitations reconnues** sont **listées sans exception**, y compris les points où la marge du mécanisme est **étroite plutôt que confortable**.

Ceci n'est **pas un récit qualitatif**. Il en résulte des **prédictions quantitatives et falsifiables** posées **en amont des données** :

- Une ou plusieurs **interfaces sismiques entre 200 et 530 km de profondeur**, produites par des **couches concentriques** de teneur en fer croissante vers l'intérieur — testable par **Chang'e-7** (août 2026) et **Artemis III**.
- Un **seuil d'enrichissement Fe/Si quantifié** pour les éjectas du **bassin Pôle Sud–Aitken**, testable dans les **échantillons Chang'e-6** existants et les prélèvements futurs — **le premier test géochimique entièrement pré-enregistré** de cette théorie.

Une **simulation 3D interactive** du mécanisme complet est librement accessible : https://orion4622.github.io/moon-formation-triple-phase-transition/Animation_Formation_de_la_Lune_v2.html

**La théorie tiendra ou tombera sur ces résultats.**

---

## 🔴 ▶ LANCER LA SIMULATION INTERACTIVE

[**Ouvrir la simulation interactive**](https://orion4622.github.io/moon-formation-triple-phase-transition/Animation_Formation_de_la_Lune_v2.html) — Aucune installation requise, s'ouvre directement dans tout navigateur.

---

## Cinq arguments pour ε ∈ [40°, 70°]

1. **Absence de stabilisateur de marée** — logiquement nécessaire : pas de Lune → pas d'amortissement par marée lunaire
2. **Laskar et al. (1993)** — sans satellite, la zone chaotique s'étend de 0° à ≈85°
3. **Rotation rapide à 3,5 h, contrainte par la littérature sur l'accrétion** — précession trop rapide pour les résonances de type Laskar ; l'obliquité diffuse stochastiquement
4. **Bombardement continu de planétésimaux** — la fréquence des impacts majeurs maintient le désalignement axial bien plus efficacement qu'une lente relaxation visqueuse
5. **Couples des CME T-Tauri** — perturbations impulsives quotidiennes à hebdomadaires sur le vecteur de spin

---

## Le mécanisme d'éjection, en bref

L'éjection se déclenche lorsqu'un coefficient d'instabilité généralisé, construit à partir d'une analyse de stabilité de Solberg–Høiland du tore magmatique en rotation, passe d'une valeur négative (confinement stable) à une valeur positive (éjection). Ce coefficient combine plusieurs contributions physiques :

- un **terme de Coriolis non traditionnel** (l'« effet Eötvös »), qui allège tout écoulement prograde au sein de la bande active ;
- un **gradient de densité compositionnel**, produit par la ségrégation progressive du Fe-Ni vers le noyau en formation, qui agit comme une source de flottabilité centrifuge ;
- un **terme de Rayleigh** stabilisant, lié au profil de rotation du tore.

Atteindre le seuil nécessite un apport de moment cinétique, fourni par le bombardement continu de grands planétésimaux durant la fenêtre active — une contribution indépendamment contrainte par la littérature récente sur l'accrétion tardive (Anslow et al. 2026).

Une analyse de sensibilité complète de ce seuil — sur les fourchettes plausibles d'obliquité, de gradient de densité et de profil de rotation — est présentée dans le manuscrit, y compris un point (Limitation L16) où le réglage nominal se situe à proximité d'une limite de stabilité géométrique indépendante du corps en rotation, une proximité signalée explicitement plutôt que dissimulée.

---

## Prédictions falsifiables

| ID | Prédiction | Mission | Échéance |
|----|------------|---------|----------|
| P1 | Interface sismique à d ≈ 200–315 km (N=3) ou ≈ 177 km (N=2), \|R\| ∈ [0,01, 0,04] | Chang'e 7, FSS, LEMS, Artemis III | Août 2026 |
| P2 | Asymétrie sismique, face visible vs. face cachée | Sismologie multi-stations / tomographie | 2026–2030 |
| P3 | Gradient Fe/Si croissant avec la profondeur | Chang'e-6, Artemis III | 2026–2029 |
| P4 | Délai de la dynamo 290–360 Ma, croissance progressive de la paléointensité (pas d'apparition abrupte) | Zircons de Jack Hills | En cours |
| P5 | Fenêtre d'instabilité ε ∈ [57°, 70°] | Simulations N-corps de l'obliquité | — |
| P6 | Enrichissement Fe/Si ≥ 1,5 % dans les éjectas du pôle Sud par rapport aux échantillons équatoriaux/face visible, avec seuil de falsification pré-enregistré explicite | Chang'e 7, Artemis III (pôle Sud) | Août 2026 / 2028–2029 |
| P7 | Signature Hf-W : 100 ± 10 Ma après les CAI | Artemis III | 2028–2029 |
| P8 | Âge de formation > 4,45 Ga (solidification de l'OML ≠ formation) | Artemis III | 2028–2029 |
| P9 | Profondeur de fusion des basaltes des mers compatible avec la Couche 1 | Apollo / Chang'e-5 géochimie | — |
| P10 | Interface sismique à d ≈ 177 km pour N = 2 (faible réflecteur, 150–200 km) | Chang'e 7, FSS | Août 2026 |
| P17 | Efficacité de capture f_cap ≳ 0,65–0,70, au-delà de l'intervalle classique 10–55 % de l'accrétion par disque | Simulation SPH 3D | En attente (L1, L2) |
| P20 | Indicateur de régime asymptotique : la vraie valeur de L_loss se situe entre les bornes monocinétique et large spectre | Simulation Monte Carlo | En attente (L2) |
| P21 | Clôture numérique du bilan de moment cinétique à ~5 % près | Simulation SPH 3D | En attente (L1, L2) |

**Condition de falsification (P1) :** aucune conversion de phase détectée dans la fenêtre 200–530 km après le déploiement d'au moins 3 stations sismiques et la détection d'au moins 10 événements lunaires de M > 2,5.

**Condition de falsification (P6) :** un enrichissement Fe/Si mesuré inférieur à 1,5 % dans les éjectas du pôle Sud falsifie la prédiction telle que construite.

*Note : une prédiction désignée P22 dans le manuscrit (signature isotopique des impacts tardifs de planétésimaux dans les couches lunaires les plus externes) est actuellement mentionnée dans le texte mais n'est pas encore formalisée comme une prédiction autonome et pleinement spécifiée ; ce point est signalé ici par souci de transparence et sera complété dans une révision future.*

---

## Limites reconnues

| # | Limite | Statut |
|---|--------|--------|
| L1 | Organisation spontanée du TMC | Qualitativement motivée ; Priorité 2 |
| L2 | Valeur numérique de f_cap | Simulation SPH requise |
| L3 | Cohésion aux petites échelles | BiKH ≫ 1 aux grandes échelles |
| L4 | Délai de la dynamo ±50 Ma | Modèle exponentiel simple |
| L5 | Profil de rotation super-rigide α > 1 | Physiquement motivé ; hypothèse de Niveau 3 |
| L6 | Transition écoulement → POB | Qualitative ; SPH requise |
| L7 | Dichotomie crustale | Qualitative ; double refusion de la face cachée prise en compte |
| L8 | Vitesse des ondes de Rossby dans un fluide BH | Analogie de canal ; problème ouvert |
| L9 | Mélange d'impact dans les éjectas du SPA | Complique l'identification du manteau primaire |
| L10 | Absence d'échantillons contraignant le manteau lunaire profond | Pas de contrainte directe existante ; en attente d'Artemis III |
| L11 | Fraction de l'Épisode 2 dans les éjectas du SPA | Fixée conservativement à 30 % ; affine le seuil P6 |
| L12 | Validité quantitative de l'approximation gaussienne pour le confinement du TMC | Limite au premier ordre de la réduction de Schrödinger non linéaire ; pas encore quantitativement bornée |
| L13 | Persistance de l'oscillation post-éjection | Repose sur une analogie d'ondes inertielles ; estimation qualitative |
| L14 | Quantification de BiKH_eff et validation numérique | Produit des trois renforcements de cohésion établi qualitativement ; SPH 3D requise |
| L15 | Bilan de moment cinétique et puits externe requis | **Priorité 1** — le déficit ΔL ≈ 2,95×10³⁴ J·s doit être évacué par un mécanisme externe ; un argument de synchronisation temporelle (perte de masse solaire T-Tauri, instabilité précoce des planètes géantes) est présenté comme contexte à l'appui, non comme une clôture |
| L16 | Proximité du seuil d'éjection nominal avec une limite de stabilité indépendante du sphéroïde de Maclaurin | Proximité numérique (~1,7 %) signalée explicitement ; lien causal plausible mais non démontré ; nécessite une simulation autorisant les déformations non axisymétriques |

---

## Feuille de route de validation

1. **Priorité 1 — Sismologie :** Chang'e 7, FSS, LEMS, Artemis III (2026–2030)
2. **Priorité 2 — Simulations SPH 3D** sur sphéroïde de Maclaurin aplati (3–5 ans)
3. **Priorité 3 — Géochimie :** gradient Fe/Si, bassin SPA (2026–2030)
4. **Priorité 4 — Chronométrie Hf-W haute précision** (en cours)
5. **Priorité 5 — Résonance de Mathieu**, couplage magma-atmosphère
6. **Priorité 6 — Dérivation rigoureuse** de c_Rossby^(BH) (analytique, problème ouvert)

---

## Contenu du dépôt

| Fichier | Description |
|---------|-------------|
| `Moon_Formation_TPT_EN_solar_clock.pdf` | Manuscrit complet — anglais (dernière version) |
| `Formation_Lune_TPT_FR_horloge_solaire.pdf` | Manuscrit complet — français (dernière version) |
| `Animation_Formation_de_la_Lune_v2.html` | Simulation interactive |
| `figure1_two_worlds_EN.png` | Figure 1 — Deux mondes, une même échelle (EN) |
| `figure1_deux_mondes.png` | Figure 1 — Deux mondes, une même échelle (FR) |
| `figure2_engine_EN.png` | Figure 2 — Le moteur de l'éjection (EN) |
| `figure2_moteur.png` | Figure 2 — Le moteur de l'éjection (FR) |
| `figure3_moon_cross_section_EN.png` | Figure 3 — Coupe interne prédite (EN) |
| `figure3_coupe_lune.png` | Figure 3 — Coupe interne prédite (FR) |
| `Animation_Screen_Shot_EN.png` | Capture d'écran de la simulation (EN) |
| `Animation_Screen_Shot_Fr.png` | Capture d'écran de la simulation (FR) |

---

## Dépôts canoniques

| Plateforme | Identifiant | Date | Statut |
|------------|-------------|------|--------|
| Zenodo (cette version) | [10.5281/zenodo.20760018](https://doi.org/10.5281/zenodo.20760018) | Juillet 2026 | ✅ ⭐ |
| OSF | [10.17605/OSF.IO/XTN4Q](https://doi.org/10.17605/OSF.IO/XTN4Q) | 23 juin 2026 | ✅ |
| Figshare | [10.6084/m9.figshare.32306832](https://doi.org/10.6084/m9.figshare.32306832) | — | ✅ |
| EarthArXiv | [10.31223/X5XB6H](https://doi.org/10.31223/X5XB6H) | Mise à jour | ⏳ |
| HAL | hal-05648861 | Mise à jour | ⏳ |
| ESSOAr | 10.22541/essoar.15003588 | Mise à jour | ⏳ |
| GitHub | [Orion4622/moon-formation-triple-phase-transition](https://github.com/Orion4622/moon-formation-triple-phase-transition) | — | ✅ |
| PSJ/AAS | manuscrit #AAS77321 | soumis le 27 mai 2026 | ⏳ |

---

## Citation

DEBAILLEUL, M. (2026). *Formation de la Lune par Triple Transition de Phase dans la Proto-Terre en cours de différenciation : un mécanisme falsifiable aux prédictions quantifiées.* Zenodo. https://doi.org/10.5281/zenodo.20760018

---

## À propos

Un cadre théorique proposant que la Lune s'est formée par une triple transition de phase au sein de la proto-Terre en cours de différenciation. Le modèle relie les transitions rhéologique, mécanique et magnétique pilotées par la ségrégation progressive du Fe-Ni, et prédit une stratigraphie interne lunaire testable par les données sismiques de Chang'e 7 (août 2026) et Artemis III (2028–2029).
