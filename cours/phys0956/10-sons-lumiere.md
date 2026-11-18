# Chapitre 10 — Sons et lumière

I. Les sons ; II. La lumière.

# I. Les sons

## 1. Sons audibles, infrasons, ultrasons

**Sons audibles :** entre **20 Hz et 20 000 Hz** (5 000 Hz à 90 ans — « moi 50 Hz à 12 000 Hz », dit le professeur). La sensibilité de l'oreille humaine est **maximale à 3 000 Hz**.

**Infrasons :** tonnerre ; tremblements de terre ; certains animaux (éléphants) communiquent par infrasons.

**Ultrasons :** perçus par les chiens (jusqu'à 35 kHz), les chats (jusqu'à 25 kHz), dauphins et chauves-souris (jusqu'à 100 kHz) ; médecine (échographie) ; chauves-souris (écholocation).

La science qui étudie les sons s'appelle l'**acoustique** ; la **psychoacoustique** combine l'acoustique avec la physiologie (manière dont les sons sont perçus et interprétés par le cerveau).

## 2. Nature des ondes sonores

- **Vibrations longitudinales** (ondes de compression) qui se superposent au mouvement aléatoire des molécules.
- **Fluctuations périodiques** de la densité du fluide et de la pression : P ∈ [P₀ − ΔP ; P₀ + ΔP].
- **Seuil d'audibilité :** ≈ **20 µPa** (rappel : P_atm = 10⁵ Pa).
- **Vitesse de propagation :** **v ≈ 20 √T** (T en kelvin ; voir cours de thermodynamique). Exemple : v(16 °C) = **340 m/s**.

Un haut-parleur produit des **compressions** et des **raréfactions** dans l'air d'un tube. Un point de **déplacement nul** correspond à une **variation maximale de la pression**, et vice versa.

**Front d'onde :** lieu géométrique (lignes ou surfaces) des points sur lesquels, à cet instant, l'amplitude de l'onde est maximale.

## 3. L'effet Doppler

L'**effet Doppler** est la **modification apparente de la fréquence** d'une onde suite au **mouvement relatif** de la source et de l'observateur. (Appliqué aux ondes électromagnétiques : effet **Doppler-Fizeau**.)

**Historique :**
- **J.C. Doppler (1842)** : lien entre la couleur et le mouvement des étoiles. (Notes : cette corrélation entre ondes sonores et couleur des étoiles était incorrecte, même si qualitativement les résultats sont similaires.)
- **C. Buys Ballot (1845)** : expérience des musiciens (trompettistes embarqués sur un train jouant des notes de 1000 Hz). Haute fréquence quand la source approche, basse quand elle s'éloigne (ambulance).
- Expérience : mettre en évidence l'effet par le mouvement circulaire d'un buzzer.

**Rappel :** c = λ/T = λ f → f = c/λ (c : vitesse du son, célérité).

**Cas 1 — Source au repos / observateur en mouvement** (la vitesse apparente de l'onde est modifiée, la longueur d'onde reste inchangée) :
**f′ = c′/λ = (c ± v_o)/c · f**
(signe « moins » quand l'observateur **ne** se déplace **pas vers** la source)

**Cas 2 — Source en mouvement / observateur au repos** (la vitesse apparente reste inchangée, la longueur d'onde est modifiée) :
**f′ = c/λ′ = c/(c ∓ v_s) · f**
(signe « plus » quand la source **ne** se déplace **pas vers** l'observateur)
- Longueur d'onde apparente (rapprochement) : **λ′ = (c − v_s) T** — à la longueur d'onde, il faut retrancher la distance d = v_s T : λ′ = λ − v_s T = cT − v_sT = (c − v_s)T.

**Généralisation — source et observateur en mouvement :**

**f′ = (c ± v_o)/(c ∓ v_s) · f**
(signe du haut : « vers » ; signe du bas : « s'éloigne »)
- Source et observateur se dirigent l'un vers l'autre : f′ = (c + v_o)/(c − v_s) f
- Ils s'éloignent l'un de l'autre : f′ = (c − v_o)/(c + v_s) f
- L'observateur « poursuit » la source : f′ = (c + v_o)/(c + v_s) f
- La source « poursuit » l'observateur : f′ = (c − v_o)/(c − v_s) f
- Pour choisir le signe de v_o, il suffit de considérer la source comme fixe ; idem pour v_s.

Attention (notes) : ces développements ne valent que pour des ondes sonores ou équivalentes. Pour les ondes électromagnétiques, il faut tenir compte d'**effets relativistes** (cours de 2ᵉ bac).

**Exercice.** Une voiture de police roule à 50 m/s dans la même direction qu'un camion (25 m/s). Sirène : 1200 Hz. Fréquence entendue par le chauffeur du camion quand la voiture est (a) derrière ; (b) devant ; (c) estimer mentalement.
- (a) f′ = (c − v_o)/(c − v_s) f = (340 − 25)/(340 − 50) · 1200 = **1303 Hz**
- (b) f′ = (c + v_o)/(c + v_s) f = (340 + 25)/(340 + 50) · 1200 = **1123 Hz**
- (c) Δf/f ≅ v_rel/c → Δf ≈ 1200 · (25/340) ≈ 100 Hz → **1300 Hz et 1100 Hz**

**Exercice.** Même camion et voiture se déplaçant l'un **vers** l'autre :
- (a) la voiture s'approche : f′ = (340 + 25)/(340 − 50) · 1200 = **1510 Hz**
- (b) après le croisement : f′ = (340 − 25)/(340 + 50) · 1200 = **969 Hz**

**Exercice — son réfléchi.** Sirène d'une voiture de police à 40 m/s : 600 Hz. Un camion roule devant à 20 m/s dans la même direction. Fréquence du son réfléchi entendu par le policier ?
- Perçue par le camion : f′ = (340 − 20)/(340 − 40) · 600 = **640 Hz** (c'est la fréquence réfléchie par le camion)
- Perçue par la police : f″ = (340 + 40)/(340 + 20) · 640 = **676 Hz**

**Approximation** (rappel : (1 + x)^a ≈ 1 + a x si x ≪ 1) :
- Observateur mobile : f′/f = 1 + v_o/c → Δf/f = v_o/c
- Source mobile : f′/f = 1/(1 − v_s/c) ≈ 1 + v_s/c → Δf/f ≈ v_s/c
- Les deux : f′/f = (1 + v_o/c)/(1 − v_s/c) ≈ 1 + (v_o + v_s)/c → **Δf/f ≈ v_relative/c**
- Quand la vitesse relative est faible devant la célérité des ondes, **la variation relative de fréquence ≈ le rapport entre cette vitesse et la célérité**.
- NB : c = λ f → λ df + f dλ = 0 → **df/f = −dλ/λ**

**Pratiquement : Δf/f ≅ v_rel/c**
- **Δf > 0** : source et observateur se **rapprochent** globalement.
- **Δf < 0** : source et observateur s'**éloignent** globalement.

**Exercice.** Une analyse Doppler montre une **diminution** de fréquence de 3,5 % (ultrasons dans l'eau, c_eau = 1500 m/s). Vitesse de la source si l'observateur se déplace à 10 m/s ?
- Δf/f ≈ Δv/c → Δv = 0,035 · 1500 = 52,5 m/s
- Source et observateur dans le **même sens** : v = 10 + 52,5 = **62,5 m/s**
- ou s'**éloignant** l'un de l'autre : v = 52,5 − 10 = **42,5 m/s**
- NB : variantes possibles (augmentation de fréquence, variations relatives de longueurs d'onde, …).

**Applications : mesurer des vitesses**
- Vitesses de véhicules (radars) ou de particules atmosphériques ;
- Débits sanguins (faisceaux d'ultrasons) ;
- Vitesse d'éloignement des **galaxies** ou de rotation des étoiles.
- Si source et observateur ne sont pas sur une même droite, le décalage dépend de la **vitesse radiale** (composante selon la droite source-observateur).
- Le spectre de la plupart des galaxies présente un **décalage vers le rouge** (*redshift*) : diminution apparente de fréquence qui a mis en évidence l'**expansion de l'univers**.

**« Seuls les physiciens comprendront… »** (dessin à commenter : voiture qui approche / s'éloigne). Attention : le lien qu'on pourrait faire avec la relativité peut poser question !

## 4. Mur du son

Si la vitesse de la source dépasse la célérité de l'onde (comparer v_source = 0, < c, = c, > c) : création d'**ondes de choc** quand **v_s > c**. Les parois du cône (**cône de Mach**) forment l'onde de choc.
- **sin θ = v_son / v_avion** (à démontrer explicitement)
- NB : l'avion requiert une poussée supplémentaire en franchissant le mur du son (il rencontre un « mur d'ondes sonores »).
- Les variations de pression autour de l'avion peuvent condenser la vapeur d'eau : brouillard en forme de cône à l'arrière de l'avion.
- Le **claquement d'un fouet** est aussi le passage du mur du son par son extrémité.
- Sillage d'un bateau : 39° !

**Effet Tcherenkov.** La relativité interdit de se déplacer plus vite que la lumière **dans le vide**. Dans un autre milieu, la vitesse de la lumière vaut **c′ = c/n** (n : indice de réfraction). Une particule chargée plus rapide que c′ crée une onde de choc lumineuse : l'**effet Tcherenkov** (lueur bleue visible dans les réacteurs nucléaires ; se produit généralement quand des matières radioactives sont plongées dans l'eau).

**Pourquoi le sillage des bateaux forme-t-il toujours 39° ?** Point commun entre le sillage d'un canard et celui d'un navire de fort tonnage : quelle que soit leur vitesse, l'angle au sommet du cône a une valeur identique, **39°** (**sillage de Kelvin**).

## 5. Application : l'écholocation (chauve-souris)

1. **Émission** : onde émise par le nez ou la bouche, qui voyage jusqu'à un obstacle (une proie).
2. **Réflexion** : l'onde réfléchie rejoint les oreilles ; le cerveau décode les aspects de l'obstacle.
3. **Direction** : proie à gauche → l'onde réfléchie atteint d'abord l'oreille gauche, et inversement.
4. **Taille** : plus la proie est grande, plus l'amplitude de l'onde réfléchie est importante.
5. **Distance** : plus la proie est loin, plus l'onde met de temps à revenir (décalage temporel des ondes réfléchies).
6. **Vitesse** : plus la proie se rapproche, plus l'onde est compressée et sa fréquence modifiée (Doppler).

## 6. Intensité des sons

L'**intensité** I d'une onde est **définie** par l'énergie reçue par seconde (**puissance acoustique**) et par unité d'aire normale à la direction de propagation :

**I = P / A** (P : puissance acoustique reçue ; A : aire de réception — tympan, micro, …) — unité SI : **W/m²**
- L'intensité est proportionnelle au **carré de l'amplitude** de la vibration ; c'est la qualité qui donne la sensation qu'un son est plus ou moins fort.

Source ponctuelle émettant dans toutes les directions : **I(r) = P_source / (4π r²)** → **I ∝ 1/r²**

**Oreille humaine :** sensibilité entre **10⁻¹² W/m² et 1 W/m²**.

**Sensation subjective de puissance — A.G. Bell :** « Pour doubler la puissance (apparente) perçue, il semble qu'il faille multiplier l'intensité par 10. » (Notes : cette expression ne correspond pas à la relation logarithmique ; c'est après une étude plus fine que l'échelle logarithmique fut adoptée.)

Étude systématique → **échelle logarithmique** : la perception humaine du son semble proportionnelle au **logarithme** de l'intensité (« **niveau sonore** ») :

**β = 10 log (I / I₀)** — en **décibels (dB)**
- I₀ = **10⁻¹² W/m²** : valeur de référence arbitraire, choisie pour fixer un niveau sonore nul au seuil d'audibilité.
- NB : la grande étendue de sensibilité justifie vraisemblablement que l'oreille se soit développée en étant sensible au logarithme plutôt que proportionnellement à l'intensité.

**Seuils :**
- Seuil d'audibilité : I = 10⁻¹² W/m² → β = 10 log(10⁻¹²/10⁻¹²) = **0 dB**
- Seuil de sensation douloureuse : I = 1 W/m² → β = 10 log(1/10⁻¹²) = **120 dB**
- N.B. Effet d'une intensité **doublée** : β′ = 10 log(2I/I₀) = β + 10 log 2 ≈ **β + 3 dB**

| Intensités sonores | dB |
|---|---|
| Seuil d'audibilité | 0 |
| Bruissement de feuilles | 10 |
| Corridor calme | 25 |
| Bureau | 60 |
| Conversation | 60 |
| Circulation intense (à 3 m) | 80 |
| Musique classique forte | 95 |
| Musique rock forte | 120 |
| Réacteur d'avion (à 20 m) | 130 |

**Exercice.** Puissance incidente d'un son sur le tympan (aire 0,4 cm²) correspondant à (a) 120 dB ; (b) 0 dB ?
- β = 10 log(I/I₀) → β = 10 log I + 120
- (a) 10 log I = 0 → I = 1 W/m² → **P = I·A = 4·10⁻⁵ W**
- (b) log I = −12 → I = 10⁻¹² W/m² → **P = I·A = 4·10⁻¹⁷ W**

**Défi.** Une explosion émet un son de puissance 20 000 W (source isotrope).
1. À quelle distance le niveau sonore est-il de 10 dB ? (Réponse crédible ? Discutez.)
   - β = 10 log(I/I₀) = 10 log I + 120 = 10 log(P/(4πr²)) + 120 = 163 − 10 log(4πr²) → **β(r) = 152 − 20 log r**
   - 10 = 152 − 20 log r → r = 10^7,1 = **12 589 km**, c.-à-d. sur une grande partie de la surface terrestre !
2. En tenant compte de l'absorption de l'air (≈ 7 dB/km) :
   - 10 = 152 − 20 log r − 7·10⁻³ r → 7,1 = log r + 3,5·10⁻⁴ r → r = 20 286 − 2 857 log r (équation transcendante)
   - Avec Excel et une méthode itérative de type « x = f(x) » : **r = 8,99 km**

**Pour réfléchir.** Pour une source ponctuelle, le bruit diminue de **6 dB** à chaque doublement de distance. Justifier.
- À chaque doublement de distance, l'intensité sonore est réduite d'un **facteur 4** (I ∝ 1/r²) → *(calcul déduit)* Δβ = 10 log(1/4) ≈ −6 dB.

**Exercice.** Deux sources indépendantes produisent individuellement 80 dB et 85 dB en un point. Niveau total ? (86,2 dB)
- β = 10 log(I/I₀) → I = I₀ · 10^(β/10)
- I_total = I₁ + I₂ = I₀ (10^(β₁/10) + 10^(β₂/10)) → I_total/I₀ = 10⁸ + 10^8,5 → **β_total = 10 log(I_total/I₀) = 86,2 dB**
- Plus généralement : **β_total = 10 log(Σ 10^(βᵢ/10))** (les décibels ne s'additionnent pas !)

**Exercice.** Si une personne crie dans les gradins d'un stade, l'intensité au centre du terrain vaut 50 dB. Niveau sonore si 20 000 spectateurs crient à peu près à la même distance ? (Réponse : **93 dB** ; par la même formule : 50 + 10 log 20 000 ≈ 93 dB.)

# II. La lumière

## 7. Historique

**Lumière : flux de particules ou faisceau immatériel ?**
- **1842** : lumière = onde transversale.
- **1845** : **Faraday** suggère que la lumière fait intervenir des oscillations de champs électriques et magnétiques.
- **1865** : **J.C. Maxwell** conclut que la lumière est une **onde électromagnétique** (synthèse de 2 disciplines : optique et électromagnétisme).
- **1887** : **H. Hertz** vérifie expérimentalement les théories de Maxwell.
- **1905** : **Einstein** explique l'**effet photoélectrique**.
- **1909** : **Marconi** : exploitation commerciale (radio, …) — même s'il semble que Nikola Tesla ait expérimenté cette technologie avant lui.

## 8. Spectre électromagnétique

Le spectre des ondes électromagnétiques est divisé en **7 domaines** (des photons de haute énergie aux photons de basse énergie) :
1. les rayons γ ; 2. les rayons X ; 3. les ultraviolets (UV) ; 4. la lumière « visible » ; 5. les infrarouges (IR) ; 6. les micro-ondes ; 7. les ondes hertziennes (radio).

**Gamme du visible : 400 à 700 nm** (violet-bleu → rouge). Notre sens de la vue et la photosynthèse ont évolué dans la gamme de longueurs d'onde du rayonnement solaire que notre atmosphère n'absorbe que très peu.

## 9. Lumière : onde ou corpuscule ?

- **17ᵉ s.** : concurrence entre **Christiaan Huygens** (lumière = ondes) et **Isaac Newton** (lumière = flot de particules).
- **1801** : **Thomas Young** réalise l'expérience « des fentes de Young », qui démontre clairement la **nature ondulatoire** de la lumière ; confirmée par **Augustin Fresnel** en 1821.
- **1865** : **James Maxwell** explique la lumière comme propagation d'**ondes électromagnétiques** (ses célèbres équations) ; confirmé par **Heinrich Hertz** en 1887.
- **1905** : **dualité onde-corpuscule** (presque) admise suite aux travaux d'**Albert Einstein** sur l'effet photoélectrique.

**Expérience des fentes de Young.** On éclaire par une source lumineuse (laser) un écran percé de **deux fentes très fines et rapprochées**, qui se comportent comme deux **sources secondaires**. Une plaque photographique (écran) derrière enregistre la lumière issue des deux fentes : **franges** alternées.
- En chaque point de l'écran existe une **différence de marche** (différence de distance aux deux fentes) ; ce déphasage explique la figure : interférences **constructives** (franges brillantes) et **destructives** (franges sombres).
- NB : on peut diminuer l'intensité de la source jusqu'à émettre la lumière **photon par photon** : les franges deviennent alors inexplicables sans la **dualité onde-corpuscule** et la notion d'**états superposés** (bac 2, physique moderne).

## 10. L'effet de serre

**Introduction.** Tout corps à température T rayonne, et la distribution du rayonnement émis dépend de la température.
- Le **maximum** du rayonnement solaire (T à la surface ≈ 5000-6000 K) se trouve dans la **partie visible** du spectre (l'œil humain s'est d'ailleurs développé pour être sensible à cette gamme, 400 à 700 nm).
- **Loi de déplacement de Wien** : **λ_max · T = 2,898·10⁻³ m·K** → λ_max = 2,898·10⁻³ / 6000 K = **483 nm**

**Température de couleur.** La couleur d'une source lumineuse est comparée à celle d'un **corps noir** théorique chauffé entre 2 000 et 10 000 K, qui aurait dans le visible un spectre d'émission similaire. Exemples : Soleil à l'horizon 2 000 K ; lampe au sodium 2 200 K ; lampe à incandescence 2 400-2 700 K ; fluorescente blanc chaud 2 700-3 000 K ; halogénures métalliques 3 000-4 200 K ; halogène 3 000-3 200 K ; fluorescente blanc neutre 3 900-4 200 K ; Soleil au zénith 5 800 K ; fluorescente lumière du jour 5 400-6 100 K ; lumière naturelle normée 5 000 ou 6 500 K. (Ex. : ampoule « blanc chaud 2800 K ».)

**Dans une serre :**
- Le rayonnement solaire incident est le plus intense à λ_max = 483 nm, où il **traverse facilement le verre**.
- Une partie est absorbée par les objets de la serre, qui réémettent un rayonnement intense à : λ_max = 2,898·10⁻³ / 300 K ≈ **10⁻⁵ m (infrarouge)**.
- Ce rayonnement est dans la partie infrarouge, pour laquelle le **verre est relativement opaque**.
- **Il y a échauffement jusqu'à l'établissement d'un équilibre** (le flux d'énergie solaire est piégé).
- (Le bilan thermique d'une vraie serre s'explique essentiellement par la **convection** et non le rayonnement : la chaleur s'accumule car les parois bloquent les échanges convectifs.)

**La Terre** peut être considérée comme une immense serre : l'atmosphère joue le rôle du vitrage ; la **vapeur d'eau** et le **CO₂** de l'air sont d'excellents absorbants pour l'infrarouge.
- Contributions approximatives à l'effet de serre : **H₂O : 60 % ; CO₂ : 26 % ; O₃ : 8 % ; CH₄ et N₂O : 6 %**.
- Bilan : 30 % du rayonnement solaire réfléchi ; 70 % atteint le globe ; la chaleur réémise (infrarouges) est piégée à 95 % par les gaz à effet de serre (H₂O, CO₂, NO₂, CH₄, …) ; sol à 15 °C.
- Remarque : **Vénus**, atmosphère très dense, effet de serre très marqué (T moyenne assez stable ≈ 460 °C), alors que **Mercure**, dénué d'atmosphère, voit sa température fluctuer entre −170 °C et 430 °C.

**Bilan CO₂ :**
- Activité biologique (plantes, …) → **équilibre** entre absorption et émission de CO₂.
- Combustion des matières fossiles (pétrole, charbon, …) → **augmente** la teneur en CO₂.
- → L'activité industrielle engendre une augmentation de la température moyenne de la Terre pouvant conduire à des **changements climatiques majeurs**.
- **Attention :** l'effet de serre est **indispensable à notre survie** : il **régule** la température dans une gamme très étroite.

## 11. La vitesse de la lumière : une quête historique

| Date | Auteur | Méthode | Valeur |
|---|---|---|---|
| 1635 | Galilée | Expériences | peu concluantes |
| 1676 | Römer | Mesures astronomiques : vitesse finie | 2,1·10⁸ m/s |
| 1726 | Bradley | Mesures astronomiques | 2,8·10⁸ m/s |
| 1849 | Fizeau | Mesures terrestres (sur 9 km) | 3,13·10⁸ m/s |
| 1862 | Foucault | Mesures en laboratoire | 2,98·10⁸ m/s |
| 1920 | Michelson | Méthode plus précise (sur 35 km) | 2,998·10⁸ m/s |
| 1978 | Woods, Shotton et Rowley | Ultime mesure | 2,99792458·10⁸ m/s |

**Römer (1676)**, astronome danois : il prouve que la vitesse de la lumière est **finie** en prédisant une éclipse de **Io** (satellite de Jupiter) différée dans le temps.
- Il mesure la périodicité de l'éclipse (**42,5 h**) : elle se produit un peu **en avance** quand la Terre se rapproche de Jupiter, **en retard** quand elle s'éloigne. L'accumulation des avances (quelques secondes) donne **22 min** quand la Terre passe de B à A.
- c = diamètre de l'orbite / (22·60) = 138·10⁹·2 / (22·60) ≈ 2,1·10⁸ m/s → **c = 210 000 km/s** (à l'époque, distance Terre-Soleil estimée à 138 millions de km).
- Analogie : des messagers courant très régulièrement à 10 km/h sur 10 km. Avec quels décalages perçoit-on 2 informations envoyées à 13 h et 14 h ? Idem sur 100 km ? Et si le récepteur avançait vers le messager ?
- Une Terre immobile mesurerait toujours 42,5 h : c'est parce que l'observateur s'éloigne ou se rapproche que les éclipses successives sont décalées (vitesse finie de la lumière).

**Bradley (1726)**, astronome anglais, découvre l'**aberration optique**.
- Introduction : dans le référentiel du piéton, la direction de la pluie par rapport à la verticale est donnée par tan θ = v_piéton / v_pluie (on incline son parapluie en marchant).
- Une étoile à la verticale : pendant que la lumière descend dans le télescope, celui-ci progresse avec la Terre → il faut l'incliner légèrement.
- En estimant l'angle entre la direction **apparente** et la direction **réelle** de l'étoile, Bradley obtient le rapport entre la vitesse de la Terre sur son orbite et celle de la lumière : v_obs/v_lumière = tan(0,00562°) = 0,00009815
- v_lumière = v_obs / 9,815·10⁻⁵ = ω D_TS / 9,815·10⁻⁵ = [2π/(365·24·3600)] · D_TS / 9,815·10⁻⁵ ≈ **280 000 km/s** (avec D_TS estimée à 137·10⁹ m au lieu de 150·10⁹ m).
- Notes : ce raisonnement concluait aussi de manière indiscutable en faveur de la **théorie héliocentrique** — 185 ans après Copernic ! La distance Terre-Soleil restait imprécise (erreur de près de 10 %) : la mesure permettait d'estimer c à partir de cette distance… ou inversement la distance à partir de c.

**Expérience d'Arago (1810).** « Si on se rappelle que la déviation qu'éprouvent les rayons lumineux en pénétrant obliquement dans les corps est une fonction déterminée de leur vitesse primitive, on verra que l'observation de la déviation totale à laquelle ils sont assujettis en traversant un prisme fournit une mesure naturelle de leur vitesse. » (François Arago, 1786-1853, astronome, physicien et homme d'État.)
- Le matin, l'observateur terrestre **s'éloigne** de l'étoile observée ; le soir, il s'en **rapproche** : la vitesse relative de la lumière perçue devrait varier, donc la déviation dans le prisme (achromatique) aussi.
- **Résultat NUL !!!** Arago n'observe **aucune différence**.

**Fizeau (1849)** mesure, par méthode **terrestre** et pour la première fois, la vitesse de la lumière (roue dentée ; la mesure est prise lorsque l'observateur ne reçoit plus aucune lumière) :
- Δt = 2d/c et Δt = T/(2n) → **c = 4 d n / T**
- Expérience de Fizeau : d = 8,6 km ; n = 720 ; T = 1/12,6 s → **c = 313 000 km/s**

**Foucault (1862)** : l'astuce consiste à utiliser un **miroir tournant** → **c = 298 000 ± 500 km/s**.

**Michelson (1920)** : miroir tournant **à 8 faces**. Plusieurs centaines de mesures → **c = 299 796 ± 4 km/s**. Ses dernières (et meilleures) mesures, en 1926, sur une base de 35 km entre le mont Wilson et le mont San Antonio (Baldy), avec des miroirs à 8, 12 et 16 faces tournant à 528 t/s.

En **1978**, Woods, Shotton et Rowley obtiennent **299 792,4587 ± 0,0002 km/s** — précision meilleure que celle du mètre-étalon !

**Redéfinition de l'unité de distance.** Cette quête de précision devenait insensée, et même inutile vu l'imprécision du mètre-étalon. **Le mètre est la distance parcourue par la lumière en 1/299 792 458 s.** La vitesse de la lumière s'en déduit directement :
c = e/t = 1 m / (1/299 792 458 s) = **299 792 458 m/s** — valeur fixée (sans décimales) en **1983** par le Bureau International des Poids et Mesures.

**QCM.** Si l'on définissait le mètre sur base d'une vitesse de la lumière égale à 300 000 km/s, que représenterait un mètre par rapport au mètre actuel ? (100,7 cm ; 107 cm ; 100,0007 cm ; 99,93 cm)
- Le mètre deviendrait la distance parcourue en **1/300 000 000 s** au lieu de 1/299 792 458 s. Puisque 1/300 000 000 < 1/299 792 458, la lumière parcourrait une distance plus courte : le mètre deviendrait plus petit.
- Il correspondrait à 299 792 458 / 300 000 000 m = 0,9993 m → **99,93 cm**.
- Sur 100 km, la modification serait de 70 m ; le rayon de la Terre diminuerait de 4,5 km et la distance Terre-Lune de 270 km. (Cela aurait-il modifié notre quotidien ?)

*« Ah, messagère admirable, lumière éclatante, je sais votre célérité ! La constante lumineuse restera désormais là, dans votre cervelle »* (moyen mnémotechnique : nombre de lettres de chaque mot → **299 792 458 m/s**).

## 12. Le système GPS

**Principe** (notes) : constellation de satellites qui transmettent leur **position** et l'**heure précise** ; le récepteur fait des mesures de **triangulation** pour obtenir sa position (couverture mondiale, continue, en 3 dimensions : position et altitude). Développé par le Department of Defense (DOD) américain, très fiable (insensible aux conditions atmosphériques, à la topographie, aux interférences radio). Accessible aux civils, mais deux codes : un code crypté militaire (**PPS**) et un code civil (**SPS**).

**Points clés :** la triangulation ; la mesure de distance ; la mesure précise du temps ; les sources d'erreurs.

**1. Triangulation.** Sur une carte, avec des visées vers des points connus, les droites se croisent en notre position (avec un 3ᵉ, un 4ᵉ point, … les droites passent par notre position).

**Analogie 2D :** se situer dans une pièce carrée (10 × 10) en connaissant la distance aux coins — mais chaque distance a une **erreur « systématique »** (la même pour chaque mesure).
- Avec 2 cercles (lieux des possibilités), on obtient une seule possibilité. Exemple : d₁ = 5 ; d₂ = 10 ; d₃ = 6 ; d₄ = 11 → x² + y² = 5² ; (x − 10)² + y² = 10² → 100 − 20x = 75 → x = 1,25 → y = ±4,8412 (on rejette y = −4,8412, hors du carré).
- À cause de l'erreur systématique, la position (1,25 ; 4,8412) est erronée et **incompatible** avec un 3ᵉ lieu.
- On modifie **toutes** les distances de la même valeur jusqu'à obtenir un point commun aux 3 cercles (simulation Excel : on corrige selon le signe du « Delta » entre d₃ calculé et d₃ mesuré ; si le Delta change de signe, on divise le pas par 10 — ou **méthode dichotomique** : on modifie l'intervalle de recherche selon le signe du Delta).
- On converge rapidement vers **x_exact = 1,4025 ; y_exact = 4,4805**. Non seulement on obtient la position, mais on a **déterminé l'erreur systématique** et donc **calibré** le système de mesure.

**Méthode des hyperboloïdes** (même analogie) : si les erreurs sont systématiques, on sait que d₂ − d₁ = 5 → (x − 5)²/6,25 − y²/18,75 = 1 ; de même (y − 5)²/0,25 − x²/24,75 = 1. (Selon l'IA « Claude » consultée par le professeur, la solution est analytiquement impossible.)

**Triangulation en 3D :** la connaissance de la distance à **3 satellites** permet d'obtenir une position dans l'espace : une mesure → une sphère ; deux mesures → un cercle ; trois mesures → deux points, dont l'un est aberrant. **Attention** : ce raisonnement suppose que le récepteur possède une **horloge atomique**, ce qui est impossible en réalité vu son prix.

**2. Mesure de la distance.** Le satellite envoie un signal (contenant l'heure de l'envoi) ; le récepteur détermine le temps de transmission et déduit la distance par **d = v t**.

**3. Mesure précise du temps.**
- Une erreur d'**un millième de seconde** produit une erreur de position de **300 km** !
- À la vitesse de la lumière, la précision doit être de l'ordre de la **nanoseconde**. Les horloges des satellites sont **atomiques** (césium) ; celles des récepteurs beaucoup moins précises.
- Solution : **utiliser un 4ᵉ satellite**. Sans horloge précise, le récepteur connaît la **différence** des distances à 2 satellites → un **hyperboloïde de révolution** ; un 3ᵉ satellite réduit le lieu à une courbe (intersection de 2 hyperboloïdes) ; un 4ᵉ permet la localisation précise.
- Exemple sur la carte : une erreur systématique (d'étalonnage, quelques degrés, la même sur chaque droite) fait qu'il n'y a plus de droites concourantes.

**Méthode itérative :**
- Les informations de 3 satellites donnent un lieu de 2 points, dont l'un s'élimine naturellement (sous terre, en altitude, …), mais l'erreur reste (beaucoup trop) grande à cause de l'imprécision de l'horloge du récepteur.
- Avec cette position calculée mais erronée, le récepteur calcule la distance qui devrait le séparer d'un **4ᵉ satellite** : elle s'avère inexacte.
- Il modifie alors son horloge **par itérations** jusqu'à ce que ces distances soient identiques → **position parfaitement définie théoriquement ET horloge synchronisée**.

Notes : chaque satellite transmet sa position, son altitude et l'heure d'émission. Deux types de messages : l'**almanach** (information générale sur la localisation et la santé des satellites, pour savoir où chercher) et les **éphémérides** (position précise du satellite, pour le calcul des distances).

**4. Sources d'erreurs :**
1. **Horloge interne du satellite** : très précise, mais tout de même source d'erreur.
2. **Dégradation volontaire** : principale source d'erreur ; préserve l'avantage de l'armée américaine sur les civils.
3. **Éphémérides qui évoluent** : il faut tenir compte du déplacement des satellites sur leur orbite.
4. **Traversée atmosphérique** : le signal ralentit dans l'atmosphère → erreur sur la distance.
5. **Réverbération** : le signal peut être dévié par des obstacles (en montagne notamment).

**Le DGPS (GPS différentiel)** améliore la précision : le récepteur reçoit des informations d'une **borne** qui connaît exactement sa position X ; elle calcule l'erreur = Y − X (Y : position calculée) et la diffuse ; l'utilisateur corrige : position « réelle » R = P − erreur. (Il faut un récepteur différentiel compatible et être assez proche d'une antenne différentielle.)

La technologie GPS prend aussi en compte des effets physiques importants : 1. l'**effet Doppler** ; 2. des effets liés aux **théories de la relativité** (dilatation du temps, blueshift gravitationnel, effet Sagnac).

**Projet GALILEO (2019)** — système européen de positionnement par satellites :
- garantira l'**autonomie de l'Union européenne** vis-à-vis des États-Unis et de la Russie dans des domaines stratégiques (applications militaires, …) ;
- précision attendue : **le décimètre**.
- (Témoignage d'un ancien étudiant : à son entretien d'embauche, le PDG lui a demandé « sais-tu comment le système GPS fonctionne ? » — ce cours l'a sauvé.)
