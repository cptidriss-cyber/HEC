# Chapitre 3 — Dynamique du point : les lois de Newton

Il s'agit de décrire la **dynamique newtonienne**, dont les limites sont devenues apparentes au début du XXᵉ s. Alors que la cinématique décrivait uniquement le mouvement des corps, la dynamique **explique les causes** de celui-ci.

## 1. Force et masse

**La force**
- Une force n'est pas « visible », mais nous ressentons ses effets (déformation d'un corps, variation de vitesse, …).
- Il y a des forces dites **de contact** et des forces qui agissent **à distance**.
- Une force est caractérisée par une **grandeur**, une **direction**, un **sens** (représentés par un vecteur) et un **point d'application**.
- Les forces s'ajoutent **vectoriellement** (formant la **résultante**).
- Certaines forces se mesurent avec un **dynamomètre**.
- Unité : le **newton (N)**.

**La masse**
- Newton définissait la masse comme une « quantité de matière » — notion qui manque de précision.
- La masse d'un corps mesure son **inertie**, c'est-à-dire sa **résistance aux variations de vitesse** (il est plus difficile de modifier le mouvement d'un camion que celui d'une balle de tennis) — comme le précise la 2ᵉ loi de Newton.
- La masse est une grandeur **scalaire**.
- La masse est une grandeur **intrinsèque** d'un corps (à ne pas confondre avec le **poids**).
- Unité : le **kilogramme**.

## 2. Première loi de Newton — principe d'inertie

En l'absence de forces, un corps **conserve son état de mouvement ou de repos** :
**ΣF⃗ = F⃗_R = 0⃗ → v⃗ = constante**

Pourtant, selon **Aristote**, un objet bouge tant qu'une force agit sur lui ; en termes anachroniques, Aristote prétend que F ≈ v. C'est rejeté de nos jours… alors que c'est un peu ce que l'on voit en poussant un objet sur une table ! (Film *Gravity*, 39ᵉ s. : principe d'inertie non respecté.)

## 3. Deuxième loi de Newton — loi fondamentale de la dynamique

Newton fait le lien entre **force** et **accélération** (variation de vitesse) :

**F⃗ = m a⃗** — F en N, m en kg, a en m/s²

- La 1ʳᵉ loi apparaît comme un **cas particulier** de la 2ᵉ.
- Cette loi peut apparaître comme un **postulat** : il n'y a pas de démonstration ni d'expérience pour l'établir. Elle peut même être considérée comme une **définition** de la notion de force.

**Forces extérieures et intérieures** : la 2ᵉ loi ne fait intervenir que les forces **extérieures** (externes), pas les forces intérieures (internes). Si l'on veut tenir compte des forces internes, elles donnent une contribution **nulle**, puisque chaque force interne est associée à une force opposée (principe d'action et réaction). (Ex. : la personne qui pousse le véhicule depuis l'intérieur ; le ventilateur qui souffle dans la voile de son propre bateau — « fake ou réalité ? »)

## 4. Troisième loi de Newton — principe d'action et réaction

L'analyse des **collisions** permet à Newton d'établir sa 3ᵉ loi. En déterminant la variation de vitesse de chacune des billes, et sachant que les forces agissent pendant la même durée sur les 2 billes, Newton en déduit que les 2 forces sont **identiques en grandeur** et qu'elles apparaissent **par paire** :
- F⃗_A = m_A Δv⃗_A / t_A ; F⃗_B = m_B Δv⃗_B / t_B
- Mesures : m_A Δv⃗_A = − m_B Δv⃗_B → F⃗_A t_A = − F⃗_B t_B ; comme t_A = t_B : **F⃗_A = − F⃗_B**

Tout corps A exerçant une force sur un corps B subit une force d'intensité égale, mais de sens opposé, exercée par le corps B :

**F⃗_AB = − F⃗_BA** (F⃗_AB : force exercée sur A par B)

**Paradoxe du « cheval et de la remorque »** (notation F_XY : force sur X par Y). Le cheval, qui croit connaître les lois de la dynamique, observe que plus il tire vers l'avant, plus la remorque tire vers l'arrière : il se fatigue donc inutilement. Pourtant la remorque avance !
- Résolution : les forces incriminées sont des **forces intérieures** au système cheval-remorque et n'ont pas d'effet sur l'accélération du système. Les forces extérieures sont dues au **sol**. La loi de Newton donne : **F_CS − F_RS = (m_C + m_R) aₓ**

**Application : le vol des avions.** Le principe d'action et réaction permet aussi d'expliquer d'une certaine manière pourquoi les avions volent (ce n'est pas vraiment une explication — on justifie par l'observation — mais c'est équivalent à traiter le problème avec les équations de Bernoulli ou de Navier-Stokes).
- 4 forces principales : la **traction** (poussée, due aux moteurs), la **traînée** (frottements de l'air), le **poids**, la **portance** (due à l'écoulement de l'air autour des ailes).
- Si l'aile a pour effet de **dévier l'air vers le bas**, cela implique (action-réaction) qu'il y a forcément une force **vers le haut** exercée par l'air sur l'aile : c'est la **portance**.

## 5. Méthode de résolution — exercice de la luge

Une luge de 8 kg est sur une pente **sans frottement** inclinée à 35°. Elle est attachée à une corde faisant un angle de 20° par rapport à la pente, avec une tension de 40 N. Déterminer l'accélération de la luge et la force normale exercée par la pente.

1. **Loi de Newton projetée** (axe x le long de la pente, y perpendiculaire) :
   F⃗ = m a⃗ → T⃗ + N⃗ + P⃗ = m a⃗
   - T cos α − m g sin θ = m aₓ
   - T sin α + N − m g cos θ = 0
2. **Prise en compte des données** (m g ≈ 80 N) :
   - 40 cos 20° − 80 sin 35° = 8 aₓ
   - 40 sin 20° + N − 80 cos 35° = 0
3. **Résolution** (calculée, le slide laisse « … ») : aₓ ≈ (37,6 − 45,9)/8 ≈ **−1,04 m/s²** (la luge accélère vers le bas de la pente) ; N ≈ 65,5 − 13,7 ≈ **51,9 N**.

## 6. Dynamique du mouvement circulaire

Un corps en **MCU** est soumis à une accélération **a_r = v²/r**. Pour maintenir ce mouvement, il faut une force, appelée **force centripète** :

**F_cent = m v² / r**

- C'est le cas du mouvement des planètes, dont l'origine est gravitationnelle.
- La force centripète **ne doit pas être ajoutée** aux autres forces : elle trouve son origine dans des forces « physiques » (gravitation, frottement, …).
- Ne pas confondre force **centripète** et force **centrifuge**, qui apparaît dans un repère **non inertiel**.

## 7. La loi de la gravitation

Avec les principes fondamentaux de la mécanique, la deuxième — et probablement la plus importante — contribution de Newton fut la découverte de la loi de l'interaction de **gravitation**, responsable de la force qui nous maintient au sol et du mouvement des planètes.

**Raisonnement de Newton (1655).** Une planète de masse m_p se déplace à la vitesse v sur une trajectoire approximativement circulaire de rayon r autour du Soleil. Pour maintenir ce mouvement circulaire (accélération radiale), une force centripète doit exister :
- F⃗ = m_p a⃗_r avec a_r = v²/r
- F = m_p v²/r = m_p (4π² r / T²) = (m_p / r²) · 4π² · (r³/T²)
- **3ᵉ loi de Kepler** : r³/T² est constant quelle que soit la planète du système solaire (« le carré de la période de l'orbite d'une planète est proportionnel au cube de sa distance moyenne au Soleil »).
- Donc **F = K_s m_p / r²**, où K_s ne dépend que du Soleil, pas de la planète.

**Action-réaction :** il existe une force F′, égale en grandeur à F, exercée par la planète sur le Soleil : F′ = K_p m_s / r².
- F′ = F → K_s / m_s = K_p / m_p = … = **G**
- K_s = G m_s → **F = G m_s m_p / r²**

L'hypothèse de Newton : cette loi s'applique à **toutes les paires d'objets** de l'univers :

**F⃗ = G m₁ m₂ / r² · e⃗** (e⃗ : vecteur unitaire selon la droite joignant les 2 masses)

- La constante G restait inconnue, tout comme la masse de la Terre : il faudra attendre les travaux de **Cavendish** pour estimer G (**1798**).
- Deux points matériels quelconques s'attirent selon la droite qui les joint, proportionnellement au produit de leurs masses et inversement proportionnellement au carré de leur distance. Non seulement la Terre attire les corps à sa surface, mais **ceux-ci attirent aussi la Terre** : la pesanteur n'est qu'un cas particulier de l'attraction universelle.
- Ces forces sont extrêmement faibles : on ne les met en évidence au laboratoire qu'avec une **balance de torsion** très sensible.
- La loi de gravitation a conduit à la découverte de **Neptune** et **Pluton** : les anomalies de l'orbite d'Uranus amenèrent **Le Verrier** (1811-1877) à prédire Neptune, confirmée par **Galle** en 1848 ; les perturbations de l'orbite de Neptune conduisirent à la découverte de Pluton.

## 8. Poids d'un corps

Le **poids** d'un corps est la force gravitationnelle qui agit sur lui :
**P = G m m_terre / R_terre² = m (G m_terre / R_terre²) = m g**, avec g ≈ 9,81 m/s²
(m_terre = 5,98·10²⁴ kg ; R_terre = 6,37·10⁶ m ; G = 6,674·10⁻¹¹ N m² kg⁻²)

Un corps uniquement soumis à son poids subit l'accélération : F = m a → m g = m a → **a = g** (expérience de pensée d'Aristote et Galilée, 1604 ; plume de faucon et marteau).

**Remarque :** ne pas confondre « **poids** d'un corps » et « **poids apparent** » (personne dans un ascenseur qui accélère) : le poids apparent dépend du référentiel, éventuellement accéléré.

## 9. Gravitation et matière noire

Tout corps de masse m gravitant autour d'un corps de masse M respecte :
F = m a → G m M / R² = m v²/R → G M / R² = v²/R → **v = √(G M / R)**
(Valeurs bien vérifiées par les mesures : Lune autour de la Terre, Terre autour du Soleil, …)

**Remarque :** la vitesse **ne dépend pas de la masse m** de l'objet qui gravite (comme un corps en chute libre). Connaître v et R pour tout corps en orbite permet d'obtenir **M**.

**Exemple :** la Terre se déplace à 107 000 km/h sur une orbite de rayon 150 millions de km : masse du Soleil ?
M = R v² / G = 1,5·10¹¹ · (1,07·10⁸)² / [6,7·10⁻¹¹ · (3600)²] ≈ **2·10³⁰ kg**

La relation reste valable pour les **étoiles en orbite autour d'une galaxie** : si l'on mesure la vitesse d'une étoile (et sa position), on en déduit la **masse de la galaxie**. Cette vitesse se mesure simplement grâce à l'**effet Doppler** (chapitre « Son et lumière »).
- Résultat **sans équivoque** : il y a de la matière qu'on ne peut ni voir ni détecter directement : la **matière noire** (premiers résultats discutables en 1970).
- **Matière noire : 27 % ; énergie noire : 68 % ; matière ordinaire : 5 %.**
- L'hypothèse selon laquelle la loi de Newton serait inexacte sur de grandes distances a pu être rejetée ; d'autres preuves existent (lentilles gravitationnelles, …).
- La découverte de la matière noire compte parmi les plus grands événements scientifiques des dernières décennies (voir cours de Bloc 2).

## 10. Applications

**Masse du Soleil** (distance Terre-Soleil 150 millions de km + période de révolution) :
- F = m_terre a_r → G m_soleil m_terre / D_ts² = m_terre v²/D_ts
- G m_soleil / D_ts² = (4π²/T²) D_ts → **m_soleil = 4π² D_ts³ / (G T²) = 2·10³⁰ kg** (voir plus loin pour éviter d'utiliser G)

**Distance Terre-Lune** (période de révolution de la Lune : 28 jours ; masse de la Terre : 5,97·10²⁴ kg) :
- F = m_Lune a_r → G m_Lune m_Terre / D_TL² = m_Lune v²/D_TL = m_Lune (2π D_TL/T)² / D_TL
- G m_Terre / D_TL² = (4π²/T²) D_TL → **D_TL³ = G m_Terre T² / (4π²)** → **D ≈ 389 000 km**

**Exercice — satellite géostationnaire** (seules données : R_Terre = 6400 km et g = 9,81 m/s²). Estimer l'altitude requise.
- F = m a : G M_T m / (R_T + h)² = m [2π(R_T + h)/T]² / (R_T + h)
- Avec g = G M_T / R_T² : g R_T² = 4π² (R_T + h)³ / T²
- **R_T + h = (g R_T² T² / 4π²)^(1/3)** ≈ (10 · 6,4²·10¹² · (2,4·10¹ · 3,6·10³)² / (4·10))^(1/3) ≈ 10^(23/3) ≈ **4·10⁷ m = 40 000 km**
- Approximations utilisées : 6² ≈ 4·10¹ ; 3600 ≈ 4·10³ ; 2,4 ≈ 10¹ ; ∛100 ≈ 4 ; π² ≈ 10 ; 1 jour = 24·3600 s.
- (Valeur exacte : 35 784 km.)

**Centrifugation de l'uranium.** Principal usage d'une centrifugeuse dans un contexte nucléaire : **enrichir l'uranium en uranium 235**. L'uranium 238 constitue 99,3 % de l'uranium extrait ; c'est l'isotope 235 qui est requis. Séparer l'U-235 de l'U-238 est primordial pour une réaction de fission en chaîne (centrale ou bombe).
- Le gaz (hexafluorure d'uranium) est introduit dans des cascades de milliers de centrifugeuses (rotor de 1 à 2 m de haut, 15 à 20 cm de diamètre).
- Quand les rotors tournent très vite, les molécules d'**U-238** (plus lourdes) se concentrent à l'**extérieur**, celles d'**U-235** près de l'**axe**.
- Les centrifugeuses tournent à 50 000-70 000 tours/min (paroi à 400-500 m/s). La fraction légèrement enrichie alimente la centrifugeuse suivante ; la fraction appauvrie repart à la précédente.

## 11. Constante G et masse de la Terre

1. **Ératosthène** (−200 av. J.-C.) : une mesure de 7,2° (et de la distance AB ≈ 800 km) permet d'estimer le rayon de la Terre : **R_T = d_AB · (360°/7,2°) / 2π ≈ 6400 km**.
2. **Cavendish** (1798) : à l'aide d'un **pendule de torsion** (masses de 0,78 kg et 158 kg), il mesure la force d'attraction entre 2 masses et en déduit **G**. La masse de la Terre se déduit alors par **g = G m_terre / R_terre²** (certains disent que Cavendish a « mesuré la masse de la Terre »).

## 12. Distance Terre-Soleil — unité astronomique (UA)

Estimations successives (méthodes géométriques, durées d'éclipses) :

| Auteur | Distance |
|---|---|
| Anaximandre (−560) | 172 000 km |
| Aristarque (−300) | 6 720 000 km |
| Ptolémée (2ᵉ s. ap. J.-C.) | 7 710 000 km |
| Copernic (1532) | 7 520 000 km |
| Kepler | 21 930 000 km |
| Vendelinus (1650) | 88 000 000 km |
| Cassini (1672) | 140 000 000 km |
| J. De Lalande (1761) | 150 000 000 km |
| Aujourd'hui (définition de l'UA) | 149 597 870 km |

NB : cette distance donne le temps mis par la lumière pour le trajet Soleil-Terre : **8 min**.

## 13. Principe d'équivalence

**Principe d'équivalence** : localement, les effets d'un **champ gravitationnel** sur toute expérience sont **identiques** aux effets d'une **accélération du référentiel** de l'observateur. Il est impossible de trouver une expérience permettant de distinguer ces 2 situations.

Exemple (notes) : deux personnes enfermées dans deux cabines identiques, l'une à la surface de la Terre, l'autre accrochée à une fusée qui accélère dans l'espace. Elles lâchent une pomme. La première voit la pomme tomber sous l'effet de la gravité. Dans la seconde, sans gravité, la cabine est accélérée vers le haut ; la pomme lâchée ne suit pas le mouvement et semble donc tomber. Si la puissance de la fusée est bien choisie, elle tombe exactement comme sur Terre : les deux observateurs ne peuvent pas savoir dans quelle cabine ils se trouvent.

**Einstein** généralisa cette idée à toutes les lois de la physique et lui donna le nom de principe d'équivalence : point de départ de la **relativité générale**, qui allait révolutionner la physique et l'astrophysique (effet de la matière sur le temps — trous noirs —, influence d'un champ gravitationnel sur la trajectoire d'un rayon lumineux).

## 14. Les marées

*(Lecture du schéma du slide, sans texte explicatif.)* L'attraction de la **Lune** n'est pas la même en tout point de la Terre (plus forte du côté face à la Lune, plus faible du côté opposé) : la différence par rapport à l'attraction au centre de la Terre étire les océans selon l'axe Terre-Lune → **2 marées hautes** (côté face à la Lune et côté opposé) et 2 marées basses. Le Soleil intervient aussi (configurations A et B du schéma).

## 15. Forces fictives : le vol parabolique

Un très bon exemple de **forces fictives d'inertie** (f.f.i.) est le **vol parabolique** : l'avion suit la même trajectoire qu'un objet lancé obliquement (chute libre), c'est-à-dire un mouvement dont le vecteur accélération est g⃗ (phase à « 0 g », encadrée de phases à 1,8 g).

Dans le référentiel de l'avion, une personne à bord ressent :
**F⃗_totale = m g⃗ + f⃗fi = m g⃗ − m g⃗ = 0⃗**

- NB1 : résultat similaire dans un ascenseur abandonné à lui-même en chute libre.
- NB2 : nous sommes incapables de discerner une force « réelle » d'une f.f.i., puisque ses effets sont identiques.

## 16. Forces de frottement (entre 2 surfaces en contact)

Lorsque 2 corps sont en contact apparaissent des forces **perpendiculaires** à la surface de contact (les **normales**) et, en réalité, des forces **tangentes** à cette surface : le **frottement** (ou friction). Le frottement « gêne » le mouvement, cause l'abrasion et l'usure et convertit en chaleur l'énergie mécanique.
- L'expérience montre qu'il faut distinguer frottement **statique** et frottement **cinétique**.
- Les relations suivantes constituent le **modèle de Coulomb**, valable généralement pour des surfaces « sèches ».

**1. Frottement cinétique :** **f_c = μ_c N**
(μ_c : coefficient de frottement cinétique ; N : composante normale de la réaction de la surface — attention, **N n'est pas nécessairement égale au poids**.)

**2. Frottement statique :** **f_s^max = μ_s N ⇔ f_s ≤ μ_s N** (μ_s : coefficient de frottement statique)

Exemple : un déménageur tente de déplacer un meuble de 25 kg (μ_s = 0,2) : N = m g ≈ 250 N → **f_s^max = μ_s N = 50 N**.
- F = 10 N → f_s = 10 N : le frottement empêche le mouvement.
- F = 30 N → f_s = 30 N : le frottement empêche le mouvement.
- F = 50 N → f_s = 50 N : frottement maximal atteint, le meuble va bouger.
- F = 60 N : il n'y a plus de frottement statique mais **cinétique** ; le meuble est en mouvement (il accélère même, puisque 60 > 50).

**Coefficients de frottement (μ_s / μ_c) :**

| Surfaces | μ_s | μ_c |
|---|---|---|
| Bois sur bois | 0,4 | 0,2 |
| Bois ciré sur neige fondante | 0,14 | 0,1 |
| Glace sur glace | 0,1 | 0,03 |
| Métal sur métal (lubrifié) | 0,15 | 0,07 |
| Acier sur acier (non lubrifié) | 0,7 | 0,6 |
| Caoutchouc sur ciment sec | 1,0 | 0,8 |
| Caoutchouc sur ciment mouillé | 0,7 | 0,5 |
| Téflon sur téflon dans l'air | 0,04 | 0,04 |
| Téflon sur acier dans l'air | 0,04 | 0,04 |
| Roulement à billes lubrifiées | < 0,01 | < 0,01 |
| Articulations du corps humain (membranes synoviales) | 0,01 | 0,01 |

**Remarque : μ_s > μ_c.** Graphe de la force de frottement en fonction de la force appliquée : f croît (frottement statique, f = F_A) jusqu'à μ_s N, puis chute et reste constante à μ_c N (frottement cinétique).

**Exercice (forces de frottement).** Bloc de 5 kg sur une surface horizontale (μ_s = 0,2 ; μ_c = 0,1). On le tire avec une force orientée à 60° par rapport à l'horizontale. Une force de 20 N suffit-elle ? Si oui, quelle accélération ?
1. **Loi de Newton projetée** : f⃗ + T⃗₀ + N⃗ + m g⃗ = m a⃗
   - T₀ cos θ − f = m a → 20 · ½ − f = 5 a
   - N + T₀ sin θ − m g = 0 → N + 20 · √3/2 − 50 = 0 → **N = 32,7 N**
2. **Calcul de f — mouvement ou pas ?** Hypothèse de repos (a = 0) : f = 10 N. Est-ce que f ≤ f_s^max = μ_s N ? 10 ≤ 0,2 · 32,7 ≈ 6,5 → **NON**.
   → La force de 20 N **suffit** à créer un mouvement, et la force de frottement (cinétique) est connue.
3. a = (20 · ½ − μ_c N)/m = (10 − 3,27)/5 ≈ **1,35 m/s²** (valeur calculée, le slide s'arrête à « … »).
