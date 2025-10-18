# 🤝 Guía de Contribución

¡Gracias por tu interés en contribuir a **Photo**! Este repositorio crece gracias a la comunidad y todas las contribuciones son bienvenidas.

## 📋 Tabla de Contenidos

- [Código de Conducta](#código-de-conducta)
- [¿Cómo Puedo Contribuir?](#cómo-puedo-contribuir)
- [Proceso de Contribución](#proceso-de-contribución)
- [Guía de Estilo](#guía-de-estilo)
- [Estructura de Prompts](#estructura-de-prompts)
- [Revisión de Pull Requests](#revisión-de-pull-requests)

## 📜 Código de Conducta

Este proyecto se adhiere a un código de conducta. Al participar, se espera que mantengas un ambiente respetuoso y colaborativo.

### Comportamientos Esperados

- ✅ Ser respetuoso con otros contribuidores
- ✅ Aceptar críticas constructivas
- ✅ Enfocarse en lo mejor para la comunidad
- ✅ Mostrar empatía hacia otros miembros

### Comportamientos Inaceptables

- ❌ Lenguaje ofensivo o discriminatorio
- ❌ Ataques personales o políticos
- ❌ Acoso público o privado
- ❌ Publicar información privada de otros

## 🎯 ¿Cómo Puedo Contribuir?

### 1. Añadir Nuevos Prompts

La forma más común de contribuir es añadiendo prompts nuevos y probados.

**Requisitos:**
- El prompt debe estar **probado y funcional**
- Incluir al menos **un ejemplo visual** del resultado
- Seguir la [plantilla oficial](./assets/template-prompt.md)
- Documentar parámetros y configuraciones usadas

### 2. Mejorar Prompts Existentes

- Optimizar prompts para mejores resultados
- Añadir variaciones o tips adicionales
- Actualizar ejemplos visuales
- Corregir errores o información desactualizada

### 3. Reportar Problemas

- Prompts que no funcionan como se describe
- Errores en la documentación
- Problemas técnicos del repositorio
- Sugerencias de mejora

### 4. Mejorar Documentación

- Corregir errores tipográficos
- Mejorar explicaciones
- Traducir contenido
- Añadir guías y tutoriales

## 🔄 Proceso de Contribución

### Paso 1: Fork del Repositorio

```bash
# Haz clic en el botón "Fork" en GitHub
# Luego clona tu fork
git clone https://github.com/TU-USUARIO/photo.git
cd photo
```

### Paso 2: Crear una Rama

```bash
# Crea una rama descriptiva
git checkout -b prompt/modelo-categoria-nombre
# Ejemplos:
# - prompt/nanobanana-portrait-cyberpunk
# - fix/midjourney-landscape-parameters
# - docs/improve-contributing-guide
```

### Paso 3: Realizar Cambios

1. **Para nuevos prompts:**
   - Copia la plantilla: `cp assets/template-prompt.md prompts/[modelo]/[categoria]/[nombre].md`
   - Completa toda la información
   - Añade imágenes de ejemplo en `examples/[modelo]/`

2. **Para mejoras:**
   - Edita los archivos necesarios
   - Mantén el formato consistente

### Paso 4: Commit de Cambios

```bash
# Añade tus cambios
git add .

# Commit con mensaje descriptivo
git commit -m "feat: add cyberpunk portrait prompt for NanoBanana"

# Tipos de commit:
# - feat: nuevo prompt o característica
# - fix: corrección de errores
# - docs: cambios en documentación
# - style: formato, sin cambios de código
# - refactor: reorganización de código
# - test: añadir tests
```

### Paso 5: Push y Pull Request

```bash
# Push a tu fork
git push origin tu-rama

# Ve a GitHub y crea un Pull Request
# Describe claramente qué añades o cambias
```

## 📝 Guía de Estilo

### Nombres de Archivos

- Usar **kebab-case**: `fire-water-portrait.md`
- Ser **descriptivos**: `cyberpunk-street-night.md`
- Evitar caracteres especiales

### Formato Markdown

- Usar encabezados jerárquicos (`#`, `##`, `###`)
- Incluir emojis para mejor legibilidad 🎨
- Usar bloques de código con sintaxis: ` ```bash ` 
- Añadir tablas para parámetros

### Imágenes

- Formato: **JPG** o **PNG**
- Tamaño máximo: **2MB** por imagen
- Resolución recomendada: **1024x1024** o similar
- Nombres descriptivos: `nanobanana-fire-water-portrait.jpg`

## 🎨 Estructura de Prompts

Cada prompt debe incluir:

### ✅ Obligatorio

1. **Información General**
   - Modelo utilizado
   - Categoría
   - Estilo

2. **Prompt Completo**
   - Texto exacto usado
   - Formato de código

3. **Negative Prompt**
   - Qué evitar en la generación

4. **Parámetros**
   - Configuración específica
   - Valores recomendados

5. **Ejemplo Visual**
   - Al menos una imagen
   - Resultado real generado

### 🌟 Recomendado

- Tips y variaciones
- Notas adicionales
- Tags relevantes
- Información del autor

### ❌ Evitar

- Prompts no probados
- Imágenes sin relación
- Información incompleta
- Parámetros incorrectos

## 🔍 Revisión de Pull Requests

### Criterios de Aceptación

Tu PR será revisado según:

1. **Calidad del Prompt**
   - ¿Funciona como se describe?
   - ¿Produce resultados consistentes?
   - ¿Está bien documentado?

2. **Documentación**
   - ¿Sigue la plantilla?
   - ¿Incluye toda la información necesaria?
   - ¿Tiene ejemplos visuales?

3. **Formato**
   - ¿Sigue la guía de estilo?
   - ¿Los archivos están en las carpetas correctas?
   - ¿Los nombres son descriptivos?

### Tiempo de Revisión

- PRs simples: **1-3 días**
- PRs complejos: **3-7 días**
- Puedes mencionar a maintainers si no hay respuesta

### Feedback

- Responde a los comentarios de revisión
- Realiza los cambios solicitados
- Mantén la conversación profesional

## 🏷️ Convenciones de Naming

### Ramas

```
tipo/modelo-categoria-descripcion

Ejemplos:
- prompt/nanobanana-portrait-warrior
- fix/dalle-landscape-parameters
- docs/update-readme
```

### Commits

```
tipo: descripción breve

Ejemplos:
- feat: add epic warrior portrait for NanoBanana
- fix: correct CFG scale in cyberpunk prompt
- docs: improve contribution guidelines
```

## 💡 Tips para Contribuidores

### Para Nuevos Contribuidores

1. **Empieza pequeño**: Añade un prompt simple primero
2. **Lee ejemplos**: Revisa prompts existentes como referencia
3. **Pregunta**: Usa Discussions si tienes dudas
4. **Sé paciente**: Las revisiones pueden tomar tiempo

### Para Contribuidores Experimentados

1. **Ayuda a otros**: Revisa PRs de nuevos contribuidores
2. **Mejora existentes**: Optimiza prompts antiguos
3. **Documenta**: Añade guías y tutoriales
4. **Innova**: Experimenta con nuevas técnicas

## 🎓 Recursos Útiles

- [Markdown Guide](https://www.markdownguide.org/)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [How to Write Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

## 📞 ¿Necesitas Ayuda?

- 💬 [Discussions](https://github.com/webmip/photo/discussions) - Preguntas generales
- 🐛 [Issues](https://github.com/webmip/photo/issues) - Reportar problemas
- 📧 Email: [Tu email de contacto]

## 🙏 Agradecimientos

Gracias por contribuir a **Photo**. Cada prompt, corrección o sugerencia ayuda a que esta colección sea más útil para toda la comunidad de creadores con IA.

---

**¿Listo para contribuir?** 🚀

1. Fork el repositorio
2. Crea tu rama
3. Añade tu prompt
4. Abre un Pull Request

¡Esperamos ver tus contribuciones!
