# Chapitre 6 — Mécanique du solide indéformable

Au programme : le centre de masse, le moment d'inertie, le moment cinétique, le moment d'une force, … ; l'équilibre statique d'un corps rigide ; la rotation d'un corps rigide autour d'un axe.

## 1. Le centre de masse (CM)

Dans tout système composé de plusieurs particules, un point « central », appelé **centre de masse**, est particulièrement intéressant en raison de ses propriétés. Sa position est **définie** par :

**x⃗_CM = (m₁x⃗₁ + m₂x⃗₂ + …)/(m₁ + m₂ + …) = Σ mᵢx⃗ᵢ / M**, avec M = Σ mᵢ

- Exemple : seule une force appliquée **au CM** engendre une **translation sans rotation**.
- **Propriété remarquable :** du point de vue mécanique, c'est au centre de masse qu'il faut appliquer la **résultante des forces de gravité**.

En général, un corps solide est un système « **continu** » : on calcule la position par intégration :
**x⃗_CM = (1/M) ∫ x⃗ dm**

**Exercice — 4 particules** (m₁ = 2 kg en (3 ; −1), m₂ = 4 kg en (3 ; 3), m₃ = 5 kg en (−4 ; 4), m₄ = 1 kg en (−3 ; −2)) :
1. Choix d'un système de référence ; 2. Calcul de la masse totale (12 kg) ; 3. Expression de chaque composante.
- x_CM = [2·3 + 4·3 + 5·(−4) + 1·(−3)]/12 = **−0,417 m**
- y_CM = [2·(−1) + 4·3 + 5·4 + 1·(−2)]/12 = **2,33 m**

**Cas particuliers et généralisation :** en décomposant le système en plusieurs sous-systèmes dont la position du CM est connue, on obtient facilement le CM global (ex. : système homogène en L de côtés 2L et L).

## 2. Trois approches de calcul

**Exercice :** position du CM d'une surface carrée de côté 2R dans laquelle on a retiré un disque de rayon R/2 (dans un coin). Origine au centre du carré ; σ = densité superficielle.

**Approche n°1 — le système composé des 2 parties** (carré troué M₁ + disque M₂ = carré plein) :
- M₁ = σ(4R² − πR²/4) ; M₂ = σ πR²/4 ; M₁ + M₂ = σ 4R²
- Le CM du carré plein est à l'origine : (M₁ + M₂)·0 = M₁ x_CM + M₂ · R/2
- 0 = σ(4R² − πR²/4) x_CM + σ(πR²/4)(R/2)
- **x_CM = y_CM = −(πR³/8)/((16R² − πR²)/4) = −π/(32 − 2π) R ≈ −0,122 R**

**Approche n°2 — masse « négative » au trou** (carré troué = carré plein M₁′ − disque M₂′) :
- (M₁′ − M₂′) x_CM = M₁′·0 − M₂′ · R/2
- x_CM = −M₂′/(M₁′ − M₂′) · R/2 = −(πR²/4)/(4R² − πR²/4) · R/2 = **−π/(32 − 2π) R**
- Donc **x⃗_CM = (−0,122 ; −0,122) R**

**Approche n°3 — décomposer en parties** dont on connaît facilement CM et masse (ici 4 quarts ; les masses peuvent être remplacées par les surfaces) :
- (4R² − πR²/4) x_CM = R²(−R/2) + R²(−R/2) + R²(R/2) + (R² − πR²/4)(R/2)
- x_CM = [−R/2 + (1 − π/4) R/2] / (4 − π/4) = −(π/8)/(4 − π/4) R = **−π/(32 − 2π) R**

**Exercice — planche trouée.** Une planche homogène de 20 kg mesure 2 m. On y pratique un trou circulaire dont le centre est à 0,5 m d'une extrémité. Si le CM est à 0,9 m de l'autre extrémité, quelle masse de bois a-t-on enlevée ?
- Approche n°1 : 20·1 = (20 − m)·0,9 + m·1,5 → **m = 3,3 kg**
- Approche n°2 (masse négative) : (20 − m)·0,9 = 20·1 − m·1,5 → m = 3,3 kg
- Approche n°3 (deux moitiés de 1 m) : (20 − m)·0,9 = 10·0,5 + (10 − m)·1,5 → m = 3,3 kg

**Exercice — disque percé** (approche n°2). Disque uniforme de 1 m de diamètre et 100 kg. Où percer un trou de 10 cm de diamètre pour déplacer le CM de 2 mm ?
- (100 − 1)·2·10⁻³ = 0 − x·1 → **x = −0,198 m**
- La masse retirée vaut 1 kg (pourquoi ? surface 100 fois plus petite : (10/100)² = 1/100). Le CM du disque plein est à l'origine.
- **Le trou sera percé à 19,8 cm du centre du disque** (du côté opposé au déplacement du CM).

**Exercice — carré auquel on a retiré un quart** (côté L, origine au centre) :
- x_CM = ⅓(L/4) + ⅓(−L/4) + ⅓(−L/4) = **−L/12**
- y_CM = ⅓(L/4) + ⅓(L/4) + ⅓(−L/4) = **L/12**

**Exercice — forme en C** (segment vertical L, deux segments horizontaux : L/2 en haut, L en bas) :
- x_CM = (2/5)(L/2) + (2/5)(0) + (1/5)(L/4) = **L/4**
- y_CM = (2/5)(0) + (2/5)(L/2) + (1/5)(L) = **2L/5**

## 3. Mouvement du centre de masse

- Un **projectile qui explose** : après l'explosion, le CM de l'ensemble suit **la même trajectoire** que s'il n'y avait pas eu d'explosion.
- Une **clé à molette** tournant sur elle-même sur une surface sans frottement : le CM suit une **trajectoire rectiligne**.
- Une échelle de corde est attachée à une montgolfière immobile dans les airs. Un homme monte sur l'échelle : dans quelle direction se déplace la montgolfière ? (R : **vers le bas**, évidemment. Pourquoi ?)
- **Saut en hauteur** : l'impulsion initiale permet au CM d'atteindre une certaine hauteur ; grâce à la technique, le sauteur passe au-dessus de la barre mais pas (ou à peine) son centre de masse.

**Application : le bicône de l'abbé Nollet** (paradoxe de Galilée). Alors qu'un cylindre dévalerait la pente, le bicône la **remonte** ! Expliquer ce paradoxe.

**Question d'examen janvier 2021 — le canoë.** Une personne de 60 kg est à 50 cm de l'extrémité gauche d'un canoë de 5 m et 90 kg. Elle va s'asseoir à 50 cm de l'extrémité droite. De combien s'est déplacé le canoë (pas de friction entre canoë et eau) ?
- Repère au centre du canoë : x¹_CM = (−2·60 + 0·90)/(60 + 90) = −0,8 ; x²_CM = (2·60 + 0·90)/150 = 0,8
- Le CM ne se déplace pas sous l'effet de forces internes : **le canoë se déplace vers la gauche de 0,8 + 0,8 = 1,6 m**.
- Avec un repère **absolu** (extrémité gauche du canoë avant le mouvement) : x¹_CM = (0,5·60 + 2,5·90)/150 = 255/150 ; x²_CM = [(5 − 0,5 − d)·60 + (2,5 − d)·90]/150
- x¹_CM = x²_CM → 255 = (4,5 − d)·60 + (2,5 − d)·90 → **d = (495 − 255)/150 = 1,6 m**

## 4. Équilibre et centre de masse

La notion de CM est très utile pour traiter des problèmes d'**équilibre** : elle simplifie l'effet des forces gravitationnelles en appliquant **une seule force au CM** (le poids) et une aux points d'appui.

- **Équilibre stable** : lorsque les forces appliquées tendent à **ramener** le système dans sa position d'équilibre quand on la modifie légèrement. (Dans le cas d'un objet suspendu, l'équilibre ne peut être stable que si le CM se situe **en dessous du point d'appui** et sur un axe vertical.)
- **Équilibre instable** : sinon (CM au-dessus du point d'appui).

**Défi — l'équerre.** Une équerre composée de 2 segments perpendiculaires de même longueur L est suspendue librement par une extrémité. Déterminer l'angle α entre la verticale et le segment supérieur. (Conseil : déterminer d'abord le CM ; une propriété du CM donne ensuite α.)
- x_CM = y_CM = [(M/2)(L/2) + 0]/M = **L/4**
- Le CM se place sous le point de suspension : **tg α = (L/4)/(3L/4) = ⅓ → α ≈ 20°**

**Équilibre stable, instable, indifférent**
- **Stable** : pour tout déplacement infiniment petit, l'objet tend à revenir à sa position initiale en effectuant un mouvement d'amplitude infiniment petite.
- **Instable** : pour tout déplacement infiniment petit, l'objet s'éloigne de cette position et n'y revient pas.
- **Indifférent** : pour tout déplacement infiniment petit, l'objet reste en équilibre à cette nouvelle position.
- (Bille au fond d'un creux : stable ; au sommet d'une bosse : instable ; sur un plan : indifférent. Dans quelle catégorie placer la sphère, le cylindre et le cône couchés ?)

## 5. Moment de force

Le **levier** est un système efficace pour soulever un corps en exerçant une force inférieure à son poids.
- **Archimède** (250 av. J.-C.) détermine la condition d'équilibre de la tige : **r₁F₁ = r₂F₂**
- **Léonard de Vinci** (15ᵉ s.) généralise au cas où la force n'est pas perpendiculaire à la tige : **r₁F₁ sin θ₁ = r₂F₂ sin θ₂**
- L'équilibre d'un corps (en rotation) dépend donc de cette grandeur.

L'étude de la rotation est grandement simplifiée par la notion de **moment d'une force** :
**τ = r F sin θ = r⊥ F**, où r⊥ = r sin θ est le **bras de levier** (distance entre le point de rotation et la ligne d'action de la force).

Notion plus générale sous forme **vectorielle** : **τ⃗ = r⃗ × F⃗**

Le moment d'une force mesure la **capacité d'une force à imprimer une rotation** à un corps autour d'un axe.

## 6. Équilibre statique

La statique étudie les forces et moments de force agissant sur des corps **au repos**. Conditions d'équilibre statique :
- **ΣF⃗_ext = 0⃗** — équilibre de **translation** du CM
- **Στ⃗_ext = 0⃗** — équilibre de **rotation**

La première condition n'est **pas suffisante** : deux forces opposées non alignées (couple) font tourner le corps.

**Exercice — tige sur 2 supports.** Tige homogène de poids 35 N soutenue à ses extrémités par 2 supports ; un bloc de 10 N est placé au quart de la distance entre les extrémités. Forces exercées par les supports ?
1. Somme des forces : ΣF_y = N₁ + N₂ − P₁ − N₃ = 0 → N₁ + N₂ − 35 − 10 = 0
2. Somme des moments (par rapport au milieu) : −N₁d/2 − N₃d/4 + N₂d/2 = 0 → −N₁ + N₂ − N₃/2 = 0 → −N₁ + N₂ − 10/2 = 0
3. Résolution (calculée) : **N₁ = 20 N ; N₂ = 25 N** (N₂ du côté du bloc).

**Exercice — l'échelle.** Échelle de longueur L et poids P posée sur un plancher rugueux (μ_s = 0,6) et contre un mur **sans frottement**. Angle maximal entre le mur et l'échelle pour qu'elle ne glisse pas ?
1. Somme des forces : ΣF_y = N₁ − P = 0 → N₁ = P ; ΣFₓ = N₂ − f₁ = 0 → N₂ = f₁ = μ_s N₁ = μ_s P
2. Somme des moments (par rapport au pied B) : (PL/2) sin θ − N₂ L cos θ = 0 → P tg θ = 2N₂
3. Résolution : P tg θ = 2μ_s P → **tg θ = 2μ_s → θ ≈ 50°**
- Exercice complémentaire : refaire l'exercice avec des frottements aussi sur le mur vertical (réponse donnée sur le slide : **tg θ = 2μ₁ / (1 − μ₁μ₂)**, μ₁ : sol, μ₂ : mur).

## 7. Équilibre et stabilité

Un système solide soumis à son poids et posé sur un support reste en équilibre si **la verticale tracée à partir de son CM traverse le polygone d'appui** (ou base de sustentation : le plus grand polygone formé par les points de support du corps). (On suppose que la rugosité empêche tout glissement.)
- Si la verticale du CM sort du polygone : les forces de contact étant forcément dirigées vers le haut, il est impossible d'obtenir une résultante des moments nulle → le système **pivote**.
- Inversement, si la verticale du CM traverse le polygone d'appui, l'équilibre peut être assuré.

**La canette inclinée :** la position du CM dépend de la quantité de liquide présente. On peut obtenir une canette inclinée (sans la tenir) en dosant le liquide pour que le CM se trouve au-dessus de la zone d'appui (pratiquement : canette remplie **au 1/3**).

**Le problème des légos.** Les 4 premiers blocs forment un escalier vers la gauche, tous les autres un escalier vers la droite. Nombre maximal de blocs ajoutés dans cette direction sans que la tour ne bascule vers la droite ? (Chaque bloc a une masse et une longueur unitaires.)
- Le basculement a lieu quand **x_CM > 0** (CM au-delà du dernier point d'appui).
- x¹_CM = −0,5 ; x²_CM = (−0,5 − 1)/2 = −0,75 ; x³_CM = (−0,5 − 1 − 1,5)/3 = −1 ; x⁴_CM = (−0,5 − 1 − 1,5 − 2)/4 = −1,5 ; puis x⁵_CM = (−0,5 − 1 − 1,5 − 2 − 1,5)/5, …
- Pour tester la positivité, le dénominateur ne compte pas : il suffit de compter les termes de la série qui rendent l'expression positive : −0,5 − 1 − 1,5 − 2 − 1,5 − 1 − 0,5 + 0 + 0,5 + 1 + 1,5 + 2 + 2,5 + 3 …
- **Le 14ᵉ bloc provoquera le basculement.**
- Même problème **sans la pièce du bas** : −0,5 − 1 − 1,5 − 1 − 0,5 + 0 + 0,5 + 1 + 1,5 + 2 + … → **le 10ᵉ bloc provoquera le basculement.**

**Détermination pratique du CM :** suspendre l'objet par un point quelconque et tracer la verticale passant par ce point ; recommencer avec un ou plusieurs autres points : le CM est à l'**intersection** des droites. (Si le CM n'est pas sur cet axe, un moment de force apparaît et met le corps en rotation.)

**Équilibre et stabilité — 5 expériences** (Y. Perelman, *Oh la physique*, Dunod) :
1. Face au mur, pieds et tête touchant le mur : impossible de se dresser sur la pointe des pieds.
2. De profil contre le mur, un pied et un bras au contact du mur : en levant la jambe de côté, l'équilibre est très compromis.
3. Assis bien droit sur une chaise, pieds devant, dos/cuisses/jambes à angle droit : impossible de se lever sans incliner le tronc vers l'avant.
4. Debout, dos au mur, talons collés à la plinthe : se baisser jambes tendues pour toucher le sol… chute assurée.
5. À genoux, bras dans le dos, se pencher pour renverser une boîte d'allumettes avec le nez.

**Application : le pluviomètre** à bascule. Condition de basculement : **F₂d₂ > F₁d₁**.

**Exercice (examen 2017).** Quelle force minimale horizontale faut-il appliquer au CM d'un cylindre homogène de 50 kg (rayon 45 cm) pour lui faire franchir l'arête d'une marche de 30 cm ? Cette force doit-elle rester constante tout au long de la manœuvre ? (Selon de nombreux étudiants, question extrêmement compliquée… et exactement identique à celle posée aux ingénieurs civils !)
- ΣF⃗_ext = 0⃗ ; Στ⃗_ext = 0⃗ (moments par rapport à l'arête de la marche)
- Bras de levier de F : 45 − 30 = 15 cm ; de P : d = √(45² − 15²) = 30√2 cm
- F·15 − P·d = 0 → **F = 30√2 · 500/15 = 1000√2 ≈ 1414 N**

## 8. Machines simples

On appelle **machine simple** un système mécanique (sans moteur) qui permet de **réduire la force** nécessaire pour une manœuvre : levier, plan incliné, poulie/palan.

**Avantage mécanique** (efficacité du système) : **AM = F_sans / F_avec**
- F_sans : force résistante, celle qu'on devrait appliquer **sans** système (souvent un poids) ;
- F_avec : force appliquée **avec** le système (levier, plan incliné, poulie, palan, …).

Pour un système idéal (sans perte d'énergie), le **travail est conservé** :
W = F_avec · d_avec = F_sans · d_sans → **AM = d_avec / d_sans**

NB : il est plus que souhaitable de savoir déterminer un AM dans le cas de **leviers, palans, poulies, plans inclinés**, …

## 9. Dynamique des mouvements circulaires — résumé et analogies

| | Translation | Rotation |
|---|---|---|
| Loi fondamentale | Σf⃗ = m a⃗ | Στ⃗ = I α⃗, avec **I = Σ mᵢ rᵢ²** et τ⃗ = r⃗ × F⃗ |
| Énergie cinétique | E_c = ½ m v² | E_c = ½ I ω² |
| Quantité de mouvement | p⃗ = m v⃗ | **L⃗ = r⃗ × m v⃗ = I ω⃗** (moment cinétique ou angulaire) |
| Loi fondamentale (nouvelle formulation) | Σf⃗ = dp⃗/dt | Στ⃗ = dL⃗/dt |
| Puissance | P = F⃗·v⃗ | P = τ⃗·ω⃗ |

## 10. Le problème d'Edison

Une des célèbres questions du concours d'Edison (Thomas Edison, 1847-1931, organisa un concours pour récompenser « le garçon le plus ingénieux » des États-Unis : 57 questions de physique, chimie et mathématiques) :

« Imaginez que vous avez été abandonné sur une île tropicale déserte de l'océan Pacifique sans outillage. Comment pourriez-vous renverser un rocher de granit de 30 m de long sur 5 m de haut pesant 3 tonnes ? »

1. **Épaisseur e de la roche** (ρ_granit ≈ 3 g/cm³ = 3000 kg/m³) : M = ρV = ρ(L × H × e) → 3000 = 3000 · 30 · 5 · e → **e = 1/(30·5) = 0,0066 m ≈ 7 mm** !
   → Il suffit d'appuyer avec les mains ou l'épaule pour renverser ce mur. Calculons la force.
2. **Moments par rapport au point de rotation** (pour éliminer le moment de la réaction du sol), force appliquée à ≈ 1,5 m de haut : Στ⃗_ext = 0⃗ → F · 1,5 − P · 3,5·10⁻³ = 0
3. **Force minimale** : F = 3000 · 9,81 · 3,5·10⁻³ / 1,5 ≈ 105/1,5 = **70 N** — une force que chacun d'entre nous pourrait effectuer.
4. **Même le vent** : un simple calcul montrerait que même un faible vent ferait renverser le mur.
