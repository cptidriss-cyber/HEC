# Chapitre 2 — Cinématique : déplacement, vitesse et accélération

La **cinématique** étudie le mouvement des corps **sans se soucier des causes** créant ce mouvement.

## 1. Cinématique à 1 dimension

Soit un mobile se déplaçant le long d'un axe ; sa position x est représentée en fonction du temps.

**Vitesse moyenne** entre tᵢ et t_f :
**v_moyen = (x_f − xᵢ) / (t_f − tᵢ) = Δx / Δt**
Sur le graphique x(t), elle vaut numériquement la **pente de la droite** passant par les positions initiale et finale. (On parlera plus tard d'espace-temps.)

**Vitesse instantanée** : on fait tendre Δt vers 0 :
**v_instant = lim(Δt→0) Δx/Δt = dx/dt**
Représentée par la **pente de la tangente** à la courbe au temps considéré (v > 0 quand x croît, v = 0 au sommet, v < 0 quand x décroît).

## 2. Mouvement rectiligne uniforme (MRU)

Si v_instant = constante (graphe espace/temps = droite) :
Δx/Δt = v = cte → (x − x₀)/(t − 0) = v → **x = x₀ + v t** (x = v t si x₀ = 0)

v peut être positif ou négatif selon que le mobile se déplace ou non dans le sens des x croissants.

NB : il est utile d'adopter dès ce stade une **notation vectorielle** (elle permet une définition rigoureuse de la vitesse) :
**x⃗(t) = x⃗₀ + v⃗ t**, avec v⃗ = dx⃗(t)/dt = constante.

**Exercice — moyenne harmonique.** Un marcheur fait un aller-retour. Sa moyenne horaire (vitesse moyenne) à l'aller est de 3 km/h, au retour de 6 km/h. Moyenne globale ?
- v_moy = 2d/(t₁ + t₂) = 2d/(d/v₁ + d/v₂) = 2 (1/v₁ + 1/v₂)⁻¹ = **2 v₁v₂ / (v₁ + v₂)**
- v_moy = 2 · 3·6/(3 + 6) = **4 km/h** (et non 4,5 km/h)
- En fait, c'est l'**inverse** de la moyenne horaire (parfois appelé « **allure** ») qui obéit à une moyenne arithmétique : **1/v_moy = ½ (1/v₁ + 1/v₂)** → **moyenne harmonique**.
- Si vous courez à 4 min/km à l'aller et 6 min/km au retour, l'allure globale est 5 min/km.

**Exercice.** À 120 km/h, un automobiliste a 20 min d'avance ; à 80 km/h, 10 min de retard. À quelle vitesse doit-il rouler pour arriver à l'heure ? (a) 90 km/h ; b) 95 km/h ; c) 100 km/h ; d) impossible sans la distance.)
- *Résolution (même méthode que l'exercice du cycliste ci-dessous) :* d/120 = t* − 1/3 et d/80 = t* + 1/6 (en h) → d = 120 km, t* = 4/3 h → **v = 90 km/h (a)**.

**Exercice (examen janvier 2021).** Un cycliste fait un aller-retour à vitesse constante v sans vent. Avec du vent, il roule w km/h plus vite vent dans le dos et w km/h plus lentement vent de face. Montrer que la vitesse moyenne est la plus élevée sans vent.
- v_moy = 2d / [d/(v + w) + d/(v − w)] = 2 [1/(v + w) + 1/(v − w)]⁻¹
- ou directement par les allures moyennes : 1/v_moy = ½ [1/(v + w) + 1/(v − w)]
- **v_moy = (v² − w²)/v = v − w²/v < v** — évident.
- NB : on peut aussi utiliser la propriété qu'une **moyenne harmonique est toujours inférieure à la moyenne arithmétique**.

**Exercice.** À 30 km/h, un cycliste arrive m min en avance ; à 15 km/h, il a d min de retard. À quelle vitesse doit-il rouler pour arriver à l'heure ?
- v = x/t ; v₁ = 30 km/h, v₂ = 15 km/h, v₃ = ? ; t* = temps nécessaire pour arriver à l'heure.
- 30 = x / (t* − m/60) ; 15 = x / (t* + d/60)
- → t* = (d + 2m)/60 ; x = (d + m)/2
- → **v₃ = x/t* = 30 (d + m)/(d + 2m)**
- Vérification utile et conseillée (pas une preuve) : si d = 0 → v₃ = 15 km/h ; si m = 0 → v₃ = 30 km/h.

## 3. Mouvement rectiligne uniformément accéléré (MRUA)

La vitesse évolue linéairement avec le temps :
Δv/Δt = a = cte → (v − v₀)/(t − 0) = a → **v = v₀ + a t**
- a s'exprime en **m/s²** ; a peut être > 0 ou < 0 selon le sens de l'accroissement de la vitesse.
- Vectoriellement : a⃗ = dv⃗(t)/dt → **v⃗(t) = v⃗₀ + a⃗ t**
- La variation de la vitesse par rapport au temps est appelée **accélération**.
- Ne pas confondre l'accélération comme **variation du vecteur vitesse** (vraie définition physique) et comme variation de la norme du vecteur vitesse.

## 4. Distance parcourue : méthode des aires

Sur base du graphe de la vitesse en fonction du temps, on peut déterminer l'espace parcouru :
- vitesse constante : Δx = v Δt (aire du rectangle) ;
- en général : Δx = Σ v(t) Δt → **Δx = ∫ v(t) dt** (de t₁ à t₂) = **aire sous la courbe v(t)**.

**Exercice.** Espace parcouru durant les 9 premières secondes par un mobile dont la vitesse décroît de 20 m/s à 5 m/s entre t = 0 et t = 4 s, remonte à 10 m/s à t = 5 s, puis reste à 10 m/s jusqu'à t = 9 s ?
- d = (20 + 5)·4/2 + (10 + 5)·1/2 + 10·4 = **97,5 m**

**Cas du MRUA** (aire d'un trapèze) :
Δx = ½ (vᵢ + v_f) Δt = ½ (vᵢ + vᵢ + a Δt) Δt = **vᵢ Δt + ½ a Δt²**
- En fixant l'origine des temps : **x(t) = x₀ + v₀ t + ½ a t²**
- Sous forme vectorielle : **x⃗(t) = x⃗₀ + v⃗₀ t + ½ a⃗ t²**
- NB : par intégration aussi : v⃗(t) = v⃗(0) + a⃗ t → x⃗(t) = x⃗₀ + v⃗₀ t + ½ a⃗ t²

## 5. Remarque importante

Les **signes de x** (position), **v** (vitesse) et **a** (accélération) **dépendent du repère choisi**, et plus particulièrement de son sens.
→ Il est donc **incorrect d'associer le terme « décélération » ou « accélération » au signe de a**.

**Exercice.** Une automobile accélère de façon constante à partir du repos jusqu'à 30 m/s en 10 s. Trouver : (a) son accélération ; (b) la distance parcourue pendant l'accélération ; (c) la distance parcourue pendant que sa vitesse passe de 10 à 20 m/s.
- Équations du mouvement (repère adéquat) : x = ½ a t² ; v = a t
- (a) a = v/t = **3 m/s²**
- (b) x = ½ · 3 · 10² = **150 m**
- (c) Δx = 10 t + ½ · 3 t² ; 20 = 10 + 3 t → t = 3,33 s → **x = 50 m**

## 6. Relation complémentaire pratique (MRUA uniquement)

Parfois le **temps** n'est pas essentiel. Ex. : « un mobile voit sa vitesse passer de 30 à 20 m/s sur 50 m : quelle est sa décélération ? » ou « un mobile partant du repos subit 10 m/s² sur 100 m : quelle vitesse atteint-il ? »

En éliminant t des équations x = x₀ + v₀t + ½at² et v = v₀ + at (t = (v − v₀)/a) :
x = x₀ + v₀ (v − v₀)/a + ½ (v − v₀)²/a → 2a(x − x₀) = 2v₀(v − v₀) + (v − v₀)² = v² − v₀²

**v² = v₀² + 2a (x − x₀)** (relation uniquement valable dans un MRUA)

## 7. Chute des corps (chute libre)

La chute des corps, uniquement due à la pesanteur, est un **MRUA particulier** : le vecteur accélération, presque constant, est dirigé vers le centre de la Terre, de valeur ≈ **9,81 m/s²**.
- x⃗(t) = x⃗₀ + v⃗₀ t + ½ g⃗ t²
- Si les x croissants correspondent au sens bas → haut, avec g = +9,81 m/s² : **x(t) = x₀ + v₀ t − ½ g t²**

**Exercice.** Balle lancée verticalement vers le haut à 5 m/s. a) Hauteur maximale ; b) moment où la vitesse vaut 2 m/s ; c) vitesse à l'impact au sol. (g ≈ 10 m/s²)
- Équation des espaces : y(t) = y₀ + v₀t − ½gt² → **y(t) = 5t − ½·10t²**
- Équation des vitesses : **v(t) = 5 − 10t**
- a) v = 0 → t = 0,5 s → y = 2,5 − 1,25 = **1,25 m**
- b) v(t) = 5 − 10t = ±2 → **t = 0,3 s et 0,7 s**
- c) *(calcul non détaillé sur le slide, même méthode)* : y = 0 → t = 1 s → v = 5 − 10 = −5 m/s, soit **5 m/s vers le bas**.

**Exercice — graphe v(t).** Une balle lancée vers le haut retombe au sol : quel graphe représente le mieux v_y(t) ?
- Un « V inversé » est faux : la vitesse ne s'annule pas au point culminant.
- Une courbe en cloche est fausse : mouvement pas uniformément accéléré.
- Un « V » (v toujours du même signe) n'est correct que si v_y représente la norme du vecteur vitesse.
- **Bonne réponse : une droite décroissante** qui traverse l'axe : accélération constante, changement de signe de la vitesse.

## 8. Mouvement à 2 ou 3 dimensions

Les équations d'un mouvement non accéléré ou uniformément accéléré dans l'espace restent :
**x⃗(t) = x⃗₀ + v⃗₀ t + ½ a⃗ t²** ; **v⃗(t) = v⃗₀ + a⃗ t**
Il faut traiter **chacune des composantes** (Galilée fut le premier à comprendre cette décomposition du mouvement).

Corps uniquement soumis à l'attraction terrestre (g⃗ dirigé vers le centre de la Terre) :
**x⃗(t) = x⃗₀ + v⃗₀ t + ½ g⃗ t²** ; **v⃗(t) = v⃗₀ + g⃗ t**, avec v₀ₓ = v₀ cos θ₀ et v₀ᵧ = v₀ sin θ₀.

**Exercice — tir horizontal.** Balle projetée horizontalement à 15 m/s d'une falaise de 20 m. (a) Durée dans l'air ; (b) portée horizontale R.
1. Choix du repère ; 2. Équations du mouvement ; 3. Mise en équation de la condition et résolution.
- x = 0 + 15t + 0 ; y = 20 + 0·t − (10/2) t²
- vₓ(t) = 15 ; v_y(t) = 0 − 10t
- y = 0 → 20 − 5t² = 0 → **t = 2 s**
- **R = x(2) = 15·2 = 30 m**

**Question — portée maximale.** Démontrer que la portée maximale d'un projectile qui atterrit au niveau initial correspond à un angle de 45°. Déterminer cette portée et l'équation de la trajectoire.
- Équations : x = v₀ cos α · t ; y = v₀ sin α · t − ½ g t²
- Portée : y = 0 → t* = 2 v₀ sin α / g → x(t*) = v₀ cos α · 2 v₀ sin α / g → **P = (v₀²/g) sin 2α**
- Portée maximale : sin 2α = 1 → **α = 45°** → **P_max = v₀²/g**
- Trajectoire (on élimine le temps) : y = v₀ sin α · x/(v₀ cos α) − ½ g (x/(v₀ cos α))² → **y = x tg α − g x² / (2 v₀² cos² α)** (parabole)

**Exercice.** Mouvement d'un mobile volant : x = 3t³ − 32t − 1 ; y = 0 ; z = 12 − 3t ([t] = s ; [x, y, z] = m ; z vertical).
- a) Vitesse verticale à t = 10 s : v_z = −3 → **3 m/s vers le bas**
- b) Vitesse à t = 2 s : vₓ = 9t² − 32 → vₓ(2) = 4 ; v_z(2) = −3 → **v = √(4² + 3²) = 5 m/s**
- c) Angle avec l'horizontale à l'impact (z = 0) : 12 − 3t* = 0 → t* = 4 s → vₓ = 9·16 − 32 = 112 ; v_z = −3 → tg θ = 3/112 → **θ ≈ 0,03 rad**

## 9. Mouvement circulaire

- Arc parcouru : s = r Δθ
- **Vitesse angulaire** : **ω = dθ/dt**
- **Vitesse linéaire** (norme du vecteur vitesse) : **v = ds/dt = ω r**
- **Accélération angulaire** : **α = dω/dt**
- ω constant → **MCU** (mouvement circulaire uniforme) ; α constant et non nul → **MCUA** (uniformément accéléré).

Par analogie avec le MRUA (ω et α pris avec leur signe) :
**θ(t) = θ₀ + ω₀ t + ½ α t²** ; **ω(t) = ω₀ + α t**

Accélération **centripète** (synonyme : accélération **radiale**) : **a_r = ω² r = v²/r**

**Exercice.** a) La Terre fait un tour complet en 23 h 56 min : vitesse linéaire et accélération centripète d'un point à l'équateur et à 45° de latitude (rayon terrestre 6350 km).
- ω = 2π / (23·3600 + 56·60) → v_équateur = ω r = 463 m/s = 1667 km/h → a_r = ω² r = v²/r = **3,4·10⁻² m/s²**
- À 45° : r = R cos 45° → v = 327 m/s = 1179 km/h → a_r = **2,4·10⁻² m/s²**
- À comparer aux 9,81 m/s² : cela montre la variabilité de la « constante » g à la surface terrestre.

b) Même question pour l'orbite de la Terre autour du Soleil (rayon 1,5·10⁸ km) :
- ω = 2π/(365·24·3600) → v = ω r = 29 886 m/s = 107 590 km/h → a_r = v²/r = **5,95·10⁻³ m/s²**

**Exercice.** Un moteur passe de 1800 à 1500 tours/min en 5 s. a) Accélération angulaire et nombre de tours pendant ces 5 s ? b) Combien de tours avant l'arrêt (MCUA) ?
- ω₀ = 1800·2π/60 = 60π rad/s ; ω(5) = 1500·2π/60 = 50π rad/s
- **α = (50π − 60π)/5 = −2π rad/s²**
- θ(t) = 60π t − π t² ; ω(t) = 60π − 2π t
- a) θ(5) = 300π − 25π → **N = θ(5)/2π = 137,5 tours**
- b) ω = 0 → t = 30 s → θ = 60π·30 − π·30² → **N = θ/2π = 900 − 450 = 450 tours**
