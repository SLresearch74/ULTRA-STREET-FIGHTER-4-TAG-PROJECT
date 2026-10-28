[English](../../ROSTER_CHANGES.md) · [Sprachen](../README.md)

# USF4 TAG Project — Änderungen der Pre-Alpha-Kämpferriege

**Pre-Alpha v0.1 · Version 0.1.0 · Abgenommener Kampf-Build 105 · Launcher-Revision 6 · 42 unterstützte Charaktere · Stand: 28. Oktober 2026**

Dieses Dokument beschreibt die abgeschlossene Kampf-Pre-Alpha. Wählt **Standard-Ultra**-Charaktere. **Hugo und Hakan sind zurückgestellt.** Diese Version nutzt gewöhnliche Einzelcharakter-Kämpfe und das ursprüngliche HUD; Team-/Tag-Spiel bleibt ein getrenntes Vorhaben.

## Schreibweise

- **LP / MP / HP:** leichter / mittlerer / schwerer Schlag.
- **LK / MK / HK:** leichter / mittlerer / schwerer Tritt.
- **Close / far:** der je nach Gegnerabstand gewählte Normalangriff.
- **QCF:** Viertelkreis vorwärts. **QCB:** Viertelkreis rückwärts. **HCF:** Halbkreis vorwärts.
- **2× QCF / 2× HCF:** Bewegung zweimal ausführen.
- **PPP / KKK:** alle drei Schlag- / Tritttasten gleichzeitig.
- Richtungen beziehen sich auf die Blickrichtung des Charakters. Charakter-, Bewegungs- und Launcher-Schaltflächennamen bleiben wie im englischen Dokument erhalten, damit sie eindeutig zugeordnet werden können.

Framewerte beschreiben die Balanceeinstellungen und Zielwerte dieses Builds. Nicht alle Start- und Vorteilswerte wurden unabhängig im Spiel gemessen. Ursprüngliche Anforderungen an Ressourcen, Höhe, Reichweite und Eingaben gelten, sofern keine Änderung genannt wird.

## Gemeinsames Kampfsystem

### Launcher und Verfolgung

Jeder unterstützte Charakter besitzt mindestens einen Launcher. **Trefft damit und haltet Oben, um dem Gegner in die Luft zu folgen.** Die Verfolgung erfordert einen Treffer. Bei mehrteiligen Launchern nennt die Tabelle den Treffer, der die Verfolgung freigibt.

### Standard-Luftkombos

Die neuen Normalangriffsketten werden über die Launcher-Verfolgung zugänglich. Gewöhnliche Sprungangriffe behalten ihre ursprünglichen Abläufe, abgesehen von den unten genannten Charakteränderungen.

- Luftketten folgen **leicht → mittel → schwer**. Pro Stärke kann Schlag oder Tritt gewählt werden.
- Stärken dürfen übersprungen werden. **Nur LP, LK, MP oder MK können die normale Verfolgungskette beginnen; HP/HK können sie nicht beginnen.** Schwere Abschlussangriffe bleiben nach leicht oder mittel verfügbar.
- Jede Stärke wird höchstens einmal verwendet. Verbindungen derselben Stärke und Rückkehr zu schwächeren Normalangriffen sind im Standardablauf ausgeschlossen.
- Beispiele: **LP → MP → HP**, **LK → MK → HK**, **LP → MK → HP**, **MP → HK**.
- **HP oder HK beendet die Normalkette normalerweise mit einem Abwärtsschlag und Bodenabpraller.** Die Abschnitte zu Rufus, Chun-Li, Gen und Elena erläutern ihre Abschlussangriffe.
- Zusätzliche Luft-Specials, Befehls-Normals, Würfe und Ultras nutzen die unten beschriebenen charaktereigenen Abläufe. Ein während der Erholung verfügbarer Special startet die Normalkette nicht neu.

**Gen besitzt eine eigene Variante der leichten/mittleren Kette.** Der übrige Kader nutzt die Standardregeln mit den ausdrücklich genannten Target-Combo- und Mehrfachtreffer-Fortsetzungen. Der Beginn mit leicht/mittel gilt auch für beide Gen-Stile und Makotos Einstiege über Fukiage-Sprungabbrüche. Charaktereigener Zugang zu Luft-Specials, Würfen und Befehls-Normals bleibt erhalten.

### Juggles, Bodenabpraller und Erholung

- Mittlere/schwere Boden-Normals erhalten die gemeinsame Luft-Juggle-Reaktion. **Gewöhnliche LP/LK am Boden und im Sprung behalten ihre ursprünglichen USF4-Juggle-Eigenschaften und -Reaktionen.** LP/LK innerhalb der Launcher-Verfolgung behalten die für funktionierende Luftketten nötigen Reaktionen.
- Die genannten Schlag-Specials und Projektile erhalten eine höhere Juggle-Treffermöglichkeit. Das ändert die ursprüngliche Trefferreaktion nicht automatisch in einen Schwebezustand; konkrete Reaktionsänderungen stehen unten.
- Schwere Luftabschlüsse erzeugen einen Bodenabpraller für weitere Bodenangriffe. Trifft keine Fortsetzung, geht der Gegner durch Niederschlag und Aufstehen zurück ins normale Spiel.
- Die Luftkombo-Erholung nutzt einen Vorwärtssalto oder eine geeignete eigene Drehung. Charakterspezifische Animationskorrekturen gelten wie angegeben für erfolgreiche Abschlüsse und verfehlte Angriffe.
- Unterstützte Charaktere verwenden ihren **Omega-Vorwärtsdash**, angepasst an ihre Standard-Movesets. **Dhalsim behält seinen Standard-USF4-Vorwärtsdash.** Daraus werden keine vollständigen Omega-Versionen.

### Ausnahmen für leichte Specials

**Leichte Boden-Specials mit Vorwärts-Dragon-Punch-Eingabe behalten ihre ursprünglichen USF4-Juggle-Eigenschaften und -Reaktionen.** Das gilt für LP und LK einschließlich anerkannter Abkürzungen für vorwärts → unten → unten-vorwärts. Die Eingabefamilie zählt, nicht nur der Name Shoryuken: etwa leichter Cannon Spike, Seismic Hammer, Fukiage, Soul Throw, Banishing Flat und Tiger Knee. Umgekehrte DP-Bewegungen sind nicht betroffen.

Mittlere/schwere/EX-Versionen behalten ihr aufgeführtes Pre-Alpha-Verhalten. **Leichte Luft-Specials bleiben von dieser Rücknahme unberührt.** Leichte Feuerbälle und andere leichte Specials außerhalb der Boden-Vorwärts-DP-Familie behalten ebenfalls ihre genannten Änderungen.

### Betäubung in Launcher-Kombos

**Positive Betäubungswerte werden ab dem tatsächlichen Launcher-Treffer bis zum Ende dieser Kombo halbiert**, einschließlich fortgesetzter Luft-, Bodenabprall- und Bodenangriffe. Lebensschaden bleibt gleich. Eine neue separate Kombo verwendet den normalen Betäubungsfaktor, bis wieder ein Launcher trifft; Verfehlen oder Blockieren löst die Regel nicht aus. Ursprüngliche Rundung und mindestens ein Betäubungspunkt bleiben erhalten.

Bei mehrteiligen Launchern beginnt die Halbierung mit dem hochschleudernden Treffer; frühere Treffer behalten ihr normales Betäubungsscaling.

Die Zusatzregel gilt derzeit nur im **Offline-Standard-Ultra-Training**. Der Launcher aktiviert sie nach Abschluss von Simp automatisch; wartet vor Training auf **Patching complete**. Es ist kein eigener Betäubungsbutton nötig. Andere Modi erhalten diese Sitzungsregel nicht; eine breitere Modusunterstützung ist zukünftige Arbeit.

### Ultras nach Bodenabprallern

Schlag- und Projektil-Ultras erhalten die Möglichkeit, nach Bodenabprallern einen Gegner in der Luft zu treffen. Ursprüngliche Reichweite, Timing, Höhe und Bedingungen für die Filmsequenz bleiben wichtig. Schaden und Schadensscaling bleiben erhalten.

Greif-/Fang-Ultras, Konter und nicht angreifende Verstärkungs- oder Heilungs-Ultras behalten ihr Verhalten, mit zwei gewünschten Ausnahmen: **T. Hawks Ultra 2** und **Zangiefs Ultra 2** können nach Bodenabprallern greifen.

Die erhöhten Grenzwerte bleiben endlich. Nur die beiden ausdrücklich ergänzten Angriffe **Evil Ryus Air Raging Demon** und **Juris EX Shikusen** löschen den bisherigen Juggle-Zähler des Gegners. Ihre Abschnitte erläutern dies genauer.

## Launcher-Kurzübersicht

Klickt für alle Änderungen auf einen Charakternamen.

| Charakter | Launcher / Verfolgungsbeginn |
| --- | --- |
| [Abel](#abel) | Geducktes HP schleudert beim zweiten Treffer hoch. Der erste Treffer behält seine normale Bodenreaktion. |
| [Adon](#adon) | Nahes stehendes HK schleudert hoch. Fernes stehendes HK behält sein Bodenverhalten. |
| [Akuma](#akuma) | Geducktes HP schleudert hoch. |
| [Balrog](#balrog) | Geducktes HP schleudert hoch, einschließlich der aktiven aktualisierten Version. |
| [Blanka](#blanka) | Nahes stehendes HP schleudert hoch. Fernes HP behält seine Bodenreaktion. |
| [C. Viper](#c-viper) | Nahes stehendes HK schleudert beim zweiten Treffer hoch. Erster Treffer und fernes stehendes HK behalten ihre Bodenreaktionen. |
| [Cammy](#cammy) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion. |
| [Chun-Li](#chun-li) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion. |
| [Cody](#cody) | Geducktes HP schleudert sowohl unbewaffnet als auch mit Messer hoch. Messer-Schläge behalten eigene Animationen und Luftkombowege; Trittwege funktionieren in beiden Haltungen. |
| [Dan](#dan) | Geducktes HP schleudert hoch. Dan verwendet die Standard-Luftkettenregeln. |
| [Decapre](#decapre) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion. |
| [Dee Jay](#dee-jay) | Stehendes HP ohne Richtung führt das bisherige ferne HP bei beiden Distanzen aus. Es ist der Launcher, hat 7 Startframes und kann bei Treffer oder Block in Specials abgebrochen werden. |
| [Dhalsim](#dhalsim) | Rückwärts+HK, sein kurzer stehender Normalangriff, schleudert hoch. Gewöhnliches langgestrecktes stehendes HK behält seine Bodenreaktion. |
| [Dudley](#dudley) | Geducktes HP schleudert hoch. |
| [E. Honda](#e-honda) | Nahes stehendes HP schleudert hoch, mit 6 statt 8 Startframes, und kann bei Treffer oder Block in Specials abgebrochen werden. Fernes HP behält seine Bodenreaktion. |
| [El Fuerte](#el-fuerte) | Geducktes HP schleudert hoch. |
| [Elena](#elena) | Stehendes HP schleudert hoch, ohne Nah-/Fern-Aufteilung von HP. |
| [Evil Ryu](#evil-ryu) | Geducktes HP schleudert hoch, mit 5 Startframes als abschließendem Timingziel. Stehendes HP behält seine Bodenreaktion und erhält keine Verfolgung. |
| [Fei Long](#fei-long) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion. |
| [Gen](#gen) | Stehendes Mantis-HP schleudert beim letzten Treffer hoch.<br>Stehendes Crane-HP schleudert beim zweiten Treffer hoch. Geducktes Crane-HK schleudert ebenfalls hoch. |
| [Gouken](#gouken) | Geducktes MK schleudert hoch. |
| [Guile](#guile) | Geducktes HP schleudert hoch. |
| [Guy](#guy) | Einzeln eingesetztes nahes stehendes HP schleudert hoch. Fernes HP und Bushin-Ketten-HP erhalten den Boden-Launcher nicht.<br>Die Target Combo MP → HP schleudert nicht hoch. Ihr letzter Treffer erhält einen nur bei Treffer möglichen Sprungabbruch durch gehaltenes Oben, der in die Luftkombo führt. Block oder Verfehlen gibt diesen Abbruch nicht frei. |
| [Ibuki](#ibuki) | Geducktes HP schleudert hoch, unter Beibehaltung seiner ursprünglichen Sprungabbruch-Einstiege. |
| [Juri](#juri) | Geducktes HP ist der Launcher, einschließlich zugehöriger Feng-Shui-Engine-Wege. Nahes stehendes HP erhält sein Bodenverhalten zurück und keine Verfolgung. |
| [Ken](#ken) | Geducktes HP schleudert hoch. |
| [M. Bison](#m-bison) | Geducktes HP schleudert hoch, mit 6 Startframes und +1 bei Block. Special-Abbrüche sind bei Treffer oder Block möglich. |
| [Makoto](#makoto) | Geducktes HK ist der Launcher. Geducktes HP behält seinen Bodenfeger.<br>EX Fukiage behält seinen natürlichen Launcher und erhält nach Treffer über den Sprungabbruch Luftkombo-/Tsurugi-Zugang.<br>Sprungabbruch und daraus folgender Luftkombozugang bei normalem Fukiage erfordern einen Treffer. Ursprüngliche neutrale, vorwärts und rückwärts gerichtete Sprünge bleiben verfügbar. |
| [Oni](#oni) | Geducktes HP schleudert hoch. |
| [Poison](#poison) | Nahes stehendes HK schleudert beim letzten Treffer hoch. Erster Treffer und fernes HK behalten ihre Bodenreaktionen. |
| [Rolento](#rolento) | Nahes stehendes HP schleudert hoch. Fernes HP behält seine Bodenreaktion. |
| [Rose](#rose) | Geducktes HP schleudert hoch. |
| [Rufus](#rufus) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion. |
| [Ryu](#ryu) | Geducktes HP schleudert hoch. |
| [Sagat](#sagat) | Nahes stehendes MP schleudert hoch. Fernes MP behält seine Bodenreaktion. |
| [Sakura](#sakura) | Geducktes HP schleudert hoch, wobei die Verfolgung ab dem ersten aktiven Treffer für eine frühere Fortsetzung freigegeben wird. |
| [Seth](#seth) | Geducktes HP schleudert beim zweiten/letzten Treffer hoch. Der erste behält seine Bodenreaktion. |
| [T. Hawk](#t-hawk) | Nur nahes stehendes HK schleudert hoch. Fernes stehendes HK schleudert nicht hoch und erhält keine Verfolgung. |
| [Vega](#vega) | Nahes stehendes HK schleudert beim zweiten Treffer hoch. Der erste Treffer und fernes HK behalten ihre Bodenreaktionen. |
| [Yang](#yang) | Nahes stehendes HP schleudert nur beim zweiten Treffer hoch. Der erste behält seine Bodenreaktion.<br>Nahes stehendes MK behält seinen natürlichen Launcher und erhält Verfolgung mit gehaltenem Oben. |
| [Yun](#yun) | Nahes stehendes HP schleudert nur beim zweiten/letzten Treffer hoch. Der erste behält seine Bodenreaktion.<br>Nahes stehendes MK behält seinen natürlichen Launcher und erhält Verfolgung mit gehaltenem Oben. |
| [Zangief](#zangief) | Nahes stehendes HK schleudert hoch. Fernes HK behält seine Bodenreaktion und erhält keinen Verfolgungsabbruch. |

## Charakteränderungen

Alle folgenden Charaktere erhalten das gemeinsame Kampfsystem. Diese Abschnitte nennen Launcher, weitere Änderungen und Ausnahmen. **Die gemeinsamen Ausnahmen für gewöhnliche leichte Normals und leichte Boden-DPs gelten für alle allgemeinen Juggle-Listen unten.**

### Abel

- **Geducktes HP schleudert beim zweiten Treffer hoch.** Der erste Treffer behält seine normale Bodenreaktion.
- Die Schlagtrefferzonen von Change of Direction, Wheel Kick und Falling Sky können juggeln.
- Erfolgreiche Luftabschlüsse und Erholung nach Verfehlen nutzen den Vorwärtssalto im Cody-Stil.
- Gegen bereits schwebende Gegner nutzt der zweite Treffer des geduckten HP die gemeinsame kurze Fallreaktion.

### Adon

- **Nahes stehendes HK schleudert hoch.** Fernes stehendes HK behält sein Bodenverhalten.
- **L/M/H/EX-Luft-Jaguar Kick** ist bei Verfolgung, nach leichten/mittleren Lufttreffern und während der Luftkombo-Erholung verfügbar.
- Luft-Jaguar Kick hält Gegner mit einer fortlaufenden Juggle-Reaktion in der Luft statt eines Luft-Resets.
- Schlagvarianten von Jaguar Kick, Jaguar Tooth und Rising Jaguar können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Akuma

- **Geducktes HP schleudert hoch.**
- **L/M/H/EX-Luftfeuerball und Luft-Tatsu** sind bei Verfolgung, Luftketten und Lufterholung mit ihren normalen Eingaben und Beschränkungen verfügbar.
- **Das bisherige ferne stehende HK wird zu vorwärts+HK**, bei beiden Distanzen nutzbar. Stehendes HK ohne Richtung verwendet bei beiden Distanzen das bisherige nahe HK.
- Vorwärts+MP, Dive Kick, Tatsu, M/H/EX Shoryuken, Demon-Flip-Schläge und normale Feuerbälle können juggeln. **Leichter Boden-Shoryuken behält seine ursprünglichen USF4-Juggle-Eigenschaften.**
- Verfolgung und Erholung nutzen Akumas eigene Vorwärtssprunganimation.

### Balrog

- **Geducktes HP schleudert hoch**, einschließlich der aktiven aktualisierten Version.
- Dash-Schläge und Uppercuts, ihre Overhead-/Tiefvarianten, Buffalo Head und Turn-Punch-Schlagvarianten können juggeln.
- Schwere Luftabschlüsse und verfehlte Luftkombos nutzen die Salto-Erholung im Cody-Stil, angepasst an Handschuhe und Skelett.
- Violent Buffalo erhält die gemeinsame Ultra-Aufnahmemöglichkeit; Dirty Bull behält sein Greifverhalten.

### Blanka

- **Nahes stehendes HP schleudert hoch.** Fernes HP behält seine Bodenreaktion.
- **Electric Thunder akzeptiert fünf Schlagtastendrücke oder QCF+P.** QCF+zwei Schläge wählt EX.
- **Alle Electric-Thunder-Versionen behalten das ursprüngliche USF4-Juggle-Verhalten**, einschließlich fortgesetzter Impulse und EX-Varianten. Die gemeinsame erhöhte Juggle-Toleranz wurde aus der Elektrizität entfernt.
- Rollende und vertikale Ball-Schlagvarianten behalten ihre zusätzliche Juggle-Treffermöglichkeit.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen Salto-Erholung.

### C. Viper

- **Nahes stehendes HK schleudert beim zweiten Treffer hoch.** Erster Treffer und fernes stehendes HK behalten ihre Bodenreaktionen.
- **L/M/H/EX-Luft-Burning Kick** ist bei Verfolgung und Erholung verfügbar.
- **Ultra 2, Burning Dance, ist während Luftkombos verfügbar**, unter den ursprünglichen Bedingungen für Eingabe, Ressourcen, Höhe und Ultra-Auswahl.
- **M/H/EX Seismic Hammer können Luftgegner juggeln**, sodass Juggle- und Bodenabprall-Fortsetzungen in normaler Reichweite funktionieren. **Leichter Seismic Hammer behält seine ursprünglichen USF4-Juggle-Eigenschaften.**
- Erholung nach Treffer und Verfehlen nutzt ihren vollständigen eigenen Vorwärtssalto.

### Cammy

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion.
- **Luftwurf, LP+LK, ist während Verfolgung und nach leichten/mittleren Lufttreffern verfügbar**, mit Juggle-tauglichem Fangen und Schaden.
- **M/H/EX Cannon Spike erhalten erhöhte Juggle-Toleranz. Leichter Cannon Spike behält seine ursprünglichen USF4-Juggle-Eigenschaften.** Eine Cannon-Spike-Eingabe in der Luft wird damit nicht ergänzt.
- **L/M/H/EX Cannon Strike ist während Luftkombos und Lufterholung verfügbar.** Lufttreffer führen den Juggle fort statt eines Luft-Resets.
- Die Schlagtrefferzonen von Spiral Arrow, Quick Spin Knuckle und Hooligan Slide können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Chun-Li

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion.
- **Luftwurf ist während Verfolgung verfügbar**, mit an gejugglelte Gegner angepasstem Fangen und Schaden.
- **Yosokyaku ist während Luftkombos verfügbar**, mit ursprünglichem unten/unten-vorwärts+MK und Fortsetzungen mit drei Tritten.
- **Hyakuretsukyaku akzeptiert QCF+K oder fünf schnelle Tritttastendrücke.** Mash-Fortsetzungen und EX-Ressourcenregeln bleiben erhalten.
- **Luft-HP → HP erzeugt nur beim zweiten Schlag einen Bodenabpraller.** Der erste hält den Gegner in der Luft. Ohne zweiten Schlag endet der erste ohne Abpraller. HP kann nicht in HK oder schwächere Normals übergehen.
- **L/M/H/EX Hazanshu erzeugen die gemeinsame Luft-Juggle-Reaktion**, behalten aber ihre Bodenreaktionen.
- Kikouken-Projektile können juggeln.
- Erholung nach Treffer und Verfehlen nutzt den korrigierten Salto im Cody-Stil.

### Cody

- **Geducktes HP schleudert sowohl unbewaffnet als auch mit Messer hoch.** Messer-Schläge behalten eigene Animationen und Luftkombowege; Trittwege funktionieren in beiden Haltungen.
- **Criminal Upper aller Stärken und EX kann nach jedem kontaktierenden Treffer per FADC abgebrochen werden**, auch nach späteren Tornadotreffern. Treffer- oder Blockkontakt ist nötig.
- **HP Criminal Upper: 23 Erholungsframes. EX Criminal Upper: 25 Erholungsframes.**
- **HK Ruffian Kick: 25 Erholungsframes**, reduziert von 27.
- **LK/MK/HK-Super: 22 Erholungsframes**, einschließlich Fortsetzungszweigen nach erfolgreichem Treffer.
- Criminal Upper, Bad Stone, geworfene Messer und Schlag-Specials können juggeln.
- Erfolgreiche schwere Abschlüsse und verfehlte Luftkombos nutzen den Vorwärtssalto, einschließlich Messer-Schlagwegen.

### Dan

- **Geducktes HP schleudert hoch.** Dan verwendet die Standard-Luftkettenregeln.
- **L/M/H/EX-Luft-Dankukyaku und die ursprüngliche Luftprovokation sind während Luftkombos und Erholung verfügbar.**
- **Die Luftprovokation behält ihre ursprünglichen Treffer- und Juggle-Eigenschaften.** Provokationen erhalten keine erhöhte Juggle-Toleranz.
- L/M/H/EX Gadoken und Dankukyaku können juggeln. **M/H/EX Koryuken behalten die Pre-Alpha-Änderungen; leichter Boden-Koryuken behält seine ursprünglichen USF4-Juggle-Eigenschaften.**
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Decapre

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion.
- **Luftwurf ist während Verfolgung und Lufterholung verfügbar**, mit Juggle-tauglichem Fangen und Schaden. Grundschaden und Komboscaling bleiben ursprünglich.
- **Rapid Dagger akzeptiert QCF+P oder die ursprünglichen fünf Schlagtastendrücke**, einschließlich ursprünglicher EX-Stärken- und Ressourcenauswahl.
- **L/M/H/EX-Luft-Spiral Arrow ist bei Verfolgung, Luftketten und Erholung verfügbar**, mit ursprünglicher Eingabe und Höhenanforderung.
- Die Erholung nutzt ihren eigenen Vorwärtssprung-Salto und behebt die frühere Getroffen-Pose.

### Dee Jay

- **Stehendes HP ohne Richtung führt das bisherige ferne HP bei beiden Distanzen aus.** Es ist der Launcher, hat **7 Startframes** und kann bei Treffer oder Block in Specials abgebrochen werden.
- **Rückwärts+HP führt das bisherige nahe stehende HP bei beiden Distanzen aus.** Bodenreaktion und Abbrüche bleiben ursprünglich.
- **Double Rolling Sobat verwendet QCF+K**, einschließlich EX.
- **Leichter Double Rolling Sobat nutzt seine AE2012-Aktions- und Trefferdaten**, einschließlich Unverwundbarkeit gegen tiefe Angriffe und Blockverhalten, zusammen mit QCF-Eingabe und Juggle-Treffermöglichkeit.
- **Knee Shot, unten+LK, ist bei Verfolgung und nach Abschluss eines Luft-Normals verfügbar.** Es erzeugt einen fortlaufenden Luft-Juggle statt eines Resets.
- Knee Shot ist **kein direkter Kettenabbruch aus Luft-Normals** und öffnet die Normalkette nicht erneut. Die unmittelbare Erholung nach schwerem Kontakt ergänzt keinen Knee-Shot-Abbruch.
- Air-Slasher-Projektile und die Schlagtrefferzonen von Machinegun Upper, Sobat und Jackknife Maximum können juggeln.

### Dhalsim

- **Rückwärts+HK, sein kurzer stehender Normalangriff, schleudert hoch.** Gewöhnliches langgestrecktes stehendes HK behält seine Bodenreaktion.
- Verfolgungsketten verwenden die kurzen Luft-Normals mit normalen Schlag-/Tritteingaben; Rückwärts muss dafür nicht gehalten werden.
- **Alle drei Winkel von Yoga Spear sowie Yoga Mummy sind bei Verfolgung und Erholung verfügbar**, mit ursprünglichen Eingaben: unten+Tritt beziehungsweise unten+HP.
- Feuerbälle und Schlag-Specials können juggeln.
- **Der Vorwärtsdash ist auf Standard-USF4 zurückgesetzt**, einschließlich Bewegung, Animation und Abbruchzeitpunkten.
- Erholung nach Treffer und Verfehlen nutzt eine vollständige eigene Dhalsim-Saltopose und behebt Bein-/Fußverzerrungen.

### Dudley

- **Geducktes HP schleudert hoch.**
- Boden-Befehls-Normals und Target-Combo-Angriffe erhalten die gemeinsame Luft-Juggle-Reaktion.
- Machinegun Blow, Jet Upper, Short Swing Blow, Ducking-Schlagfortsetzungen, Thunderbolt und die Schlaganteile von Cross Counter können juggeln.
- Luftkombos nutzen Dudleys eigene Vorwärtssprungangriffe und Erholungsanimation. Rosenprojektile behalten ihr ursprüngliches Verhalten.

### E. Honda

- **Nahes stehendes HP schleudert hoch**, mit **6 statt 8 Startframes**, und kann bei Treffer oder Block in Specials abgebrochen werden. Fernes HP behält seine Bodenreaktion.
- **EX Sumo Smash erzeugt nur beim letzten absteigenden Treffer einen Bodenabpraller.** Aufsteigender Treffer und Nicht-EX-Versionen behalten normale Reaktionen.
- **Hundred Hand Slap akzeptiert fünf schnelle Schlagtastendrücke oder QCF+P.** Ursprüngliche Mash-Fortsetzungen sind neben der Bewegungseingabe wiederhergestellt; EX behält seine Schlagtastenauswahl.
- Schlag-Specials erhalten die gemeinsame Juggle-Treffermöglichkeit. Bestehende Headbutt-, Sumo-Smash-, Super- und Ultra-Eingaben behalten ihre ursprünglichen Anforderungen.

### El Fuerte

- **Geducktes HP schleudert hoch.**
- **Luftwurf, LP+LK, ist bei Verfolgung, leichten/mittleren Ketten und Erholung verfügbar.** Fangen und beide Schadenswege können im Juggle treffen; Grundschaden und Scaling bleiben erhalten.
- Schlag-Specials können juggeln; ursprüngliche Lauf- und Wandsprungwege bleiben bestehen.
- Erholung nach Treffer und Verfehlen nutzt seinen vollständigen eigenen Vorwärtssprung-Salto.
- Beide Greif-Ultras behalten gemäß der allgemeinen Ultra-Ausnahme ihr ursprüngliches Fangverhalten.

### Elena

- **Stehendes HP schleudert hoch**, ohne Nah-/Fern-Aufteilung von HP.
- Alle sechs Luft-Normals stehen bei Verfolgung zur Verfügung, einschließlich korrigierter Eingabefreigabe der eigenen Luftangriffe.
- **Luft-HK behält beide Treffer; nur der letzte erzeugt einen Bodenabpraller.** HP bietet ebenfalls einen Bodenabprall-Abschluss.
- Erholung nach Treffer und Verfehlen nutzt eine eigene Drehung aus Mallet Smash mit ihrem ursprünglichen Skelett.
- Schlag-Specials können juggeln. Brave Dance erhält die gemeinsame Ultra-Aufnahmemöglichkeit; Healing bleibt ursprünglich.

### Evil Ryu

- **Geducktes HP schleudert hoch**, mit **5 Startframes** als abschließendem Timingziel. Stehendes HP behält seine Bodenreaktion und erhält keine Verfolgung.
- **Vorwärts+MK erhält eine fortlaufende Luft-Juggle-Reaktion.**
- **Alle Ryusokyaku-Axttritte können juggeln. EX erzeugt einen Bodenabpraller**, bei mehrteiligen Aktionen auf dem abschließenden Treffer.
- Hadoken, Shakunetsu, Boden-/Luft-Tatsu und M/H/EX Shoryuken können juggeln. **Leichter Boden-Shoryuken behält seine ursprünglichen USF4-Juggle-Eigenschaften.**
- **L/M/H/EX-Luft-Tatsu ist bei Verfolgung und Luftkombowegen verfügbar.**
- **Air Raging Demon wurde mit Onis ursprünglicher Bewegungssequenz ergänzt.** Bei voller Super-Leiste in der Luft **LP, LP, vorwärts, LK, HP** eingeben. Abbrüche aus gewöhnlichen Sprung-Normals ermöglichen die Aktivierung.
- Der Aktivierungston von Air Demon verwendet die zu Evil Ryu passenden Sprach-/Effektklänge.
- **Air Demon löscht während seines Greiffensters den bisherigen Juggle-Zähler des Gegners**, sodass er nach langen Juggles möglich ist. Die Rücksetzung läuft auch bei erfolglosem Versuch; ursprüngliche Reichweite, Luft-Eignung und Unverwundbarkeit gelten weiter.

### Fei Long

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion.
- Die Schlagtrefferzonen von Rekka, Shienkyaku und Rekkukyaku können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.
- Rekkashingeki erhält die gemeinsame Ultra-Aufnahmemöglichkeit; Gekirinken behält sein Konterverhalten.

### Gen

- **Stehendes Mantis-HP schleudert beim letzten Treffer hoch.**
- **Stehendes Crane-HP schleudert beim zweiten Treffer hoch. Geducktes Crane-HK schleudert ebenfalls hoch.**
- Nahe und ferne stehende HP-Versionen sowie die entsprechenden Target-Combo-HP-Kopien folgen der letzten Trefferregel ihrer Haltung.
- Beide Haltungen besitzen eigene Luftkomboangriffe und Verfolgungswege.
- **Nur Gen darf innerhalb der leichten und mittleren Stärke Schlag und Tritt in beliebiger Reihenfolge verwenden.** Jeder Normalangriff ist einmal nutzbar. Stärken dürfen übersprungen werden; eine stärkere Stufe sperrt jedoch alle schwächeren.
- **HP oder HK beendet die Kette. HP → HK und HK → HP sind gesperrt.**
- Beispiele: **LP → LK → MP → MK → HK**, **LK → LP → MK → MP → HP**, **LP → MK → HP**. Mittel → leicht und schwer → mittel/leicht sind nicht erlaubt.
- **Crane-Luft-HK mit zwei Treffern erzeugt nur beim zweiten Treffer einen Bodenabpraller.**
- **Hyakurenko akzeptiert fünf schnelle Schlagtastendrücke oder QCF+P**, einschließlich ursprünglicher Mash-Fortsetzungen. EX behält seine Schlagtastenauswahl.
- Schlag-Specials können juggeln. Beide Haltungen nutzen bei Treffer und Verfehlen Saltos im Cody-Stil zur Erholung.

### Gouken

- **Geducktes MK schleudert hoch.**
- **L/M/H/EX-Luft-Tatsu ist bei Verfolgung und Erholung verfügbar.**
- **Jeder Verfolgungs-Tatsu bewegt sich vorwärts auf den Gegner zu und besitzt pro Aktivierung ein einziges schadensverursachendes Trefferfenster.** Gewöhnlicher Sprung-Tatsu behält seine ursprünglichen Mehrfachtrefferaktionen und Eingaben.
- Normale Hadokens und Schlag-Specials können juggeln.
- Die Erholung nutzt seinen vollständigen eigenen Vorwärtssalto.

### Guile

- **Geducktes HP schleudert hoch.**
- **Fernes stehendes HP, fernes stehendes HK und geducktes HP können bei Treffer oder Block in gewöhnliche Specials abgebrochen werden.**
- Normale und EX-Sonic-Boom-Projektile können juggeln.
- **Vorwärts- und Rückwärtsluftwürfe sind bei Verfolgung verfügbar**, mit LP+LK; Rückwärts wählt den Rückwärtswurf.
- **Verfolgungsluftwürfe verwenden die ursprünglichen Opferreaktionen ohne zusätzlichen Bodenabpraller.** Guiles abgenommener schnellerer Landeablauf als Angreifer bleibt erhalten.
- **Ursprüngliche USF4-Charge-Eingaben sind für sämtliche Guile-Angriffe wiederhergestellt, einschließlich Super und beider Ultras.** Frühere Bewegungseingaben und Abkürzungen sind entfernt.

### Guy

- **Einzeln eingesetztes nahes stehendes HP schleudert hoch.** Fernes HP und Bushin-Ketten-HP erhalten den Boden-Launcher nicht.
- **Die Target Combo MP → HP schleudert nicht hoch.** Ihr letzter Treffer erhält einen **nur bei Treffer möglichen Sprungabbruch durch gehaltenes Oben**, der in die Luftkombo führt. Block oder Verfehlen gibt diesen Abbruch nicht frei.
- **L/M/H/EX-Luft-Kaiten Izuna Otoshi ist bei Verfolgung, nach leichten/mittleren Treffern und während der Erholung verfügbar**, mit Juggle-tauglichem Fangen und ursprünglichen Schadensabschlüssen.
- Hozanto, Senpukyaku, Schlagfortsetzungen aus dem Lauf und Izuna-Ellbogenschläge können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Ibuki

- **Geducktes HP schleudert hoch**, unter Beibehaltung seiner ursprünglichen Sprungabbruch-Einstiege.
- **Luftwurf, LP+LK, ist bei Verfolgung und leichten/mittleren Ketten verfügbar.** Alle drei Schadenstreffer können im Juggle treffen; Schaden und Scaling bleiben ursprünglich.
- **L/M/H/EX Kunai ist während Luftkombos und Erholung verfügbar.** Normale/EX-Kunai-Projektile können juggeln und behalten ihre ursprünglichen Reaktionen und Winkel.
- Schlag-Specials können juggeln.
- Erholung nach Treffer und Verfehlen nutzt ihren vollständigen eigenen Vorwärtssprung-Salto.

### Juri

- **Geducktes HP ist der Launcher**, einschließlich zugehöriger Feng-Shui-Engine-Wege. Nahes stehendes HP erhält sein Bodenverhalten zurück und keine Verfolgung.
- **L/M/H/EX Shikusen ist während Luftkombos und Erholung verfügbar**, mit ursprünglichen Folgeeingaben.
- **Der letzte Tritt von EX Shikusen erhält seinen ursprünglichen Wandabpraller zurück.** Die gemeinsame ursprüngliche Wandreaktion gegen Ryu ist repariert; der Gegner folgt der richtigen Schadensanimation und Wandabprallbahn.
- **Alle anfänglichen und folgenden EX-Angriffsfenster löschen den bisherigen Juggle-Zähler des Gegners**, damit die EX-Folge nach langen Juggles fortgesetzt werden kann. Die Rücksetzungen laufen auch beim Verfehlen dieser EX-Fenster. Normales Shikusen erhält diese Rücksetzungen nicht.
- Normale Fuhajin-Projektile erhalten fortlaufende Luft-Juggle-Reaktionen; Senpusha- und Shikusen-Schläge können juggeln.
- Erholung nach Treffer und Verfehlen nutzt Saltos im Cody-Stil.
- Ursprüngliche Aktivierung und gewöhnliche Kettenregeln von Feng Shui Engine bleiben erhalten; die neue Verfolgung nutzt Standard-Luftkettenregeln.

### Ken

- **Geducktes HP schleudert hoch.**
- **Nahes stehendes HK stößt bei Treffer 20% weniger zurück, hat 16 Erholungsframes und +5 bei normalem Bodentreffer.** Der Kontertrefferbonus bleibt erhalten.
- **Nahes stehendes MK stößt bei Treffer 25% weniger zurück.**
- **Nahes stehendes MP, der Target-Combo-Einstieg, hat 4 Startframes.** Die HP-Fortsetzung bleibt verfügbar.
- **Luft-Tatsu nutzt Bewegung und Timing des älteren Grundspiels.** Ursprünglicher Schaden, Ressourcenverbrauch und Treffergeometrie bleiben erhalten.
- Gewöhnliche neutrale/gerichtete Luft-Normals erhalten **Luft-Tatsu-Abbrüche bei Treffer oder Block**. Normaler/EX-Luft-Tatsu ist auch bei Verfolgung, Luftketten und Lufterholung schwerer Abschlüsse verfügbar.
- Normaler/EX-Hadoken und Boden-/Luft-Tatsu können juggeln. **Leichter Boden-Shoryuken behält ursprüngliche USF4-Juggle-Eigenschaften; M/H/EX behalten ihre Pre-Alpha-Änderungen.**

### M. Bison

- **Geducktes HP schleudert hoch**, mit **6 Startframes und +1 bei Block**. Special-Abbrüche sind bei Treffer oder Block möglich.
- **Double Knee Press wird HCF+K. Psycho Crusher wird HCF+P.** Normal und EX akzeptieren zusätzlich **unten-rückwärts → unten → unten-vorwärts → vorwärts** mit passenden Tasten.
- **EX Head Press erzeugt einen höheren Bodenabpraller.** Nur EX Head Press erhält diese Zusatzhöhe; gewöhnlicher Head Press und gemeinsame schwere Abschlüsse behalten ihre Reaktionen.
- **MP → MP, Hell Attack, ist bei Treffer während der Verfolgung verfügbar.** Die Fortsetzung kann in HP oder HK führen. Beispiele: **MP → MP → HK**, **LP → MP → MP → HP**. Schleifen oder Rückkehr zu schwächeren Normals sind ausgeschlossen.
- Die Schlagtrefferzonen von Knee Press, Psycho Crusher, Head Press, Skull Diver und Devil Reverse können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Makoto

- **Geducktes HK ist der Launcher. Geducktes HP behält seinen Bodenfeger.**
- **L/M/H/EX Tsurugi, der Luft-Axttritt, ist bei Verfolgung, Luftketten und Erholung verfügbar.**
- **EX Oroshi erzeugt einen Bodenabpraller.** Nicht-EX-Oroshi erhält diesen Abpraller nicht.
- **Geducktes HP kann nur bei Treffer in gewöhnliche Specials abgebrochen werden**, darunter Hayate, Oroshi, Fukiage und Karakusa. Kein neuer Abbruch bei Block oder Verfehlen.
- **EX Fukiage behält seinen natürlichen Launcher und erhält nach Treffer über den Sprungabbruch Luftkombo-/Tsurugi-Zugang.**
- **Sprungabbruch und daraus folgender Luftkombozugang bei normalem Fukiage erfordern einen Treffer.** Ursprüngliche neutrale, vorwärts und rückwärts gerichtete Sprünge bleiben verfügbar.
- **Schwerer Fukiage wird von 13 auf 11 Startframes geändert.**
- Die Schlagfamilien Hayate, Oroshi, Fukiage und Tsurugi können juggeln.

### Oni

- **Geducktes HP schleudert hoch.**
- **Zanku Hadosho ist bei Verfolgung, nach leichten/mittleren Lufttreffern und während der Erholung verfügbar**, einschließlich ursprünglicher EX-Tastenvarianten. Seine Angriffsanteile nutzen fortlaufende Luft-Juggle-Reaktionen.
- **L/M/H/EX-Luft-Tatsu und Messatsu-Gozanku, Luft-Ultra 1, sind während Luftkombos und Erholung verfügbar**, unter normalen Ressourcen-, Höhen- und Ultra-Auswahlbedingungen.
- Normale Gohado-/Gorai-Projektile erhalten fortlaufende Luft-Juggle-Reaktionen; Schlag-Specials und Befehls-/Target-Combo-Angriffe erhalten gemeinsame Juggle-Eigenschaften.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.
- Onis eigene Boden- und Luft-Raging-Demon-Supers behalten ihr ursprüngliches Verhalten.

### Poison

- **Nahes stehendes HK schleudert beim letzten Treffer hoch.** Erster Treffer und fernes HK behalten ihre Bodenreaktionen.
- Normale Feuerbälle und Schlag-Specials können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen ihren vollständigen eigenen Vorwärtssprung-Salto.
- Love Storm erhält die gemeinsame Ultra-Aufnahmemöglichkeit; Poison Kiss behält sein Greifverhalten.

### Rolento

- **Nahes stehendes HP schleudert hoch.** Fernes HP behält seine Bodenreaktion.
- Mehrphasiges Luft-MP behält im Standard-Luftkombosystem beide ursprünglichen Trefferanteile.
- Stinger-Projektile und Schlag-Specials können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen seinen vollständigen eigenen Vorwärtssalto. Ursprüngliche Pogo- und Tricklandungswege bleiben erhalten.

### Rose

- **Geducktes HP schleudert hoch.**
- **M/H/EX Soul Throw behalten die Änderungen zur Aufnahme nach Bodenabprallern**, mit passender Freigabe für Kombofangen und Schadensabschluss. **Leichter Soul Throw behält seine ursprünglichen USF4-Juggle-Eigenschaften.** Soul Throw beginnt weiterhin am Boden; ursprüngliche Reichweite und Fangbedingungen gelten.
- Soul-Spark-Projektile erhalten fortlaufende Luft-Juggle-Reaktionen. Schlaganteile von Soul Spiral und Soul Reflect können juggeln; Reflect-Fangdaten bleiben ursprünglich.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen Salto-Erholung. **HP-Abschlusserholung enthält die ursprüngliche Schal-Rückholanimation**, wodurch Schalverzerrung auf beiden Seiten behoben wird.

### Rufus

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion.
- **Luft-HP erzeugt einen Bodenabpraller. Luft-HK behält seinen ursprünglichen zweiteiligen Luft-Juggle**, ohne zusätzlichen Bodenabpraller oder erzwungenen Niederschlag. Beide schweren Angriffe beenden die Normalkette; HK führt vor der Erholung den zweiten Treffer aus.
- **Falcon Kick ist bei Verfolgung, nach leichten/mittleren Lufttreffern und während der Erholung verfügbar.** Seine Lufttreffer führen den Juggle fort statt eines Luft-Resets.
- Galactic Tornado, Messiah und Snake Strike können mit ihren Trefferzonen juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen den reparierten Salto; frühere Körperstreckung/-verdrehung ist behoben.

### Ryu

- **Geducktes HP schleudert hoch.**
- **Ein einheitliches stehendes HP verwendet das bisherige nahe HP bei beiden Distanzen**, mit **4 Startframes**. Das getrennte ferne HP entfällt; stehendes HP nutzt eine einzelne Taste.
- **Nahes stehendes HK stößt 20% weniger zurück**, und beide Treffer können bei Treffer oder Block in gewöhnliche Specials abgebrochen werden.
- **Geducktes HK kann bei Treffer oder Block in Specials abgebrochen werden.** Der Feuerball-Blockabbruch verwendet ein späteres Fenster als andere Special-Abbrüche.
- Normaler/EX-Hadoken und Boden-/Luft-Tatsu können juggeln. **Leichter Boden-Shoryuken behält ursprüngliche USF4-Juggle-Eigenschaften; M/H/EX behalten ihre Pre-Alpha-Änderungen.**
- **L/M/H/EX-Vorwärts-Luft-Tatsu ist bei Verfolgung und Luftkombowegen verfügbar.**
- **Die Geschwindigkeit von EX Hadoken hängt von der Schlagtastenkombination ab:**

| Tasten | Projektilgeschwindigkeit |
| --- | --- |
| LP+HP | Langsam, entsprechend normalem LP Hadoken |
| LP+MP | Mittel, entsprechend normalem MP Hadoken |
| MP+HP | Ursprüngliche EX-Geschwindigkeit um 5% erhöht |

Ryus ursprüngliche Wandabprallreaktion als Opfer ist neben dem getrennten gemeinsamen Bodenabprallsystem wiederhergestellt und behebt den übernommenen Wandreaktionskonflikt.

### Sagat

- **Nahes stehendes MP schleudert hoch.** Fernes MP behält seine Bodenreaktion.
- Hohe und tiefe Tiger-Shot-Projektile und Schlag-Specials können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.

### Sakura

- **Geducktes HP schleudert hoch**, wobei die Verfolgung ab dem ersten aktiven Treffer für eine frühere Fortsetzung freigegeben wird.
- **Der letzte Treffer von Boden-EX-Tatsu schleudert ebenfalls in eine Verfolgung mit gehaltenem Oben**, gegen Boden- und Luftgegner.
- **Jeder Schadenstreffer von EX Tatsu kann juggeln**, mit fortlaufenden Luftreaktionen und erhaltenem bisherigem Abschluss-Launcher.
- **L/M/H/EX-Vorwärts-Luft-Tatsu ist bei Verfolgung und Luftkombowegen verfügbar.**
- L/M/H/EX-Boden-Tatsu und normale/aufgeladene/EX-Hadoken-Projektile können juggeln.
- **Nahes und fernes stehendes HK können bei Treffer oder Block in gewöhnliche Specials abgebrochen werden**, mit **−1 bei Block** als eingestelltem Ziel am ersten aktiven Treffer.
- **Schwerer Shouoken nutzt den Startablauf der mittleren Version mit Ziel 7 Startframes.** Trefferfolge und Schaden der schweren Version bleiben erhalten.

### Seth

- **Geducktes HP schleudert beim zweiten/letzten Treffer hoch.** Der erste behält seine Bodenreaktion.
- **Unten+MK ist bei Verfolgung verfügbar**, mit ursprünglicher Dreifachtritt-Folge.
- **Unten+HK ist bei Verfolgung verfügbar**, mit fortlaufender Luft-Juggle-Reaktion und ursprünglicher Mindesthöhe. Gewöhnliches unten+HK im Sprung bleibt unverändert.
- Sonic Booms und Schlag-Specials können juggeln.
- Verfolgung und Erholung nach Treffer/Verfehlen nutzen seinen vollständigen eigenen Vorwärtssalto.

### T. Hawk

- **Nur nahes stehendes HK schleudert hoch. Fernes stehendes HK schleudert nicht hoch und erhält keine Verfolgung.**
- In Luftkombos **aktiviert PPP normalen Condor Dive; KKK aktiviert EX Condor Dive**. Ursprüngliche Höhen- und Ressourcenbedingungen gelten. Die ursprüngliche EX-PPP-Fortsetzung aus EX Tomahawk bleibt auf ihrem bisherigen Weg.
- **Tomahawk Buster verwendet wieder Standard-USF4-Daten**, einschließlich ursprünglicher stärkenabhängiger Trefferzahlen, Timings und Juggle-Einstellungen.
- **Ultra 2, Raging Slash, kann Luftgegner nach Bodenabprallern fangen**, mit Juggle-tauglichem Fangen und Schadenstreffern. Ultra 1 und andere Befehlswürfe bleiben ursprünglich.
- Andere Schlag-Specials behalten ihre zusätzliche Juggle-Treffermöglichkeit.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen Salto-Erholung.

### Vega

- **Nahes stehendes HK schleudert beim zweiten Treffer hoch.** Der erste Treffer und fernes HK behalten ihre Bodenreaktionen.
- Luftkombos unterstützen Schlagtrefferzonen mit und ohne Kralle.
- **L/M/H/EX-Flying-Barcelona-Attack-Schläge können juggeln und erzeugen fortlaufende Luft-Juggle-Reaktionen**, von beiden Wänden und mit oder ohne Kralle. EX-Abflugschläge erhalten zusätzliche Juggle-Toleranz.
- **Izuna Drop kann gejugglelte Luftgegner fangen und beschädigen**, mit erhaltenen passenden normalen und EX-Fangwegen.
- **Luftwurf ist bei Verfolgung und Lufterholung verfügbar.** Der eigene Schadensabschluss ist korrigiert, damit erfolgreiches Juggle-Fangen Schaden verursacht; Grundschaden und normales Komboscaling bleiben erhalten.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen Salto-Erholung.

### Yang

- **Nahes stehendes HP schleudert nur beim zweiten Treffer hoch.** Der erste behält seine Bodenreaktion.
- **Nahes stehendes MK behält seinen natürlichen Launcher und erhält Verfolgung mit gehaltenem Oben.**
- **L/M/H-Dive-Kicks sind bei Verfolgung verfügbar und erzeugen einen fortlaufenden Luft-Juggle statt eines Resets.**
- Luftkombosystem und Launcher-Regeln unterstützen auch **Seiei-Enbu-Varianten**, mit ursprünglichen Aktivierungs-/Effektregeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen die Salto-Erholung im Cody-Stil.
- **Die Filmsequenz-Unterbrechung von Ultra 2 ist behoben**: Der Gegner verschwindet nicht mehr, erscheint nicht über dem Bildschirm und bleibt nicht schwebend hängen. Tatsächliche Ultra-Schlagtreffer behalten die gemeinsame Aufnahmemöglichkeit.

### Yun

- **Nahes stehendes HP schleudert nur beim zweiten/letzten Treffer hoch.** Der erste behält seine Bodenreaktion.
- **Nahes stehendes MK behält seinen natürlichen Launcher und erhält Verfolgung mit gehaltenem Oben.**
- **L/M/H-Dive-Kicks sind während Luftkombos verfügbar und erzeugen einen fortlaufenden Luft-Juggle statt eines Resets.**
- Launcher-, Luftkombo- und Dive-Kick-Änderungen gelten auch für **Genei-Jin-Varianten**, mit ursprünglichem erhöhtem Angriffsschaden und Super-Timing.
- Schlag-Specials können juggeln.
- Erfolgreiche Abschlüsse und verfehlte Angriffe nutzen im normalen und Genei-Jin-Zustand die Salto-Erholung im Cody-Stil.

### Zangief

- **Nahes stehendes HK schleudert hoch.** Fernes HK behält seine Bodenreaktion und erhält keinen Verfolgungsabbruch.
- **Ultra 2, Siberian Blizzard, ist während Luftkombos verfügbar und kann nach Bodenabprallern fangen**, mit Juggle-tauglichem Fangen und Schadenstreffern.
- **EX Spinning Piledriver kann einen Luftgegner nach Bodenabprallern fangen**, mit erhaltenem ursprünglichem Bodengriff und Schadens-/Freigabeablauf. **L/M/H-SPD erhalten keine Luftaufnahme.**
- **Double Lariat und Quick Double Lariat verwenden wieder ursprüngliche USF4-Aktionsdaten und Juggle-Verhalten.**
- Andere Schlag-Specials behalten die gemeinsame Juggle-Treffermöglichkeit.
- Erholung nach Treffer und Verfehlen nutzt eine vollständige eigene Erholungsdrehung von Zangief und behebt frühere Rumpf-/Beinverzerrungen.

## Launcher und Installation

Der herunterladbare Launcher zeigt **USF4 TAG! pre-alpha v0.1**. **Revision 6** installiert den abgenommenen **Build 105** und richtet die getestete Simp-Version automatisch ein. Eine passende installierte Kopie wird wiederverwendet, andernfalls heruntergeladen und geprüft; fehlt Simp, ist Internet nötig. Der Startfehler nach Simp wurde behoben; **Patching complete** wurde in einem echten Ladevorgang bestätigt.

1. Steam-USF4-Ordner wählen und **Install Pre-Alpha** anklicken. Bereits vom Launcher verwaltete Installationen können aktualisiert werden.
2. **Launch USF4** anklicken und im **Hauptmenü** warten.
3. Zum Launcher zurückkehren und **Load Pre-Alpha** anklicken.
4. In Simp **tag_pre_v0100** auswählen und **Launch** anklicken.
5. Auf **Patching complete** warten, zum Spiel zurückkehren und **Standard-Ultra-Training** betreten.

Das Fenster bestätigt den Patchabschluss und den Start der Training-Betäubungsregel. Den Launcher bis dahin offen lassen. USF4 und Simp vor Installation, Update, Reparatur oder Entfernung normal beenden. Originaldateien und Spielstände bleiben erhalten; verwaltete Kampfupdates bewahren den vorherigen Build in einem Wiederherstellungsordner. Für das Originalspiel mit geschlossenem Simp eine frische Steam-Sitzung starten.

Das Menü **Manage** enthält:

- **Check for updates:** sucht einen neueren auf GitHub veröffentlichten Installer. Bei gewähltem Update wird dieser heruntergeladen, geprüft und installiert.
- **Open logs:** öffnet lokale Vorgangsdetails und Fehlerberichte.
- **Report a bug:** Problem beschreiben und kurze Diagnosevorschau prüfen; anschließend öffnet sich ein vorausgefülltes GitHub-Issue zum Prüfen und Absenden. Rohprotokolle und Dateien werden nicht automatisch hochgeladen.
- **Verify installation, Repair installation und Remove Pre-Alpha:** pflegen die verwaltete Installation und bewahren fremde oder veränderte Dateien.

## Tests und Umfang

Kampf-Build 105 wurde durch lokale Charaktertests abgenommen. Der reale Ladetest von Launcher-Revision 5 bestätigte Abschlussfenster und Start der Training-Betäubungsregel. Öffentliche Revision 6 behält diese Laufzeitkomponenten und ergänzt den geprüften automatischen Simp-Bezug. Dieser Starttest ist kein neuer vollständiger Gameplaytest aller Charaktere und bestätigt die Zusatzregel nicht für andere Modi.

Unabhängige Installationstests auf einem zweiten Rechner und vollständige Matchup-Abdeckung stehen noch aus. Die zuvor erwogene Mindestschadensgrenze für Ultras ist in diesem Build nicht umgesetzt.
