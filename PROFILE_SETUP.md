# Guia de instalacion del perfil GitHub

Repositorio especial:

```text
WILLIAMMDN/WILLIAMMDN
```

## Estructura

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
        |-- certification-vault.svg
        |-- core-panel.svg
        |-- divider-system-pulse.svg
        |-- footer-pulse.svg
        |-- hero-william-medina.svg
        |-- panel-certifications.svg
        |-- panel-lab.svg
        |-- panel-projects.svg
        `-- system-access-title.svg
```

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
