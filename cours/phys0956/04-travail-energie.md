# Chapitre 4 — Travail et énergie

Référence principale du cours : *Physique*, Harris Benson (De Boeck).

Les notions de **travail** et d'**énergie** sont essentielles en physique :
- elles permettent d'énoncer un grand principe : la **conservation de l'énergie** (la physique moderne modifie et précise cette notion) ;
- elles fournissent une **méthode de résolution de problèmes très efficace**.

## 1. Travail d'une force

**W = F⃗ · d⃗ = F · d · cos θ**

- W en **joules (J)**, F en **newtons (N)**, d en **mètres (m)** ;
- θ = angle entre la force F⃗ et le déplacement d⃗.
- Un travail peut être **positif, négatif ou nul**.

Plus généralement (force variable le long du trajet) : **W = ∫ F⃗ · dx⃗** (intégrale de la position initiale i à la position finale f).

## 2. Travail et énergie

Lorsqu'un travail est réalisé sur un corps, celui-ci acquiert une **énergie équivalente**.

**Cas 1 — On soulève lentement une masse m d'une hauteur h**
- W = F · d = m g h
- **Wₚ = m g h** : la masse a acquis une énergie dite **potentielle**.

**Cas 2 — Force constante sur un corps qui glisse sans frottement sur un plan horizontal**
- Le corps accélère : W = f · d = m a · d
- Cinématique : v_f² = v_i² + 2 a d ; départ au repos : v² = 2 a d, donc a = v² / (2d)
- D'où W = m · v²/(2d) · d, soit **W_c = ½ m v²** : la masse a acquis une énergie dite **cinétique**.

NB : ces énergies **dépendent du référentiel**.

D'autres formes d'énergie potentielle existent, une pour chaque type d'interaction (force électrique, force de rappel d'un ressort, …).

## 3. Conservation de l'énergie

- **Galilée** (expérience du pendule) fut le premier à penser que, dans le mouvement d'un corps, une quantité demeure constante — et ce longtemps avant les travaux de Newton.
- Si l'on modifie l'oscillation d'un pendule par un clou, la masse continue de s'élever **jusqu'au niveau initial**.
- **L'énergie potentielle se transforme en énergie cinétique et inversement.**
- La grandeur conservée est l'**énergie totale**, appelée aussi **énergie mécanique** (énergie potentielle + énergie cinétique).

**Généralisation :** l'énergie peut changer de forme, mais elle ne peut **jamais être créée ni détruite**.

## 4. Théorème de l'énergie cinétique

**Énoncé simplifié :** la variation d'énergie cinétique est égale à la somme des travaux W des **forces extérieures** qui s'exercent sur le corps considéré :

**W = ΔE_c**

- Forces extérieures : forces appliquées quelconques, poids, forces de frottement, …
- Cet énoncé est une manière d'exprimer simplement la **conservation de l'énergie mécanique**.
- Un *théorème* est un énoncé qui peut être démontré mathématiquement par un raisonnement logique à partir d'hypothèses justifiables (autres théorèmes, postulats, …).
- Ce théorème n'est publié qu'en **1820**, alors que les lois de Newton datent de **1687**.

**Démonstration :**
W = ∫ F⃗·dx⃗ = ∫ m a⃗·dx⃗ = ∫ m (dv⃗/dt)·dx⃗ = ∫ m (dx⃗/dt)·dv⃗ = ∫ m v⃗·dv⃗ = [½ m v²] entre v₁ et v₂ = ΔE_c

## 5. Puissance mécanique

La puissance exprime le **travail réalisé par unité de temps** :

**P = W / t** — unité : le **watt**, 1 W = 1 J/s

Puissance, force et vitesse sont aussi reliées : P = W/t = F⃗·d⃗ / t, donc **P = F⃗ · v⃗**

On exprime aussi souvent des énergies en kWh : **1 kWh = 1000 J/s × 3600 s = 3,6·10⁶ J**

(On parlera plus tard de puissance électrique.)

## 6. Exercices du cours

**Exercice 1 — Chute libre.** On lâche une masse m = 2 kg d'une hauteur de 5 m. Quelle est la vitesse acquise ?
- W = ΔE_c → m g h = ½ m v² → **v = √(2 g h)** ≈ **10 m/s**
- (La masse se simplifie : la vitesse ne dépend pas de m.)

**Exercice 2 — Bloc tiré avec frottement.** Un bloc de m = 4 kg est tiré sur 2 m par une force F = 30 N faisant un angle de 53° avec l'horizontale. Bloc initialement au repos, coefficient de frottement cinétique μ_c = 0,125. Vitesse acquise ?
- Théorème de l'énergie cinétique : F cos θ · d − f_f · d = ½ m v²
- Frottement : f_f = μ_c N = μ_c (m g − F sin θ) (la composante verticale de F diminue la normale)
- F cos θ · d − μ_c (m g − F sin θ) · d = ½ m v²
- **v = √[ (2 F cos θ · d − 2 μ_c (m g − F sin θ) · d) / m ]**
- Application numérique (calculée avec g = 9,8 m/s²) : v ≈ 4,0 m/s

**Exercice 3 — Examen janvier 2024 (?).**
a. Estimer g sur la Lune (masse de la Lune = 1,23 % de celle de la Terre ; rayon = 27,2 % de celui de la Terre).
b. Un astronaute tombant d'une falaise de 100 m sur la Lune serait-il sauvé par la faible gravité ?
c. À quelle hauteur sur Terre cette chute occasionnerait-elle les mêmes séquelles ?

Résolution :
- g_T = G M_T / R_T² ; g_L = G M_L / R_L² = g_T · 1,23·10⁻² / (2,7·10⁻¹)² = g_T · 1,2·10⁻² / 7·10⁻² ≈ **g_T / 6**
- Sur Terre : v = √(2 g h) = √2000 ≈ 45 m/s ≈ 160 km/h
- Sur la Lune : v = v_Terre / √6 ≈ 18 m/s ≈ 65 km/h
- Probablement mortel dans les 2 cas : la chute de 100 m sur la Lune correspond à une chute de **17 m sur Terre** (6 fois moins), soit près de 5 étages.

## Questions

- Un travail peut-il être réalisé par une force centripète ?
- Si l'énergie cinétique d'une particule double, par quel facteur la vitesse est-elle multipliée ?
- L'énergie cinétique d'une particule peut-elle être négative ?

*Pistes déduites des formules du chapitre :* force centripète ⊥ déplacement → cos 90° = 0 → W = 0. E_c = ½ m v² : E_c × 2 → v × √2. E_c = ½ m v² avec m > 0 et v² ≥ 0 → jamais négative.
