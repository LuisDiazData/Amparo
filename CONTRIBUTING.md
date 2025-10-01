---


## 3) CONTRIBUTING.md


```markdown
# Guía de Contribución


¡Gracias por querer contribuir a Amparo! Este documento explica cómo proponer cambios de forma clara y segura.


## Requisitos previos
- Android Studio actualizado
- JDK 17+
- Gradle Wrapper (incluido en el repo)


## Flujo de trabajo
1. **Fork** y crea rama desde `main`: `feat/…`, `fix/…`, `chore/…`
2. Asegúrate de que el build y el lint pasen localmente
3. Abre un **PR** usando la plantilla; enlaza Issues
4. Espera revisión (al menos 1 aprobador)


## Convenciones de commits (Conventional Commits)
Formato: `tipo(scope): mensaje`
Tipos comunes: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.
Ejemplos:
- `feat(login): agregar autenticación con Google`
- `fix(ocr): corregir parseo de montos`


## Estilo de código
- Kotlin: Ktlint/Detekt (si están configurados)
- Nombres descriptivos y pruebas donde aplique


## Issues
- Usa las plantillas de **Bug** y **Feature**
- Incluye pasos para reproducir, contexto y criterios de aceptación


## PRs
- Pequeños y enfocados
- Incluye **antes/después** cuando apliquen (capturas)
- Actualiza `RELEASE_NOTES.md` si el cambio es visible


## Seguridad
No subas secretos o llaves. Si encuentras una vulnerabilidad, sigue `SECURITY.md`.