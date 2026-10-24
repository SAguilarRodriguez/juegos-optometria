# juegos-optometria

Juegos clásicos remasterizados con estética 8 bits como ejercicios de optometría.

## Juegos

| Juego | Basado en | Carpeta |
|---|---|---|
| Súper INOP | Super Mario Bros. (mundo 1-1) | [`juegos/super-inop`](juegos/super-inop/index.html) |
| Pupi-Man | Pac-Man | [`juegos/pupi-man`](juegos/pupi-man/index.html) |
| Pupi-Man vs Bacterias | Pac-Man | [`juegos/pupi-man-bacterias`](juegos/pupi-man-bacterias/index.html) |

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

## App para Android

Pupi-Man vs Bacterias también se instala como app en el celular. Cada vez que cambia el juego, GitHub compila un APK nuevo (ver `.github/workflows/android.yml` y la carpeta `android/`).

Descarga directa desde el celular: https://github.com/SAguilarRodriguez/juegos-optometria/releases/latest/download/PupiMan-INOP.apk

La app funciona sin internet. La fuente Press Start 2P va incluida bajo la licencia SIL Open Font License.
