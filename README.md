# CyberLabs

Repositorio personal de laboratorios de ciberseguridad: pentesting, CTF, blue team y fundamentos. El objetivo es documentar mi proceso de aprendizaje de forma consistente y, con el tiempo, tener un historial navegable en GitHub.

## Estructura

```
cyberlabs/
  pentest/       # Explotación, hacking ético, máquinas vulnerables
  ctf/           # Retos tipo capture-the-flag (forense, cripto, web, reversing...)
  blueteam/      # Detección, análisis de logs, respuesta a incidentes, hardening
  fundamentos/   # Conceptos base: redes, sistemas, protocolos
  templates/     # Plantilla de writeup usada en todos los labs
```

Cada lab vive en su propia carpeta, nombrada como `lab-NN-nombre-descriptivo`, y contiene al menos:

```
lab-01-nombre/
  writeup.md      # Basado en templates/writeup-template.md
  evidencia/       # Capturas, outputs, archivos de apoyo
```

## Flujo de trabajo

1. Crear la carpeta del lab en la categoría correspondiente.
2. Copiar `templates/writeup-template.md` como `writeup.md` dentro del lab.
3. Ir documentando en tiempo real: recon, pasos, hallazgos, evidencia.
4. Cerrar el writeup con lecciones aprendidas.
5. Commit del lab terminado.

## Control de versiones y GitHub

Este proyecto está inicializado como repo git local. El siguiente paso es conectarlo a un repositorio en GitHub para llevar el historial completo y que sirva como portafolio de aprendizaje público o privado.

## Convenciones

- Nombres de carpeta en minúsculas y con guiones: `lab-01-nombre`.
- No subir credenciales reales, IPs privadas sensibles ni datos personales en la evidencia.
- Un writeup por lab, siempre basado en la plantilla.
