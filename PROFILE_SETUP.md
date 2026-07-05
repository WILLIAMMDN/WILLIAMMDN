# Guia de instalacion del perfil GitHub

Repositorio especial:

```text
WILLIAMMDN/WILLIAMMDN
```

## Estructura actual

```text
WILLIAMMDN/
|-- README.md
|-- docs/
|   |-- CERTIFICATIONS.md
|   |-- PROJECTS.md
|   `-- SECURITY-LAB.md
|-- .github/
|   `-- workflows/
|       `-- contribution-snake.yml
`-- assets/
    `-- profile/
        |-- asset-manifest.md
        `-- intro.svg
```

## Estilo

- Inspirado en perfiles profesionales, pero con lenguaje más cercano.
- Sin fondos pesados ni estética hacker genérica.
- Banner con variante para modo claro y modo oscuro.
- Sin tablas anchas para mejorar la lectura en celular.
- Stack visual con `skillicons.dev`.
- Secciones plegables solo para gráficos secundarios.
- Snake de contribuciones conservado.

## Responsive y tema

GitHub README no permite Angular, CSS propio ni JavaScript. Para simular componentes profesionales se usa Markdown/HTML compatible con GitHub:

- `<picture>` para cambiar imágenes según modo claro/oscuro.
- Badges de `shields.io`.
- Iconos de `skillicons.dev`.
- Cards de `github-profile-summary-cards`.
- `<details>` para no saturar el perfil en móvil.

## Snake

El workflow `.github/workflows/contribution-snake.yml` genera:

```text
output/github-contribution-grid-snake.svg
output/github-contribution-grid-snake-dark.svg
```

Si no aparece:

1. Ve a `Settings > Actions > General`.
2. Activa `Read and write permissions`.
3. Ejecuta manualmente `Generate contribution snake`.

## Certificados

Cuando tengas imagenes o enlaces verificables de Cisco, badges o Google AI, colocalos en `assets/certifications/` y enlazalos desde `docs/CERTIFICATIONS.md`.
