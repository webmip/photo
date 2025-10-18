# 🎨 Guía de Midjourney

> **Nota:** Esta guía está en desarrollo. Contribuye con tus conocimientos y experiencias.

## 📖 Introducción

Midjourney es conocido por su capacidad de crear **arte conceptual y creatividad visual excepcional**. Esta guía te ayudará a dominar sus características únicas.

## 🎯 Características Principales

- **Arte conceptual**: Excelente para ideas creativas y únicas
- **Estilo artístico**: Interpretación artística de prompts
- **Versatilidad**: Desde fotorrealismo hasta arte abstracto
- **Composición**: Sentido natural de la composición visual

## 💡 Mejores Prácticas

### Estructura de Prompts

```
[Descripción del Sujeto] + [Estilo Artístico] + [Iluminación/Atmósfera] + [Parámetros]
```

**Ejemplo:**
```
Cyberpunk street scene at night, rain-soaked neon reflections, 
volumetric fog, moody lighting, cinematic composition --ar 16:9 --v 6
```

### Parámetros de Midjourney

- `--ar [ratio]`: Aspect ratio (ej: `--ar 16:9`, `--ar 1:1`)
- `--v [version]`: Versión del modelo (ej: `--v 6`)
- `--style raw`: Para resultados más fotorrealistas
- `--stylize [0-1000]`: Control de estilización (default: 100)
- `--chaos [0-100]`: Variabilidad de resultados
- `--quality [.25, .5, 1]`: Calidad de renderizado

## 🚫 Negative Prompts

En Midjourney, usa `--no` para excluir elementos:

```
--no blur, distortion, low quality, watermark
```

## ⚙️ Configuraciones Recomendadas

### Para Fotorrealismo

```
[tu prompt] --style raw --v 6 --ar 16:9
```

### Para Arte Conceptual

```
[tu prompt] --stylize 250 --v 6 --ar 16:9
```

### Para Experimentación

```
[tu prompt] --chaos 50 --stylize 500 --v 6
```

## 🎨 Estilos Populares

### Cinematográfico

```
cinematic lighting, movie still, dramatic composition, 
professional color grading
```

### Editorial/Fashion

```
editorial photography, high fashion, studio lighting, 
vogue style, professional photography
```

### Arquitectura

```
architectural photography, golden hour lighting, 
ultra wide angle, professional real estate photography
```

## 💡 Tips Avanzados

1. **Usa referencias de artistas** (con respeto)
   - `in the style of [artist name]`

2. **Especifica el medio**
   - `photograph`, `digital art`, `oil painting`

3. **Controla la composición**
   - `centered composition`, `rule of thirds`, `symmetrical`

4. **Ajusta la iluminación**
   - `golden hour`, `blue hour`, `studio lighting`, `natural light`

## 📊 Tabla de Aspect Ratios

| Ratio | Uso Común | Comando |
|-------|-----------|---------|
| 1:1 | Instagram, cuadrado | `--ar 1:1` |
| 16:9 | Pantalla ancha, YouTube | `--ar 16:9` |
| 9:16 | Vertical, Stories | `--ar 9:16` |
| 4:3 | Clásico | `--ar 4:3` |
| 21:9 | Ultra ancho | `--ar 21:9` |

## 🔄 Workflow Recomendado

1. **Genera variaciones** con `/imagine`
2. **Upscale** la mejor opción
3. **Refina** con `/vary` o `/remix`
4. **Ajusta parámetros** según necesites

## 📚 Recursos Adicionales

- [Documentación Oficial de Midjourney](https://docs.midjourney.com/)
- [Ejemplos de la Comunidad](../../prompts/midjourney/)
- [Discusiones](https://github.com/webmip/photo/discussions)

## 🤝 Contribuye

¿Tienes tips o técnicas que funcionan bien con Midjourney? ¡Contribuye a esta guía!

---

*Última actualización: 2024*
