# Guía de instalación del perfil GitHub

Este paquete está diseñado para el repositorio especial de perfil:

```text
WILLIAMMDN/WILLIAMMDN
```

GitHub muestra automáticamente el `README.md` de ese repositorio en la portada pública del perfil.

## Pasos

1. Crea un repositorio público llamado exactamente `WILLIAMMDN`.
2. Copia en la raíz de ese repositorio:
   - `README.md`
   - `assets/profile/`
3. Haz commit y push.
4. Abre `https://github.com/WILLIAMMDN` para revisar el resultado.

## Personalización recomendada

- Si tienes correo profesional, agrega un badge `mailto:` en la sección `Contact`.
- Si publicas repositorios de VialCentiva, Paltodoc o Academia Daemon, añade tarjetas `Pinned Repo` con `github-readme-stats`.
- Si algún servicio externo de estadísticas falla temporalmente, el README seguirá funcionando porque los assets principales son locales.

## Estructura esperada

```text
WILLIAMMDN/
├─ README.md
└─ assets/
   └─ profile/
      ├─ hero-william-medina.svg
      ├─ mission-control.svg
      ├─ signal-divider.svg
      ├─ footer-pulse.svg
      └─ asset-manifest.md
```
