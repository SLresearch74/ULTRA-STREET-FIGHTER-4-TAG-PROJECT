# USF4 TAG Project — Pre-Alpha Roster Changes

[Other languages / Traductions / Übersetzungen / 翻译 / 翻訳 / 번역](docs/README.md)

**Pre-alpha v0.1 · Version 0.1.0 · Accepted combat build 105 · Launcher revision 6 · 42 supported characters · Updated 28 October 2026**

This changelog covers the completed combat pre-alpha. Select **standard Ultra** characters. **Hugo and Hakan are deferred.** This version uses ordinary single-character matches and the stock HUD; team/tag gameplay remains separate.

## Notation

- **LP / MP / HP:** light / medium / heavy punch.
- **LK / MK / HK:** light / medium / heavy kick.
- **Close / far:** the normal selected by distance from the opponent.
- **QCF:** quarter-circle forward. **QCB:** quarter-circle back. **HCF:** half-circle forward.
- **2× QCF / 2× HCF:** perform the motion twice.
- **PPP / KKK:** all three punches / all three kicks together.
- Directions are relative to the direction your character faces.

Frame values below describe the build's balance settings and targets. Not every startup or advantage value has been independently measured in game. Existing meter costs, height requirements, range and motion requirements apply unless a change is listed.

## Shared combat system

### Launchers and pursuit

Each supported character has at least one launcher. **Hit with the launcher and hold Up to follow the opponent into the air.** Pursuit requires a successful hit. For a multi-hit launcher, the table below identifies the hit that opens pursuit.

### Standard air combos

The new normal chains are accessed through launcher pursuit. Ordinary jumping attacks keep their native routes apart from the character-specific changes below.

- Air chains progress **light → medium → heavy**. Choose punch or kick at each strength.
- Strengths may be skipped. **Only LP, LK, MP or MK can start the pursuit normal chain; HP/HK cannot start it.** Heavy finishers remain available after a light or medium.
- Each strength is used at most once. Same-strength links and returns to weaker normals are excluded from the standard route.
- Examples: **LP → MP → HP**, **LK → MK → HK**, **LP → MK → HP**, **MP → HK**.
- **HP or HK normally ends the normal chain with a downward slam and floor bounce.** Rufus, Chun-Li, Gen and Elena have the finisher details listed in their sections.
- Added air specials, command normals, throws and Ultras use the character-specific routes below. Access to a special during recovery does not restart the normal chain.

**Gen has his own light/medium chain variation.** The rest of the roster uses the standard rules, subject to the explicitly listed target-combo and multi-hit follow-ups. The light/medium opening rule also applies to both Gen stances and Makoto's Fukiage jump-cancel entrances. Character-specific access to air specials, throws and command normals is retained.

### Juggles, floor bounce and recovery

- Medium/heavy ground normals gain the shared airborne juggle reaction. **Ordinary grounded and jumping LP/LK retain their native USF4 juggle properties and reactions.** LP/LK inside launcher-pursuit air combos keep their working juggle reactions so air chains continue.
- The listed strike specials and projectiles gain increased juggle eligibility. Increased eligibility does not automatically change a move's native reaction into a float; specific reaction changes are listed below.
- Heavy air finishers produce a floor bounce for continued ground follow-ups. If no follow-up connects, the opponent returns through knockdown/recovery.
- Air-combo recovery uses a forward somersault or a suitable native flip. Character-specific animation corrections apply to successful finishers and whiffs where listed.
- Supported characters use their own **Omega forward-dash behavior**, adapted to their standard move sets. **Dhalsim keeps his standard USF4 forward dash.** This does not turn the characters into their full Omega versions.

### Light-special exceptions

**Grounded light specials using the forward Dragon Punch motion retain native USF4 juggle properties and reactions.** This applies to both LP and LK versions, including the game's accepted shortcuts for forward → down → down-forward. It follows the input family, rather than only moves named Shoryuken: examples include light Cannon Spike, Seismic Hammer, Fukiage, Soul Throw, Banishing Flat and Tiger Knee. Reverse-DP moves are outside this change.

Medium/heavy/EX versions retain their listed pre-alpha behavior. **Light air specials are unaffected by this rollback.** Light fireballs and other light specials outside the grounded forward-DP family also retain their listed changes.

### Stun during launcher combos

**Positive stun damage is halved from the actual launcher hit until that combo ends**, including continuing air, floor-bounce and ground follow-ups. Health damage is unchanged. A new separate combo uses the normal stun rate until another launcher connects; whiffing or blocking a launcher does not trigger this rule. Native rounding and the one-point stun minimum remain.

For multi-hit launchers, the reduction begins on the launching hit; earlier nonlaunching hits keep their normal stun scaling.

The extra stun rule currently applies only in **offline standard Ultra Training**. The launcher enables it automatically after Simp finishes; wait for **Patching complete** before entering Training. No separate stun button is required. Other modes do not receive this session rule; broader match-mode support remains future work.

### Ultras after floor bounce

Strike and projectile Ultras gain airborne pickup eligibility so they can connect after floor bounce. Native range, timing, height and cinematic conditions still matter. These changes preserve damage and damage scaling.

Grab/capture Ultras, counters and nonattacking installs or healing retain their existing behavior, with two requested exceptions: **T. Hawk's Ultra 2** and **Zangief's Ultra 2** gain floor-bounce pickups.

The increased allowances are finite. The two added moves that explicitly clear the opponent's prior juggle count are **Evil Ryu's air Raging Demon** and **Juri's EX Shikusen**. Their individual sections explain those changes.

## Launcher quick reference

Click a character's name for the full changes.

| Character | Launcher / pursuit starter |
| --- | --- |
| [Abel](#abel) | Crouching HP — second hit |
| [Adon](#adon) | Close standing HK |
| [Akuma](#akuma) | Crouching HP |
| [Balrog](#balrog) | Crouching HP |
| [Blanka](#blanka) | Close standing HP |
| [C. Viper](#c-viper) | Close standing HK — second hit |
| [Cammy](#cammy) | Close standing HK |
| [Chun-Li](#chun-li) | Close standing HK |
| [Cody](#cody) | Crouching HP — unarmed and knife stances |
| [Dan](#dan) | Crouching HP |
| [Decapre](#decapre) | Close standing HK |
| [Dee Jay](#dee-jay) | Standing HP — former far HP, available at either distance |
| [Dhalsim](#dhalsim) | Back+HK — his short standing normal |
| [Dudley](#dudley) | Crouching HP |
| [E. Honda](#e-honda) | Close standing HP |
| [El Fuerte](#el-fuerte) | Crouching HP |
| [Elena](#elena) | Standing HP |
| [Evil Ryu](#evil-ryu) | Crouching HP |
| [Fei Long](#fei-long) | Close standing HK |
| [Gen](#gen) | Mantis standing HP — final hit; Crane standing HP — second hit; Crane crouching HK |
| [Gouken](#gouken) | Crouching MK |
| [Guile](#guile) | Crouching HP |
| [Guy](#guy) | Standalone close standing HP; MP → HP gains a hit-only jump cancel without launching |
| [Ibuki](#ibuki) | Crouching HP |
| [Juri](#juri) | Crouching HP, including Feng Shui Engine routes |
| [Ken](#ken) | Crouching HP |
| [M. Bison](#m-bison) | Crouching HP |
| [Makoto](#makoto) | Crouching HK; normal/EX Fukiage can lead to air combos through their jump cancels |
| [Oni](#oni) | Crouching HP |
| [Poison](#poison) | Close standing HK — final hit |
| [Rolento](#rolento) | Close standing HP |
| [Rose](#rose) | Crouching HP |
| [Rufus](#rufus) | Close standing HK |
| [Ryu](#ryu) | Crouching HP |
| [Sagat](#sagat) | Close standing MP |
| [Sakura](#sakura) | Crouching HP; EX Tatsu's finishing hit also launches into pursuit |
| [Seth](#seth) | Crouching HP — second/final hit |
| [T. Hawk](#t-hawk) | Close standing HK only |
| [Vega](#vega) | Close standing HK — second hit |
| [Yang](#yang) | Close standing HP — second hit; close standing MK retains its natural launch and gains pursuit |
| [Yun](#yun) | Close standing HP — second/final hit; close standing MK retains its natural launch and gains pursuit |
| [Zangief](#zangief) | Close standing HK only |

## Character changes

All characters below receive the shared combat system. These sections identify their launchers, additional move changes and exceptions. **The shared ordinary-light-normal and grounded-light-DP exceptions apply to every character's general juggle lists below.**

### Abel

- **Crouching HP launches on its second hit.** The first hit keeps its normal grounded reaction.
- Change of Direction, Wheel Kick and Falling Sky strike hitboxes gain juggle eligibility.
- Successful air finishers and whiff recovery use the Cody-style forward somersault.
- Crouching HP's second hit uses the shared short-fall juggle reaction against an already-airborne opponent.

### Adon

- **Close standing HK launches.** Far standing HK keeps its grounded behavior.
- **L/M/H/EX airborne Jaguar Kick** is available during pursuit, after light/medium air hits and during air-combo recovery.
- Airborne Jaguar Kick uses a continuous juggle reaction against airborne opponents instead of an air reset.
- Jaguar Kick, Jaguar Tooth and Rising Jaguar strike variants gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.

### Akuma

- **Crouching HP launches.**
- **L/M/H/EX air fireball and air Tatsu** are available during pursuit, air chains and airborne recovery, retaining their normal inputs and restrictions.
- **Former far standing HK becomes forward+HK**, usable at either distance. Plain standing HK uses the former close HK at either distance.
- Forward+MP, dive kick, Tatsu, M/H/EX Shoryuken, Demon Flip strikes and ordinary fireball variants gain juggle eligibility. **Grounded light Shoryuken retains its native USF4 juggle properties.**
- Pursuit and recovery use Akuma's native forward-jump animation.

### Balrog

- **Crouching HP launches**, including the active updated version.
- Dash punches and uppercuts, their overhead/low variants, Buffalo Head and Turn Punch strike variants gain juggle eligibility.
- Air-combo heavy finishers and whiffs use Cody-style somersault recovery, adapted for his gloves and rig.
- Violent Buffalo gains the shared Ultra pickup allowance; Dirty Bull retains its grab behavior.

### Blanka

- **Close standing HP launches.** Far HP keeps its grounded reaction.
- **Electric Thunder accepts either five punch presses or QCF+P.** QCF+two punches selects EX.
- **All Electric Thunder versions keep stock USF4 juggle behavior**, including continued pulses and EX variants. The shared enhanced juggle allowance was removed from electricity.
- Rolling and vertical-ball strike variants retain the added juggle eligibility.
- Successful finishers and whiffs use somersault recovery.

### C. Viper

- **Close standing HK launches on its second hit.** The first hit and far standing HK keep their grounded reactions.
- **L/M/H/EX airborne Burning Kick** is available during pursuit and recovery.
- **Ultra 2, Burning Dance, is available during air combos**, subject to its native command, meter, height and Ultra-selection requirements.
- **M/H/EX Seismic Hammer gain airborne juggle eligibility**, enabling juggle and floor-bounce follow-ups at their normal range. **Light Seismic Hammer retains its native USF4 juggle properties.**
- Hit and whiff recovery use her complete native forward somersault.

### Cammy

- **Close standing HK launches.** Far HK keeps its grounded reaction.
- **Air throw, LP+LK, is available during pursuit and after light/medium air hits**, with juggle-compatible capture and damage.
- **M/H/EX Cannon Spike gain increased juggle eligibility. Light Cannon Spike retains its native USF4 juggle properties.** These changes do not add an airborne Cannon Spike input.
- **L/M/H/EX Cannon Strike is available during air combos and airborne recovery.** Air hits use a continuous juggle reaction instead of an air reset.
- Spiral Arrow, Quick Spin Knuckle and Hooligan slide strike hitboxes gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.

### Chun-Li

- **Close standing HK launches.** Far HK keeps its grounded reaction.
- **Air throw is available during pursuit**, with both capture and damage adapted for juggled opponents.
- **Yosokyaku is available during air combos**, retaining its native down/down-forward+MK inputs and three-stomp follow-ups.
- **Hyakuretsukyaku accepts QCF+K or five quick kick presses.** Existing mash continuation and EX meter rules remain.
- **Air HP → HP causes floor bounce on the second punch only.** The first keeps the opponent airborne. If the second punch is not entered, the first recovers without a floor bounce. HP cannot link into HK or weaker normals.
- **L/M/H/EX Hazanshu causes the shared airborne juggle reaction**, retaining its grounded reactions.
- Kikouken projectiles gain juggle eligibility.
- Hit and whiff recovery use the corrected Cody-style somersault.

### Cody

- **Crouching HP launches in both unarmed and knife stances.** Knife punches retain their own animations and air-combo routes; kick routes work in either stance.
- **Criminal Upper, all strengths and EX, can FADC from any connected hit**, including later tornado hits. Hit or block contact is required.
- **HP Criminal Upper recovery: 23 frames.** **EX Criminal Upper recovery: 25 frames.**
- **HK Ruffian Kick recovery: 25 frames**, reduced from 27.
- **LK/MK/HK Super recovery: 22 frames**, including successful-hit follow-up branches.
- Criminal Upper, Bad Stone and knife-throw projectiles, plus striking specials, gain juggle eligibility.
- Successful heavy finishers and air-combo whiffs use the forward somersault, including knife punch routes.

### Dan

- **Crouching HP launches.** Dan uses the standard air-chain rules.
- **L/M/H/EX air Dankukyaku and the native air taunt are available during air combos and recovery.**
- **Air taunt keeps its stock hit and juggle properties.** No enhanced juggle allowance is added to the taunts.
- L/M/H/EX Gadoken and Dankukyaku gain juggle eligibility. **M/H/EX Koryuken retain the pre-alpha juggle changes; grounded light Koryuken retains its native USF4 juggle properties.**
- Successful finishers and whiffs use Cody-style somersault recovery.

### Decapre

- **Close standing HK launches.** Far HK keeps its grounded reaction.
- **Air throw is available during pursuit and airborne recovery**, with juggle-compatible capture and damage. Native base damage and combo scaling are retained.
- **Rapid Dagger accepts QCF+P or the original five punch presses**, including the native EX strength and meter selection.
- **L/M/H/EX air Spiral Arrow is available during pursuit, air chains and recovery**, retaining its native command and height requirements.
- Recovery uses her native forward-jump somersault, correcting the earlier hit-pose recovery.

### Dee Jay

- **Plain standing HP performs the former far HP at either distance.** It is the launcher, has **7-frame startup**, and gains special cancels on hit or block.
- **Back+HP performs the former close standing HP at either distance.** It keeps its native grounded reaction and existing cancels.
- **Double Rolling Sobat uses QCF+K**, including EX.
- **Light Double Rolling Sobat uses its AE2012 action and hit data**, including low-invulnerability and block behavior, together with the new QCF input and juggle eligibility.
- **Knee Shot, down+LK, is available during pursuit and after an air normal completes.** It causes a continuous airborne juggle instead of an air reset.
- Knee Shot is **not a direct chain cancel** from air normals and does not reopen the normal chain. Immediate heavy-contact recovery does not add a Knee Shot cancel.
- Air Slasher projectiles and Machinegun Upper, Sobat and Jackknife Maximum strike hitboxes gain juggle eligibility.

### Dhalsim

- **Back+HK, his short standing normal, launches.** Ordinary stretching standing HK keeps its grounded reaction.
- Pursuit air chains use his short aerial normals with normal punch/kick inputs; Back does not need to be held for those air buttons.
- **Yoga Spear's three angles and Yoga Mummy are available during pursuit and recovery**, using their native commands: down+kick and down+HP respectively.
- Fireballs and striking specials gain juggle eligibility.
- **Forward dash is restored to standard USF4**, including its movement, animation and cancel timing.
- Hit and whiff recovery use one complete native Dhalsim somersault pose, correcting leg/foot warping.

### Dudley

- **Crouching HP launches.**
- Grounded command normals and target-combo attacks gain the shared airborne juggle reaction.
- Machinegun Blow, Jet Upper, Short Swing Blow, Ducking strike follow-ups, Thunderbolt and Cross Counter's strike portions gain juggle eligibility.
- Air combos use Dudley's own forward-jump attacks and native recovery animation. Rose projectiles keep their stock behavior.

### E. Honda

- **Close standing HP launches**, with **6-frame startup instead of 8**, and gains special cancels on hit or block. Far HP keeps its grounded reaction.
- **EX Sumo Smash causes floor bounce on its final descending hit only.** The rising hit and non-EX versions retain their normal reactions.
- **Hundred Hand Slap accepts five quick punch presses or QCF+P.** Native mash continuations are restored alongside the motion input; EX retains its punch-button selection.
- Striking specials gain the shared juggle eligibility. Existing Headbutt, Sumo Smash, Super and Ultra inputs retain their native requirements.

### El Fuerte

- **Crouching HP launches.**
- **Air throw, LP+LK, is available during pursuit, light/medium chains and recovery.** Its capture and both damage paths can connect during a juggle, retaining native base damage and scaling.
- Striking specials gain juggle eligibility; native run and wall-jump routes remain intact.
- Hit and whiff recovery use his complete native forward-jump somersault.
- Both grab Ultras keep their native capture behavior under the general Ultra exception.

### Elena

- **Standing HP launches**, without a close/far HP split.
- All six air normals are available in pursuit, including the corrected private air-input eligibility.
- **Air HK keeps both hits; only its last hit causes floor bounce.** HP also supplies a floor-bounce finisher.
- Hit and whiff recovery use a native flip from her Mallet Smash animation, retaining her own rig.
- Striking specials gain juggle eligibility. Brave Dance gains the shared Ultra pickup allowance; Healing stays native.

### Evil Ryu

- **Crouching HP launches**, with **5-frame startup** as the final timing target. Standing HP keeps its grounded reaction and does not gain pursuit.
- **Forward+MK gains a continuous airborne juggle reaction.**
- **All Ryusokyaku axe kicks gain juggle eligibility. EX axe kick causes floor bounce**, on the finishing hit where the action has multiple hits.
- Hadoken, Shakunetsu, grounded/air Tatsu and M/H/EX Shoryuken gain juggle eligibility. **Grounded light Shoryuken retains its native USF4 juggle properties.**
- **L/M/H/EX air Tatsu is available during pursuit and air-combo routes.**
- **Air Raging Demon is added using Oni's native move sequence.** With full Super meter, enter **LP, LP, forward, LK, HP** while airborne. Ordinary jumping-normal cancel access supports activation.
- Air Demon activation audio is corrected to use Evil Ryu's appropriate voice/effect sounds.
- **Air Demon clears the opponent's prior juggle count during its grab window**, allowing it after extended juggles. The reset also runs during an unsuccessful attempt; native range, airborne eligibility and invulnerability still apply.

### Fei Long

- **Close standing HK launches.** Far HK keeps its grounded reaction.
- Rekka, Shienkyaku and Rekkukyaku strike hitboxes gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.
- Rekkashingeki gains the shared Ultra pickup allowance; Gekirinken retains its counter behavior.

### Gen

- **Mantis standing HP launches on its final hit.**
- **Crane standing HP launches on its second hit. Crane crouching HK also launches.**
- Both close and far standing HP versions, and the corresponding target-combo HP copies, follow their stance's final-hit rule.
- Both stances have their own air-combo attacks and pursuit routes.
- **Gen alone may use both punch and kick within the light and medium tiers, in either order.** Each normal may be used once. Strengths may be skipped, but moving to a stronger tier closes the weaker tiers.
- **Either HP or HK ends the chain. HP → HK and HK → HP are blocked.**
- Examples: **LP → LK → MP → MK → HK**, **LK → LP → MK → MP → HP**, **LP → MK → HP**. Medium → light and heavy → medium/light are not allowed.
- **Crane's two-hit air HK causes floor bounce on its second hit only.**
- **Hyakurenko accepts five quick punch presses or QCF+P**, including native mash continuations. EX retains its punch-button selection.
- Striking specials gain juggle eligibility. Hit and whiff recovery use Cody-style somersaults in both stances.

### Gouken

- **Crouching MK launches.**
- **L/M/H/EX air Tatsu is available during pursuit and recovery.**
- **Every pursuit Tatsu travels forward toward the opponent and has one damaging hit window per activation.** Ordinary jumping Tatsu keeps its native multi-hit actions and inputs.
- Ordinary Hadokens and striking specials gain juggle eligibility.
- Recovery uses his complete native forward somersault.

### Guile

- **Crouching HP launches.**
- **Far standing HP, far standing HK and crouching HP gain ordinary-special cancels on hit or block.**
- Normal and EX Sonic Boom projectiles gain juggle eligibility.
- **Forward and backward air-throw inputs are available during pursuit**, using LP+LK, with Back selecting the backward throw.
- **Pursuit air throws use native victim reactions and no added floor bounce.** Guile retains the accepted faster attacker landing route.
- **Native USF4 charge commands are restored for all of Guile's moves, including Super and both Ultras.** The earlier motion replacements and shortcuts are removed.

### Guy

- **Standalone close standing HP launches.** Far HP and the Bushin-chain HP do not gain the grounded launcher.
- **MP → HP target combo does not launch.** Its last hit gains a **hit-only held-Up jump cancel**, leading into the air-combo route. Block or whiff does not enable this new jump cancel.
- **L/M/H/EX air Kaiten Izuna Otoshi is available during pursuit, after light/medium hits and during recovery**, with juggle-compatible capture and native damage finishes.
- Hozanto, Senpukyaku, run follow-up strikes and Izuna elbow strikes gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.

### Ibuki

- **Crouching HP launches**, retaining its native jump-cancel entries.
- **Air throw, LP+LK, is available during pursuit and light/medium chains.** All three damage hits can connect during a juggle, retaining native damage and scaling.
- **L/M/H/EX Kunai is available during air combos and recovery.** Normal/EX Kunai projectiles gain juggle eligibility, retaining their native reactions and angles.
- Striking specials gain juggle eligibility.
- Hit and whiff recovery use her complete native forward-jump somersault.

### Juri

- **Crouching HP is the launcher**, including the corresponding Feng Shui Engine routes. Close standing HP is restored to its grounded behavior and does not gain pursuit.
- **L/M/H/EX Shikusen is available during air combos and recovery**, retaining its native follow-up inputs.
- **EX Shikusen's final kick restores its native wall bounce.** The shared native wall reaction used against Ryu is repaired, so the opponent follows the correct damage animation and wall-rebound route.
- **All EX starting and follow-up attack windows clear the opponent's prior juggle count**, allowing the EX sequence to continue after extended juggles. The resets also run if those EX attack windows whiff. Normal Shikusen does not gain these resets.
- Ordinary Fuhajin projectiles gain continuous airborne juggle reactions; Senpusha and Shikusen strikes gain juggle eligibility.
- Hit and whiff recovery use Cody-style somersaults.
- Feng Shui Engine's native install and ordinary chain rules remain; its new pursuit route uses the standard air-chain rules.

### Ken

- **Crouching HP launches.**
- **Close standing HK has 20% less pushback on hit, 16-frame recovery and +5 on a normal grounded hit.** Its counter-hit bonus is retained.
- **Close standing MK has 25% less pushback on hit.**
- **Close standing MP, the target-combo opener, has 4-frame startup.** Its HP follow-up remains available.
- **Air Tatsu uses the older base-game movement and timing.** Native damage, meter and hit geometry are retained.
- Ordinary neutral/directional air normals gain **air-Tatsu cancels on hit or block**. Normal/EX air Tatsu is also available during pursuit, air chains and airborne heavy-finisher recovery.
- Normal/EX Hadoken and grounded/air Tatsu gain juggle eligibility. **Grounded light Shoryuken retains its native USF4 juggle properties; M/H/EX retain their pre-alpha juggle changes.**

### M. Bison

- **Crouching HP launches**, with **6-frame startup and +1 on block**. It gains special cancels on hit or block.
- **Double Knee Press changes to HCF+K. Psycho Crusher changes to HCF+P.** Normal and EX versions also accept **down-back → down → down-forward → forward** with the appropriate buttons.
- **EX Head Press causes floor bounce with a higher rebound.** Only EX Head Press receives this increased rebound height; ordinary Head Press and the shared heavy finishers keep their existing reactions.
- **MP → MP, Hell Attack, is available on hit during pursuit.** Its follow-up can lead to HP or HK. Examples: **MP → MP → HK**, **LP → MP → MP → HP**. It cannot loop or return to weaker normals.
- Knee Press, Psycho Crusher, Head Press, Skull Diver and Devil Reverse strike hitboxes gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.

### Makoto

- **Crouching HK is the launcher. Crouching HP keeps its grounded sweep.**
- **L/M/H/EX Tsurugi, the air axe kick, is available during pursuit, air chains and recovery.**
- **EX Oroshi causes floor bounce.** Non-EX Oroshi does not gain this bounce.
- **Crouching HP gains ordinary-special cancels on hit only**, including Hayate, Oroshi, Fukiage and Karakusa. No new block or whiff cancel is added.
- **EX Fukiage retains its natural launch and gains air-combo/Tsurugi access through its jump cancel after a hit.**
- **Normal Fukiage's jump cancel and resulting air-combo access require a hit.** Native neutral, forward and backward jump directions remain available.
- **Heavy Fukiage startup changes from 13 to 11 frames.**
- Hayate, Oroshi, Fukiage and Tsurugi strike families gain juggle eligibility.

### Oni

- **Crouching HP launches.**
- **Zanku Hadosho is available during pursuit, after light/medium air hits and during recovery**, including native EX button variants. Its attacking portions use continuous airborne juggle reactions.
- **L/M/H/EX air Tatsu and Messatsu-Gozanku, airborne Ultra 1, are available during air combos and recovery**, subject to normal meter, height and Ultra-selection requirements.
- Ordinary Gohado/Gorai projectiles gain continuous airborne juggle reactions; striking specials and command/target-combo attacks gain the shared juggle properties.
- Successful finishers and whiffs use Cody-style somersault recovery.
- Oni's own ground and air Raging Demon Supers retain their native behavior.

### Poison

- **Close standing HK launches on its final hit.** The first hit and far HK keep their grounded reactions.
- Normal fireballs and striking specials gain juggle eligibility.
- Successful finishers and whiffs use her complete native forward-jump somersault.
- Love Storm gains the shared Ultra pickup allowance; Poison Kiss retains its grab behavior.

### Rolento

- **Close standing HP launches.** Far HP keeps its grounded reaction.
- Multi-phase air MP retains both native hit portions in the standard air-combo kit.
- Stinger projectiles and striking specials gain juggle eligibility.
- Successful finishers and whiffs use his complete native forward somersault. Native pogo and trick-landing routes remain intact.

### Rose

- **Crouching HP launches.**
- **M/H/EX Soul Throw retain their floor-bounce pickup changes**, including matching eligibility on the combo capture and damage finish. **Light Soul Throw retains its native USF4 juggle properties.** Soul Throw still starts from the ground; native range and capture conditions apply.
- Soul Spark projectiles gain continuous airborne juggle reactions. Soul Spiral and Soul Reflect's strike portions gain juggle eligibility; Reflect's capture records remain native.
- Successful finishers and whiffs use somersault recovery. **HP-finisher recovery includes the native scarf-return animation**, correcting scarf distortion on both sides.

### Rufus

- **Close standing HK launches.** Far HK keeps its grounded reaction.
- **Air HP causes floor bounce. Air HK keeps its native two-hit airborne juggle**, without the added floor-bounce/forced-knockdown reaction. Both heavies end the normal chain, and HK completes its second hit before recovery.
- **Falcon Kick is available during pursuit, after light/medium air hits and during recovery.** Its airborne hits use a continuous juggle instead of an air reset.
- Galactic Tornado, Messiah and Snake Strike hitboxes gain juggle eligibility.
- Successful finishers and whiffs use the repaired somersault, correcting the earlier body stretching/twisting.

### Ryu

- **Crouching HP launches.**
- **One unrestricted standing HP uses the former close HP at either distance**, with **4-frame startup**. The separate far HP is removed; standing HP uses a single-button input.
- **Close standing HK has 20% less pushback**, and both hits can cancel into ordinary specials on hit or block.
- **Crouching HK can special cancel on hit or block.** Its fireball block-cancel route uses a later window than the other special cancels.
- Normal/EX Hadoken and grounded/air Tatsu gain juggle eligibility. **Grounded light Shoryuken retains its native USF4 juggle properties; M/H/EX retain their pre-alpha juggle changes.**
- **L/M/H/EX forward air Tatsu is available during pursuit and air-combo routes.**
- **EX Hadoken speed depends on the two-punch combination:**

| Buttons | Projectile speed |
| --- | --- |
| LP+HP | Slow, matching ordinary LP Hadoken |
| LP+MP | Medium, matching ordinary MP Hadoken |
| MP+HP | Original EX speed increased by 5% |

Ryu's native wall-bounce victim reaction is restored alongside the separate shared floor-bounce system, correcting the inherited wall-reaction conflict.

### Sagat

- **Close standing MP launches.** Far MP keeps its grounded reaction.
- High and low Tiger Shot projectiles and striking specials gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery.

### Sakura

- **Crouching HP launches**, with the pursuit gate opening from its first active hit for an earlier follow-up.
- **Grounded EX Tatsu's finishing hit also launches into held-Up pursuit**, against grounded or airborne opponents.
- **Every damaging EX Tatsu hit can juggle**, with continuing airborne reactions and its existing final launcher retained.
- **L/M/H/EX forward air Tatsu is available during pursuit and air-combo routes.**
- L/M/H/EX grounded Tatsu and ordinary/charged/EX Hadoken projectiles gain juggle eligibility.
- **Close and far standing HK gain ordinary-special cancels on hit or block**, with **−1 on block** as the configured first-active-hit target.
- **Heavy Shouoken uses the medium version's startup schedule, targeting 7-frame startup.** Its heavy-version hit sequence and damage remain.

### Seth

- **Crouching HP launches on its second/final hit.** The first hit keeps its grounded reaction.
- **Down+MK is available during pursuit**, retaining the native three-stomp follow-up sequence.
- **Down+HK is available during pursuit** with a continuous airborne juggle reaction and its native minimum-height requirement. Ordinary jumping down+HK remains unchanged.
- Sonic Booms and striking specials gain juggle eligibility.
- Pursuit and hit/whiff recovery use his complete native forward somersault.

### T. Hawk

- **Close standing HK launches. Far standing HK does not launch or gain pursuit.**
- During air combos, **PPP activates normal Condor Dive; KKK activates EX Condor Dive**. Native height and meter requirements apply. The original EX PPP follow-up from EX Tomahawk remains on its stock route.
- **Tomahawk Buster is restored to standard USF4 data**, including its native strength-specific hit counts, timing and juggle settings.
- **Ultra 2, Raging Slash, can catch an airborne opponent after floor bounce**, with juggle-compatible capture and damage hits. Ultra 1 and unrelated command grabs remain native.
- Other striking specials retain their added juggle eligibility.
- Successful finishers and whiffs use somersault recovery.

### Vega

- **Close standing HK launches on its second hit.** The first hit and far HK keep their grounded reactions.
- Air combos support both claw-on and claw-off punch hitboxes.
- **L/M/H/EX Flying Barcelona Attack swipes gain juggle eligibility and continuous airborne juggle reactions**, covering both wall directions and claw states. EX takeoff strikes gain additional juggle allowance.
- **Izuna Drop can catch and damage juggled airborne opponents**, with the applicable normal and EX capture paths retained.
- **Air throw is available during pursuit and airborne recovery.** Its private damage finish is corrected so a successful juggle capture deals damage, retaining native base damage and normal combo scaling.
- Successful finishers and whiffs use somersault recovery.

### Yang

- **Close standing HP launches only on its second hit.** The first hit keeps its grounded reaction.
- **Close standing MK keeps its natural launch and gains held-Up pursuit.**
- **L/M/H dive kicks are available during pursuit and cause a continuous airborne juggle instead of an air reset.**
- The air-combo kit and launcher rules also support **Seiei Enbu variants**, retaining the native install/effect rules.
- Successful finishers and whiffs use Cody-style somersault recovery.
- **Ultra 2's cinematic interruption is fixed**, preventing the opponent from disappearing, reappearing above the screen and remaining suspended. Actual Ultra strike hits retain the shared pickup allowance.

### Yun

- **Close standing HP launches only on its second/final hit.** The first hit keeps its grounded reaction.
- **Close standing MK keeps its natural launch and gains held-Up pursuit.**
- **L/M/H dive kicks are available during air combos and cause a continuous airborne juggle instead of an air reset.**
- The launcher, air-combo and dive-kick changes also cover **Genei Jin variants**, retaining native boosted attack damage and Super timing.
- Striking specials gain juggle eligibility.
- Successful finishers and whiffs use Cody-style somersault recovery in normal and Genei Jin states.

### Zangief

- **Close standing HK launches.** Far HK keeps its grounded reaction and has no pursuit cancel.
- **Ultra 2, Siberian Blizzard, is available during air combos and can catch after floor bounce**, with juggle-compatible capture and damage hits.
- **EX Spinning Piledriver can catch an airborne opponent after floor bounce**, retaining its original grounded grab and native damage/release sequence. **L/M/H SPD do not gain the airborne pickup.**
- **Double Lariat and Quick Double Lariat are restored to stock USF4 action data and juggle behavior.**
- Other striking specials retain the shared juggle eligibility.
- Hit and whiff recovery use a complete native Zangief recovery flip, correcting the earlier torso/leg warping.

## Launcher and installation

The downloadable launcher displays **USF4 TAG! pre-alpha v0.1**. Launcher **revision 6** installs accepted combat **build 105** and sets up the tested Simp version automatically. It reuses a matching installed copy or downloads and verifies it; internet access is needed when Simp is missing. The startup failure that could stop loading after Simp finished has been corrected; the **Patching complete** popup has been confirmed in a real loading session.

1. Choose your Steam USF4 folder and click **Install Pre-Alpha**. Existing owned installations can be updated.
2. Click **Launch USF4** and wait at the game's **main menu**.
3. Return to the launcher and click **Load Pre-Alpha**.
4. In Simp, select **tag_pre_v0100** and click **Launch**.
5. Wait for **Patching complete**, then return to USF4 and enter **standard Ultra Training**.

The popup confirms that patching completed and the Training stun rule started. Keep the launcher open until it appears. Exit USF4 and Simp normally before installing, updating, repairing or removing the pre-alpha. The launcher preserves the original game files and saves; owned combat updates retain the previous build in a recovery folder. For stock play, start a fresh Steam session with Simp closed.

The **Manage** menu includes:

- **Check for updates:** finds a newer published installer on the project's GitHub. Choosing to update downloads, verifies and installs it.
- **Open logs:** opens local operation details and error reports.
- **Report a bug:** lets you describe the problem and review a short diagnostics preview, then opens a pre-filled GitHub issue for you to review and submit. Raw logs and files are not uploaded automatically.
- **Verify installation, Repair installation and Remove Pre-Alpha:** maintain the owned installation while preserving unrelated or changed files.

## Testing and scope

Combat build105 was accepted through local character playtesting. Launcher revision5's live loading check confirmed both the completion popup and successful startup of the Training stun rule. Public launcher revision6 retains that working runtime and adds verified automatic Simp acquisition. This startup check does not claim a new full-roster gameplay pass or support for the extra stun rule in other modes.

Independent second-machine installation testing and exhaustive matchup coverage remain pending. The previously proposed minimum Ultra damage floor is not implemented in this build.
