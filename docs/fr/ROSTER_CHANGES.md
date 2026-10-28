[English](../../ROSTER_CHANGES.md) · [Langues](../README.md)

# USF4 TAG Project — Modifications du roster pré-alpha

**Pré-alpha v0.1 · Version 0.1.0 · Build de combat accepté 105 · Lanceur révision 6 · 42 personnages pris en charge · Mis à jour le 28 octobre 2026**

Ce document couvre la pré-alpha de combat terminée. Sélectionnez les personnages **Ultra standard**. **Hugo et Hakan sont reportés.** Cette version utilise des combats ordinaires à un personnage et le HUD d'origine ; le jeu en équipe/tag reste un chantier distinct.

## Notation

- **LP / MP / HP :** poing léger / moyen / fort.
- **LK / MK / HK :** pied léger / moyen / fort.
- **Close / far :** attaque normale choisie selon la distance de l'adversaire.
- **QCF :** quart de cercle avant. **QCB :** quart de cercle arrière. **HCF :** demi-cercle avant.
- **2× QCF / 2× HCF :** effectuez deux fois le mouvement.
- **PPP / KKK :** les trois poings / trois pieds simultanément.
- Les directions sont relatives au côté vers lequel regarde votre personnage. Les noms de personnages, de coups et de boutons du lanceur restent ceux du document anglais pour faciliter le repérage.

Les valeurs en frames décrivent les réglages et objectifs d'équilibrage du build. Toutes les valeurs de démarrage ou d'avantage n'ont pas été mesurées indépendamment en jeu. Les coûts de jauge, hauteurs, portées et commandes d'origine s'appliquent sauf modification indiquée.

## Système de combat commun

### Launchers et poursuite

Chaque personnage pris en charge possède au moins un launcher. **Touchez avec ce coup et maintenez Haut pour poursuivre l'adversaire dans les airs.** La poursuite exige une touche réussie. Pour les launchers à plusieurs coups, le tableau précise quelle touche ouvre la poursuite.

### Combos aériens standard

Les nouvelles chaînes de coups normaux sont accessibles après la poursuite d'un launcher. Les attaques de saut ordinaires conservent leurs enchaînements natifs, sauf exceptions indiquées ci-dessous.

- Les chaînes suivent **léger → moyen → fort**. Choisissez poing ou pied à chaque puissance.
- Il est possible de sauter une puissance. **Seuls LP, LK, MP ou MK peuvent commencer la chaîne normale de poursuite ; HP/HK ne peuvent pas la commencer.** Les finishers forts restent accessibles après un léger ou un moyen.
- Chaque puissance n'est utilisée qu'une fois au maximum. Les liens entre coups de même puissance et les retours vers des normaux plus faibles sont exclus de la chaîne standard.
- Exemples : **LP → MP → HP**, **LK → MK → HK**, **LP → MK → HP**, **MP → HK**.
- **HP ou HK termine normalement la chaîne par une frappe vers le bas et un rebond au sol.** Les sections de Rufus, Chun-Li, Gen et Elena précisent leurs finishers.
- Les spéciaux aériens, normaux de commande, projections et Ultras ajoutés utilisent les routes propres à chaque personnage. L'accès à un spécial pendant la récupération ne relance pas la chaîne normale.

**Gen possède sa propre variante de chaîne légère/moyenne.** Les autres personnages suivent les règles standard, sous réserve des target combos et suites à plusieurs touches explicitement indiqués. La règle de départ léger/moyen s'applique aussi aux deux styles de Gen et aux entrées par jump cancel de Fukiage de Makoto. L'accès propre à chaque personnage aux spéciaux aériens, projections et normaux de commande est conservé.

### Juggles, rebond au sol et récupération

- Les normaux moyens/forts au sol reçoivent la réaction aérienne de juggle commune. **Les LP/LK ordinaires au sol et en saut conservent leurs propriétés et réactions de juggle USF4 natives.** Les LP/LK des combos aériens de poursuite gardent les réactions permettant de poursuivre la chaîne.
- Les spéciaux de frappe et projectiles indiqués peuvent toucher plus facilement pendant un juggle. Cette possibilité accrue ne transforme pas automatiquement leur réaction native en flottement ; les changements de réaction sont précisés plus bas.
- Les finishers aériens forts produisent un rebond au sol permettant des suites au sol. Sans suite réussie, l'adversaire passe par sa chute puis sa relève.
- La récupération du combo aérien utilise un salto avant ou une rotation native adaptée. Les corrections propres aux personnages s'appliquent aux finishers réussis et aux attaques dans le vide lorsque cela est précisé.
- Les personnages pris en charge utilisent leur **dash avant Omega**, adapté à leur palette standard. **Dhalsim conserve son dash avant USF4 standard.** Cela ne transforme pas les personnages en versions Omega complètes.

### Exceptions pour les spéciaux légers

**Les spéciaux légers au sol utilisant le mouvement Dragon Punch avant conservent leurs propriétés et réactions de juggle USF4 natives.** Cela concerne LP et LK, y compris les raccourcis acceptés pour avant → bas → bas-avant. La règle dépend de la famille de commande, pas seulement des coups appelés Shoryuken : Cannon Spike, Seismic Hammer, Fukiage, Soul Throw, Banishing Flat et Tiger Knee légers en font partie. Les mouvements DP inversés ne sont pas concernés.

Les versions moyennes/fortes/EX conservent leur comportement pré-alpha indiqué. **Les spéciaux aériens légers ne sont pas affectés par ce retour aux propriétés d'origine.** Les boules de feu légères et les autres spéciaux légers hors de cette famille au sol conservent également leurs modifications indiquées.

### Étourdissement pendant les combos de launcher

**L'étourdissement positif est divisé par deux à partir de la touche qui lance réellement et jusqu'à la fin du combo**, y compris les suites aériennes, après rebond et au sol. Les dégâts de vie ne changent pas. Un nouveau combo distinct retrouve le taux normal jusqu'à ce qu'un autre launcher touche ; un launcher dans le vide ou bloqué ne déclenche pas la règle. L'arrondi natif et le minimum d'un point d'étourdissement restent en vigueur.

Pour les launchers à plusieurs touches, la réduction commence à la touche qui lance ; les touches précédentes conservent leur réduction d'étourdissement normale.

La règle supplémentaire s'applique actuellement uniquement en **Training Ultra standard hors ligne**. Le lanceur l'active automatiquement une fois Simp terminé ; attendez **Patching complete** avant d'entrer en Training. Aucun bouton d'étourdissement séparé n'est nécessaire. Les autres modes ne reçoivent pas cette règle de session ; leur prise en charge reste à développer.

### Ultras après rebond au sol

Les Ultras de frappe et à projectiles peuvent attraper une cible aérienne après rebond au sol. Leurs contraintes natives de portée, de timing, de hauteur et de cinématique restent importantes. Les dégâts et leur scaling sont conservés.

Les Ultras à prise/capture, les contres et les activations sans attaque ou soins gardent leur comportement, avec deux exceptions demandées : **l'Ultra 2 de T. Hawk** et **l'Ultra 2 de Zangief** peuvent reprendre après rebond au sol.

Les tolérances accrues restent limitées. Les deux coups ajoutés qui effacent explicitement le compteur de juggle précédent sont **l'air Raging Demon d'Evil Ryu** et **l'EX Shikusen de Juri**. Leurs sections détaillent ces changements.

## Référence rapide des launchers

Cliquez sur un personnage pour voir ses modifications complètes.

| Personnage | Launcher / début de poursuite |
| --- | --- |
| [Abel](#abel) | HP accroupi lance à sa deuxième touche. La première conserve sa réaction normale au sol. |
| [Adon](#adon) | HK debout proche lance. HK debout lointain conserve son comportement au sol. |
| [Akuma](#akuma) | HP accroupi lance. |
| [Balrog](#balrog) | HP accroupi lance, y compris sa version mise à jour active. |
| [Blanka](#blanka) | HP debout proche lance. HP lointain conserve sa réaction au sol. |
| [C. Viper](#c-viper) | HK debout proche lance à sa deuxième touche. La première touche et HK debout lointain gardent leurs réactions au sol. |
| [Cammy](#cammy) | HK debout proche lance. HK lointain conserve sa réaction au sol. |
| [Chun-Li](#chun-li) | HK debout proche lance. HK lointain conserve sa réaction au sol. |
| [Cody](#cody) | HP accroupi lance à mains nues et au couteau. Les poings au couteau gardent leurs animations et routes aériennes propres ; les routes de pieds fonctionnent dans les deux styles. |
| [Dan](#dan) | HP accroupi lance. Dan suit les règles de chaîne aérienne standard. |
| [Decapre](#decapre) | HK debout proche lance. HK lointain conserve sa réaction au sol. |
| [Dee Jay](#dee-jay) | HP debout seul effectue l'ancien HP lointain aux deux distances. C'est le launcher, avec 7 frames de démarrage et des annulations en spécial en touche ou en garde. |
| [Dhalsim](#dhalsim) | Arrière+HK, son normal debout court, lance. Le HK debout extensible ordinaire garde sa réaction au sol. |
| [Dudley](#dudley) | HP accroupi lance. |
| [E. Honda](#e-honda) | HP debout proche lance, avec 6 frames de démarrage au lieu de 8, et peut être annulé en spécial en touche ou en garde. HP lointain garde sa réaction au sol. |
| [El Fuerte](#el-fuerte) | HP accroupi lance. |
| [Elena](#elena) | HP debout lance, sans distinction proche/lointain pour HP. |
| [Evil Ryu](#evil-ryu) | HP accroupi lance, avec 5 frames de démarrage comme cible finale. HP debout garde sa réaction au sol et ne donne pas accès à la poursuite. |
| [Fei Long](#fei-long) | HK debout proche lance. HK lointain garde sa réaction au sol. |
| [Gen](#gen) | HP debout en Mantis lance à sa dernière touche.<br>HP debout en Crane lance à sa deuxième touche. HK accroupi en Crane lance également. |
| [Gouken](#gouken) | MK accroupi lance. |
| [Guile](#guile) | HP accroupi lance. |
| [Guy](#guy) | HP debout proche utilisé seul lance. HP lointain et le HP de la chaîne Bushin ne reçoivent pas ce launcher au sol.<br>Le target combo MP → HP ne lance pas. Sa dernière touche reçoit un jump cancel en maintenant Haut, uniquement en touche, menant au combo aérien. La garde ou le vide ne l'autorisent pas. |
| [Ibuki](#ibuki) | HP accroupi lance, avec ses entrées natives de jump cancel. |
| [Juri](#juri) | HP accroupi est le launcher, y compris dans les routes correspondantes de Feng Shui Engine. HP debout proche retrouve son comportement au sol et ne donne pas de poursuite. |
| [Ken](#ken) | HP accroupi lance. |
| [M. Bison](#m-bison) | HP accroupi lance, avec 6 frames de démarrage et +1 en garde. Il peut être annulé en spécial en touche ou en garde. |
| [Makoto](#makoto) | HK accroupi est le launcher. HP accroupi conserve son balayage au sol.<br>EX Fukiage conserve son lancement naturel et reçoit l'accès au combo aérien/Tsurugi via son jump cancel après une touche.<br>Le jump cancel de Fukiage normal et l'accès aérien qui en découle exigent une touche. Les directions de saut natives neutre, avant et arrière restent possibles. |
| [Oni](#oni) | HP accroupi lance. |
| [Poison](#poison) | HK debout proche lance sur sa dernière touche. La première et HK lointain gardent leurs réactions au sol. |
| [Rolento](#rolento) | HP debout proche lance. HP lointain garde sa réaction au sol. |
| [Rose](#rose) | HP accroupi lance. |
| [Rufus](#rufus) | HK debout proche lance. HK lointain garde sa réaction au sol. |
| [Ryu](#ryu) | HP accroupi lance. |
| [Sagat](#sagat) | MP debout proche lance. MP lointain garde sa réaction au sol. |
| [Sakura](#sakura) | HP accroupi lance, avec ouverture de la poursuite dès sa première touche active pour une suite plus précoce. |
| [Seth](#seth) | HP accroupi lance à sa deuxième/dernière touche. La première garde sa réaction au sol. |
| [T. Hawk](#t-hawk) | HK debout proche lance. HK debout lointain ne lance pas et ne donne pas de poursuite. |
| [Vega](#vega) | HK debout proche lance à sa deuxième touche. La première et HK lointain gardent leurs réactions au sol. |
| [Yang](#yang) | HP debout proche lance uniquement à sa deuxième touche. La première garde sa réaction au sol.<br>MK debout proche garde son lancement naturel et reçoit la poursuite en maintenant Haut. |
| [Yun](#yun) | HP debout proche lance uniquement à sa deuxième/dernière touche. La première garde sa réaction au sol.<br>MK debout proche garde son lancement naturel et reçoit la poursuite en maintenant Haut. |
| [Zangief](#zangief) | HK debout proche lance. HK lointain garde sa réaction au sol et ne dispose pas d'annulation de poursuite. |

## Modifications par personnage

Tous les personnages ci-dessous reçoivent le système commun. Ces sections présentent leurs launchers, changements supplémentaires et exceptions. **Les exceptions communes des normaux légers ordinaires et des DP légers au sol s'appliquent à toutes les listes générales de juggle ci-dessous.**

### Abel

- **HP accroupi lance à sa deuxième touche.** La première conserve sa réaction normale au sol.
- Les zones de frappe de Change of Direction, Wheel Kick et Falling Sky gagnent la possibilité de juggle.
- Les finishers aériens réussis et la récupération dans le vide utilisent le salto avant de type Cody.
- Contre un adversaire déjà aérien, la deuxième touche de HP accroupi utilise la réaction commune de chute courte.

### Adon

- **HK debout proche lance.** HK debout lointain conserve son comportement au sol.
- **Jaguar Kick aérien L/M/H/EX** est accessible pendant la poursuite, après les touches aériennes légères/moyennes et pendant la récupération du combo aérien.
- Jaguar Kick aérien maintient un juggle continu contre une cible aérienne au lieu de provoquer un reset aérien.
- Les variantes de frappe de Jaguar Kick, Jaguar Tooth et Rising Jaguar gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Akuma

- **HP accroupi lance.**
- **La boule de feu aérienne et le Tatsu aérien L/M/H/EX** sont accessibles pendant la poursuite, les chaînes aériennes et la récupération aérienne, avec leurs commandes et restrictions habituelles.
- **L'ancien HK debout lointain devient avant+HK**, utilisable aux deux distances. HK debout seul utilise l'ancien HK proche aux deux distances.
- Avant+MP, dive kick, Tatsu, Shoryuken M/H/EX, frappes de Demon Flip et boules de feu ordinaires gagnent la possibilité de juggle. **Shoryuken léger au sol conserve ses propriétés de juggle USF4 natives.**
- La poursuite et la récupération utilisent l'animation native de saut avant d'Akuma.

### Balrog

- **HP accroupi lance**, y compris sa version mise à jour active.
- Les dash punches et uppercuts, leurs variantes overhead/basses, Buffalo Head et les frappes de Turn Punch gagnent la possibilité de juggle.
- Les finishers forts et les attaques dans le vide du combo aérien utilisent la récupération en salto de type Cody, adaptée à ses gants et à son squelette.
- Violent Buffalo reçoit la possibilité commune de reprise d'Ultra ; Dirty Bull conserve son comportement de prise.

### Blanka

- **HP debout proche lance.** HP lointain conserve sa réaction au sol.
- **Electric Thunder accepte cinq pressions de poing ou QCF+P.** QCF+deux poings sélectionne EX.
- **Toutes les versions d'Electric Thunder gardent le juggle USF4 d'origine**, y compris les impulsions prolongées et les variantes EX. La tolérance commune accrue a été retirée de l'électricité.
- Les frappes de Rolling et des variantes de boule verticale conservent leur possibilité de juggle ajoutée.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto.

### C. Viper

- **HK debout proche lance à sa deuxième touche.** La première touche et HK debout lointain gardent leurs réactions au sol.
- **Burning Kick aérien L/M/H/EX** est accessible pendant la poursuite et la récupération.
- **L'Ultra 2, Burning Dance, est accessible pendant les combos aériens**, sous réserve des commandes, jauges, hauteurs et choix d'Ultra natifs.
- **Seismic Hammer M/H/EX peut toucher en juggle aérien**, permettant des suites de juggle et de rebond à sa portée normale. **Seismic Hammer léger conserve ses propriétés de juggle USF4 natives.**
- La récupération en cas de touche ou dans le vide utilise son salto avant natif complet.

### Cammy

- **HK debout proche lance.** HK lointain conserve sa réaction au sol.
- **La projection aérienne, LP+LK, est accessible pendant la poursuite et après les touches aériennes légères/moyennes**, avec capture et dégâts compatibles avec le juggle.
- **Cannon Spike M/H/EX gagne une tolérance de juggle accrue. Cannon Spike léger conserve ses propriétés USF4 natives.** Aucun Cannon Spike aérien n'est ajouté.
- **Cannon Strike L/M/H/EX est accessible pendant les combos et la récupération aériens.** Les touches aériennes maintiennent le juggle au lieu de réinitialiser la cible en l'air.
- Les zones de frappe de Spiral Arrow, Quick Spin Knuckle et de la glissade Hooligan gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Chun-Li

- **HK debout proche lance.** HK lointain conserve sa réaction au sol.
- **La projection aérienne est accessible pendant la poursuite**, avec capture et dégâts adaptés aux adversaires en juggle.
- **Yosokyaku est accessible pendant les combos aériens**, avec ses commandes natives bas/bas-avant+MK et ses suites à trois piétinements.
- **Hyakuretsukyaku accepte QCF+K ou cinq pressions rapides de pied.** Les prolongations par pressions répétées et les règles de jauge EX restent inchangées.
- **HP aérien → HP produit le rebond au sol uniquement au deuxième poing.** Le premier garde la cible en l'air. Sans deuxième poing, le premier récupère sans rebond. HP ne peut pas se lier à HK ou à un normal plus faible.
- **Hazanshu L/M/H/EX utilise la réaction aérienne de juggle commune**, tout en gardant ses réactions au sol.
- Les projectiles Kikouken gagnent la possibilité de juggle.
- La récupération en cas de touche ou dans le vide utilise le salto de type Cody corrigé.

### Cody

- **HP accroupi lance à mains nues et au couteau.** Les poings au couteau gardent leurs animations et routes aériennes propres ; les routes de pieds fonctionnent dans les deux styles.
- **Criminal Upper, toutes puissances et EX, peut être annulé en FADC à chaque touche connectée**, y compris les dernières touches de tornade. Un contact en touche ou en garde est nécessaire.
- **Récupération de HP Criminal Upper : 23 frames. EX Criminal Upper : 25 frames.**
- **Récupération de HK Ruffian Kick : 25 frames**, au lieu de 27.
- **Récupération du Super LK/MK/HK : 22 frames**, y compris les branches de suite après touche réussie.
- Criminal Upper, Bad Stone, les couteaux lancés et les spéciaux de frappe gagnent la possibilité de juggle.
- Les finishers forts réussis et les combos aériens dans le vide utilisent le salto avant, y compris les routes de poings au couteau.

### Dan

- **HP accroupi lance.** Dan suit les règles de chaîne aérienne standard.
- **Dankukyaku aérien L/M/H/EX et la provocation aérienne native sont accessibles pendant les combos aériens et la récupération.**
- **La provocation aérienne garde ses propriétés de touche et de juggle d'origine.** Aucune tolérance de juggle accrue n'est ajoutée aux provocations.
- Gadoken et Dankukyaku L/M/H/EX gagnent la possibilité de juggle. **Koryuken M/H/EX conserve ses changements pré-alpha ; Koryuken léger au sol garde ses propriétés de juggle USF4 natives.**
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Decapre

- **HK debout proche lance.** HK lointain conserve sa réaction au sol.
- **La projection aérienne est accessible pendant la poursuite et la récupération aérienne**, avec capture et dégâts compatibles avec le juggle. Les dégâts de base et le scaling natifs restent inchangés.
- **Rapid Dagger accepte QCF+P ou les cinq pressions de poing d'origine**, avec la sélection native de puissance EX et de jauge.
- **Spiral Arrow aérien L/M/H/EX est accessible pendant la poursuite, les chaînes aériennes et la récupération**, avec ses exigences natives de commande et de hauteur.
- La récupération utilise son salto natif de saut avant, corrigeant l'ancienne pose de personnage touché.

### Dee Jay

- **HP debout seul effectue l'ancien HP lointain aux deux distances.** C'est le launcher, avec **7 frames de démarrage** et des annulations en spécial en touche ou en garde.
- **Arrière+HP effectue l'ancien HP debout proche aux deux distances.** Il garde sa réaction au sol et ses annulations natives.
- **Double Rolling Sobat utilise QCF+K**, y compris EX.
- **Double Rolling Sobat léger utilise l'action et les données de touche AE2012**, dont l'invulnérabilité basse et le comportement en garde, avec la nouvelle commande QCF et la possibilité de juggle.
- **Knee Shot, bas+LK, est accessible pendant la poursuite et après la fin d'un normal aérien.** Il maintient un juggle aérien au lieu d'un reset.
- Knee Shot **ne s'annule pas directement en chaîne depuis les normaux aériens** et ne rouvre pas la chaîne normale. La récupération immédiate après contact d'un fort n'ajoute pas d'annulation en Knee Shot.
- Air Slasher et les zones de frappe de Machinegun Upper, Sobat et Jackknife Maximum gagnent la possibilité de juggle.

### Dhalsim

- **Arrière+HK, son normal debout court, lance.** Le HK debout extensible ordinaire garde sa réaction au sol.
- La poursuite utilise ses normaux aériens courts avec les entrées poing/pied normales ; il n'est pas nécessaire de maintenir Arrière pour ces coups aériens.
- **Les trois angles de Yoga Spear et Yoga Mummy sont accessibles pendant la poursuite et la récupération**, avec leurs commandes natives : respectivement bas+pied et bas+HP.
- Les boules de feu et les spéciaux de frappe gagnent la possibilité de juggle.
- **Le dash avant redevient celui d'USF4 standard**, avec son déplacement, son animation et ses timings d'annulation.
- La récupération en touche ou dans le vide utilise une pose native complète du salto de Dhalsim, corrigeant les déformations des jambes et pieds.

### Dudley

- **HP accroupi lance.**
- Les normaux de commande au sol et les attaques de target combo reçoivent la réaction aérienne de juggle commune.
- Machinegun Blow, Jet Upper, Short Swing Blow, les suites de frappe de Ducking, Thunderbolt et les portions de frappe de Cross Counter gagnent la possibilité de juggle.
- Les combos aériens utilisent ses attaques de saut avant et sa récupération natives. Les projectiles de rose gardent leur comportement d'origine.

### E. Honda

- **HP debout proche lance**, avec **6 frames de démarrage au lieu de 8**, et peut être annulé en spécial en touche ou en garde. HP lointain garde sa réaction au sol.
- **EX Sumo Smash produit un rebond au sol uniquement sur sa dernière touche descendante.** La montée et les versions non-EX gardent leurs réactions normales.
- **Hundred Hand Slap accepte cinq pressions rapides de poing ou QCF+P.** Les prolongations natives par pressions répétées sont restaurées en parallèle de la commande par mouvement ; EX garde sa sélection par boutons de poing.
- Les spéciaux de frappe gagnent la possibilité de juggle commune. Les commandes de Headbutt, Sumo Smash, Super et Ultra gardent leurs exigences natives.

### El Fuerte

- **HP accroupi lance.**
- **La projection aérienne, LP+LK, est accessible pendant la poursuite, les chaînes légères/moyennes et la récupération.** Sa capture et ses deux routes de dégâts peuvent toucher en juggle, en gardant les dégâts de base et le scaling natifs.
- Les spéciaux de frappe gagnent la possibilité de juggle ; les routes natives de course et saut mural sont préservées.
- La récupération en touche ou dans le vide utilise son salto natif complet de saut avant.
- Les deux Ultras à prise conservent leur capture native, conformément à l'exception générale des Ultras.

### Elena

- **HP debout lance**, sans distinction proche/lointain pour HP.
- Les six normaux aériens sont accessibles en poursuite, y compris l'éligibilité corrigée des entrées aériennes propres au combo.
- **HK aérien garde ses deux touches ; seule la dernière produit le rebond au sol.** HP fournit également un finisher avec rebond.
- La récupération en touche ou dans le vide utilise une rotation native de Mallet Smash, en conservant son squelette.
- Les spéciaux de frappe gagnent la possibilité de juggle. Brave Dance reçoit la reprise commune d'Ultra ; Healing reste natif.

### Evil Ryu

- **HP accroupi lance**, avec **5 frames de démarrage** comme cible finale. HP debout garde sa réaction au sol et ne donne pas accès à la poursuite.
- **Avant+MK reçoit une réaction aérienne de juggle continu.**
- **Tous les axe kicks Ryusokyaku peuvent juggle. La version EX produit un rebond au sol**, sur la dernière touche si l'action en possède plusieurs.
- Hadoken, Shakunetsu, Tatsu au sol/aérien et Shoryuken M/H/EX gagnent la possibilité de juggle. **Shoryuken léger au sol conserve ses propriétés de juggle USF4 natives.**
- **Tatsu aérien L/M/H/EX est accessible pendant la poursuite et les routes de combo aérien.**
- **Air Raging Demon est ajouté à partir de la séquence native d'Oni.** Avec la jauge Super pleine, entrez **LP, LP, avant, LK, HP** en l'air. L'annulation depuis les normaux de saut ordinaires permet son activation.
- Le son d'activation d'Air Demon utilise les voix et effets adaptés à Evil Ryu.
- **Air Demon efface le compteur de juggle précédent de l'adversaire pendant sa fenêtre de prise**, permettant de le placer après de longs juggles. La remise à zéro s'effectue même si la tentative échoue ; portée, éligibilité aérienne et invulnérabilités natives restent applicables.

### Fei Long

- **HK debout proche lance.** HK lointain garde sa réaction au sol.
- Les zones de frappe de Rekka, Shienkyaku et Rekkukyaku gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.
- Rekkashingeki reçoit la reprise commune d'Ultra ; Gekirinken garde son comportement de contre.

### Gen

- **HP debout en Mantis lance à sa dernière touche.**
- **HP debout en Crane lance à sa deuxième touche. HK accroupi en Crane lance également.**
- Les HP debout proches et lointains ainsi que les copies HP de target combo suivent la règle de dernière touche propre au style.
- Chaque style possède ses propres attaques de combo aérien et routes de poursuite.
- **Gen seul peut utiliser poing et pied dans les catégories légère et moyenne, dans l'ordre de son choix.** Chaque normal n'est utilisable qu'une fois. Les puissances peuvent être sautées, mais passer à une puissance supérieure ferme les catégories inférieures.
- **HP ou HK termine la chaîne. HP → HK et HK → HP sont interdits.**
- Exemples : **LP → LK → MP → MK → HK**, **LK → LP → MK → MP → HP**, **LP → MK → HP**. Moyen → léger et fort → moyen/léger sont interdits.
- **Le HK aérien à deux touches de Crane produit un rebond au sol uniquement sur la deuxième touche.**
- **Hyakurenko accepte cinq pressions rapides de poing ou QCF+P**, avec les prolongations natives par pressions répétées. EX garde sa sélection par boutons de poing.
- Les spéciaux de frappe gagnent la possibilité de juggle. La récupération en touche ou dans le vide utilise des saltos de type Cody dans les deux styles.

### Gouken

- **MK accroupi lance.**
- **Tatsu aérien L/M/H/EX est accessible pendant la poursuite et la récupération.**
- **Chaque Tatsu de poursuite avance vers l'adversaire et possède une seule fenêtre infligeant des dégâts par activation.** Le Tatsu de saut ordinaire garde ses actions à plusieurs touches et ses commandes natives.
- Les Hadoken ordinaires et les spéciaux de frappe gagnent la possibilité de juggle.
- La récupération utilise son salto avant natif complet.

### Guile

- **HP accroupi lance.**
- **HP debout lointain, HK debout lointain et HP accroupi peuvent être annulés en spécial ordinaire en touche ou en garde.**
- Les Sonic Boom normaux et EX gagnent la possibilité de juggle.
- **Les projections aériennes avant et arrière sont accessibles en poursuite**, avec LP+LK ; Arrière choisit la projection arrière.
- **Les projections aériennes de poursuite utilisent les réactions natives de la victime sans rebond au sol ajouté.** La route acceptée d'atterrissage plus rapide de Guile reste en place.
- **Les commandes USF4 natives à charge sont restaurées pour tous les coups de Guile, y compris le Super et les deux Ultras.** Les anciens remplacements par mouvements et raccourcis sont supprimés.

### Guy

- **HP debout proche utilisé seul lance.** HP lointain et le HP de la chaîne Bushin ne reçoivent pas ce launcher au sol.
- **Le target combo MP → HP ne lance pas.** Sa dernière touche reçoit un **jump cancel en maintenant Haut, uniquement en touche**, menant au combo aérien. La garde ou le vide ne l'autorisent pas.
- **Kaiten Izuna Otoshi aérien L/M/H/EX est accessible pendant la poursuite, après les touches légères/moyennes et pendant la récupération**, avec capture compatible avec le juggle et fins de dégâts natives.
- Hozanto, Senpukyaku, les suites de frappe après course et les coudes Izuna gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Ibuki

- **HP accroupi lance**, avec ses entrées natives de jump cancel.
- **La projection aérienne, LP+LK, est accessible pendant la poursuite et les chaînes légères/moyennes.** Ses trois touches de dégâts peuvent connecter en juggle, avec dégâts et scaling natifs.
- **Kunai L/M/H/EX est accessible pendant les combos aériens et la récupération.** Les projectiles Kunai normaux/EX gagnent la possibilité de juggle, sans changer leurs réactions et angles natifs.
- Les spéciaux de frappe gagnent la possibilité de juggle.
- La récupération en touche ou dans le vide utilise son salto natif complet de saut avant.

### Juri

- **HP accroupi est le launcher**, y compris dans les routes correspondantes de Feng Shui Engine. HP debout proche retrouve son comportement au sol et ne donne pas de poursuite.
- **Shikusen L/M/H/EX est accessible pendant les combos aériens et la récupération**, avec ses commandes natives de suite.
- **Le dernier pied d'EX Shikusen retrouve son rebond mural natif.** La réaction murale native commune utilisée contre Ryu est réparée, afin que la cible suive la bonne animation de dégâts et la bonne trajectoire de rebond.
- **Toutes les fenêtres d'attaque initiales et de suite EX effacent le compteur de juggle précédent de l'adversaire**, permettant de poursuivre la séquence EX après de longs juggles. Ces fenêtres EX le remettent à zéro même dans le vide. Shikusen normal ne reçoit pas ces remises à zéro.
- Les projectiles Fuhajin ordinaires reçoivent des réactions aériennes de juggle continu ; les frappes de Senpusha et Shikusen gagnent la possibilité de juggle.
- La récupération en touche ou dans le vide utilise des saltos de type Cody.
- L'activation et les chaînes ordinaires natives de Feng Shui Engine sont conservées ; sa nouvelle poursuite suit les règles standard des chaînes aériennes.

### Ken

- **HP accroupi lance.**
- **HK debout proche repousse 20% moins en touche, récupère en 16 frames et donne +5 sur une touche ordinaire au sol.** Le bonus de contre est conservé.
- **MK debout proche repousse 25% moins en touche.**
- **MP debout proche, début du target combo, démarre en 4 frames.** Sa suite HP reste accessible.
- **Le Tatsu aérien utilise le déplacement et le timing de l'ancien jeu de base.** Dégâts, jauge et géométrie de touche natifs restent inchangés.
- Les normaux aériens ordinaires neutres/directionnels peuvent être **annulés en Tatsu aérien en touche ou en garde**. Tatsu aérien normal/EX est aussi accessible pendant la poursuite, les chaînes et la récupération aérienne des finishers forts.
- Hadoken normal/EX et Tatsu au sol/aérien gagnent la possibilité de juggle. **Shoryuken léger au sol conserve ses propriétés de juggle USF4 natives ; M/H/EX gardent leurs changements pré-alpha.**

### M. Bison

- **HP accroupi lance**, avec **6 frames de démarrage et +1 en garde**. Il peut être annulé en spécial en touche ou en garde.
- **Double Knee Press devient HCF+K. Psycho Crusher devient HCF+P.** Normal et EX acceptent aussi **bas-arrière → bas → bas-avant → avant** avec les boutons appropriés.
- **EX Head Press produit un rebond au sol plus haut.** Seul EX Head Press gagne cette hauteur ; Head Press ordinaire et les finishers forts communs gardent leurs réactions.
- **MP → MP, Hell Attack, est accessible en touche pendant la poursuite.** Sa suite peut mener à HP ou HK. Exemples : **MP → MP → HK**, **LP → MP → MP → HP**. Aucune boucle ou retour vers un normal plus faible n'est possible.
- Les zones de frappe de Knee Press, Psycho Crusher, Head Press, Skull Diver et Devil Reverse gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Makoto

- **HK accroupi est le launcher. HP accroupi conserve son balayage au sol.**
- **Tsurugi L/M/H/EX, l'axe kick aérien, est accessible pendant la poursuite, les chaînes aériennes et la récupération.**
- **EX Oroshi produit un rebond au sol.** Oroshi non-EX ne reçoit pas ce rebond.
- **HP accroupi peut être annulé en spécial ordinaire uniquement en touche**, dont Hayate, Oroshi, Fukiage et Karakusa. Aucune nouvelle annulation en garde ou dans le vide n'est ajoutée.
- **EX Fukiage conserve son lancement naturel et reçoit l'accès au combo aérien/Tsurugi via son jump cancel après une touche.**
- **Le jump cancel de Fukiage normal et l'accès aérien qui en découle exigent une touche.** Les directions de saut natives neutre, avant et arrière restent possibles.
- **Le démarrage de Fukiage fort passe de 13 à 11 frames.**
- Les familles de frappe Hayate, Oroshi, Fukiage et Tsurugi gagnent la possibilité de juggle.

### Oni

- **HP accroupi lance.**
- **Zanku Hadosho est accessible pendant la poursuite, après les touches aériennes légères/moyennes et pendant la récupération**, y compris ses variantes EX natives de boutons. Ses parties offensives utilisent des réactions aériennes de juggle continu.
- **Tatsu aérien L/M/H/EX et Messatsu-Gozanku, l'Ultra 1 aérien, sont accessibles pendant les combos aériens et la récupération**, sous réserve des exigences habituelles de jauge, hauteur et sélection d'Ultra.
- Les projectiles ordinaires Gohado/Gorai reçoivent des réactions aériennes de juggle continu ; les spéciaux de frappe et attaques de commande/target combo reçoivent les propriétés communes.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.
- Les Supers Raging Demon au sol et aériens propres à Oni gardent leur comportement natif.

### Poison

- **HK debout proche lance sur sa dernière touche.** La première et HK lointain gardent leurs réactions au sol.
- Les boules de feu normales et les spéciaux de frappe gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent son salto natif complet de saut avant.
- Love Storm reçoit la reprise commune d'Ultra ; Poison Kiss garde son comportement de prise.

### Rolento

- **HP debout proche lance.** HP lointain garde sa réaction au sol.
- MP aérien à plusieurs phases conserve ses deux parties de frappe natives dans le kit aérien standard.
- Les projectiles Stinger et les spéciaux de frappe gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent son salto avant natif complet. Ses routes natives de pogo et d'atterrissage acrobatique sont préservées.

### Rose

- **HP accroupi lance.**
- **Soul Throw M/H/EX conserve ses reprises après rebond au sol**, avec éligibilité correspondante pour la capture de combo et la fin de dégâts. **Soul Throw léger garde ses propriétés de juggle USF4 natives.** Soul Throw commence toujours au sol ; portée et conditions de capture natives s'appliquent.
- Soul Spark reçoit des réactions aériennes de juggle continu. Les parties de frappe de Soul Spiral et Soul Reflect gagnent la possibilité de juggle ; les données de capture de Reflect restent natives.
- Les finishers réussis et les attaques dans le vide utilisent une récupération en salto. **La récupération du finisher HP comprend le retour natif de l'écharpe**, corrigeant sa déformation des deux côtés.

### Rufus

- **HK debout proche lance.** HK lointain garde sa réaction au sol.
- **HP aérien produit un rebond au sol. HK aérien garde son juggle natif à deux touches**, sans rebond au sol ni mise à terre forcée ajoutés. Les deux forts terminent la chaîne normale ; HK finit sa deuxième touche avant la récupération.
- **Falcon Kick est accessible pendant la poursuite, après les touches aériennes légères/moyennes et pendant la récupération.** Ses touches aériennes maintiennent le juggle au lieu de provoquer un reset.
- Les zones de frappe de Galactic Tornado, Messiah et Snake Strike gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent le salto réparé, corrigeant l'étirement/la torsion du corps.

### Ryu

- **HP accroupi lance.**
- **Un HP debout unique utilise l'ancien HP proche aux deux distances**, avec **4 frames de démarrage**. Le HP lointain séparé est supprimé ; HP debout utilise une pression simple.
- **HK debout proche repousse 20% moins**, et ses deux touches peuvent être annulées en spéciaux ordinaires en touche ou en garde.
- **HK accroupi peut être annulé en spécial en touche ou en garde.** L'annulation en boule de feu en garde possède une fenêtre plus tardive que les autres annulations en spécial.
- Hadoken normal/EX et Tatsu au sol/aérien gagnent la possibilité de juggle. **Shoryuken léger au sol garde ses propriétés de juggle USF4 natives ; M/H/EX gardent leurs changements pré-alpha.**
- **Tatsu aérien avant L/M/H/EX est accessible pendant la poursuite et les routes aériennes.**
- **La vitesse d'EX Hadoken dépend des deux poings utilisés :**

| Boutons | Vitesse du projectile |
| --- | --- |
| LP+HP | Lente, identique au Hadoken LP ordinaire |
| LP+MP | Moyenne, identique au Hadoken MP ordinaire |
| MP+HP | Vitesse EX d'origine augmentée de 5% |

La réaction native de rebond mural de la victime de Ryu est restaurée à côté du système distinct de rebond au sol commun, corrigeant le conflit de réaction murale hérité.

### Sagat

- **MP debout proche lance.** MP lointain garde sa réaction au sol.
- Les Tiger Shot hauts/bas et les spéciaux de frappe gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.

### Sakura

- **HP accroupi lance**, avec ouverture de la poursuite dès sa première touche active pour une suite plus précoce.
- **La dernière touche du Tatsu EX au sol lance aussi vers une poursuite en maintenant Haut**, contre les cibles au sol ou aériennes.
- **Chaque touche infligeant des dégâts du Tatsu EX peut juggle**, en maintenant les réactions aériennes et son launcher final existant.
- **Tatsu aérien avant L/M/H/EX est accessible pendant la poursuite et les routes aériennes.**
- Tatsu au sol L/M/H/EX et les Hadoken ordinaires/chargés/EX gagnent la possibilité de juggle.
- **HK debout proche et lointain peuvent être annulés en spéciaux ordinaires en touche ou en garde**, avec **−1 en garde** comme cible configurée sur la première frame active.
- **Shouoken fort utilise le calendrier de démarrage de la version moyenne, visant 7 frames.** Sa séquence de touches et ses dégâts forts restent inchangés.

### Seth

- **HP accroupi lance à sa deuxième/dernière touche.** La première garde sa réaction au sol.
- **Bas+MK est accessible pendant la poursuite**, avec sa suite native de trois piétinements.
- **Bas+HK est accessible pendant la poursuite**, avec juggle aérien continu et hauteur minimale native. Bas+HK en saut ordinaire reste inchangé.
- Sonic Boom et les spéciaux de frappe gagnent la possibilité de juggle.
- La poursuite et la récupération en touche ou dans le vide utilisent son salto avant natif complet.

### T. Hawk

- **HK debout proche lance. HK debout lointain ne lance pas et ne donne pas de poursuite.**
- Pendant les combos aériens, **PPP active Condor Dive normal ; KKK active EX Condor Dive**. Hauteur et jauge natives s'appliquent. La suite EX PPP d'origine depuis EX Tomahawk reste sur sa route native.
- **Tomahawk Buster retrouve les données USF4 standard**, dont les nombres de touches propres à chaque puissance, le timing et les paramètres de juggle.
- **L'Ultra 2, Raging Slash, peut capturer un adversaire aérien après rebond au sol**, avec capture et touches de dégâts compatibles. L'Ultra 1 et les autres prises de commande restent natifs.
- Les autres spéciaux de frappe gardent leur possibilité de juggle ajoutée.
- Les finishers réussis et les attaques dans le vide utilisent une récupération en salto.

### Vega

- **HK debout proche lance à sa deuxième touche.** La première et HK lointain gardent leurs réactions au sol.
- Les combos aériens prennent en charge les zones de poing avec ou sans griffe.
- **Les frappes de Flying Barcelona Attack L/M/H/EX gagnent la possibilité de juggle et des réactions aériennes continues**, pour les deux murs et les deux états de griffe. Les frappes de décollage EX reçoivent une tolérance supplémentaire.
- **Izuna Drop peut capturer et blesser les cibles aériennes en juggle**, avec conservation des routes de capture normales et EX correspondantes.
- **La projection aérienne est accessible pendant la poursuite et la récupération aérienne.** Sa fin de dégâts propre au combo est corrigée pour qu'une capture en juggle inflige des dégâts, avec dégâts de base et scaling natifs.
- Les finishers réussis et les attaques dans le vide utilisent une récupération en salto.

### Yang

- **HP debout proche lance uniquement à sa deuxième touche.** La première garde sa réaction au sol.
- **MK debout proche garde son lancement naturel et reçoit la poursuite en maintenant Haut.**
- **Les dive kicks L/M/H sont accessibles pendant la poursuite et maintiennent un juggle aérien au lieu d'un reset.**
- Le kit aérien et les règles de launcher couvrent aussi les **variantes Seiei Enbu**, en conservant les règles natives d'activation et d'effets.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody.
- **L'interruption de cinématique de l'Ultra 2 est corrigée**, évitant que l'adversaire disparaisse puis réapparaisse suspendu au-dessus de l'écran. Les vraies touches de frappe d'Ultra gardent la reprise commune.

### Yun

- **HP debout proche lance uniquement à sa deuxième/dernière touche.** La première garde sa réaction au sol.
- **MK debout proche garde son lancement naturel et reçoit la poursuite en maintenant Haut.**
- **Les dive kicks L/M/H sont accessibles pendant les combos aériens et maintiennent un juggle aérien au lieu d'un reset.**
- Les changements de launcher, combo aérien et dive kick couvrent aussi les **variantes Genei Jin**, en gardant leurs dégâts renforcés et timings de Super natifs.
- Les spéciaux de frappe gagnent la possibilité de juggle.
- Les finishers réussis et les attaques dans le vide utilisent la récupération en salto de type Cody en état normal et Genei Jin.

### Zangief

- **HK debout proche lance.** HK lointain garde sa réaction au sol et ne dispose pas d'annulation de poursuite.
- **L'Ultra 2, Siberian Blizzard, est accessible pendant les combos aériens et peut capturer après rebond au sol**, avec capture et touches de dégâts compatibles.
- **EX Spinning Piledriver peut capturer un adversaire aérien après rebond au sol**, en gardant sa prise au sol d'origine et sa séquence native de dégâts/libération. **SPD L/M/H ne reçoit pas la capture aérienne.**
- **Double Lariat et Quick Double Lariat retrouvent leurs actions et leur juggle USF4 d'origine.**
- Les autres spéciaux de frappe gardent la possibilité de juggle commune.
- La récupération en touche ou dans le vide utilise une rotation native complète de Zangief, corrigeant les anciennes déformations du torse et des jambes.

## Lanceur et installation

Le lanceur téléchargeable affiche **USF4 TAG! pre-alpha v0.1**. Sa **révision 6** installe le **build 105** accepté et configure automatiquement la version testée de Simp. Il réutilise une copie installée identique ou la télécharge et la vérifie ; une connexion est nécessaire si Simp manque. L'échec de démarrage après Simp est corrigé ; la fenêtre **Patching complete** a été confirmée lors d'un chargement réel.

1. Choisissez le dossier Steam USF4 et cliquez sur **Install Pre-Alpha**. Les installations appartenant au lanceur peuvent être mises à jour.
2. Cliquez sur **Launch USF4** et attendez au **menu principal** du jeu.
3. Revenez au lanceur et cliquez sur **Load Pre-Alpha**.
4. Dans Simp, sélectionnez **tag_pre_v0100** puis **Launch**.
5. Attendez **Patching complete**, puis revenez au jeu et entrez en **Training Ultra standard**.

La fenêtre confirme la fin du patch et le démarrage de la règle d'étourdissement Training. Gardez le lanceur ouvert jusque-là. Quittez normalement USF4 et Simp avant installation, mise à jour, réparation ou suppression. Les fichiers originaux et sauvegardes sont conservés ; les mises à jour gérées gardent l'ancien build dans un dossier de récupération. Pour jouer sans mod, lancez une nouvelle session Steam avec Simp fermé.

Le menu **Manage** comprend :

- **Check for updates :** recherche un installateur plus récent publié sur GitHub ; si vous acceptez la mise à jour, il le télécharge, le vérifie et l'installe.
- **Open logs :** ouvre les détails locaux des opérations et les rapports d'erreur.
- **Report a bug :** permet de décrire le problème et de vérifier un court aperçu du diagnostic, puis ouvre une issue GitHub préremplie à relire et envoyer. Aucun journal ou fichier brut n'est téléversé automatiquement.
- **Verify installation, Repair installation et Remove Pre-Alpha :** entretiennent l'installation gérée en préservant les fichiers étrangers ou modifiés.

## Tests et portée

Le build de combat 105 a été accepté après tests locaux par personnage. Le chargement réel de la révision 5 a confirmé la fenêtre de fin et le démarrage de la règle d'étourdissement Training. La révision publique 6 conserve ce runtime et ajoute l'acquisition automatique vérifiée de Simp. Ce contrôle de démarrage ne constitue pas un nouveau test de gameplay de tout le roster ni une validation de la règle d'étourdissement dans les autres modes.

Les tests indépendants d'installation sur une deuxième machine et la couverture exhaustive des matchups restent à terminer. Le minimum de dégâts d'Ultra précédemment envisagé n'est pas implémenté.
