[English](../../ROSTER_CHANGES.md) · [Idiomas](../README.md)

# USF4 TAG Project — Cambios de personajes de la prealfa

**Prealfa v0.1 · Versión 0.1.0 · Build de combate aprobada 105 · Lanzador revisión 6 · 42 personajes compatibles · Actualizado el 28 de octubre de 2026**

Este documento cubre la prealfa de combate terminada. Selecciona personajes **Ultra estándar**. **Hugo y Hakan quedan pendientes.** Esta versión usa combates normales de un solo personaje y el HUD original; el juego por equipos/tag sigue siendo un trabajo independiente.

## Notación

- **LP / MP / HP:** puño ligero / medio / fuerte.
- **LK / MK / HK:** patada ligera / media / fuerte.
- **Close / far:** normal elegido según la distancia al rival.
- **QCF:** cuarto de círculo hacia delante. **QCB:** cuarto de círculo hacia atrás. **HCF:** medio círculo hacia delante.
- **2× QCF / 2× HCF:** realizar el movimiento dos veces.
- **PPP / KKK:** los tres puños / las tres patadas a la vez.
- Las direcciones son relativas al lado al que mira tu personaje. Los nombres de personajes, movimientos y botones del lanzador se conservan como en el documento inglés para poder identificarlos.

Los valores en fotogramas describen los ajustes y objetivos de equilibrio de la build. No todos los valores de inicio o ventaja se han medido de forma independiente dentro del juego. Los costes de barra, alturas, alcances y comandos originales siguen vigentes salvo cambio indicado.

## Sistema de combate compartido

### Lanzadores y persecución

Cada personaje compatible tiene al menos un lanzador. **Acierta con el lanzador y mantén Arriba para seguir al rival por el aire.** La persecución requiere un impacto. Para los lanzadores de varios golpes, la tabla indica qué impacto abre la persecución.

### Combos aéreos estándar

Las nuevas cadenas de normales se acceden mediante la persecución del lanzador. Los ataques de salto normales conservan sus rutas originales salvo los cambios particulares indicados abajo.

- Las cadenas siguen **ligero → medio → fuerte**, eligiendo puño o patada en cada nivel.
- Se pueden omitir niveles. **Solo LP, LK, MP o MK pueden iniciar la cadena normal de persecución; HP/HK no pueden iniciarla.** Los remates fuertes siguen disponibles tras un ligero o medio.
- Cada nivel se usa una sola vez como máximo. La ruta estándar excluye enlaces de igual fuerza y volver a normales más débiles.
- Ejemplos: **LP → MP → HP**, **LK → MK → HK**, **LP → MK → HP**, **MP → HK**.
- **HP o HK suele cerrar la cadena con un golpe descendente y rebote en el suelo.** Las secciones de Rufus, Chun-Li, Gen y Elena detallan sus remates.
- Los especiales aéreos, normales de comando, agarres y Ultras añadidos usan las rutas específicas de cada personaje. Acceder a un especial durante la recuperación no reinicia la cadena normal.

**Gen tiene su propia variante de cadena ligera/media.** El resto usa las reglas estándar, con las excepciones explícitas de target combos y continuaciones multigolpe. La regla de inicio ligero/medio también se aplica a ambas posturas de Gen y a las entradas por cancelación de salto de Fukiage de Makoto. Se conserva el acceso particular a especiales aéreos, agarres y normales de comando.

### Juggles, rebote en el suelo y recuperación

- Los normales medios/fuertes de suelo reciben la reacción aérea de juggle compartida. **Los LP/LK normales de suelo y salto conservan las propiedades y reacciones de juggle originales de USF4.** Los LP/LK de los combos aéreos de persecución mantienen las reacciones necesarias para continuar las cadenas.
- Los especiales de golpe y proyectiles indicados reciben mayor capacidad de conectar en juggle. Esto no convierte automáticamente su reacción original en flotación; los cambios de reacción concretos aparecen abajo.
- Los remates aéreos fuertes producen rebote en el suelo para continuar con ataques de suelo. Si no conecta ninguna continuación, el rival pasa por derribo y recuperación.
- La recuperación del combo aéreo usa una voltereta hacia delante u otra rotación original apropiada. Donde se indica, las correcciones particulares se aplican a remates acertados y ataques fallados.
- Los personajes compatibles usan su **avance rápido hacia delante Omega**, adaptado a sus movimientos estándar. **Dhalsim mantiene su avance de USF4 estándar.** No se convierten en versiones Omega completas.

### Excepciones de especiales ligeros

**Los especiales ligeros de suelo con movimiento Dragon Punch hacia delante conservan las propiedades y reacciones de juggle originales de USF4.** Afecta a LP y LK, incluidos los atajos aceptados para delante → abajo → abajo-delante. Se aplica a la familia de comandos, no solo a movimientos llamados Shoryuken: por ejemplo Cannon Spike, Seismic Hammer, Fukiage, Soul Throw, Banishing Flat y Tiger Knee ligeros. Los DP inversos quedan fuera.

Las versiones medias/fuertes/EX mantienen el comportamiento prealfa indicado. **Los especiales aéreos ligeros no se ven afectados por esta restauración.** Las bolas de fuego ligeras y demás especiales ligeros fuera de esa familia de DP de suelo también conservan sus cambios indicados.

### Aturdimiento durante combos de lanzador

**El aturdimiento positivo se reduce a la mitad desde el golpe que realmente lanza hasta el final del combo**, incluidas las continuaciones aéreas, tras rebote y en el suelo. El daño a la vida no cambia. Un combo nuevo separado usa la tasa normal hasta otro lanzador acertado; fallarlo o que lo bloqueen no activa la regla. Se mantienen el redondeo original y el mínimo de un punto de aturdimiento.

En lanzadores multigolpe, la reducción empieza en el impacto que lanza; los impactos anteriores mantienen su escalado de aturdimiento normal.

La regla adicional solo se aplica actualmente en **Training Ultra estándar sin conexión**. El lanzador la activa automáticamente cuando termina Simp; espera **Patching complete** antes de entrar en Training. No hay que activar otro botón de aturdimiento. Los demás modos no reciben esta regla de sesión; ampliar su compatibilidad queda pendiente.

### Ultras tras rebote en el suelo

Las Ultras de golpe y proyectil pueden recoger rivales aéreos tras un rebote. Siguen importando el alcance, tiempo, altura y requisitos de cinemática originales. Se conservan daño y escalado de daño.

Las Ultras de agarre/captura, los contraataques y las activaciones sin ataque o curaciones mantienen su comportamiento, con dos excepciones solicitadas: **Ultra 2 de T. Hawk** y **Ultra 2 de Zangief** pueden recoger tras rebote en el suelo.

Las tolerancias ampliadas siguen siendo finitas. Las dos técnicas añadidas que borran explícitamente el contador previo de juggle son **Air Raging Demon de Evil Ryu** y **EX Shikusen de Juri**. Sus secciones explican estos cambios.

## Referencia rápida de lanzadores

Pulsa un nombre para ver todos sus cambios.

| Personaje | Lanzador / inicio de persecución |
| --- | --- |
| [Abel](#abel) | HP agachado lanza en el segundo impacto. El primero conserva su reacción normal de suelo. |
| [Adon](#adon) | HK de pie cercano lanza. HK de pie lejano conserva su comportamiento de suelo. |
| [Akuma](#akuma) | HP agachado lanza. |
| [Balrog](#balrog) | HP agachado lanza, incluida la versión actualizada activa. |
| [Blanka](#blanka) | HP de pie cercano lanza. HP lejano conserva su reacción de suelo. |
| [C. Viper](#c-viper) | HK de pie cercano lanza en el segundo impacto. El primero y HK de pie lejano conservan sus reacciones de suelo. |
| [Cammy](#cammy) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo. |
| [Chun-Li](#chun-li) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo. |
| [Cody](#cody) | HP agachado lanza desarmado y con cuchillo. Los puños con cuchillo conservan sus animaciones y rutas aéreas; las rutas de patada funcionan en ambas posturas. |
| [Dan](#dan) | HP agachado lanza. Dan usa las reglas de cadena aérea estándar. |
| [Decapre](#decapre) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo. |
| [Dee Jay](#dee-jay) | HP de pie sin dirección realiza el antiguo HP lejano a ambas distancias. Es el lanzador, tiene inicio de 7 fotogramas y cancela en especial al acertar o en guardia. |
| [Dhalsim](#dhalsim) | Atrás+HK, su normal de pie corto, lanza. HK de pie estirado ordinario conserva su reacción de suelo. |
| [Dudley](#dudley) | HP agachado lanza. |
| [E. Honda](#e-honda) | HP de pie cercano lanza, con inicio de 6 fotogramas en lugar de 8, y cancela en especial al acertar o en guardia. HP lejano conserva su reacción de suelo. |
| [El Fuerte](#el-fuerte) | HP agachado lanza. |
| [Elena](#elena) | HP de pie lanza, sin división entre HP cercano y lejano. |
| [Evil Ryu](#evil-ryu) | HP agachado lanza, con inicio de 5 fotogramas como objetivo final. HP de pie conserva reacción de suelo sin persecución. |
| [Fei Long](#fei-long) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo. |
| [Gen](#gen) | HP de pie en Mantis lanza en el último impacto.<br>HP de pie en Crane lanza en el segundo impacto. HK agachado en Crane también lanza. |
| [Gouken](#gouken) | MK agachado lanza. |
| [Guile](#guile) | HP agachado lanza. |
| [Guy](#guy) | HP de pie cercano usado solo lanza. HP lejano y HP de la cadena Bushin no reciben el lanzador de suelo.<br>El target combo MP → HP no lanza. Su último impacto recibe cancelación de salto manteniendo Arriba solo al acertar, que lleva a la ruta aérea. Bloqueo o fallo no la habilitan. |
| [Ibuki](#ibuki) | HP agachado lanza, conservando sus entradas originales de cancelación de salto. |
| [Juri](#juri) | HP agachado es el lanzador, incluidas las rutas correspondientes de Feng Shui Engine. HP de pie cercano vuelve a su comportamiento de suelo sin persecución. |
| [Ken](#ken) | HP agachado lanza. |
| [M. Bison](#m-bison) | HP agachado lanza, con inicio de 6 fotogramas y +1 en guardia. Cancela en especial al acertar o en guardia. |
| [Makoto](#makoto) | HK agachado es el lanzador. HP agachado conserva su barrido de suelo.<br>EX Fukiage conserva el lanzamiento natural y obtiene acceso al combo aéreo/Tsurugi mediante su cancelación de salto después de acertar.<br>La cancelación de salto de Fukiage normal y el acceso aéreo resultante requieren acertar. Se mantienen las direcciones de salto neutra, delante y atrás originales. |
| [Oni](#oni) | HP agachado lanza. |
| [Poison](#poison) | HK de pie cercano lanza en el último impacto. El primero y HK lejano conservan sus reacciones de suelo. |
| [Rolento](#rolento) | HP de pie cercano lanza. HP lejano conserva su reacción de suelo. |
| [Rose](#rose) | HP agachado lanza. |
| [Rufus](#rufus) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo. |
| [Ryu](#ryu) | HP agachado lanza. |
| [Sagat](#sagat) | MP de pie cercano lanza. MP lejano conserva su reacción de suelo. |
| [Sakura](#sakura) | HP agachado lanza, abriendo la persecución desde el primer impacto activo para continuar antes. |
| [Seth](#seth) | HP agachado lanza en el segundo/último impacto. El primero mantiene su reacción de suelo. |
| [T. Hawk](#t-hawk) | Solo HK de pie cercano lanza. HK de pie lejano no lanza ni obtiene persecución. |
| [Vega](#vega) | HK de pie cercano lanza en el segundo impacto. El primero y HK lejano conservan sus reacciones de suelo. |
| [Yang](#yang) | HP de pie cercano solo lanza en el segundo impacto. El primero conserva su reacción de suelo.<br>MK de pie cercano mantiene su lanzamiento natural y obtiene persecución manteniendo Arriba. |
| [Yun](#yun) | HP de pie cercano solo lanza en el segundo/último impacto. El primero conserva su reacción de suelo.<br>MK de pie cercano mantiene su lanzamiento natural y obtiene persecución manteniendo Arriba. |
| [Zangief](#zangief) | HK de pie cercano lanza. HK lejano conserva su reacción de suelo sin cancelación de persecución. |

## Cambios por personaje

Todos reciben el sistema compartido. Estas secciones indican lanzadores, otros cambios y excepciones. **Las excepciones comunes de normales ligeros ordinarios y DP ligeros de suelo se aplican a todas las listas generales de juggle de abajo.**

### Abel

- **HP agachado lanza en el segundo impacto.** El primero conserva su reacción normal de suelo.
- Las zonas de golpe de Change of Direction, Wheel Kick y Falling Sky pueden conectar en juggle.
- Los remates aéreos acertados y la recuperación al fallar usan la voltereta hacia delante de estilo Cody.
- Contra rivales ya aéreos, el segundo golpe de HP agachado usa la reacción compartida de caída corta.

### Adon

- **HK de pie cercano lanza.** HK de pie lejano conserva su comportamiento de suelo.
- **Jaguar Kick aéreo L/M/H/EX** está disponible en persecución, después de impactos aéreos ligeros/medios y durante la recuperación del combo aéreo.
- Jaguar Kick aéreo mantiene juggle continuo contra rivales aéreos en lugar de reiniciarlos en el aire.
- Las variantes de golpe de Jaguar Kick, Jaguar Tooth y Rising Jaguar pueden conectar en juggle.
- Los remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Akuma

- **HP agachado lanza.**
- **Bola de fuego aérea y Tatsu aéreo L/M/H/EX** disponibles en persecución, cadenas y recuperación aéreas, con comandos y restricciones normales.
- **El antiguo HK de pie lejano pasa a delante+HK**, utilizable a ambas distancias. HK de pie sin dirección usa el antiguo HK cercano a ambas distancias.
- Delante+MP, dive kick, Tatsu, Shoryuken M/H/EX, golpes de Demon Flip y bolas de fuego normales pueden conectar en juggle. **Shoryuken ligero de suelo conserva sus propiedades originales de USF4.**
- Persecución y recuperación usan la animación original de salto hacia delante de Akuma.

### Balrog

- **HP agachado lanza**, incluida la versión actualizada activa.
- Los puños de avance y uppercuts, sus variantes overhead/bajas, Buffalo Head y golpes de Turn Punch pueden conectar en juggle.
- Remates aéreos fuertes y ataques fallados usan recuperación en voltereta de estilo Cody, adaptada a sus guantes y esqueleto.
- Violent Buffalo recibe la recogida Ultra compartida; Dirty Bull mantiene su agarre.

### Blanka

- **HP de pie cercano lanza.** HP lejano conserva su reacción de suelo.
- **Electric Thunder acepta cinco pulsaciones de puño o QCF+P.** QCF+dos puños elige EX.
- **Todas las versiones de Electric Thunder mantienen el juggle original de USF4**, incluidos pulsos continuados y variantes EX. Se retiró de la electricidad la tolerancia compartida aumentada.
- Las variantes de golpe de bola rodante y vertical mantienen la capacidad de juggle añadida.
- Los remates acertados y ataques fallados usan recuperación en voltereta.

### C. Viper

- **HK de pie cercano lanza en el segundo impacto.** El primero y HK de pie lejano conservan sus reacciones de suelo.
- **Burning Kick aéreo L/M/H/EX** disponible en persecución y recuperación.
- **Ultra 2, Burning Dance, disponible durante combos aéreos**, con requisitos originales de comando, barra, altura y selección de Ultra.
- **Seismic Hammer M/H/EX puede conectar en juggle aéreo**, permitiendo continuaciones y recogidas tras rebote a su alcance normal. **Seismic Hammer ligero conserva sus propiedades originales de USF4.**
- La recuperación al acertar o fallar usa su voltereta hacia delante original completa.

### Cammy

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo.
- **Agarre aéreo, LP+LK, disponible en persecución y después de golpes aéreos ligeros/medios**, con captura y daño compatibles con juggle.
- **Cannon Spike M/H/EX obtiene mayor capacidad de juggle. Cannon Spike ligero mantiene las propiedades originales de USF4.** Esto no añade un comando aéreo para Cannon Spike.
- **Cannon Strike L/M/H/EX disponible en combos y recuperación aéreos.** Los impactos aéreos mantienen el juggle en vez de un reset.
- Las zonas de golpe de Spiral Arrow, Quick Spin Knuckle y deslizamiento Hooligan pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Chun-Li

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo.
- **Agarre aéreo disponible en persecución**, con captura y daño adaptados a rivales en juggle.
- **Yosokyaku disponible durante combos aéreos**, manteniendo abajo/abajo-delante+MK y sus continuaciones de tres pisotones.
- **Hyakuretsukyaku acepta QCF+K o cinco pulsaciones rápidas de patada.** Se mantienen continuaciones por pulsación repetida y reglas de barra EX.
- **HP aéreo → HP solo causa rebote en el segundo puño.** El primero mantiene al rival en el aire. Sin segundo puño, el primero recupera sin rebote. HP no enlaza con HK ni normales más débiles.
- **Hazanshu L/M/H/EX causa la reacción aérea de juggle compartida**, manteniendo sus reacciones de suelo.
- Los proyectiles Kikouken pueden conectar en juggle.
- Recuperación al acertar o fallar usa la voltereta corregida de estilo Cody.

### Cody

- **HP agachado lanza desarmado y con cuchillo.** Los puños con cuchillo conservan sus animaciones y rutas aéreas; las rutas de patada funcionan en ambas posturas.
- **Criminal Upper, todas las fuerzas y EX, permite FADC desde cualquier impacto con contacto**, incluidos los últimos del tornado. Requiere acertar o contacto en guardia.
- **Recuperación de HP Criminal Upper: 23 fotogramas. EX Criminal Upper: 25 fotogramas.**
- **Recuperación de HK Ruffian Kick: 25 fotogramas**, reducida desde 27.
- **Recuperación del Super LK/MK/HK: 22 fotogramas**, incluidas las ramas de continuación tras impacto acertado.
- Criminal Upper, Bad Stone, cuchillos lanzados y especiales de golpe pueden conectar en juggle.
- Remates fuertes acertados y combos aéreos fallados usan la voltereta hacia delante, incluidas las rutas de puño con cuchillo.

### Dan

- **HP agachado lanza.** Dan usa las reglas de cadena aérea estándar.
- **Dankukyaku aéreo L/M/H/EX y provocación aérea original disponibles en combos aéreos y recuperación.**
- **La provocación aérea conserva sus propiedades de impacto y juggle originales.** No se añade tolerancia de juggle mejorada a las provocaciones.
- Gadoken y Dankukyaku L/M/H/EX pueden conectar en juggle. **Koryuken M/H/EX mantiene los cambios prealfa; Koryuken ligero de suelo conserva las propiedades originales de USF4.**
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Decapre

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo.
- **Agarre aéreo disponible en persecución y recuperación aérea**, con captura y daño compatibles con juggle. Daño base y escalado originales se mantienen.
- **Rapid Dagger acepta QCF+P o las cinco pulsaciones de puño originales**, incluida la elección nativa de fuerza EX y barra.
- **Spiral Arrow aéreo L/M/H/EX disponible en persecución, cadenas y recuperación**, con comando y altura originales.
- Recuperación usa su voltereta original de salto hacia delante, corrigiendo la anterior pose de recibir daño.

### Dee Jay

- **HP de pie sin dirección realiza el antiguo HP lejano a ambas distancias.** Es el lanzador, tiene **inicio de 7 fotogramas** y cancela en especial al acertar o en guardia.
- **Atrás+HP realiza el antiguo HP de pie cercano a ambas distancias.** Conserva reacción de suelo y cancelaciones originales.
- **Double Rolling Sobat usa QCF+K**, incluido EX.
- **Double Rolling Sobat ligero usa sus datos de acción e impacto AE2012**, incluida invulnerabilidad a bajos y comportamiento en guardia, junto al nuevo QCF y la capacidad de juggle.
- **Knee Shot, abajo+LK, disponible en persecución y al terminar un normal aéreo.** Causa juggle aéreo continuo en lugar de reset.
- Knee Shot **no es una cancelación directa en cadena desde normales aéreos** y no reabre la cadena. La recuperación inmediata tras contacto fuerte no añade cancelación a Knee Shot.
- Air Slasher y las zonas de golpe de Machinegun Upper, Sobat y Jackknife Maximum pueden conectar en juggle.

### Dhalsim

- **Atrás+HK, su normal de pie corto, lanza.** HK de pie estirado ordinario conserva su reacción de suelo.
- Las cadenas de persecución usan sus normales aéreos cortos con entradas normales de puño/patada; no hay que mantener Atrás para esos botones aéreos.
- **Los tres ángulos de Yoga Spear y Yoga Mummy disponibles en persecución y recuperación**, con sus comandos originales: abajo+patada y abajo+HP, respectivamente.
- Bolas de fuego y especiales de golpe pueden conectar en juggle.
- **Avance rápido hacia delante restaurado al de USF4 estándar**, con movimiento, animación y tiempos de cancelación.
- Recuperación al acertar o fallar usa una pose original completa de voltereta de Dhalsim, corrigiendo deformación de piernas y pies.

### Dudley

- **HP agachado lanza.**
- Normales de comando de suelo y ataques de target combo reciben la reacción aérea de juggle compartida.
- Machinegun Blow, Jet Upper, Short Swing Blow, continuaciones de golpe de Ducking, Thunderbolt y partes de golpe de Cross Counter pueden conectar en juggle.
- Los combos aéreas usan ataques de salto hacia delante y recuperación propios de Dudley. Los proyectiles de rosa mantienen su comportamiento original.

### E. Honda

- **HP de pie cercano lanza**, con **inicio de 6 fotogramas en lugar de 8**, y cancela en especial al acertar o en guardia. HP lejano conserva su reacción de suelo.
- **EX Sumo Smash solo causa rebote en su último impacto descendente.** El golpe ascendente y versiones no-EX mantienen sus reacciones normales.
- **Hundred Hand Slap acepta cinco pulsaciones rápidas de puño o QCF+P.** Se restauran continuaciones por pulsación repetida junto a la entrada por movimiento; EX conserva su selección por botones de puño.
- Los especiales de golpe reciben la capacidad de juggle compartida. Los comandos de Headbutt, Sumo Smash, Super y Ultra mantienen sus requisitos originales.

### El Fuerte

- **HP agachado lanza.**
- **Agarre aéreo, LP+LK, disponible en persecución, cadenas ligeras/medias y recuperación.** La captura y ambas rutas de daño pueden conectar en juggle, manteniendo daño base y escalado originales.
- Los especiales de golpe pueden conectar en juggle; las rutas de carrera y salto de pared originales se conservan.
- Recuperación al acertar o fallar usa su voltereta original completa de salto hacia delante.
- Ambas Ultras de agarre mantienen su captura original según la excepción general.

### Elena

- **HP de pie lanza**, sin división entre HP cercano y lejano.
- Los seis normales aéreos están disponibles en persecución, incluida la corrección de los requisitos de entrada de los ataques aéreos propios del combo.
- **HK aéreo conserva ambos golpes; solo el último causa rebote en el suelo.** HP también ofrece un remate con rebote.
- Recuperación al acertar o fallar usa una rotación original de Mallet Smash, manteniendo su esqueleto.
- Los especiales de golpe pueden conectar en juggle. Brave Dance recibe la recogida Ultra compartida; Healing sigue original.

### Evil Ryu

- **HP agachado lanza**, con **inicio de 5 fotogramas** como objetivo final. HP de pie conserva reacción de suelo sin persecución.
- **Delante+MK recibe una reacción aérea de juggle continuo.**
- **Todas las patadas de hacha Ryusokyaku pueden hacer juggle. La versión EX causa rebote en el suelo**, en el último impacto si la acción es multigolpe.
- Hadoken, Shakunetsu, Tatsu de suelo/aéreo y Shoryuken M/H/EX pueden conectar en juggle. **Shoryuken ligero de suelo conserva sus propiedades originales de USF4.**
- **Tatsu aéreo L/M/H/EX disponible en persecución y rutas de combo aéreo.**
- **Air Raging Demon se añade usando la secuencia original de Oni.** Con barra Super llena, introduce **LP, LP, delante, LK, HP** en el aire. La cancelación desde normales de salto ordinarios permite activarlo.
- El sonido de activación usa voces y efectos adecuados de Evil Ryu.
- **Air Demon borra el contador previo de juggle del rival durante su ventana de agarre**, permitiendo usarlo tras juggles largos. El reinicio también ocurre si el intento falla; alcance, elegibilidad aérea e invulnerabilidad originales siguen vigentes.

### Fei Long

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo.
- Las zonas de golpe de Rekka, Shienkyaku y Rekkukyaku pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.
- Rekkashingeki recibe la recogida Ultra compartida; Gekirinken mantiene su contraataque.

### Gen

- **HP de pie en Mantis lanza en el último impacto.**
- **HP de pie en Crane lanza en el segundo impacto. HK agachado en Crane también lanza.**
- Los HP de pie cercanos y lejanos y las copias HP de target combo siguen la regla de último impacto de su postura.
- Cada postura tiene sus propios ataques y rutas de persecución aéreos.
- **Solo Gen puede usar puño y patada dentro de los niveles ligero y medio, en cualquier orden.** Cada normal se usa una vez. Se pueden omitir niveles, pero subir cierra los inferiores.
- **HP o HK termina la cadena. HP → HK y HK → HP están bloqueados.**
- Ejemplos: **LP → LK → MP → MK → HK**, **LK → LP → MK → MP → HP**, **LP → MK → HP**. Medio → ligero y fuerte → medio/ligero no se permiten.
- **HK aéreo de Crane de dos golpes solo causa rebote en el segundo.**
- **Hyakurenko acepta cinco pulsaciones rápidas de puño o QCF+P**, incluidas continuaciones originales por pulsación repetida. EX mantiene su selección por botones de puño.
- Los especiales de golpe pueden conectar en juggle. Ambas posturas usan volteretas de estilo Cody al acertar o fallar.

### Gouken

- **MK agachado lanza.**
- **Tatsu aéreo L/M/H/EX disponible en persecución y recuperación.**
- **Cada Tatsu de persecución avanza hacia el rival y tiene una sola ventana de daño por activación.** El Tatsu de salto normal conserva sus acciones multigolpe y entradas originales.
- Hadoken normales y especiales de golpe pueden conectar en juggle.
- Recuperación usa su voltereta hacia delante original completa.

### Guile

- **HP agachado lanza.**
- **HP de pie lejano, HK de pie lejano y HP agachado cancelan en especiales ordinarios al acertar o en guardia.**
- Los Sonic Boom normales y EX pueden conectar en juggle.
- **Agarres aéreos hacia delante y atrás disponibles en persecución**, con LP+LK; Atrás selecciona el agarre hacia atrás.
- **Los agarres aéreos de persecución usan reacciones originales de la víctima sin añadir rebote en el suelo.** Guile conserva la ruta aprobada de aterrizaje más rápido del atacante.
- **Restaurados los comandos de carga USF4 originales para todos los movimientos de Guile, incluidos Super y ambas Ultras.** Se eliminan los anteriores movimientos sustitutivos y atajos.

### Guy

- **HP de pie cercano usado solo lanza.** HP lejano y HP de la cadena Bushin no reciben el lanzador de suelo.
- **El target combo MP → HP no lanza.** Su último impacto recibe **cancelación de salto manteniendo Arriba solo al acertar**, que lleva a la ruta aérea. Bloqueo o fallo no la habilitan.
- **Kaiten Izuna Otoshi aéreo L/M/H/EX disponible en persecución, después de golpes ligeros/medios y en recuperación**, con captura compatible con juggle y finales de daño originales.
- Hozanto, Senpukyaku, golpes tras carrera y codazos Izuna pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Ibuki

- **HP agachado lanza**, conservando sus entradas originales de cancelación de salto.
- **Agarre aéreo, LP+LK, disponible en persecución y cadenas ligeras/medias.** Sus tres impactos de daño conectan en juggle, con daño y escalado originales.
- **Kunai L/M/H/EX disponible en combos aéreos y recuperación.** Los proyectiles normales/EX pueden juggle manteniendo sus reacciones y ángulos originales.
- Los especiales de golpe pueden conectar en juggle.
- Recuperación al acertar o fallar usa su voltereta original completa de salto hacia delante.

### Juri

- **HP agachado es el lanzador**, incluidas las rutas correspondientes de Feng Shui Engine. HP de pie cercano vuelve a su comportamiento de suelo sin persecución.
- **Shikusen L/M/H/EX disponible en combos aéreos y recuperación**, con entradas de continuación originales.
- **El último golpe de EX Shikusen restaura el rebote de pared original.** Se repara la reacción mural original compartida usada contra Ryu, para que el rival siga la animación de daño y ruta de rebote correctas.
- **Todas las ventanas de ataque EX iniciales y de continuación borran el contador previo de juggle del rival**, permitiendo seguir la secuencia EX tras juggles largos. También se reinicia si esas ventanas EX fallan. Shikusen normal no recibe reinicios.
- Los Fuhajin normales reciben juggle aéreo continuo; Senpusha y Shikusen pueden conectar en juggle.
- Recuperación al acertar o fallar usa volteretas de estilo Cody.
- Activación y reglas de cadena normales de Feng Shui Engine se mantienen; su nueva persecución usa las reglas aéreas estándar.

### Ken

- **HP agachado lanza.**
- **HK de pie cercano empuja un 20% menos al acertar, tiene 16 fotogramas de recuperación y +5 en un impacto normal de suelo.** Conserva el bonus de contraataque.
- **MK de pie cercano empuja un 25% menos al acertar.**
- **MP de pie cercano, apertura del target combo, tiene inicio de 4 fotogramas.** Su continuación HP sigue disponible.
- **Tatsu aéreo usa el movimiento y tiempos del antiguo juego base.** Daño, barra y geometría de impacto originales se conservan.
- Los normales aéreos neutros/direccionales ordinarios reciben **cancelación a Tatsu aéreo al acertar o en guardia**. Tatsu normal/EX también está disponible en persecución, cadenas y recuperación aérea del remate fuerte.
- Hadoken normal/EX y Tatsu de suelo/aéreo pueden conectar en juggle. **Shoryuken ligero de suelo conserva sus propiedades originales de USF4; M/H/EX mantienen sus cambios prealfa.**

### M. Bison

- **HP agachado lanza**, con **inicio de 6 fotogramas y +1 en guardia**. Cancela en especial al acertar o en guardia.
- **Double Knee Press pasa a HCF+K. Psycho Crusher pasa a HCF+P.** Normal y EX también aceptan **abajo-atrás → abajo → abajo-delante → delante** con los botones adecuados.
- **EX Head Press produce un rebote en el suelo más alto.** Solo EX Head Press recibe esa altura adicional; Head Press normal y remates fuertes compartidos conservan sus reacciones.
- **MP → MP, Hell Attack, disponible al acertar durante la persecución.** Su continuación lleva a HP o HK. Ejemplos: **MP → MP → HK**, **LP → MP → MP → HP**. No permite bucles ni volver a normales más débiles.
- Las zonas de golpe de Knee Press, Psycho Crusher, Head Press, Skull Diver y Devil Reverse pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Makoto

- **HK agachado es el lanzador. HP agachado conserva su barrido de suelo.**
- **Tsurugi L/M/H/EX, la patada de hacha aérea, disponible en persecución, cadenas y recuperación.**
- **EX Oroshi causa rebote en el suelo.** Oroshi no-EX no recibe ese rebote.
- **HP agachado cancela en especiales ordinarios solo al acertar**, incluidos Hayate, Oroshi, Fukiage y Karakusa. No añade cancelación en guardia ni al fallar.
- **EX Fukiage conserva el lanzamiento natural y obtiene acceso al combo aéreo/Tsurugi mediante su cancelación de salto después de acertar.**
- **La cancelación de salto de Fukiage normal y el acceso aéreo resultante requieren acertar.** Se mantienen las direcciones de salto neutra, delante y atrás originales.
- **Inicio de Fukiage fuerte pasa de 13 a 11 fotogramas.**
- Las familias de golpes Hayate, Oroshi, Fukiage y Tsurugi pueden conectar en juggle.

### Oni

- **HP agachado lanza.**
- **Zanku Hadosho disponible en persecución, después de golpes aéreos ligeros/medios y en recuperación**, incluidas variantes de botones EX originales. Sus partes ofensivas mantienen juggle aéreo continuo.
- **Tatsu aéreo L/M/H/EX y Messatsu-Gozanku, Ultra 1 aérea, disponibles en combos aéreos y recuperación**, con requisitos normales de barra, altura y selección de Ultra.
- Los Gohado/Gorai normales reciben juggle aéreo continuo; especiales de golpe y ataques de comando/target combo reciben las propiedades compartidas.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.
- Los Super Raging Demon terrestres y aéreos de Oni conservan su comportamiento original.

### Poison

- **HK de pie cercano lanza en el último impacto.** El primero y HK lejano conservan sus reacciones de suelo.
- Bolas de fuego normales y especiales de golpe pueden conectar en juggle.
- Remates acertados y ataques fallados usan su voltereta original completa de salto hacia delante.
- Love Storm recibe la recogida Ultra compartida; Poison Kiss mantiene su agarre.

### Rolento

- **HP de pie cercano lanza.** HP lejano conserva su reacción de suelo.
- MP aéreo de varias fases mantiene sus dos partes de impacto originales en el kit estándar.
- Los Stinger y especiales de golpe pueden conectar en juggle.
- Remates acertados y ataques fallados usan su voltereta hacia delante original completa. Las rutas originales de pogo y aterrizaje acrobático siguen intactas.

### Rose

- **HP agachado lanza.**
- **Soul Throw M/H/EX mantiene sus recogidas tras rebote en el suelo**, con elegibilidad correspondiente en captura de combo y final de daño. **Soul Throw ligero conserva sus propiedades originales de USF4.** Sigue empezando desde el suelo; se aplican alcance y condiciones de captura originales.
- Soul Spark recibe juggle aéreo continuo. Las partes de golpe de Soul Spiral y Soul Reflect pueden juggle; los registros de captura de Reflect siguen originales.
- Remates acertados y ataques fallados usan recuperación en voltereta. **La recuperación del remate HP incluye la animación original de retorno de la bufanda**, corrigiendo su deformación en ambos lados.

### Rufus

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo.
- **HP aéreo causa rebote en el suelo. HK aéreo conserva su juggle original de dos golpes**, sin rebote ni derribo forzado añadidos. Ambos fuertes cierran la cadena; HK completa su segundo impacto antes de recuperar.
- **Falcon Kick disponible en persecución, después de golpes aéreos ligeros/medios y en recuperación.** Sus impactos aéreos mantienen juggle continuo en vez de reset.
- Las zonas de golpe de Galactic Tornado, Messiah y Snake Strike pueden conectar en juggle.
- Remates acertados y ataques fallados usan la voltereta reparada, corrigiendo el estiramiento/torsión anterior del cuerpo.

### Ryu

- **HP agachado lanza.**
- **Un HP de pie único usa el antiguo HP cercano a ambas distancias**, con **inicio de 4 fotogramas**. Se elimina el HP lejano separado; HP de pie usa un solo botón.
- **HK de pie cercano empuja un 20% menos**, y ambos golpes cancelan en especiales ordinarios al acertar o en guardia.
- **HK agachado cancela en especial al acertar o en guardia.** La cancelación a bola de fuego en guardia usa una ventana más tardía que las demás cancelaciones especiales.
- Hadoken normal/EX y Tatsu de suelo/aéreo pueden conectar en juggle. **Shoryuken ligero de suelo conserva sus propiedades originales de USF4; M/H/EX mantienen sus cambios prealfa.**
- **Tatsu aéreo hacia delante L/M/H/EX disponible en persecución y rutas aéreas.**
- **La velocidad de EX Hadoken depende de los dos puños usados:**

| Botones | Velocidad del proyectil |
| --- | --- |
| LP+HP | Lenta, igual que Hadoken LP normal |
| LP+MP | Media, igual que Hadoken MP normal |
| MP+HP | Velocidad EX original aumentada un 5% |

Se restaura la reacción original de Ryu como víctima de rebote mural junto al sistema separado de rebote en el suelo compartido, corrigiendo el conflicto heredado de reacción mural.

### Sagat

- **MP de pie cercano lanza.** MP lejano conserva su reacción de suelo.
- Tiger Shot altos/bajos y especiales de golpe pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.

### Sakura

- **HP agachado lanza**, abriendo la persecución desde el primer impacto activo para continuar antes.
- **El último golpe del Tatsu EX de suelo también lanza hacia persecución manteniendo Arriba**, contra rivales de suelo o aéreos.
- **Cada golpe dañino de Tatsu EX puede juggle**, con reacciones aéreas continuas y su lanzador final existente conservado.
- **Tatsu aéreo hacia delante L/M/H/EX disponible en persecución y rutas aéreas.**
- Tatsu de suelo L/M/H/EX y Hadoken normales/cargados/EX pueden conectar en juggle.
- **HK de pie cercano y lejano cancelan en especiales ordinarios al acertar o en guardia**, con **−1 en guardia** como objetivo configurado en el primer impacto activo.
- **Shouoken fuerte usa el calendario de inicio de la versión media, buscando inicio de 7 fotogramas.** Conserva la secuencia y daño de la versión fuerte.

### Seth

- **HP agachado lanza en el segundo/último impacto.** El primero mantiene su reacción de suelo.
- **Abajo+MK disponible en persecución**, conservando la secuencia original de tres pisotones.
- **Abajo+HK disponible en persecución**, con juggle aéreo continuo y altura mínima original. Abajo+HK en salto normal queda igual.
- Sonic Boom y especiales de golpe pueden conectar en juggle.
- Persecución y recuperación al acertar/fallar usan su voltereta hacia delante original completa.

### T. Hawk

- **Solo HK de pie cercano lanza. HK de pie lejano no lanza ni obtiene persecución.**
- En combos aéreos, **PPP activa Condor Dive normal; KKK activa EX Condor Dive**. Rigen altura y barra originales. La continuación EX PPP original desde EX Tomahawk sigue en su ruta de origen.
- **Tomahawk Buster restaurado a datos USF4 estándar**, incluidos impactos por fuerza, tiempos y ajustes de juggle originales.
- **Ultra 2, Raging Slash, puede capturar un rival aéreo tras rebote en el suelo**, con captura e impactos de daño compatibles. Ultra 1 y otros agarres de comando quedan originales.
- Los demás especiales de golpe mantienen su capacidad de juggle añadida.
- Remates acertados y ataques fallados usan recuperación en voltereta.

### Vega

- **HK de pie cercano lanza en el segundo impacto.** El primero y HK lejano conservan sus reacciones de suelo.
- Los combos aéreos admiten hitboxes de puño con y sin garra.
- **Los golpes de Flying Barcelona Attack L/M/H/EX pueden conectar en juggle con reacciones aéreas continuas**, desde ambas paredes y con/sin garra. Los golpes de despegue EX reciben tolerancia adicional.
- **Izuna Drop puede capturar y dañar rivales aéreos en juggle**, manteniendo las rutas de captura normales y EX correspondientes.
- **Agarre aéreo disponible en persecución y recuperación aérea.** Se corrige su final de daño propio del combo para que una captura en juggle haga daño, con daño base y escalado normales originales.
- Remates acertados y ataques fallados usan recuperación en voltereta.

### Yang

- **HP de pie cercano solo lanza en el segundo impacto.** El primero conserva su reacción de suelo.
- **MK de pie cercano mantiene su lanzamiento natural y obtiene persecución manteniendo Arriba.**
- **Dive kicks L/M/H disponibles en persecución, con juggle aéreo continuo en vez de reset.**
- Kit aéreo y reglas de lanzador también admiten **variantes Seiei Enbu**, con activación y efectos originales.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody.
- **Corregida la interrupción cinematográfica de Ultra 2**, evitando que el rival desaparezca, reaparezca sobre la pantalla y quede suspendido. Los impactos reales de golpe Ultra mantienen la recogida compartida.

### Yun

- **HP de pie cercano solo lanza en el segundo/último impacto.** El primero conserva su reacción de suelo.
- **MK de pie cercano mantiene su lanzamiento natural y obtiene persecución manteniendo Arriba.**
- **Dive kicks L/M/H disponibles en combos aéreos, con juggle aéreo continuo en vez de reset.**
- Cambios de lanzador, combo aéreo y dive kick cubren las **variantes Genei Jin**, con daño potenciado y tiempos Super originales.
- Los especiales de golpe pueden conectar en juggle.
- Remates acertados y ataques fallados usan recuperación en voltereta de estilo Cody en estados normal y Genei Jin.

### Zangief

- **HK de pie cercano lanza.** HK lejano conserva su reacción de suelo sin cancelación de persecución.
- **Ultra 2, Siberian Blizzard, disponible en combos aéreos y capaz de capturar tras rebote en el suelo**, con captura e impactos de daño compatibles con juggle.
- **EX Spinning Piledriver puede capturar un rival aéreo tras rebote en el suelo**, conservando agarre de suelo y secuencia original de daño/liberación. **SPD L/M/H no reciben la recogida aérea.**
- **Double Lariat y Quick Double Lariat restaurados a acciones y juggle USF4 originales.**
- Los demás especiales de golpe conservan la capacidad de juggle compartida.
- Recuperación al acertar o fallar usa una rotación de recuperación original completa de Zangief, corrigiendo las deformaciones anteriores de torso y piernas.

## Lanzador e instalación

El lanzador descargable muestra **USF4 TAG! pre-alpha v0.1**. La **revisión 6** instala la **build 105** aprobada y configura automáticamente la versión probada de Simp. Reutiliza una copia instalada idéntica o la descarga y verifica; hace falta Internet si falta Simp. Se corrigió el fallo de inicio después de Simp; **Patching complete** se confirmó en una carga real.

1. Elige la carpeta Steam de USF4 y pulsa **Install Pre-Alpha**. Las instalaciones existentes gestionadas pueden actualizarse.
2. Pulsa **Launch USF4** y espera en el **menú principal**.
3. Regresa al lanzador y pulsa **Load Pre-Alpha**.
4. En Simp selecciona **tag_pre_v0100** y pulsa **Launch**.
5. Espera **Patching complete**, vuelve al juego y entra en **Training Ultra estándar**.

La ventana confirma el parcheo y el arranque de la regla de aturdimiento de Training. Mantén abierto el lanzador hasta entonces. Sal normalmente de USF4 y Simp antes de instalar, actualizar, reparar o quitar. Se conservan archivos originales y partidas; las actualizaciones gestionadas guardan la build anterior en una carpeta de recuperación. Para jugar sin mod, inicia una sesión Steam nueva con Simp cerrado.

El menú **Manage** incluye:

- **Check for updates:** busca un instalador más reciente publicado en GitHub. Si eliges actualizar, lo descarga, verifica e instala.
- **Open logs:** abre detalles locales de operaciones e informes de error.
- **Report a bug:** permite describir el fallo y revisar una breve vista diagnóstica; abre después una issue GitHub prerrellenada para revisar y enviar. No sube registros ni archivos sin procesar automáticamente.
- **Verify installation, Repair installation y Remove Pre-Alpha:** mantienen la instalación gestionada preservando archivos ajenos o modificados.

## Pruebas y alcance

La build de combate 105 fue aprobada mediante pruebas locales por personaje. La carga real de la revisión 5 confirmó la ventana final y el arranque de la regla de aturdimiento de Training. La revisión pública 6 conserva ese runtime y añade adquisición automática verificada de Simp. Este control de inicio no equivale a una nueva prueba completa del roster ni confirma la regla extra en otros modos.

Siguen pendientes pruebas independientes de instalación en una segunda máquina y cobertura exhaustiva de enfrentamientos. El mínimo de daño Ultra propuesto anteriormente no está implementado en esta build.
