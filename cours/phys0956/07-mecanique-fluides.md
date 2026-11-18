# Chapitre 7 — Mécanique des fluides

1. **Statique des fluides** ; 2. **Dynamique des fluides**.

**Notions importantes :** masse volumique et densité ; relation fondamentale de l'hydrostatique ; principe de Pascal ; principe d'Archimède ; tension superficielle ; équation de continuité ; théorème de Bernoulli — avec de nombreuses applications et exercices.

- Grandeurs physiques importantes : masse volumique et densité, pression dans les fluides, poussée.
- Grands principes : relation fondamentale, principe de Pascal, principe d'Archimède, équation de continuité, théorème de Bernoulli.
- Applications : ballons dirigeables, stabilité des bateaux, principe de l'avion, …

# Partie 1 — Statique des fluides

## 1. Masse volumique et densité

« **Eurêka** » (Archimède, IIIᵉ s. av. J.-C.)

**Masse volumique : ρ = m / V** (masse / volume)

Exemples : **ρ_eau(4°C) = 1000 kg/m³ = 1 g/cm³** ; **ρ_Hg = 13 600 kg/m³ = 13,6 g/cm³**

**Densité : d = ρ / ρ_eau(4°C)** → d_eau = 1 ; d_Hg = 13,6
La densité est le rapport entre la masse volumique d'une substance et celle de l'eau à 4 °C (1000 kg/m³). Grandeur **sans dimension**, numériquement égale à la masse volumique exprimée en g/cm³.

| Substance | ρ (kg/m³) | Substance | ρ (kg/m³) |
|---|---|---|---|
| Air | 1,29 | Bois de pin | 0,43·10³ |
| H | 0,09 | Al | 2,70·10³ |
| He | 0,18 | Fe | 7,86·10³ |
| O | 1,43 | Ag | 10,5·10³ |
| Hg | 13,6·10³ | Pb | 11,3·10³ |
| Au | 19,3·10³ | Pt | 21,4·10³ |
| Cu | 8,9·10³ | Alcool éthylique | 0,8·10³ |
| Eau de mer | 1,025·10³ | Sang | 1,05·10³ |

## 2. Force et pression

La **pression** est la force exercée par unité de surface : **P = F / S** (unité : N/m² ou **Pa**).

## 3. La pression dans les fluides au repos

**Principe :** la pression sur un petit élément de volume exercée par le fluide environnant est la même **dans toutes les directions** (à démontrer à l'aide des lois de Newton).

**La pression atmosphérique** se met facilement en évidence par l'expérience de **Torricelli**. On observe une pression atmosphérique proche de (aussi 76 cm Hg, voir plus loin) :
- **P_atm = 10⁵ N/m² = 10⁵ Pa = 1000 hPa = 1 bar ≈ 14,5 psi** (1 psi = pound(-force) per square inch, livre par pouce carré)
- Forme « parlante » (analogie, sans l'unité de pression) : **P_atm ≈ 10⁴ kg/m² = 1 kg/cm²**
- Valeur de référence, « pression atmosphérique » ou **1 atm = 1,013·10⁵ Pa** (voir cours « Thermodynamique »).

Cette valeur surprenante se met en évidence par des expériences amusantes : le **carton de bière** sur un verre plein retourné ; l'**expérience de von Guericke** (1645, hémisphères de Magdebourg que des chevaux ne parviennent pas à séparer).

**Dans la vie courante, on rencontre des pressions bien plus grandes :**
- Un doigt appuyant sur une aiguille (pointe de 0,2 mm de diamètre) : F ≈ 3 N ; S ≈ π(0,1)² ≈ 0,03 mm² = 3·10⁻⁸ m² → **P = 10⁸ N/m² ≈ 1000 atm**
- Le dard d'une guêpe peut dépasser **1 000 000 atm** (rayon de la pointe < un centième de micron) : F ≈ 10⁻⁴ N ; S ≈ π(0,00001)² ≈ 3·10⁻¹⁰ mm² = 3·10⁻¹⁶ m² → P = 3·10¹¹ N/m² ≈ 3·10⁶ atm

**Expérience (vases communicants de formes différentes) :** la pression dans un fluide **ne dépend que de la profondeur** et **pas de la forme du récipient**.

## 4. Relation fondamentale de l'hydrostatique

La pression d'un fluide à une profondeur h :

**P = P₀ + ρ g h**
(P₀ : pression atmosphérique ou pression à la surface du fluide ; ρ : masse volumique du fluide ; h : profondeur)

Démonstration : colonne de hauteur h et de section A à l'équilibre :
- P·A = P₀·A + m g = P₀·A + ρ V g = P₀·A + ρ (A h) g → **P = P₀ + ρ g h**

- La pression **augmente linéairement** avec la profondeur. Tous les 10 m, la pression de l'eau augmente de : ρ g h = 1000 · 9,81 · 10 ≈ **10⁵ Pa ≈ 1 atm**.
- De manière étonnante, un **barrage** doit être construit de la même façon quelle que soit la quantité d'eau retenue derrière (grand lac ou mince couche) : seule la hauteur compte.
- **Le crève-tonneau de Pascal** : Pascal insère un tube de 10 m de long dans un tonneau rempli d'eau. En ajoutant de l'eau dans le tube, il montre que l'augmentation de pression fait **exploser le tonneau**.

**Exercice — tube en U.** Tube en U de 1 cm de diamètre intérieur, rempli d'eau jusqu'à 50 cm du bord. On ajoute à droite 50 ml d'huile (ρ = 750 kg/m³). Calculer la hauteur L de la colonne d'huile et la différence de hauteur h entre le niveau de droite et celui de gauche.
- Dans ce type de problème, il faut toujours exprimer l'**égalité de pression entre 2 points** (au même niveau dans le même liquide).
- S = π · 0,005² m² ; V = 5·10⁻⁵ m³ → **L = V/S = 0,63 m**
- P_atm + ρ_eau g (L − h) = P_atm + ρ_huile g L → **h = L (ρ_eau − ρ_huile)/ρ_eau = 0,63 · 0,25 = 0,16 m**
- Bonus : montrer qu'il n'y aura pas de débordement : les niveaux de gauche et de droite s'élèvent respectivement de h_g = (L − h)/2 = 23 cm et h_d = (L + h)/2 = 40 cm (< 50 cm).

## 5. Applications : mesure de la pression

- **Le manomètre** : la pression relative se mesure par la différence des niveaux : **ΔP = ρ g h**
- **Le baromètre de Torricelli** : la pression ambiante se mesure par la hauteur de la colonne de liquide (souvent du mercure) : P = ρ g h → h = 10⁵ / (13 600 · 9,81) = **0,76 m**

**Exercice.** De quelle hauteur s'élèverait l'eau dans un tube renversé fermé (comme chez Torricelli) pour une pression atmosphérique de 1 atm ? ΔP = ρ g h → 10⁵ = 1000 · 9,81 · h → **h = 10,2 m** (N.B. : 10,3 = 13,6 × 0,76).

**Exercice — tension artérielle.** La prise de tension au bras doit se faire à la hauteur du cœur. Influence sur la mesure si le bras est levé de 40 cm au-dessus du cœur ? (Réponse en cm Hg ; densité du sang : 1,05.)
- ΔP = ρ_sang g h = 1,05·10³ · 10 · 0,4 = 4200 Pa = 4,2·10³ · 76/10⁵ = **3,2 cm Hg (en moins)**
- On peut donc estimer une augmentation (diminution) de l'ordre de **1 cm Hg tous les 10 cm**.

## 6. Pompe aspirante

Lorsqu'une pompe aspire de l'eau, elle crée une **dépression** dans le tuyau d'entrée (idéalement, le vide) — principe de la paille. C'est la **pression atmosphérique** qui pousse l'eau vers la pompe (ce n'est pas la pompe qui tire, mais la P_atm qui pousse ; le rôle de la pompe n'est qu'indirect).
- Il n'est donc **pas possible de pomper de l'eau à une profondeur de plus de 10,34 m** (en pratique 6-7 m).
- Torricelli observe que les fontainiers de Florence ne peuvent monter l'eau avec une pompe aspirante à plus de 10,4 m ; il comprend que cette limite est due à la pression atmosphérique.
- NB : il s'agit ici de pompes **à aspiration** ; d'autres pompes, dites **à refoulement**, sont capables de pousser l'eau.

## 7. Le principe de Pascal

En **1653**, **Pascal** énonce : une pression extérieure exercée sur un fluide dans un récipient **fermé** est **transmise intégralement** à toutes les parties du fluide et aux parois du récipient.

**F₂/A₂ = F₁/A₁ ⇔ F₂/F₁ = A₂/A₁**

Applications : **pont élévateur**, **freins d'automobile** (pédale → piston → huile → étrier, plaquettes, disque).

Blaise Pascal (1620-1662) n'a pas été seulement le moraliste des *Pensées* : mathématicien et physicien, il mena des recherches expérimentales sur le vide et la pression atmosphérique et vérifia les hypothèses de Torricelli (élève de Galilée).

## 8. Le principe d'Archimède

**Qu'est-ce que la poussée ?** Tout corps immergé entièrement ou en partie subit **son poids** et **une poussée** (notée B⃗, dirigée vers le haut ; la pression est supérieure sous le corps). La résultante des forces de pression *semble* difficile à calculer pour un corps de forme quelconque… et pourtant.

De manière générale, un corps immergé **monte si B > mg** et **s'enfonce si B < mg**.

**Comment déterminer la poussée ?** Considérons 2 situations :
- Un corps solide quelconque plongé dans le fluide (système = le solide). La poussée ne dépend **que de la forme de la surface extérieure**, pas de la nature de la matière intérieure.
- Le récipient ne contient que le fluide, mais on considère comme système une portion de fluide de surface extérieure identique : la poussée est donc **identique**.
- Cette portion de fluide est en équilibre : **B = m g = ρ_fluide V g**
- Si le corps est partiellement immergé : **B = ρ_fluide V_sub g**

(Notes : la poussée est la résultante des forces de pression ; on la détermine en imaginant le remplacement du corps par un corps de même volume mais de même nature que le fluide environnant.)

**Principe d'Archimède :** un corps plongé dans un fluide subit une poussée (force dirigée vers le haut) **égale au poids du fluide que le corps « déplace »** :

**B = ρ_f V g** (B : poussée ; ρ_f : masse volumique du fluide déplacé ; V : volume du corps ; g : accélération de la pesanteur)

Trois possibilités :
- **ρ_c > ρ_f** : le corps s'enfonce complètement ;
- **ρ_c < ρ_f** : le corps flotte ;
- **ρ_c = ρ_f** : le corps est immobile mais immergé.

Si le corps n'est pas homogène, c'est la **masse volumique moyenne** qui intervient (navire : coque d'acier + air ou matériaux légers → masse volumique moyenne inférieure à celle de l'eau). L'égalité des masses volumiques moyennes est recherchée par les **plongeurs** (poids de la ceinture de plomb compensant l'action des bouteilles).

**Applications :** corps flottants (bateaux, morceau de bois, …) ; ballons dirigeables ; immersion et émersion des sous-marins ; le **ludion**.
NB : pour un corps partiellement immergé, il faut éventuellement tenir compte de la poussée due à l'air (souvent négligeable).

## 9. Exercices — principe d'Archimède

**Méthode :** la résolution passe par l'**égalisation du poids et de la poussée**. À l'équilibre : m g⃗ + B⃗ = 0⃗, soit en norme **m g = B**. On débute les exercices par **P = B**.

**Exercice — l'iceberg.** Iceberg (ρ = 920 kg/m³) flottant sur un océan (ρ = 1025 kg/m³). Fraction de son volume submergée ?
- P = B → ρ_iceberg V_iceberg g = ρ_eau V_sub g
- **V_sub / V_iceberg = ρ_iceberg / ρ_eau = 920/1025 ≈ 90 %**
- Question : un objet flottant sur la Terre flotterait-il de la même manière sur la Lune ?

**Application — le glaçon qui fond** dans un verre d'eau à 0 °C : comment évolue le niveau ?
- Le niveau est **stationnaire** : en fondant, la glace occupe **exactement** le volume initialement immergé.
- Attention : un glaçon d'**eau douce** dans de l'**eau de mer** → le niveau **augmente**. Pourquoi ?
- Ce n'est donc **pas la fonte de la banquise** (eau de mer) qui contribue à l'élévation du niveau de la mer, mais la fonte des **glaciers** (calotte glaciaire), constitués d'eau douce (neige, …). Un iceberg provient d'un glacier (eau douce) : sa fonte a donc un effet.
- Image (notes) : si la glace était 3 fois moins dense que l'eau (très exagéré), la partie immergée vaudrait 1/3 du volume (poids = poussée) ; une fois fondu, le glaçon occuperait une place exactement 3 fois plus petite (masse volumique × 3, conservation de la masse) → niveau constant.

**Exercice — décrire formellement le raisonnement :**
- Poids = poussée : ρ_glace V_glace g = ρ_eau V_sub g → V_sub/V_glace = ρ_glace/ρ_eau
- Conservation de la masse : m_eau = m_glace → ρ_eau V_eau = ρ_glace V_glace → V_eau = V_glace ρ_glace/ρ_eau = V_glace · V_sub/V_glace
- → **V_eau = V_sub**

**Énigme — le bateau dans l'aquarium.** Que se passe-t-il lorsque le bateau se déplace vers la droite ? L'aquarium (posé en porte-à-faux) basculera-t-il ?
- Non : le mouvement du bateau à l'intérieur ne change pas la position du **centre de masse** de l'ensemble (aquarium + eau + bateau). Le déplacement du bateau est exactement compensé par le déplacement de l'eau. La stabilité n'est pas compromise tant que le CM total reste au-dessus du support.

**Application — la montgolfière.** Sous l'action de la chaleur, l'air se dilate, avec un **double effet** : **augmentation** du volume (donc de la poussée d'Archimède) et **diminution** du poids de l'air — 2 effets favorisant la montée. La température est régulée par le **brûleur** et la **soupape** (qui laisse échapper l'air chaud par le haut) pour monter ou descendre. La montgolfière ne peut pas se diriger latéralement, sauf en profitant des courants d'air.

**Exercice — ballon d'hélium.** Un ballon sphérique rempli d'hélium à 1 atm soulève tout juste une charge de 2 kg (masse du ballon comprise, sans le gaz). Son rayon ? (ρ_He = 0,18 kg/m³ ; ρ_air = 1,29 kg/m³)
- P = B : P = (m_charge + ρ_He V) g ; B = ρ_air V g
- m_charge + ρ_He V = ρ_air V → V = m_charge/(ρ_air − ρ_He) = **1,8 m³**
- **R = ∛(V/(4π/3)) = 0,75 m** (NB : pour ces gaz, R = 0,603 · m^(1/3))

**Exercice — bloc de bois.** Un cube de bois de 500 g flotte avec 40 % de son volume immergé. Masse minimale à placer dessus pour qu'il soit totalement immergé ?
- Situation 1 (poussée = poids) : 0,5 g = ρ_eau (0,4 V) g → ρ_eau V = 1,25
- Situation 2 (immersion complète) : (0,5 + m) g = ρ_eau V g → **m = 0,75 kg**

**Questions**
- Pourquoi le jet d'eau d'un robinet devient-il de plus en plus mince en tombant ?
- Une balle flotte sur l'eau dans un bocal. Si le couvercle est scellé et que la pression au-dessus du fluide augmente, la balle s'enfonce-t-elle ? (balle et liquide incompressibles)
- Un objet suspendu à une ficelle est plongé dans un bocal d'eau placé sur une balance. Qu'indiquera la balance (augmentation ou diminution) ?

# Partie 2 — Dynamique des fluides

Équation de continuité ; théorème de Bernoulli.

## 10. Types d'écoulement

- L'écoulement peut être **laminaire** ou **turbulent** (on se limite au laminaire). L'écoulement laminaire se représente par des **lignes de courant** (rendues visibles en injectant de la teinture) ; un ensemble de lignes forme un **tube d'écoulement**. La vitesse d'une particule est tangente à la ligne de courant.
- L'écoulement peut être **stable** : les lignes de courant **ne se coupent jamais**.
- Si la vitesse du fluide est grande ou s'il rencontre de nombreux obstacles, l'écoulement devient turbulent.

## 11. L'équation de continuité

Pour un fluide **incompressible**, l'égalité des débits en « 1 » et « 2 » donne :

**Q = A₁ v₁ = A₂ v₂**

(Le fluide va plus vite là où la section est plus petite.)

## 12. Le théorème de Bernoulli

Fluide **non visqueux, incompressible**, écoulement **stable et laminaire**. On applique le **théorème de l'énergie cinétique** à la région de fluide suivie entre 2 instants (« avant » et « après ») :
- Travail des forces extérieures : W = F₁Δl₁ − F₂Δl₂ − mg(y₂ − y₁) = P₁A₁Δl₁ − P₂A₂Δl₂ − mg(y₂ − y₁)
- Fluide incompressible : A₁Δl₁ = A₂Δl₂ = V
- W = ΔK : (P₁ − P₂)V − mg(y₂ − y₁) = ½ m (v₂² − v₁²)
- Avec ρ = m/V : **P₁ + ρgy₁ + ½ρv₁² = P₂ + ρgy₂ + ½ρv₂²**

**Théorème de Bernoulli** (établi en 1738 par Daniel Bernoulli) :

**P + ρ g y + ½ ρ v² = constante**
- P : pression « statique » ; ρgy : pression « gravifique » ; ½ρv² : pression « dynamique ».

## 13. Applications du théorème de Bernoulli

**Effet Bernoulli :** atomiseur de parfum, carburateur. (Lorsque l'air soufflé par le tube A passe devant le sommet de B, la pression au sommet de B est inférieure à la normale ; le liquide est aspiré dans B, se mélange à l'air et sort en fines gouttelettes.)

**Énoncé simplifié :** quand l'air est en mouvement, sa **pression est d'autant plus faible que sa vitesse est grande**, et inversement. (Expériences : souffler entre deux feuilles, deux balles suspendues, balle dans un jet d'air, entonnoir, …)

**Mais aussi :** ventilation dans les terriers ; « effets de sol » en automobilisme ; effet du vent sur les toitures (accélération → dépression → toit arraché) ; trompe à eau ou pompe à eau ; bateaux qui « remontent » au vent ; ailes d'avion (en partie expliqué par Bernoulli) ; parapluie retourné ; capote de voiture qui se soulève.

**Le rideau de douche** se rapproche irrémédiablement jusqu'à se coller à la peau. Pourquoi ? Principalement à cause du **jet d'eau qui met l'air en mouvement**, ce qui crée une dépression. (On attribue parfois l'effet à l'eau chaude qui chauffe l'air : cause marginale, une douche froide montre aussi l'effet.)

**Réservoir percé — théorème de Torricelli.** Vitesse de l'eau à la sortie de l'orifice (h sous la surface) :
- P₁ = P₂ = P_atm ; v₁ = 0 → ρ g h = ½ ρ v₂² → **v₂ = √(2 g h)**

**Exercice.** Un trou est percé à une hauteur h dans un récipient cylindrique très large rempli d'eau jusqu'à h₀. Que doit valoir h pour que le jet horizontal touche le sol le plus loin possible ? Distance maximale ?
- Torricelli : v₀ = √(2g(h₀ − h))
- Cinématique : x = v₀ t ; y = h − ½ g t² → arrivée au sol y* = 0 → x* = P = v₀ √(2h/g)
- P = √(2g(h₀ − h)) · √(2h/g) = **2 √(h (h₀ − h))**
- Maximiser P : **h = h₀/2** et **P = h₀**

**Effet Magnus-Robins.** La surface d'un objet en rotation entraîne avec elle les molécules du fluide. Le vent du tourbillon **s'additionne** au vent de déplacement d'un côté et **se soustrait** de l'autre → différence de pression → déviation (coup franc « brossé » contournant le mur ; balle liftée, plate ou coupée au tennis).

**Débitmètre de Venturi.** En mesurant une différence de pression, on obtient le débit :
- Bernoulli (même hauteur) : P₁ + ½ρv₁² = P₂ + ½ρv₂² → 2ΔP = ρ(v₂² − v₁²)
- Continuité : v₂ = v₁ A₁/A₂ → 2ΔP = ρ v₁² (A₁²/A₂² − 1) → v₁² = 2A₂²ΔP / [ρ(A₁² − A₂²)]
- **Débit : Q = A₂A₁ √[2ΔP / (ρ(A₁² − A₂²))]**
- La différence de pression se mesure par un capteur quelconque, ou par une différence de niveau (ΔP = ρ g Δh).
- **Effet Venturi** : formation d'une dépression dans une zone où les particules de fluide sont accélérées.

**Le tube de Pitot** permet notamment de mesurer la **vitesse d'un avion par rapport à l'air**. Principe : mesurer une différence de pression et en déduire la vitesse par Bernoulli :
- P_ext + ½ ρ_air v² = P_capteur → **v² = 2(P_capteur − P_ext)/ρ_air**
