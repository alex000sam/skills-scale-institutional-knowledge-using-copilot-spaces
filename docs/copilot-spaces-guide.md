## Guía rápida: Escalar conocimiento institucional con Copilot Spaces

Esta guía explica cómo usar Copilot Spaces para centralizar, compartir y mantener el conocimiento del proyecto (políticas, procesos, plantillas y respuestas frecuentes) de forma colaborativa.

Objetivo
- Facilitar que el equipo encuentre respuestas rápidas y actualizadas.
- Reducir la carga de repetición en entrevistas y onboarding.

¿Qué encontrarás aquí?
- Cómo estructurar un Space para documentación operativa.
- Plantillas de issues/PRs y pages para la base de conocimiento.
- Ejemplos de prompts y flujos de trabajo recomendados.

1) Estructura recomendada del Space
- Home: visión, enlaces rápidos y responsables.
- Procesos: planificación, ejecución, QA, despliegue.
- Plantillas: issues, PRs, runbooks, checklist de release.
- Preguntas frecuentes (FAQ) y atajos de troubleshooting.
- Historial de cambios y responsables por sección.

2) Roles y permisos
- Owner: mantiene la estructura y revisa cambios semestrales.
- Editors: equipos que actualizan procesos y runbooks.
- Viewers: resto del equipo.

3) Plantillas útiles (copiar/pegar)

- Plantilla de issue - Añadir/Actualizar documento

```
Título: [docs] Actualizar <nombre-del-doc> — motivo

Descripción:
- ¿Qué se cambia? (resumen)
- Motivación o enlace a la discusión
- Impacto / stakeholders

Checklist:
- [ ] Redacción revisada
- [ ] Owner asignado
- [ ] Enlace en README principal actualizado
```

- Plantilla de PR - Cambios en docs

```
Resumen del cambio

Files changed:
- docs/<archivo.md>

Notas para el revisor:
- Comprueba consistencia de tono y enlaces

Relacionado con: #issue
```

4) Ejemplos de prompts (para usar dentro del Space o con Copilot)
- "Resume este runbook en 3 bullets para un onboarding rápido."
- "Genera una checklist de pre-release basada en este documento: <enlace>."
- "Detecta y sugiere titulares claros para esta página larga." 

5) Flujo mínimo recomendado para cambios en la KB
1. Crear issue con la plantilla "Actualizar documento".
2. Asignar owner y deadline corto (p.ej. 3 días).
3. Abrir PR con cambios y referencias.
4. Revisar (1 reviewer) y mergear.
5. Actualizar el índice en `docs/README.md` y la sección de changelog.

6) Buenas prácticas
- Citar fuentes y decisiones: siempre enlaza la issue/PR que motivó el cambio.
- Pequeños commits: facilita revisiones rápidas.
- Revisiones periódicas: programar auditoría trimestral de pages críticas.
- Uso de etiquetas: `process`, `runbook`, `template`, `stale`.

7) Plantilla de auditoría trimestral (short)
- Lista de páginas críticas
- Última modificación
- Responsable
- Acción sugerida (actualizar/archivar)

Próximos pasos sugeridos
- Crear un Space de prueba y migrar 2-3 documentos clave.
- Documentar el owner y el proceso de cambios en la página Home del Space.

Contacto
- Para dudas sobre esta guía: abrir issue en este repo con la etiqueta `copilot-spaces`.

© 2025 — Guía generada para el ejercicio "Scale institutional knowledge using Copilot Spaces".
