[English](../../ROSTER_CHANGES.md) · [Lingue](../README.md)

# USF4 TAG Project — Modifiche ai personaggi della pre-alpha

**Pre-alpha v0.1 · Versione 0.1.0 · Build di combattimento approvata 105 · Launcher revisione 6 · 42 personaggi supportati · Aggiornato il 28 ottobre 2026**

Questo documento descrive la pre-alpha di combattimento completata. Scegliete i personaggi **Ultra standard**. **Hugo e Hakan sono rimandati.** Questa versione usa incontri normali con un solo personaggio e l'HUD originale; il gioco a squadre/tag resta un lavoro separato.

## Notazione

- **LP / MP / HP:** pugno leggero / medio / pesante.
- **LK / MK / HK:** calcio leggero / medio / pesante.
- **Close / far:** attacco normale selezionato in base alla distanza dall'avversario.
- **QCF:** quarto di cerchio avanti. **QCB:** quarto di cerchio indietro. **HCF:** mezzo cerchio avanti.
- **2× QCF / 2× HCF:** eseguire due volte il movimento.
- **PPP / KKK:** tutti e tre i pugni / calci insieme.
- Le direzioni sono relative al lato verso cui guarda il personaggio. Nomi di personaggi, mosse e pulsanti del launcher restano quelli del documento inglese per facilitarne l'identificazione.

I valori in frame indicano impostazioni e obiettivi di bilanciamento della build. Non tutti i valori di avvio o vantaggio sono stati misurati indipendentemente nel gioco. Costi di barra, altezza, portata e comandi originali rimangono validi salvo modifiche indicate.

## Sistema di combattimento condiviso

### Launcher e inseguimento

Ogni personaggio supportato ha almeno un launcher. **Colpite con il launcher e tenete premuto Su per seguire l'avversario in aria.** Serve un colpo a segno. Per i launcher multicolpo, la tabella indica quale impatto abilita l'inseguimento.

### Combo aeree standard

Le nuove catene di attacchi normali si usano tramite l'inseguimento del launcher. Gli attacchi in salto ordinari mantengono i percorsi originali, salvo le modifiche specifiche sotto.

- Le catene seguono **leggero → medio → pesante**, scegliendo pugno o calcio per ogni potenza.
- Si possono saltare potenze. **Solo LP, LK, MP o MK possono iniziare la catena normale d'inseguimento; HP/HK non possono iniziarla.** I finali pesanti restano disponibili dopo un leggero o un medio.
- Ogni potenza si usa al massimo una volta. La catena standard esclude collegamenti della stessa potenza e ritorni a normali più deboli.
- Esempi: **LP → MP → HP**, **LK → MK → HK**, **LP → MK → HP**, **MP → HK**.
- **HP o HK normalmente conclude la catena con un colpo verso il basso e un rimbalzo a terra.** Le sezioni di Rufus, Chun-Li, Gen ed Elena specificano i loro finali.
- Speciali aerei, normali a comando, prese e Ultra aggiunti seguono i percorsi specifici sotto. Accedere a uno speciale durante il recupero non riavvia la catena normale.

**Gen ha una propria variante di catena leggera/media.** Gli altri usano le regole standard, con le eccezioni esplicite per target combo e continuazioni multicolpo. La partenza leggera/media vale anche per entrambe le posizioni di Gen e gli ingressi tramite jump cancel di Fukiage di Makoto. Rimane l'accesso specifico a speciali aerei, prese e normali a comando.

### Juggle, rimbalzo a terra e recupero

- I normali medi/pesanti a terra ricevono la reazione aerea di juggle condivisa. **LP/LK ordinari a terra e in salto conservano proprietà e reazioni di juggle originali di USF4.** LP/LK nelle combo aeree d'inseguimento mantengono le reazioni che consentono di continuare la catena.
- Gli speciali d'attacco e i proiettili elencati possono colpire più facilmente in juggle. Questa maggiore possibilità non trasforma automaticamente la reazione originale in uno stato fluttuante; le reazioni modificate sono specificate sotto.
- I finali aerei pesanti producono un rimbalzo a terra per ulteriori attacchi al suolo. Senza una continuazione a segno, l'avversario passa per atterramento e recupero.
- Il recupero aereo usa una capriola in avanti o una rotazione originale adatta. Dove indicato, le correzioni specifiche valgono per finali riusciti e attacchi a vuoto.
- I personaggi supportati usano il proprio **scatto in avanti Omega**, adattato alle mosse standard. **Dhalsim mantiene lo scatto in avanti USF4 standard.** Non diventano versioni Omega complete.

### Eccezioni per gli speciali leggeri

**Gli speciali leggeri a terra con movimento Dragon Punch in avanti mantengono le proprietà e reazioni di juggle USF4 originali.** Vale per LP e LK, comprese le scorciatoie accettate per avanti → giù → giù-avanti. Conta la famiglia di comando, non solo il nome Shoryuken: ad esempio Cannon Spike, Seismic Hammer, Fukiage, Soul Throw, Banishing Flat e Tiger Knee leggeri. I movimenti DP inversi sono esclusi.

Le versioni medie/pesanti/EX mantengono il comportamento pre-alpha indicato. **Gli speciali aerei leggeri non sono interessati da questo ripristino.** Le palle di fuoco leggere e gli altri speciali leggeri fuori dalla famiglia DP in avanti a terra mantengono le modifiche elencate.

### Stordimento nelle combo da launcher

**Lo stordimento positivo viene dimezzato dal colpo che effettivamente lancia fino alla fine della combo**, comprese le continuazioni aeree, dopo il rimbalzo e a terra. I danni alla vita non cambiano. Una nuova combo separata usa il tasso normale fino a un altro launcher a segno; un launcher parato o a vuoto non attiva la regola. Restano arrotondamento originale e minimo di un punto di stordimento.

Per i launcher multicolpo la riduzione parte dal colpo che lancia; i colpi precedenti mantengono il normale scaling dello stordimento.

La regola aggiuntiva vale attualmente solo nel **Training Ultra standard offline**. Il launcher la attiva automaticamente dopo Simp; aspettate **Patching complete** prima del Training. Non serve un pulsante separato. Gli altri modi non ricevono questa regola di sessione; il supporto più ampio resta da sviluppare.

### Ultra dopo il rimbalzo a terra

Le Ultra d'attacco e a proiettile possono riprendere bersagli aerei dopo il rimbalzo. Restano importanti portata, tempismo, altezza e condizioni cinematiche originali. Danni e scaling dei danni sono preservati.

Ultra a presa/cattura, contrattacchi e attivazioni senza attacco o cure mantengono il comportamento esistente, con due eccezioni richieste: **Ultra 2 di T. Hawk** e **Ultra 2 di Zangief** possono riprendere dopo il rimbalzo.

Le tolleranze maggiorate restano finite. Solo le due mosse aggiunte **Air Raging Demon di Evil Ryu** e **EX Shikusen di Juri** azzerano esplicitamente il precedente contatore di juggle del bersaglio. I rispettivi paragrafi lo spiegano.

## Riferimento rapido dei launcher

Selezionate un nome per vedere tutte le modifiche.

| Personaggio | Launcher / avvio inseguimento |
| --- | --- |
| [Abel](#abel) | HP accovacciato lancia al secondo colpo. Il primo mantiene la reazione normale a terra. |
| [Adon](#adon) | HK in piedi vicino lancia. HK in piedi lontano mantiene il comportamento a terra. |
| [Akuma](#akuma) | HP accovacciato lancia. |
| [Balrog](#balrog) | HP accovacciato lancia, inclusa la versione aggiornata attiva. |
| [Blanka](#blanka) | HP in piedi vicino lancia. HP lontano mantiene la reazione a terra. |
| [C. Viper](#c-viper) | HK in piedi vicino lancia al secondo colpo. Il primo colpo e HK in piedi lontano mantengono le reazioni a terra. |
| [Cammy](#cammy) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra. |
| [Chun-Li](#chun-li) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra. |
| [Cody](#cody) | HP accovacciato lancia sia disarmato sia con il coltello. I pugni con coltello mantengono animazioni e percorsi aerei propri; i percorsi di calcio funzionano in entrambe le posizioni. |
| [Dan](#dan) | HP accovacciato lancia. Dan usa le regole standard delle catene aeree. |
| [Decapre](#decapre) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra. |
| [Dee Jay](#dee-jay) | HP in piedi senza direzione esegue il precedente HP lontano a entrambe le distanze. È il launcher, ha avvio di 7 frame e si cancella in speciale a segno o in parata. |
| [Dhalsim](#dhalsim) | Indietro+HK, il normale corto in piedi, lancia. HK in piedi allungato ordinario mantiene la reazione a terra. |
| [Dudley](#dudley) | HP accovacciato lancia. |
| [E. Honda](#e-honda) | HP in piedi vicino lancia, con avvio di 6 frame invece di 8, e si cancella in speciale a segno o in parata. HP lontano mantiene la reazione a terra. |
| [El Fuerte](#el-fuerte) | HP accovacciato lancia. |
| [Elena](#elena) | HP in piedi lancia, senza distinzione tra HP vicino e lontano. |
| [Evil Ryu](#evil-ryu) | HP accovacciato lancia, con avvio di 5 frame come obiettivo finale. HP in piedi mantiene la reazione a terra e non concede inseguimento. |
| [Fei Long](#fei-long) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra. |
| [Gen](#gen) | HP in piedi Mantis lancia all'ultimo colpo.<br>HP in piedi Crane lancia al secondo colpo. Anche HK accovacciato Crane lancia. |
| [Gouken](#gouken) | MK accovacciato lancia. |
| [Guile](#guile) | HP accovacciato lancia. |
| [Guy](#guy) | HP in piedi vicino usato da solo lancia. HP lontano e HP della catena Bushin non ricevono il launcher a terra.<br>La target combo MP → HP non lancia. L'ultimo colpo riceve un jump cancel tenendo Su solo a segno, che porta al percorso aereo. Parata o vuoto non lo abilitano. |
| [Ibuki](#ibuki) | HP accovacciato lancia, conservando gli ingressi originali di jump cancel. |
| [Juri](#juri) | HP accovacciato è il launcher, comprese le vie corrispondenti di Feng Shui Engine. HP in piedi vicino ritorna al comportamento a terra senza inseguimento. |
| [Ken](#ken) | HP accovacciato lancia. |
| [M. Bison](#m-bison) | HP accovacciato lancia, con avvio di 6 frame e +1 in parata. Si cancella in speciale a segno o in parata. |
| [Makoto](#makoto) | HK accovacciato è il launcher. HP accovacciato mantiene la spazzata a terra.<br>EX Fukiage mantiene il lancio naturale e riceve accesso a combo aerea/Tsurugi tramite jump cancel dopo un colpo a segno.<br>Jump cancel di Fukiage normale e conseguente accesso aereo richiedono un colpo a segno. Restano le direzioni di salto originali neutra, avanti e indietro. |
| [Oni](#oni) | HP accovacciato lancia. |
| [Poison](#poison) | HK in piedi vicino lancia all'ultimo colpo. Primo colpo e HK lontano mantengono le reazioni a terra. |
| [Rolento](#rolento) | HP in piedi vicino lancia. HP lontano mantiene la reazione a terra. |
| [Rose](#rose) | HP accovacciato lancia. |
| [Rufus](#rufus) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra. |
| [Ryu](#ryu) | HP accovacciato lancia. |
| [Sagat](#sagat) | MP in piedi vicino lancia. MP lontano mantiene la reazione a terra. |
| [Sakura](#sakura) | HP accovacciato lancia, con accesso all'inseguimento dal primo colpo attivo per una continuazione anticipata. |
| [Seth](#seth) | HP accovacciato lancia al secondo/ultimo colpo. Il primo mantiene la reazione a terra. |
| [T. Hawk](#t-hawk) | Solo HK in piedi vicino lancia. HK in piedi lontano non lancia e non concede inseguimento. |
| [Vega](#vega) | HK in piedi vicino lancia al secondo colpo. Primo colpo e HK lontano mantengono le reazioni a terra. |
| [Yang](#yang) | HP in piedi vicino lancia solo al secondo colpo. Il primo mantiene la reazione a terra.<br>MK in piedi vicino mantiene il lancio naturale e riceve inseguimento tenendo Su. |
| [Yun](#yun) | HP in piedi vicino lancia solo al secondo/ultimo colpo. Il primo mantiene la reazione a terra.<br>MK in piedi vicino mantiene il lancio naturale e riceve inseguimento tenendo Su. |
| [Zangief](#zangief) | HK in piedi vicino lancia. HK lontano mantiene la reazione a terra senza cancellazione d'inseguimento. |

## Modifiche per personaggio

Tutti i personaggi sotto ricevono il sistema condiviso. Le sezioni indicano launcher, modifiche ulteriori ed eccezioni. **Le eccezioni condivise dei normali leggeri ordinari e dei DP leggeri a terra valgono per tutti gli elenchi generali di juggle sotto.**

### Abel

- **HP accovacciato lancia al secondo colpo.** Il primo mantiene la reazione normale a terra.
- Le hitbox d'attacco di Change of Direction, Wheel Kick e Falling Sky possono colpire in juggle.
- Finali aerei riusciti e recupero a vuoto usano la capriola in avanti in stile Cody.
- Contro un avversario già in aria, il secondo colpo di HP accovacciato usa la reazione condivisa di caduta breve.

### Adon

- **HK in piedi vicino lancia.** HK in piedi lontano mantiene il comportamento a terra.
- **Jaguar Kick aereo L/M/H/EX** è disponibile nell'inseguimento, dopo colpi aerei leggeri/medi e durante il recupero della combo aerea.
- Jaguar Kick aereo mantiene un juggle continuo contro bersagli aerei invece di un reset aereo.
- Le varianti d'attacco di Jaguar Kick, Jaguar Tooth e Rising Jaguar possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Akuma

- **HP accovacciato lancia.**
- **Palla di fuoco aerea e Tatsu aereo L/M/H/EX** sono disponibili in inseguimento, catene e recupero aerei, con comandi e restrizioni normali.
- **Il precedente HK in piedi lontano diventa avanti+HK**, utilizzabile a entrambe le distanze. HK in piedi senza direzione usa il precedente HK vicino a entrambe le distanze.
- Avanti+MP, dive kick, Tatsu, Shoryuken M/H/EX, attacchi di Demon Flip e palle di fuoco ordinarie possono colpire in juggle. **Shoryuken leggero a terra mantiene le proprietà USF4 originali.**
- Inseguimento e recupero usano l'animazione originale di salto in avanti di Akuma.

### Balrog

- **HP accovacciato lancia**, inclusa la versione aggiornata attiva.
- Dash punch e uppercut, varianti overhead/basse, Buffalo Head e attacchi di Turn Punch possono colpire in juggle.
- Finali aerei pesanti e attacchi a vuoto usano il recupero in capriola in stile Cody, adattato a guanti e scheletro.
- Violent Buffalo riceve la ripresa Ultra condivisa; Dirty Bull mantiene il comportamento di presa.

### Blanka

- **HP in piedi vicino lancia.** HP lontano mantiene la reazione a terra.
- **Electric Thunder accetta cinque pressioni di pugno oppure QCF+P.** QCF+due pugni seleziona EX.
- **Tutte le versioni di Electric Thunder mantengono il juggle USF4 originale**, compresi impulsi continuati e varianti EX. La tolleranza condivisa aumentata è stata rimossa dall'elettricità.
- Le varianti d'attacco rotolanti e di palla verticale mantengono la possibilità aggiunta di juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola.

### C. Viper

- **HK in piedi vicino lancia al secondo colpo.** Il primo colpo e HK in piedi lontano mantengono le reazioni a terra.
- **Burning Kick aereo L/M/H/EX** è disponibile in inseguimento e recupero.
- **Ultra 2, Burning Dance, è disponibile nelle combo aeree**, con i requisiti originali di comando, barra, altezza e scelta dell'Ultra.
- **Seismic Hammer M/H/EX può colpire bersagli aerei in juggle**, consentendo continuazioni e riprese dopo rimbalzo alla portata normale. **Seismic Hammer leggero mantiene le proprietà USF4 originali.**
- Il recupero dopo colpo a segno o a vuoto usa la sua capriola in avanti originale completa.

### Cammy

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra.
- **Presa aerea, LP+LK, disponibile in inseguimento e dopo colpi aerei leggeri/medi**, con cattura e danno compatibili con il juggle.
- **Cannon Spike M/H/EX ottiene maggiore possibilità di juggle. Cannon Spike leggero mantiene le proprietà USF4 originali.** Non viene aggiunto un comando aereo per Cannon Spike.
- **Cannon Strike L/M/H/EX è disponibile in combo e recupero aerei.** I colpi aerei mantengono il juggle invece di resettare il bersaglio.
- Le hitbox d'attacco di Spiral Arrow, Quick Spin Knuckle e scivolata Hooligan possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Chun-Li

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra.
- **Presa aerea disponibile in inseguimento**, con cattura e danno adattati ai bersagli in juggle.
- **Yosokyaku è disponibile nelle combo aeree**, conservando giù/giù-avanti+MK e le continuazioni con tre pestate originali.
- **Hyakuretsukyaku accetta QCF+K o cinque rapide pressioni di calcio.** Restano continuazioni a pressioni ripetute e regole di barra EX.
- **HP aereo → HP causa rimbalzo solo al secondo pugno.** Il primo tiene l'avversario in aria. Senza il secondo, il primo recupera senza rimbalzo. HP non può collegarsi a HK o normali più deboli.
- **Hazanshu L/M/H/EX causa la reazione aerea di juggle condivisa**, mantenendo le reazioni a terra.
- I proiettili Kikouken possono colpire in juggle.
- Recupero a segno e a vuoto usa la capriola corretta in stile Cody.

### Cody

- **HP accovacciato lancia sia disarmato sia con il coltello.** I pugni con coltello mantengono animazioni e percorsi aerei propri; i percorsi di calcio funzionano in entrambe le posizioni.
- **Criminal Upper di tutte le potenze ed EX può essere cancellato in FADC da qualsiasi colpo con contatto**, compresi i colpi successivi del tornado. Occorre colpire o farsi parare.
- **Recupero HP Criminal Upper: 23 frame. Recupero EX Criminal Upper: 25 frame.**
- **Recupero HK Ruffian Kick: 25 frame**, ridotto da 27.
- **Recupero Super LK/MK/HK: 22 frame**, comprese le diramazioni successive al colpo riuscito.
- Criminal Upper, Bad Stone, coltelli lanciati e speciali d'attacco possono colpire in juggle.
- Finali pesanti riusciti e combo aeree a vuoto usano la capriola in avanti, anche nei percorsi di pugni col coltello.

### Dan

- **HP accovacciato lancia.** Dan usa le regole standard delle catene aeree.
- **Dankukyaku aereo L/M/H/EX e provocazione aerea originale sono disponibili nelle combo aeree e nel recupero.**
- **La provocazione aerea mantiene proprietà di impatto e juggle originali.** Le provocazioni non ricevono tolleranza aggiuntiva.
- Gadoken e Dankukyaku L/M/H/EX possono colpire in juggle. **Koryuken M/H/EX mantiene le modifiche pre-alpha; Koryuken leggero a terra mantiene le proprietà USF4 originali.**
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Decapre

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra.
- **Presa aerea disponibile in inseguimento e recupero aereo**, con cattura e danno compatibili con il juggle. Restano danni base e scaling originali.
- **Rapid Dagger accetta QCF+P o le cinque pressioni di pugno originali**, comprese la scelta della potenza EX e della barra.
- **Spiral Arrow aereo L/M/H/EX è disponibile in inseguimento, catene e recupero**, con comando e altezza originali.
- Il recupero usa la sua capriola originale di salto in avanti, correggendo la precedente posa da colpita.

### Dee Jay

- **HP in piedi senza direzione esegue il precedente HP lontano a entrambe le distanze.** È il launcher, ha **avvio di 7 frame** e si cancella in speciale a segno o in parata.
- **Indietro+HP esegue il precedente HP in piedi vicino a entrambe le distanze.** Mantiene reazione a terra e cancellazioni originali.
- **Double Rolling Sobat usa QCF+K**, compreso EX.
- **Double Rolling Sobat leggero usa azione e dati d'impatto AE2012**, inclusi invulnerabilità ai bassi e comportamento in parata, insieme al nuovo QCF e alla possibilità di juggle.
- **Knee Shot, giù+LK, è disponibile in inseguimento e dopo il completamento di un normale aereo.** Produce juggle continuo invece di reset aereo.
- Knee Shot **non è una cancellazione diretta in catena dai normali aerei** e non riapre la catena. Il recupero immediato dopo contatto pesante non aggiunge una cancellazione in Knee Shot.
- Proiettili Air Slasher e hitbox d'attacco di Machinegun Upper, Sobat e Jackknife Maximum possono colpire in juggle.

### Dhalsim

- **Indietro+HK, il normale corto in piedi, lancia.** HK in piedi allungato ordinario mantiene la reazione a terra.
- Le catene d'inseguimento usano i normali aerei corti con normali comandi di pugno/calcio; non serve tenere Indietro.
- **I tre angoli di Yoga Spear e Yoga Mummy sono disponibili in inseguimento e recupero**, con comandi originali: rispettivamente giù+calcio e giù+HP.
- Palle di fuoco e speciali d'attacco possono colpire in juggle.
- **Scatto in avanti ripristinato a USF4 standard**, con movimento, animazione e tempi di cancellazione originali.
- Recupero a segno e a vuoto usa un'intera posa originale di capriola di Dhalsim, correggendo deformazioni di gambe e piedi.

### Dudley

- **HP accovacciato lancia.**
- Normali a comando a terra e attacchi delle target combo ricevono la reazione aerea di juggle condivisa.
- Machinegun Blow, Jet Upper, Short Swing Blow, continuazioni d'attacco di Ducking, Thunderbolt e parti d'attacco di Cross Counter possono colpire in juggle.
- Le combo aeree usano attacchi di salto in avanti e recupero originali di Dudley. I proiettili rosa restano originali.

### E. Honda

- **HP in piedi vicino lancia**, con **avvio di 6 frame invece di 8**, e si cancella in speciale a segno o in parata. HP lontano mantiene la reazione a terra.
- **EX Sumo Smash causa rimbalzo solo all'ultimo colpo in discesa.** Salita e versioni non-EX mantengono le reazioni normali.
- **Hundred Hand Slap accetta cinque rapide pressioni di pugno o QCF+P.** Le continuazioni originali a pressioni ripetute sono ripristinate accanto al movimento; EX mantiene la selezione tramite pugni.
- Gli speciali d'attacco ricevono la possibilità condivisa di juggle. I comandi di Headbutt, Sumo Smash, Super e Ultra mantengono i requisiti originali.

### El Fuerte

- **HP accovacciato lancia.**
- **Presa aerea, LP+LK, disponibile in inseguimento, catene leggere/medie e recupero.** Cattura ed entrambi i percorsi di danno possono colpire in juggle, con danni base e scaling originali.
- Gli speciali d'attacco possono colpire in juggle; corsa e salti da parete restano intatti.
- Recupero a segno e a vuoto usa la sua capriola originale completa di salto in avanti.
- Entrambe le Ultra a presa mantengono la cattura originale secondo l'eccezione generale.

### Elena

- **HP in piedi lancia**, senza distinzione tra HP vicino e lontano.
- Tutti e sei i normali aerei sono disponibili in inseguimento, inclusa la correzione dei requisiti d'ingresso degli attacchi aerei dedicati.
- **HK aereo mantiene entrambi i colpi; solo l'ultimo causa rimbalzo a terra.** Anche HP offre un finale con rimbalzo.
- Recupero a segno e a vuoto usa una rotazione originale di Mallet Smash, con il suo scheletro.
- Gli speciali d'attacco possono colpire in juggle. Brave Dance ottiene la ripresa Ultra condivisa; Healing resta originale.

### Evil Ryu

- **HP accovacciato lancia**, con **avvio di 5 frame** come obiettivo finale. HP in piedi mantiene la reazione a terra e non concede inseguimento.
- **Avanti+MK riceve una reazione aerea di juggle continuo.**
- **Tutti i calci ad ascia Ryusokyaku possono jugglare. Il calcio EX causa rimbalzo a terra**, sul colpo finale se l'azione è multicolpo.
- Hadoken, Shakunetsu, Tatsu a terra/aereo e Shoryuken M/H/EX possono colpire in juggle. **Shoryuken leggero a terra mantiene le proprietà USF4 originali.**
- **Tatsu aereo L/M/H/EX è disponibile in inseguimento e nei percorsi aerei.**
- **Air Raging Demon viene aggiunto usando la sequenza originale di Oni.** Con barra Super piena, inserire **LP, LP, avanti, LK, HP** in aria. Le cancellazioni dai normali di salto ordinari ne permettono l'attivazione.
- Il suono d'attivazione di Air Demon usa voci ed effetti appropriati di Evil Ryu.
- **Air Demon azzera il precedente contatore di juggle dell'avversario durante la finestra di presa**, permettendo l'uso dopo juggle lunghi. L'azzeramento avviene anche se il tentativo fallisce; portata, requisiti aerei e invulnerabilità originali rimangono validi.

### Fei Long

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra.
- Le hitbox d'attacco di Rekka, Shienkyaku e Rekkukyaku possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.
- Rekkashingeki ottiene la ripresa Ultra condivisa; Gekirinken mantiene il contrattacco.

### Gen

- **HP in piedi Mantis lancia all'ultimo colpo.**
- **HP in piedi Crane lancia al secondo colpo. Anche HK accovacciato Crane lancia.**
- HP in piedi vicino e lontano, e le copie HP delle target combo, seguono la regola del colpo finale della rispettiva posizione.
- Entrambe le posizioni hanno attacchi e percorsi di inseguimento aerei propri.
- **Solo Gen può usare sia pugno sia calcio nelle fasce leggera e media, in entrambi gli ordini.** Ogni normale si usa una volta. Si possono saltare potenze, ma salire chiude le fasce più deboli.
- **HP oppure HK termina la catena. HP → HK e HK → HP sono bloccati.**
- Esempi: **LP → LK → MP → MK → HK**, **LK → LP → MK → MP → HP**, **LP → MK → HP**. Medio → leggero e pesante → medio/leggero non sono ammessi.
- **HK aereo Crane a due colpi causa rimbalzo solo al secondo.**
- **Hyakurenko accetta cinque rapide pressioni di pugno o QCF+P**, incluse le continuazioni originali. EX mantiene la selezione tramite pugni.
- Gli speciali d'attacco possono jugglare. Recupero a segno e a vuoto usa capriole in stile Cody in entrambe le posizioni.

### Gouken

- **MK accovacciato lancia.**
- **Tatsu aereo L/M/H/EX è disponibile in inseguimento e recupero.**
- **Ogni Tatsu d'inseguimento avanza verso l'avversario e ha una sola finestra di danno per attivazione.** Il Tatsu in salto ordinario mantiene azioni multicolpo e comandi originali.
- Hadoken ordinari e speciali d'attacco possono colpire in juggle.
- Il recupero usa la sua capriola in avanti originale completa.

### Guile

- **HP accovacciato lancia.**
- **HP in piedi lontano, HK in piedi lontano e HP accovacciato si cancellano in speciali ordinari a segno o in parata.**
- I Sonic Boom normali ed EX possono colpire in juggle.
- **Prese aeree avanti e indietro disponibili in inseguimento**, con LP+LK; Indietro seleziona la presa all'indietro.
- **Le prese aeree d'inseguimento usano le reazioni originali della vittima senza rimbalzo a terra aggiunto.** Rimane il percorso approvato di atterraggio più rapido di Guile.
- **Ripristinati i comandi a carica USF4 originali per tutte le mosse di Guile, inclusi Super ed entrambe le Ultra.** Rimossi i precedenti movimenti sostitutivi e scorciatoie.

### Guy

- **HP in piedi vicino usato da solo lancia.** HP lontano e HP della catena Bushin non ricevono il launcher a terra.
- **La target combo MP → HP non lancia.** L'ultimo colpo riceve un **jump cancel tenendo Su solo a segno**, che porta al percorso aereo. Parata o vuoto non lo abilitano.
- **Kaiten Izuna Otoshi aereo L/M/H/EX disponibile in inseguimento, dopo colpi leggeri/medi e nel recupero**, con cattura compatibile con il juggle e finali di danno originali.
- Hozanto, Senpukyaku, attacchi successivi alla corsa e gomitate Izuna possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Ibuki

- **HP accovacciato lancia**, conservando gli ingressi originali di jump cancel.
- **Presa aerea, LP+LK, disponibile in inseguimento e catene leggere/medie.** Tutti e tre i colpi di danno possono collegarsi in juggle, con danni e scaling originali.
- **Kunai L/M/H/EX disponibile nelle combo aeree e nel recupero.** I proiettili normali/EX possono jugglare mantenendo reazioni e angoli originali.
- Gli speciali d'attacco possono colpire in juggle.
- Recupero a segno e a vuoto usa la sua capriola originale completa di salto in avanti.

### Juri

- **HP accovacciato è il launcher**, comprese le vie corrispondenti di Feng Shui Engine. HP in piedi vicino ritorna al comportamento a terra senza inseguimento.
- **Shikusen L/M/H/EX disponibile nelle combo aeree e nel recupero**, con comandi di continuazione originali.
- **L'ultimo calcio di EX Shikusen ripristina il rimbalzo a parete originale.** La reazione murale originale condivisa usata contro Ryu è corretta, con animazione di danno e percorso di rimbalzo appropriati.
- **Tutte le finestre d'attacco EX iniziali e successive azzerano il precedente contatore di juggle del bersaglio**, permettendo la sequenza EX dopo juggle lunghi. Anche le finestre EX a vuoto eseguono questo azzeramento. Shikusen normale non riceve gli azzeramenti.
- I Fuhajin ordinari ricevono reazioni di juggle aereo continuo; Senpusha e Shikusen possono colpire in juggle.
- Recupero a segno e a vuoto usa capriole in stile Cody.
- Attivazione e catene ordinarie originali di Feng Shui Engine restano; il nuovo inseguimento usa le regole aeree standard.

### Ken

- **HP accovacciato lancia.**
- **HK in piedi vicino respinge il 20% in meno a segno, ha 16 frame di recupero e +5 su un normale colpo a terra.** Rimane il bonus counter hit.
- **MK in piedi vicino respinge il 25% in meno a segno.**
- **MP in piedi vicino, apertura della target combo, ha avvio di 4 frame.** La continuazione HP rimane disponibile.
- **Tatsu aereo usa movimento e tempi del vecchio gioco base.** Danni, barra e geometria d'impatto restano originali.
- I normali aerei ordinari neutri/direzionali si **cancellano in Tatsu aereo a segno o in parata**. Tatsu normale/EX è disponibile anche in inseguimento, catene e recupero aereo dei finali pesanti.
- Hadoken normale/EX e Tatsu a terra/aereo possono colpire in juggle. **Shoryuken leggero a terra mantiene le proprietà USF4 originali; M/H/EX mantengono le modifiche pre-alpha.**

### M. Bison

- **HP accovacciato lancia**, con **avvio di 6 frame e +1 in parata**. Si cancella in speciale a segno o in parata.
- **Double Knee Press diventa HCF+K. Psycho Crusher diventa HCF+P.** Normal ed EX accettano anche **giù-indietro → giù → giù-avanti → avanti** con i pulsanti appropriati.
- **EX Head Press causa un rimbalzo a terra più alto.** Solo EX Head Press riceve l'altezza aggiuntiva; Head Press normale e finali pesanti condivisi mantengono le reazioni esistenti.
- **MP → MP, Hell Attack, disponibile a segno durante l'inseguimento.** La continuazione può portare a HP o HK. Esempi: **MP → MP → HK**, **LP → MP → MP → HP**. Non può ripetersi in loop o tornare a normali più deboli.
- Le hitbox di Knee Press, Psycho Crusher, Head Press, Skull Diver e Devil Reverse possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Makoto

- **HK accovacciato è il launcher. HP accovacciato mantiene la spazzata a terra.**
- **Tsurugi L/M/H/EX, il calcio ad ascia aereo, disponibile in inseguimento, catene e recupero.**
- **EX Oroshi causa rimbalzo a terra.** Oroshi non-EX non lo riceve.
- **HP accovacciato si cancella in speciali ordinari solo a segno**, inclusi Hayate, Oroshi, Fukiage e Karakusa. Nessuna nuova cancellazione in parata o a vuoto.
- **EX Fukiage mantiene il lancio naturale e riceve accesso a combo aerea/Tsurugi tramite jump cancel dopo un colpo a segno.**
- **Jump cancel di Fukiage normale e conseguente accesso aereo richiedono un colpo a segno.** Restano le direzioni di salto originali neutra, avanti e indietro.
- **Avvio di Fukiage pesante ridotto da 13 a 11 frame.**
- Le famiglie d'attacco Hayate, Oroshi, Fukiage e Tsurugi possono colpire in juggle.

### Oni

- **HP accovacciato lancia.**
- **Zanku Hadosho disponibile in inseguimento, dopo colpi aerei leggeri/medi e nel recupero**, comprese le varianti EX originali dei pulsanti. Le parti offensive usano reazioni di juggle aereo continuo.
- **Tatsu aereo L/M/H/EX e Messatsu-Gozanku, Ultra 1 aerea, disponibili nelle combo aeree e nel recupero**, con requisiti normali di barra, altezza e selezione Ultra.
- I proiettili Gohado/Gorai ordinari ricevono juggle aereo continuo; speciali d'attacco e attacchi a comando/target combo ricevono le proprietà condivise.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.
- I Super Raging Demon a terra e aerei di Oni mantengono il comportamento originale.

### Poison

- **HK in piedi vicino lancia all'ultimo colpo.** Primo colpo e HK lontano mantengono le reazioni a terra.
- Palle di fuoco normali e speciali d'attacco possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano la sua capriola originale completa di salto in avanti.
- Love Storm ottiene la ripresa Ultra condivisa; Poison Kiss mantiene il comportamento di presa.

### Rolento

- **HP in piedi vicino lancia.** HP lontano mantiene la reazione a terra.
- MP aereo multifase conserva entrambe le parti d'impatto originali nel sistema aereo standard.
- I proiettili Stinger e gli speciali d'attacco possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano la sua capriola in avanti originale completa. Restano i percorsi originali di pogo e atterraggi acrobatici.

### Rose

- **HP accovacciato lancia.**
- **Soul Throw M/H/EX mantiene le riprese dopo rimbalzo a terra**, con requisiti corrispondenti per cattura di combo e finale di danno. **Soul Throw leggero mantiene le proprietà USF4 originali.** Inizia ancora da terra; valgono portata e condizioni di cattura originali.
- Soul Spark riceve juggle aereo continuo. Le parti d'attacco di Soul Spiral e Soul Reflect possono jugglare; i dati di cattura di Reflect restano originali.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola. **Il recupero del finale HP include l'animazione originale di ritorno della sciarpa**, correggendo la deformazione da entrambi i lati.

### Rufus

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra.
- **HP aereo causa rimbalzo a terra. HK aereo conserva il juggle originale a due colpi**, senza rimbalzo o atterramento forzato aggiunti. Entrambi concludono la catena; HK completa il secondo colpo prima del recupero.
- **Falcon Kick disponibile in inseguimento, dopo colpi aerei leggeri/medi e nel recupero.** I colpi aerei mantengono il juggle invece del reset.
- Le hitbox di Galactic Tornado, Messiah e Snake Strike possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano la capriola riparata, correggendo allungamenti e torsioni del corpo.

### Ryu

- **HP accovacciato lancia.**
- **Un unico HP in piedi usa il precedente HP vicino a entrambe le distanze**, con **avvio di 4 frame**. Rimosso il distinto HP lontano; HP in piedi usa un singolo pulsante.
- **HK in piedi vicino respinge il 20% in meno**, ed entrambi i colpi si cancellano in speciali ordinari a segno o in parata.
- **HK accovacciato si cancella in speciale a segno o in parata.** La cancellazione in palla di fuoco in parata usa una finestra più tarda delle altre cancellazioni speciali.
- Hadoken normale/EX e Tatsu a terra/aereo possono jugglare. **Shoryuken leggero a terra mantiene le proprietà USF4 originali; M/H/EX mantengono le modifiche pre-alpha.**
- **Tatsu aereo in avanti L/M/H/EX disponibile in inseguimento e percorsi aerei.**
- **La velocità di EX Hadoken dipende dai due pugni usati:**

| Pulsanti | Velocità del proiettile |
| --- | --- |
| LP+HP | Lenta, come Hadoken LP ordinario |
| LP+MP | Media, come Hadoken MP ordinario |
| MP+HP | Velocità EX originale aumentata del 5% |

La reazione originale di Ryu come vittima di rimbalzo a parete è ripristinata accanto al sistema separato di rimbalzo a terra condiviso, correggendo il conflitto murale ereditato.

### Sagat

- **MP in piedi vicino lancia.** MP lontano mantiene la reazione a terra.
- Tiger Shot alti/bassi e speciali d'attacco possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.

### Sakura

- **HP accovacciato lancia**, con accesso all'inseguimento dal primo colpo attivo per una continuazione anticipata.
- **L'ultimo colpo di Tatsu EX a terra lancia anche nell'inseguimento tenendo Su**, contro avversari a terra o aerei.
- **Ogni colpo di danno del Tatsu EX può jugglare**, con reazioni aeree continue e launcher finale esistente conservato.
- **Tatsu aereo in avanti L/M/H/EX disponibile in inseguimento e percorsi aerei.**
- Tatsu a terra L/M/H/EX e Hadoken ordinari/caricati/EX possono colpire in juggle.
- **HK in piedi vicino e lontano si cancellano in speciali ordinari a segno o in parata**, con **−1 in parata** come obiettivo impostato sul primo colpo attivo.
- **Shouoken pesante usa l'avvio della versione media, con obiettivo di 7 frame.** Restano sequenza e danni della versione pesante.

### Seth

- **HP accovacciato lancia al secondo/ultimo colpo.** Il primo mantiene la reazione a terra.
- **Giù+MK disponibile in inseguimento**, mantenendo la sequenza originale con tre pestate.
- **Giù+HK disponibile in inseguimento**, con juggle aereo continuo e altezza minima originale. Giù+HK in salto ordinario resta invariato.
- Sonic Boom e speciali d'attacco possono colpire in juggle.
- Inseguimento e recupero a segno/a vuoto usano la sua capriola in avanti originale completa.

### T. Hawk

- **Solo HK in piedi vicino lancia. HK in piedi lontano non lancia e non concede inseguimento.**
- Nelle combo aeree, **PPP attiva Condor Dive normale; KKK attiva EX Condor Dive**. Valgono altezza e barra originali. La continuazione EX PPP originale da EX Tomahawk resta sul percorso originale.
- **Tomahawk Buster ripristinato ai dati USF4 standard**, compresi numero di colpi per potenza, tempi e juggle originali.
- **Ultra 2, Raging Slash, può catturare bersagli aerei dopo rimbalzo a terra**, con cattura e danni compatibili. Ultra 1 e altre prese a comando rimangono originali.
- Gli altri speciali d'attacco mantengono la possibilità aggiunta di juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola.

### Vega

- **HK in piedi vicino lancia al secondo colpo.** Primo colpo e HK lontano mantengono le reazioni a terra.
- Le combo aeree supportano hitbox dei pugni con e senza artiglio.
- **Gli attacchi di Flying Barcelona Attack L/M/H/EX possono jugglare con reazioni aeree continue**, da entrambe le pareti e con/senza artiglio. Gli attacchi di decollo EX ricevono tolleranza aggiuntiva.
- **Izuna Drop può catturare e danneggiare bersagli aerei in juggle**, con percorsi di cattura normali ed EX pertinenti conservati.
- **Presa aerea disponibile in inseguimento e recupero aereo.** Il finale di danno dedicato è corretto perché la cattura in juggle causi danno, con danni base e scaling normali originali.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola.

### Yang

- **HP in piedi vicino lancia solo al secondo colpo.** Il primo mantiene la reazione a terra.
- **MK in piedi vicino mantiene il lancio naturale e riceve inseguimento tenendo Su.**
- **Dive kick L/M/H disponibili in inseguimento, con juggle aereo continuo invece di reset.**
- Sistema aereo e regole dei launcher supportano le **varianti Seiei Enbu**, mantenendo attivazione ed effetti originali.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody.
- **Corretta l'interruzione cinematica di Ultra 2**, evitando scomparsa dell'avversario, ricomparsa sopra lo schermo e sospensione permanente. I veri colpi d'attacco Ultra mantengono la ripresa condivisa.

### Yun

- **HP in piedi vicino lancia solo al secondo/ultimo colpo.** Il primo mantiene la reazione a terra.
- **MK in piedi vicino mantiene il lancio naturale e riceve inseguimento tenendo Su.**
- **Dive kick L/M/H disponibili nelle combo aeree, con juggle aereo continuo invece di reset.**
- Modifiche di launcher, combo aeree e dive kick coprono anche le **varianti Genei Jin**, mantenendo danni potenziati e tempi Super originali.
- Gli speciali d'attacco possono colpire in juggle.
- Finali riusciti e attacchi a vuoto usano il recupero in capriola in stile Cody negli stati normale e Genei Jin.

### Zangief

- **HK in piedi vicino lancia.** HK lontano mantiene la reazione a terra senza cancellazione d'inseguimento.
- **Ultra 2, Siberian Blizzard, disponibile nelle combo aeree e capace di catturare dopo rimbalzo a terra**, con cattura e colpi di danno compatibili con il juggle.
- **EX Spinning Piledriver può catturare un avversario aereo dopo rimbalzo a terra**, mantenendo presa al suolo e sequenza di danno/rilascio originali. **SPD L/M/H non ricevono la ripresa aerea.**
- **Double Lariat e Quick Double Lariat ripristinati ad azioni e juggle USF4 originali.**
- Gli altri speciali d'attacco mantengono la possibilità condivisa di juggle.
- Recupero a segno e a vuoto usa una rotazione di recupero originale completa di Zangief, correggendo le deformazioni di torso e gambe.

## Launcher e installazione

Il launcher scaricabile mostra **USF4 TAG! pre-alpha v0.1**. La **revisione 6** installa la **build 105** approvata e configura automaticamente la versione testata di Simp. Riutilizza una copia installata identica o la scarica e verifica; se Simp manca serve Internet. Il problema d'avvio dopo Simp è corretto; **Patching complete** è stato confermato in un caricamento reale.

1. Scegliete la cartella Steam di USF4 e premete **Install Pre-Alpha**. Le installazioni gestite esistenti possono essere aggiornate.
2. Premete **Launch USF4** e aspettate al **menu principale**.
3. Tornate al launcher e premete **Load Pre-Alpha**.
4. In Simp selezionate **tag_pre_v0100** e premete **Launch**.
5. Aspettate **Patching complete**, poi tornate al gioco ed entrate nel **Training Ultra standard**.

La finestra conferma fine delle patch e avvio della regola di stordimento Training. Tenete aperto il launcher fino ad allora. Uscite normalmente da USF4 e Simp prima di installare, aggiornare, riparare o rimuovere. File originali e salvataggi sono preservati; gli aggiornamenti gestiti conservano la build precedente in una cartella di recupero. Per giocare senza mod, avviate una nuova sessione Steam con Simp chiuso.

Il menu **Manage** include:

- **Check for updates:** cerca su GitHub un installer pubblicato più recente. Accettando l'aggiornamento lo scarica, verifica e installa.
- **Open logs:** apre dettagli locali delle operazioni e rapporti d'errore.
- **Report a bug:** permette di descrivere il problema e controllare una breve anteprima diagnostica, poi apre un'issue GitHub precompilata da rivedere e inviare. Log e file grezzi non vengono caricati automaticamente.
- **Verify installation, Repair installation e Remove Pre-Alpha:** gestiscono l'installazione preservando file estranei o modificati.

## Test e ambito

La build di combattimento 105 è stata approvata tramite prove locali per personaggio. Il caricamento reale della revisione 5 ha confermato finestra finale e avvio della regola di stordimento Training. La revisione pubblica 6 conserva quel runtime e aggiunge l'acquisizione automatica verificata di Simp. Questo controllo d'avvio non equivale a un nuovo test completo di gameplay di tutto il roster né al supporto della regola extra in altri modi.

Restano in attesa test d'installazione indipendenti su una seconda macchina e copertura completa degli abbinamenti. Il minimo di danno Ultra precedentemente proposto non è implementato in questa build.
