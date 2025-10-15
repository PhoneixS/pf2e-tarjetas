# pf2e-tarjetas
Recopilación de diferentes tarjetas para facilitar el juego Pathfinder 2e (segunda edición)

# Pruebas locales

## Requisitos

Para probar localmente, hay que tener instalado Jekyll y Ruby como indica en la guía https://docs.github.com/es/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll.

Después instalar los requisitos con:

```
bundle install
```

## Como ejecutarlo

Se puede ejecutar localmente, estando en la carpeta del proyecto y ejecutando:

```
bundle exec jekyll serve
```

Y después acceder a http://127.0.0.1:4000.

# Escribir nuevas tarjetas

## Cómo agregar iconos de acciones

Para agregar un icono hay que usar la clase "icono" mediante html. Por ejemplo:

```
Usa <span class="icono">[one-action]</span> para hacer algo importante.
```

Se pueden usar los siguientes valores:

- Single Action: [one-action]
- Two-Action Activity: [two-actions]
- Three-Action Activity: [three-actions]
- Reaction: [reaction]
- Free Action: [free-action]

