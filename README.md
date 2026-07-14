---
layout: default
title: "Formation de la Lune par Triple Transition de Phase : la fermeture du bilan de moment cinétique par la transition du plan de Laplace"
---

# Formation de la Lune par Triple Transition de Phase dans la Proto-Terre en cours de différenciation
## La fermeture du bilan de moment cinétique par la transition du plan de Laplace — un mécanisme falsifiable à prédictions quantifiées

**Michel Debailleul** — Géophysicien, Université libre de Bruxelles (ULB)
ORCID : [0009-0003-1222-1433](https://orcid.org/0009-0003-1222-1433) · Courriel : michel.debailleul@yahoo.fr · Licence : **CC BY 4.0**

🇬🇧 [Read in English](README.md)

---

> *« L'improbabilité n'est pas un argument. La Lune existe. L'improbable s'est produit. Ma tâche est d'identifier comment cela s'est produit, non de calculer si c'était probable. Le seul test valable est de savoir si les prédictions que j'en dérive sont vérifiées par l'observation. »*

---

## Résumé

**D'où vient la Lune ?**

Plusieurs traits bien établis du système Terre–Lune — la composition isotopique quasi identique de la Terre et de la Lune, la dichotomie crustale lunaire, le retard de ≈350 Ma de la dynamo terrestre, l'inclinaison orbitale résiduelle de ≈5°, et les olivines riches en fer récemment rapportées par Chang'e-6 — n'ont toujours pas d'explication pleinement satisfaisante.

Ce travail présente une alternative quantitative : la Lune a été construite à partir de la proto-Terre elle-même, par l'instabilité interne d'un corps entièrement fondu en rotation rapide — et non par une collision externe.

Le point de départ est une borne thermodynamique, non une hypothèse : l'énergie d'accrétion excède l'énergie requise pour fondre l'intégralité du manteau silicaté d'un facteur ≈121, directement liée à l'énergie de liaison gravitationnelle connue de la Terre (Solomatov 2000 ; Elkins-Tanton 2012 ; Rubie et al. 2015). La proto-Terre était donc un corps magmatique tournant toutes les ≈3,5 h — une valeur tirée de la littérature sur l'accrétion des planètes telluriques (Agnor et al. 1999 ; Kokubo & Genda 2010), et non un paramètre libre non contraint — sans Lune encore existante pour stabiliser son axe de rotation.

Aucun plan de référence externe n'étant disponible dans le Système solaire à cette époque, seul l'angle entre l'axe de rotation et l'axe principal d'inertie propre du corps a un sens physique. Cet angle oscille chaotiquement dans [40°, 70°] et ne se stabilise jamais : le bombardement continu, l'activité T-Tauri et l'absence de stabilisateur de marée maintiennent le système en permanence hors d'équilibre.

Un moteur unique — la ségrégation progressive du fer-nickel vers le noyau en formation — entraîne trois transitions couplées : l'émergence d'un Tore Magmatique Cohérent dans la bande intertropicale, deux à trois épisodes d'éjection hypersonique qui construisent la Lune couche par couche, et une transition magnétique dont le retard de ≈350 Ma découle de trois durées indépendamment contraintes, sans paramètre libre.

---

## ⭐ Le point central de cette version : le bilan de moment cinétique comme bilan vectoriel à fermer

L'étape décisive de cette révision est de cesser de traiter le moment cinétique du système Terre–Lune comme une quantité ajustable, pour le traiter comme un **bilan vectoriel qui doit être fermé** :

```
L_init  =  L_TL  +  L_esc  +  L_tidal  +  L_other
```

L'excès à évacuer — **ΔL ≈ 3 × 10³⁴ J·s** — ne peut être emporté ni par les éjectas, ni par les marées directes (trop lentes de plusieurs ordres de grandeur). Par élimination, il doit passer par un canal résonant unique.

**Ce canal est physiquement identifié : la traversée de la transition du plan de Laplace.** À mesure que l'aplatissement de la proto-Terre se relâche et que l'orbite lunaire recule, le rayon de Laplace se retire tandis que l'orbite s'étend ; leur croisement place le système sur une branche de Cassini qui agit comme un **puits résonant post-formation** pour le moment cinétique.

La même traversée rend compte simultanément de l'**inclinaison lunaire résiduelle de 5°** — un seul mécanisme, deux observables. Sa condition d'activation — une **obliquité inertielle ε_I ≳ 60°** — est précisément ce que le cadre endogène dérive indépendamment d'une proto-Terre privée de satellite stabilisateur. **Deux voies indépendantes — le bilan de moment et l'obliquité — convergent sur la même configuration hadéenne.**

La **fermeture quantitative** du bilan reste conditionnée à une seule grandeur rhéologique — le **facteur de qualité global Q** — dont la détermination est présentée ouvertement comme le test numérique de plus haute priorité (voir Limitation L15), plutôt que dissimulée.

**Relations clés.**

```
Rayon de Laplace :    r_L = [ 2 · J2 · R² · a³ · (M_p / M_soleil) ]^(1/5)
Condition Cassini :   α · sin(ε) · cos(ε) + g · sin(ε − i) = 0
L spin–orbite :       L0 = I·Ω + M_L·√(G·M_p·a) ,   I = k·M_p·R²
```

---

## Le mécanisme d'éjection, en bref

L'éjection est déclenchée lorsqu'un coefficient d'instabilité généralisé, construit à partir d'une analyse de stabilité de Solberg–Höiland du tore magmatique en rotation, passe du négatif (confinement stable) au positif (éjection) :

```
λ(U) > 0   →   éjection   (N = 2–3 épisodes)
```

Ce coefficient combine plusieurs contributions physiques :

- un terme de Coriolis non traditionnel (l'« effet Eötvös »), qui allège tout écoulement prograde dans la bande active ;
- un gradient de densité compositionnel, produit par la ségrégation progressive du Fe-Ni vers le noyau en formation, qui agit comme source de flottabilité centrifuge ;
- un terme de Rayleigh stabilisant, lié au profil de rotation du tore.

Atteindre le seuil requiert un apport de moment cinétique, fourni par le bombardement continu de gros planétésimaux durant la fenêtre active — une contribution indépendamment contrainte dans la littérature récente sur l'accrétion tardive (Anslow et al. 2026).

Une analyse de sensibilité complète de ce seuil — sur les plages plausibles d'obliquité, de gradient de densité et de profil de rotation — est présentée dans le manuscrit, y compris un point (Limitation L16) où le réglage nominal se situe près d'une limite de stabilité géométrique indépendante du corps en rotation, une proximité signalée explicitement plutôt que lissée.

---

## Cinq arguments pour ε ∈ [40°, 70°]

1. **Absence de stabilisateur de marée** — logiquement nécessaire : pas de Lune → pas d'amortissement de marée lunaire.
2. **Laskar et al. (1993)** — sans satellite, la zone chaotique s'étend de 0° à ≈85°.
3. **Rotation rapide à 3,5 h**, contrainte par la littérature d'accrétion — précession trop rapide pour les résonances de type Laskar ; l'obliquité diffuse de façon stochastique.
4. **Bombardement planétésimal continu** — la fréquence des impacts majeurs maintient le désalignement axial bien plus efficacement que la relaxation visqueuse lente.
5. **Couples des CME T-Tauri** — perturbations impulsionnelles quotidiennes à hebdomadaires sur le vecteur de rotation.

---

## Bilan de masse (sans impacteur externe)

```
M_Moon = N · f_cap · M_ej_max + M_SPA + ΔM_late
```

Avec une masse éjectée de **2,2–4,0 × 10²² kg par épisode** et une efficacité de capture motivée **f_cap ≈ 0,70**, la masse lunaire est reconstituée sans impacteur externe ; l'identité isotopique et l'appauvrissement en fer métallique s'ensuivent naturellement, la matière éjectée étant prélevée *après* la ségrégation du fer.

---

## Prédictions falsifiables

Ce n'est pas un récit qualitatif. Le travail produit des prédictions falsifiables et quantitatives, posées **avant** les données :

| ID | Prédiction | Mission | Échéance |
|----|-----------|---------|----------|
| P1 | Interface sismique à d ≈ 200–315 km (N=3) ou ≈ 177 km (N=2), \|R\| ∈ [0,01, 0,04] | Chang'e 7, FSS, LEMS, Artemis III | août 2026 |
| P2 | Asymétrie sismique, face visible vs face cachée | Sismique multi-stations / tomographie | 2026–2030 |
| P3 | Gradient Fe/Si croissant avec la profondeur | Chang'e-6, Artemis III | 2026–2029 |
| P4 | Retard de dynamo 290–360 Ma, croissance progressive de la paléo-intensité (pas de début abrupt) | Zircons de Jack Hills | En cours |
| P5 | Fenêtre d'instabilité ε ∈ [57°, 70°] | Simulations d'obliquité à N corps | — |
| P6 | Enrichissement Fe/Si ≥ 1,5 % dans les éjectas du pôle Sud par rapport aux échantillons équatoriaux/face visible, avec seuil de falsification pré-enregistré explicite | Chang'e 7, Artemis III (pôle Sud) | août 2026 / 2028–2029 |
| P7 | Signature Hf-W : 100 ± 10 Ma après les CAI | Artemis III | 2028–2029 |
| P8 | Âge de formation > 4,45 Ga (solidification de l'OML ≠ formation) | Artemis III | 2028–2029 |
| P9 | Profondeur de fusion des basaltes de mer compatible avec la Couche 1 | Géochimie Apollo / Chang'e-5 | — |
| P10 | Interface sismique à d ≈ 177 km pour N = 2 (réflecteur faible, 150–200 km) | Chang'e 7, FSS | août 2026 |
| P17 | Efficacité de capture f_cap ≳ 0,65–0,70, au-delà de l'intervalle classique 10–55 % de l'accrétion en disque | Simulation SPH 3D | En attente (L1, L2) |
| P20 | Indicateur de régime asymptotique : le vrai L_loss se situe entre les bornes monocinétique et à spectre large | Simulation Monte-Carlo | En attente (L2) |
| P21 | Fermeture numérique du bilan de moment cinétique à ~5 % près | Simulation SPH 3D | En attente (L1, L2) |

**Condition de falsification (P1) :** aucune conversion de phase détectée dans la fenêtre 200–530 km après déploiement d'au moins 3 stations sismiques et détection d'au moins 10 événements lunaires de M > 2,5.

**Condition de falsification (P6) :** un enrichissement Fe/Si mesuré inférieur à 1,5 % dans les éjectas du pôle Sud falsifie la prédiction telle que construite.

*Note : une prédiction désignée P22 dans le manuscrit (signature isotopique des impacts planétésimaux tardifs dans les couches lunaires les plus externes) est actuellement référencée dans le texte mais pas encore formalisée comme prédiction autonome pleinement spécifiée ; ceci est noté par transparence et sera complété dans une révision future.*

**La théorie tient ou tombe sur ces résultats.**

🔴 **[▶ LANCER LA SIMULATION INTERACTIVE](https://orion4622.github.io/moon-formation-triple-phase-transition/Animation_Formation_de_la_Lune_v2.html)** — Aucune installation requise, s'ouvre directement dans tout navigateur.

---

## Limites reconnues

| # | Limite | Statut |
|---|--------|--------|
| L1 | Organisation spontanée du TMC | Motivée qualitativement ; Priorité 2 |
| L2 | Valeur numérique de f_cap | Simulation SPH requise |
| L3 | Cohésion aux petites échelles | Bi_KH ≫ 1 aux grandes échelles |
| L4 | Retard de dynamo ±50 Ma | Modèle exponentiel simple |
| L5 | Profil de rotation super-rigide α > 1 | Physiquement motivé ; hypothèse de niveau 3 |
| L6 | Transition écoulement → POB | Qualitative ; SPH requise |
| L7 | Dichotomie crustale | Qualitative ; double refonte de la face cachée prise en compte |
| L8 | Vitesse des ondes de Rossby en fluide BH | Analogue de canal ; problème ouvert |
| L9 | Mélange par impact dans les éjectas SPA | Complique l'identification du manteau primaire |
| L10 | Absence d'échantillons contraignant le manteau lunaire profond | Aucune contrainte directe existante ; en attente d'Artemis III |
| L11 | Fraction de l'épisode 2 dans les éjectas SPA | Fixée prudemment à 30 % ; affine le seuil P6 |
| L12 | Validité quantitative de l'approximation gaussienne pour le confinement du TMC | Limite d'ordre dominant de la réduction de Schrödinger non linéaire ; pas encore bornée quantitativement |
| L13 | Persistance de l'oscillation post-éjection | Repose sur une analogie d'onde inertielle ; estimation qualitative |
| L14 | Quantification de Bi_KH_eff et validation numérique | Produit de trois renforcements de cohésion établi qualitativement ; SPH 3D requise |
| **L15** | **Fermeture quantitative du bilan de moment cinétique** | **Priorité 1 — le déficit ΔL ≈ 3 × 10³⁴ J·s est évacué par la transition du plan de Laplace identifiée (puits résonant post-formation) ; la fermeture numérique reste conditionnée au facteur de qualité global Q, dont la détermination est le test numérique de plus haute priorité.** |
| L16 | Proximité du seuil d'éjection nominal avec une limite de stabilité de sphéroïde de Maclaurin indépendante | Proximité numérique (~1,7 %) signalée explicitement ; lien causal plausible mais non démontré ; nécessite une simulation autorisant des déformations non axisymétriques |

---

## Feuille de route de validation

- **Priorité 1 — Sismologie :** Chang'e 7, FSS, LEMS, Artemis III (2026–2030)
- **Priorité 2 — Simulations SPH 3D** sur sphéroïde de Maclaurin aplati (3–5 ans), incluant la fermeture numérique du bilan de moment cinétique (Q global)
- **Priorité 3 — Géochimie :** gradient Fe/Si, bassin SPA (2026–2030)
- **Priorité 4 — Chronométrie Hf-W de haute précision** (en cours)
- **Priorité 5 — Résonance de Mathieu, couplage magma-atmosphère**
- **Priorité 6 — Dérivation rigoureuse de c_Rossby^(BH)** (analytique, problème ouvert)

---

## Contenu du dépôt

| Fichier | Description |
|---------|-------------|
| Moon_Formation_TPT_EN_solar_clock.pdf | Manuscrit complet — anglais (dernière version) |
| Formation_Lune_TPT_FR_horloge_solaire.pdf | Manuscrit complet — français (dernière version) |
| Animation_Formation_de_la_Lune_v2.html | Simulation interactive |
| figure1_two_worlds_EN.png | Figure 1 — Two worlds, one common scale (EN) |
| figure1_deux_mondes.png | Figure 1 — Deux mondes, une même échelle (FR) |
| figure2_engine_EN.png | Figure 2 — The ejection engine (EN) |
| figure2_moteur.png | Figure 2 — Le moteur de l'éjection (FR) |
| figure3_moon_cross_section_EN.png | Figure 3 — Predicted internal cross-section (EN) |
| figure3_coupe_lune.png | Figure 3 — Coupe interne prédite (FR) |
| Animation_Screen_Shot_EN.png | Capture de la simulation (EN) |
| Animation_Screen_Shot_Fr.png | Capture de la simulation (FR) |

---

## Dépôts canoniques

| Plateforme | Identifiant | Statut |
|------------|-------------|--------|
| Zenodo (cette version) | [10.5281/zenodo.21354424](https://doi.org/10.5281/zenodo.21354424) | ✅ ⭐ |
| OSF | [10.17605/OSF.IO/FD3HR](https://doi.org/10.17605/OSF.IO/FD3HR) | ✅ |
| Figshare | [10.6084/m9.figshare.32983133](https://doi.org/10.6084/m9.figshare.32983133) | ✅ |
| EarthArXiv | [10.31223/X5XB6H](https://doi.org/10.31223/X5XB6H) | ⏳ |
| HAL | hal-05648861 | ⏳ |
| ESSOAr | [10.22541/essoar.15003588](https://doi.org/10.22541/essoar.15003588) | ⏳ |
| GitHub | Orion4622/moon-formation-triple-phase-transition | ✅ |

---

## Citation

DEBAILLEUL, M. (2026). *Formation de la Lune par Triple Transition de Phase dans la Proto-Terre en cours de différenciation : la fermeture du bilan de moment cinétique par la transition du plan de Laplace — un mécanisme falsifiable à prédictions quantifiées.* Zenodo. https://doi.org/10.5281/zenodo.21354424

---

## À propos

Un cadre théorique proposant que la Lune s'est formée par une triple transition de phase au sein de la proto-Terre en cours de différenciation. Un moteur unique — la ségrégation progressive du Fe–Ni — relie des transitions rhéologique, mécanique et magnétique ; le problème du moment cinétique est reformulé comme un bilan vectoriel fermé par la transition du plan de Laplace (qui produit aussi l'inclinaison de 5°). Le modèle prédit une stratigraphie interne lunaire testable, vérifiable par les données sismiques de Chang'e 7 (août 2026) et Artemis III (2028–2029).
