# Guia de instalacion del perfil GitHub

Este paquete esta disenado para el repositorio especial de perfil:

```text
WILLIAMMDN/WILLIAMMDN
```

GitHub muestra automaticamente el `README.md` de ese repositorio en la portada publica del perfil.

## Pasos

1. Crea o abre el repositorio publico llamado exactamente `WILLIAMMDN`.
2. Copia en la raiz de ese repositorio:
   - `README.md`
   - `assets/profile/`
3. Haz commit y push.
4. Abre `https://github.com/WILLIAMMDN` para revisar el resultado.

## Estructura esperada

```text
WILLIAMMDN/
|-- README.md
`-- assets/
    `-- profile/
        |-- asset-manifest.md
        |-- footer-pulse.svg
        |-- hero-william-medina.svg
        |-- impact-timeline.svg
        |-- mission-control.svg
        |-- project-matrix.svg
        |-- signal-divider.svg
        `-- skill-constellation.svg
```

## Notas

- Los assets principales son SVG locales y versionables.
- Algunos widgets de estadisticas dependen de servicios externos como Shields, GitHub Readme Stats y Streak Stats.
- Si un servicio externo falla por limite temporal, el perfil sigue funcionando gracias a los SVG locales.
