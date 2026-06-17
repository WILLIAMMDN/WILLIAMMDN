# Guia de instalacion del perfil GitHub

Este paquete esta disenado para el repositorio especial de perfil:

```text
WILLIAMMDN/WILLIAMMDN
```

GitHub muestra automaticamente el `README.md` de ese repositorio en la portada publica del perfil cuando el repositorio es publico, se llama igual que el usuario y contiene `README.md` en la raiz.

## Estructura esperada

```text
WILLIAMMDN/
|-- README.md
|-- .github/
|   `-- workflows/
|       `-- contribution-snake.yml
`-- assets/
    `-- profile/
        |-- architecture-board.svg
        |-- asset-manifest.md
        |-- build-route.svg
        |-- footer-pulse.svg
        |-- hero-william-medina.svg
        |-- project-ledger.svg
        `-- signal-divider.svg
```

## Snake de contribuciones

El workflow `.github/workflows/contribution-snake.yml` genera los SVG del snake en la rama `output`.

Si no aparece despues del primer push:

1. Ve a `Settings > Actions > General`.
2. En `Workflow permissions`, selecciona `Read and write permissions`.
3. Guarda.
4. Ve a `Actions`, abre `Generate contribution snake` y ejecuta `Run workflow`.

## Notas

- Los assets principales son SVG locales y versionables.
- El snake depende de GitHub Actions y del action externo `Platane/snk`.
- Algunos widgets de estadisticas dependen de servicios externos como GitHub Readme Stats y Streak Stats.
