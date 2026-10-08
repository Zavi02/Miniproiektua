# Miniproiektua
Html-en egindako minijokoa

## Karpeten Estructura

```text
proyecto-videojuego/
├── index.html                  # Menú de inicio del juego
├── Civeles.html                # Menú de selección de niveles/jefes
│
├── Css/                        # Estilos globales y específicos
│   ├── Main.css                # Estilos globales (fuentes, colores, botones comunes)
│   ├── Menus.css               # Estilos para inicio y selección de niveles
│   └── Jefes/                  # Estilos individuales por jefe
│       ├── Jefe1.css
│       ├── Jefe2.css
│       ├── Jefe3.css
│       ├── Jefe4.css
│       └── Jefe5.css
│
├── Js/                         # Lógica del juego y scripts
│   ├── Main.js                 # Lógica global (sonidos globales, guardar progreso)
│   ├── Preguntas.js            # Base de datos de preguntas por jefe
│   └── Jefes/                  # Lógica individual de cada integrante
│       ├── Jefe1.js
│       ├── Jefe2.js
│       ├── Jefe3.js
│       ├── Jefe4.js
│       └── Jefe5.js
│
├── Assets/                     # Archivos multimedia (imágenes, audios)
│   ├── Img/
│   │   ├── Fondos/             # Botones, fondos de menú, logos
│   │   └── Jefes/              # Sprites / imágenes de cada jefe
│   │       ├── Jefe1/
│   │       ├── Jefe2/
│   │       ├── Jefe3/
│   │       ├── Jefe4/
│   │       └── Jefe5/
│   └── Audio/                  # Música y efectos de sonido
│
└── Orriak/                     # Páginas de los jefes
    ├── jefe-1/
    │   ├── introduccion.html   # Pág 1: Historia / Presentación
    │   ├── combate.html         # Pág 2: Batalla / Preguntas
    │   └── victoria.html        # Pág 3: Derrota del jefe / Recompensa
    ├── jefe-2/
    │   ├── introduccion.html
    │   ├── combate.html
    │   └── victoria.html
    ├── jefe-3/
    │   ├── introduccion.html
    │   ├── combate.html
    │   └── victoria.html
    ├── jefe-4/
    │   ├── introduccion.html
    │   ├── combate.html
    │   └── victoria.html
    └── jefe-5/
        ├── introduccion.html
        ├── combate.html
        └── victoria.html
```
