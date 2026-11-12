# Guía de Contribución

¡Hola! Nos alegra mucho que quieras contribuir a este proyecto. Tu ayuda es fundamental para mantenerlo y mejorarlo.

Al participar en este proyecto, aceptas cumplir con nuestro [Código de Conducta](CODE_OF_CONDUCT.md) y entiendes que tus contribuciones se publican bajo la [licencia del proyecto](LICENSE).

---

## Configuración del Entorno

1. **Haz un fork** del repositorio y clónalo en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repo.git
   cd nombre-del-repo
   ```

2. **Instala las dependencias** necesarias (revisa el archivo `README.md` si requiere herramientas o contenedores específicos).

3. **Crea una rama** nueva desde `main` para trabajar de forma aislada:

   ```bash
   git checkout -b fix/nombre-descriptivo
   ```

---

## Reportar Errores (Issues)

Antes de abrir un nuevo issue, revisa los [issues existentes](https://github.com/tu-usuario/nombre-del-repo/issues) para evitar duplicados. Si encuentras un fallo:

- Describe qué esperabas que ocurriera y qué ocurrió realmente.
- Incluye los pasos exactos para reproducir el problema.
- Añade detalles de tu entorno (sistema operativo, versión, logs o capturas de pantalla).

> **¿Es tu primera vez contribuyendo?** Busca etiquetas como `good first issue` para empezar con tareas sencillas.

---

## Contribuir con Código (Pull Requests)

Para mantener el historial limpio y agilizar las revisiones, seguimos estas prácticas:

### 1. Cambios Incrementales

- **Mantén los PRs pequeños y enfocados:** Un Pull Request debe resolver un solo problema o añadir una sola funcionalidad. Evita mezclar refactorizaciones grandes con correcciones de errores.

### 2. Mensajes de Commit

Escribe mensajes claros que expliquen el **porqué** del cambio:

- Usa un título corto y descriptivo (ej. `[ui] Corrige alineación en botones móviles`).
- Si hace falta contexto adicional, deja una línea en blanco y detállalo en el cuerpo del commit.

### 3. Pruebas y Calidad

- Todo cambio de código o corrección de bug debe incluir **pruebas unitarias o de integración** que validen su funcionamiento.
- Asegúrate de que tu código compile sin errores ni advertencias nuevas y pase todos los tests existentes antes de subirlo:

  ```bash
  # Ejecuta la suite de pruebas del proyecto
  npm test  # (o el comando correspondiente a tu stack)
  ```

### 4. Envío y Revisión (Code Review)

- Abre el Pull Request hacia la rama principal (`main`) rellenando la plantilla correspondiente.
- Enlaza el issue relacionado si aplica (ej. `Closes #123`).
- Responde a los comentarios de revisión; una vez aprobado por un mantenedor, tu cambio será fusionado.

---

## Encabezado de Licencia (Archivos Nuevos)

Si creas un archivo de código nuevo, incluye el encabezado estándar en la parte superior:

```text
// Copyright (c) 2026 [Tu Nombre o Organización]
// Licensed under [Nombre de la Licencia]
```
