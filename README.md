# juegos-optometria

Juegos clásicos remasterizados con estética 8 bits como ejercicios de optometría.

## Juegos

| Juego | Basado en | Carpeta |
|---|---|---|
| Súper INOP | Super Mario Bros. (mundo 1-1) | [`juegos/super-inop`](juegos/super-inop/index.html) |
| Pupi-Man | Pac-Man | [`juegos/pupi-man`](juegos/pupi-man/index.html) |
| Pupi-Man vs Bacterias | Pac-Man | [`juegos/pupi-man-bacterias`](juegos/pupi-man-bacterias/index.html) |
| Lubri Climber | Ice Climber | [`juegos/lubri-climber`](juegos/lubri-climber/index.html) |
| Lubri Climber Efron | Ice Climber | [`juegos/lubri-climber-efron`](juegos/lubri-climber-efron/index.html) |

### Súper INOP

Un optometrista recorre el mundo 1-1 recogiendo lentes en vez de monedas. El paisaje tiene cartas de Snellen, letras de optotipos, nubes con forma de gafas y colinas con ojos. Los enemigos son gérmenes y caracoles miopes; las gafas te hacen crecer y la linterna dispara rayos de luz. La meta es la Óptica INOP.

Controles: flechas para moverse, Espacio/Z para saltar, X/Shift para correr y lanzar luz, Enter para empezar, P pausa, M sonido. En pantallas táctiles aparece un control en pantalla.

Para jugar, abre `juegos/super-inop/index.html` en el navegador.

### Pupi-Man

Pupi es un ojo que recorre la retina comiendo puntos. Los fantasmas son los defectos refractivos: Miopía, Hipermetropía, Astigmatismo y Presbicia. Las gafas de las esquinas los "corrigen": se ponen azules, llevan gafas y Pupi puede atraparlos. De premio aparecen lentes de contacto, gafas y gotas. Al pasar el nivel: ¡Visión 20/20!

Controles: flechas o WASD para moverse, Enter para empezar, P pausa, M sonido. En el celular se juega deslizando el dedo o con la cruceta.

Para jugar, abre `juegos/pupi-man/index.html` en el navegador.

### Pupi-Man vs Bacterias

Variación de Pupi-Man firmada por INOP Ingeniería Óptica. Pupi recoge goticas de lubricante y los enemigos son bacterias que afectan el ojo: Estafilococo, Pseudomona, Estreptococo y Clamidia. Los antibióticos de las esquinas las debilitan (se ponen pálidas) y Pupi puede atraparlas. Al limpiar el nivel: ¡Ojo sano!

Para jugar, abre `juegos/pupi-man-bacterias/index.html` en el navegador.

### Lubri Climber

Ojo seco con la escala de Oxford. Lubri, con su tarrito de lubricante en la espalda, rompe el techo con un retinoscopio y sube la montaña: abajo está el grado V (severo) y arriba el grado 0 (ojo sano). Cada dos pisos mejora un grado; el panel de la derecha muestra la córnea teñida con fluoresceína y los puntos verdes desaparecen a medida que sube. Los enemigos son manchas secas, viento y pantallas. En cada grado aparece un Dato INOP.

Controles: flechas para moverse, Espacio para saltar, X para el retinoscopio, Enter para empezar, P pausa, M sonido. En el celular hay botones en pantalla.

### Lubri Climber Efron

Versión de Lubri Climber con la escala de Efron (grados 0 a 4 de tinción corneal) y el aspecto del Ice Climber original: fondo negro, columnas de roca con el grado en cada piso y ladrillos verdes, cafés y de hielo. Cada grado muestra un Dato INOP con la córnea teñida de ese grado.

## App para Android

La app **Juegos INOP** trae un menú con todos los juegos y funciona sin internet. Cada vez que cambia un juego, GitHub compila un APK nuevo (ver `.github/workflows/android.yml` y la carpeta `android/`).

Descarga directa desde el celular: https://github.com/SAguilarRodriguez/juegos-optometria/releases/latest/download/Juegos-INOP.apk

La fuente Press Start 2P va incluida bajo la licencia SIL Open Font License.
