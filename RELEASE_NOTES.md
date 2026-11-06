# USF4 TAG Pre-Alpha v0.1.2 — Patch 01

Setup now repairs missing or changed launcher files and keeps a recovery copy. This launcher update includes combat build 119.

Combat build 119 adds air-combo routes, shortens launch arcs and reduces the lift from repeated grounded juggles across the 42-character pre-alpha. Runtime rules apply in offline standard Ultra Training. Hugo and Hakan remain deferred. Assists are part of a separate development build.

## Air combos and juggles

- **Heavy air-combo starters return.** Starting a pursuit chain with HP or HK applies 50% damage and 40% of normal stun from that hit through the end of the combo. Light and medium starters keep the existing 50% launcher stun rule. A heavy finisher after a light or medium starter does not trigger heavy-starter scaling.
- **Four heavy air-special routes return.** Akuma’s heavy air fireball, Evil Ryu’s air Demon, Cammy’s heavy Cannon Strike and Dan’s heavy air Dankukyaku are available through their previous routes. They do not count as heavy normal starters.
- **Universal launches and held-Up pursuit are lower and quicker.** The pursuer catches up slightly above the opponent. The opponent gets 10% stronger gravity on the initial universal launch. Extra native launch routes such as Makoto’s Fukiage and Yun and Yang’s close MK retain their own motion.
- **Relaunches rise 10% less after a pursuit floor bounce.** The fixed reduction requires an actual rebound and does not compound on repeated relaunches.
- **Grounded MP and MK share diminishing lift against airborne opponents.** Successive hits add 50%, 25% and 12.5% of the reference heavy juggle height, then no added lift. Grounded HP and HK share a separate progression of 100%, 75%, 50% and 25%, then no added lift. Both counters reset when the combo ends. Initial launches, jumping normals and pursuit finishers do not consume steps.
- **Four EX specials floor bounce only against a grounded opponent on the bounce-causing hit.** This applies to E. Honda’s EX Sumo Smash, Makoto’s EX Oroshi, Evil Ryu’s EX Ryusokyaku and M. Bison’s EX Head Press. Against an airborne opponent, those hits knock down without a floor bounce. A grounded bounce applies 50% damage and 50% stun from that hit through the combo. If heavy-starter scaling is already active, the combo stays at 50% damage and 40% stun.

## Character changes

- **Vega** — Light Scarlet Terror and its light combo route return to stock USF4 juggle eligibility. Medium, heavy and EX are unchanged.
- **Oni** — Air Raging Demon is available during pursuit with its original command and meter cost. Medium Zanku Hadosho can continue into air normals on hit during pursuit. Free-jump Medium Zanku keeps its existing behavior.
- **Makoto** — Light Fukiage returns to stock USF4 juggle eligibility. Light Hayate returns to its pre-change TAG behavior. Medium, heavy and EX Fukiage keep their existing behavior.
- **Seth** — All Shoryuken routes match the public v0.1.0 combat build. After the final hit of a connected medium or heavy Shoryuken, later hits in the same combo deal 60% of their already-scaled damage. The final Shoryuken hit keeps its damage. The modifier applies once per combo, leaves stun alone and does not activate from light or EX Shoryuken.

## Install and play

Close USF4 and Simp before updating. Run **USF4TAG-PreAlpha-0.1.2-Setup.exe** and install to your Steam USF4 folder. The launcher can upgrade the existing public pre-alpha and retains a recovery copy.

Click **Launch USF4** and wait at the main menu. Click **Load Pre-Alpha** in the launcher, select **tag_pre_v0100** in Simp and click **Launch**. Wait for **Patching complete**, then enter offline standard Ultra Training.
