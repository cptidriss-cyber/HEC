# Chapitre 5 — Quantité de mouvement

## 1. Définition

- Au 17ᵉ s., **Descartes** pensait que lors d'une collision, une grandeur **scalaire** appelée « quantité de mouvement » est toujours conservée : (Σ mᵢ vᵢ)avant = (Σ mᵢ vᵢ)après (principe de conservation).
- **Mais** : 2 balles de mastic de même masse envoyées l'une vers l'autre avec la même vitesse **s'immobilisent**. La somme scalaire n'est donc pas conservée.
- Il devint clair que la grandeur conservée était plutôt la somme **vectorielle** Σ mᵢ v⃗ᵢ.

Définition moderne : **p⃗ = m v⃗**

**En résumé :** lors d'une collision, la quantité de mouvement est **conservée si les forces extérieures sont nulles ou négligeables**.

Ce principe, remarquablement simple, s'applique à des phénomènes divers : les chocs, les explosions, le recul d'armes à feu, la propulsion de fusée, les réactions nucléaires, l'absorption et l'émission de lumière.

## 2. Types de collisions

(Collision = interaction brève et intense entre 2 corps.)

**Collisions élastiques**
- **Christiaan Huygens** pense que la grandeur Σ mᵢ vᵢ² est la grandeur conservée lors de collisions entre balles dures.
- Une collision est dite **élastique** lorsque l'énergie cinétique est conservée : **Σ ½ mᵢ vᵢ² = constante**

**Collisions inélastiques**
- Une partie de l'énergie cinétique est transformée en énergie **thermique, lumineuse ou sonore**.

**Collisions parfaitement inélastiques**
- Les 2 corps **restent liés** après la collision.

## 3. Impulsion et quantité de mouvement

La 2ᵉ loi de Newton F⃗ = m a⃗ peut aussi s'écrire :
F⃗ = m a⃗ = m (dv⃗/dt) → **F⃗ dt = d(m v⃗)**

Pour un intervalle de temps fini :

**F⃗_moyen · Δt = Δ(m v⃗)**
- F⃗_moyen · Δt = **impulsion**
- Δ(m v⃗) = **variation de la quantité de mouvement**

**Exercice.** Une balle de 150 g est lancée à 30 m/s. Elle frappe un bâton qui lui donne une vitesse de 40 m/s dans le sens opposé. Durée du contact : 10⁻² s. Force moyenne sur la balle ?
- F_moyen · 10⁻² = (40 − (−30)) · 0,15
- **F_moyen = 70 · 0,15 · 100 = 1050 N**
- Attention au signe : le changement de sens donne une variation de vitesse de 70 m/s, pas de 10 m/s.

## 4. Le canon de Galilée

Expérience : une petite balle posée sur une grosse balle ; on lâche l'ensemble. La petite balle rebondit beaucoup plus haut que sa hauteur de départ. Comment l'expliquer ?

**Balle contre raquette :**
- Quand une balle frappe un objet fixe, la collision est pratiquement **élastique** : la balle repart avec la même vitesse en sens opposé.
- Si une balle de vitesse v⃗_B frappe une raquette de vitesse v⃗_R : dans le référentiel de la raquette, la balle arrive avec v⃗_B − v⃗_R et repart avec v⃗_R − v⃗_B.
- Dans le référentiel du sol, après le choc : **v⃗′_B = 2 v⃗_R − v⃗_B**

**Les 2 balles :** la grosse balle a rebondi au sol et monte avec la vitesse v, la petite descend encore avec la vitesse v (même norme, sens opposé).
- Dans le référentiel de la grosse balle, la petite arrive et rebondit avec une vitesse **2v** (on suppose la petite de masse beaucoup plus faible).
- Dans le référentiel du sol : 2v + v = **3v**.
- Comme la hauteur dépend du carré de la vitesse (v² = 2 g h) : **H′ = 9 H**.

**3ᵉ balle** de masse encore plus faible : vitesse 3v + v + 3v = **7v**, hauteur **H″ = 49 H**.

En généralisant :
- v_{n+1} = 2 v_n + v → v, 3v, 7v, 15v, 31v, …
- **v_n = (2ⁿ − 1) v**
- **H_n = (2ⁿ − 1)² H** → H, 9H, 49H, 225H, 961H, …

## Questions

- Vrai ou faux ? Dans l'étude des collisions, le principe de conservation de l'énergie ne s'applique qu'aux collisions élastiques. (Attention : il faut justifier, car les 2 réponses peuvent être correctes.)
- Comment varie l'énergie cinétique d'une particule lorsque sa quantité de mouvement double ? Comment varie sa quantité de mouvement lorsque son énergie cinétique double ?

*Pistes déduites du cours :* l'**énergie totale** est toujours conservée (ch. 4 : elle n'est ni créée ni détruite) ; seule l'**énergie cinétique** n'est conservée que dans les collisions élastiques. Avec p = m v et E_c = ½ m v² = p²/(2m) : p × 2 → E_c × 4 ; E_c × 2 → p × √2.
