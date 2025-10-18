# 📚 Fundamentos de Prompt Engineering

> Guía básica para crear prompts efectivos en modelos de generación de imágenes con IA.

## 📖 ¿Qué es Prompt Engineering?

El **Prompt Engineering** es el arte y ciencia de escribir instrucciones efectivas para que los modelos de IA generen exactamente lo que deseas.

## 🎯 Principios Fundamentales

### 1. Sé Específico

❌ **Malo:**
```
a portrait
```

✅ **Bueno:**
```
Professional studio portrait of a woman in her 30s, 
soft lighting, neutral background, shallow depth of field
```

### 2. Estructura tu Prompt

**Orden recomendado:**
1. Calidad/Estilo
2. Sujeto principal
3. Acción/Pose
4. Entorno/Fondo
5. Iluminación
6. Detalles técnicos

**Ejemplo:**
```
[Hyper-realistic photograph] of [a cyberpunk warrior] 
[standing confidently] in [a neon-lit street], 
[dramatic rim lighting], [8k, ultra detailed, bokeh]
```

### 3. Usa Descriptores de Calidad

- `photorealistic`, `hyper-realistic`
- `8k`, `4k`, `ultra detailed`
- `professional photography`
- `high quality`, `masterpiece`
- `sharp focus`, `crisp details`

### 4. Controla la Iluminación

- **Natural:** `golden hour`, `blue hour`, `overcast`
- **Studio:** `softbox lighting`, `rim light`, `key light`
- **Dramática:** `dramatic lighting`, `chiaroscuro`, `moody`
- **Ambiente:** `volumetric lighting`, `god rays`, `atmospheric`

## 🚫 Negative Prompts

Tan importante como lo que quieres es especificar lo que **NO** quieres.

### Negative Prompts Comunes

```
blurry, low quality, distorted, deformed, ugly, 
bad anatomy, bad proportions, extra limbs, 
disfigured, watermark, signature, text
```

### Por Categoría

**Para Retratos:**
```
bad anatomy, deformed face, extra fingers, 
missing limbs, asymmetric eyes
```

**Para Paisajes:**
```
blurry, low resolution, oversaturated, 
artificial, fake
```

**Para Fotorrealismo:**
```
cartoon, anime, painting, drawing, sketch, 
illustration, 3d render
```

## 🎨 Técnicas Avanzadas

### Pesos y Énfasis

Algunos modelos permiten enfatizar palabras:

```
(palabra)       - énfasis ligero
((palabra))     - énfasis medio
(palabra:1.5)   - énfasis numérico
```

### Mezcla de Conceptos

```
[concept A] and [concept B]
```

**Ejemplo:**
```
A portrait that is half fire and half water, 
dramatic contrast, symmetrical composition
```

### Estilos Artísticos

- `in the style of [artist]`
- `[medium] photography` (film, digital, instant)
- `[era] aesthetic` (vintage, modern, futuristic)

## 📊 Anatomía de un Prompt Perfecto

```
[CALIDAD] [ESTILO] [MEDIO]
[SUJETO PRINCIPAL] [DETALLES DEL SUJETO]
[ACCIÓN/POSE]
[ENTORNO] [DETALLES DEL ENTORNO]
[ILUMINACIÓN] [ATMÓSFERA]
[COMPOSICIÓN] [ÁNGULO DE CÁMARA]
[DETALLES TÉCNICOS]
```

### Ejemplo Completo

```
Hyper-realistic professional photograph
of a female warrior in ornate armor
standing confidently with sword drawn
in an ancient temple with dramatic columns
golden hour lighting streaming through windows, volumetric fog
centered composition, low angle shot
8k ultra detailed, shallow depth of field, bokeh background
```

## 💡 Tips por Categoría

### Retratos

- Especifica edad, género, expresión
- Describe iluminación facial
- Menciona profundidad de campo
- Define el fondo (blur, solid color, etc.)

### Paisajes

- Hora del día y condiciones climáticas
- Elementos de composición (foreground, background)
- Tipo de cámara/lente (wide angle, telephoto)
- Atmósfera (misty, clear, dramatic)

### Fotografía de Producto

- Fondo (white background, studio setup)
- Iluminación (soft, even, professional)
- Ángulo (top-down, 45 degrees, front view)
- Contexto (isolated, lifestyle, in-use)

### Arte Conceptual

- Mood y atmósfera
- Elementos fantásticos o surrealistas
- Paleta de colores
- Inspiraciones artísticas

## 🔍 Debugging de Prompts

### Si tus resultados son borrosos:

- Añade: `sharp focus`, `crisp details`, `high resolution`
- Negative: `blurry`, `soft focus`, `low quality`

### Si la anatomía es incorrecta:

- Sé más específico con poses
- Añade: `correct anatomy`, `proportional`
- Negative: `deformed`, `bad anatomy`, `extra limbs`

### Si los colores son malos:

- Especifica paleta: `warm colors`, `cool tones`, `muted palette`
- Añade: `professional color grading`
- Negative: `oversaturated`, `washed out`

### Si la composición es pobre:

- Define: `rule of thirds`, `centered`, `symmetrical`
- Añade: `professional composition`, `balanced`
- Especifica ángulo de cámara

## 📚 Vocabulario Útil

### Calidad

- `masterpiece`, `best quality`, `high quality`
- `ultra detailed`, `extremely detailed`
- `8k`, `4k`, `high resolution`

### Estilo Fotográfico

- `professional photography`
- `DSLR`, `film photography`
- `editorial`, `commercial`, `documentary`

### Iluminación

- `soft lighting`, `hard lighting`
- `backlit`, `rim light`, `key light`
- `natural light`, `studio lighting`

### Composición

- `rule of thirds`, `golden ratio`
- `symmetrical`, `asymmetrical`
- `centered`, `off-center`

### Ángulos de Cámara

- `eye level`, `low angle`, `high angle`
- `bird's eye view`, `worm's eye view`
- `dutch angle`, `over the shoulder`

### Profundidad de Campo

- `shallow depth of field`, `deep focus`
- `bokeh`, `background blur`
- `tack sharp`, `selective focus`

## 🎓 Ejercicios Prácticos

### Ejercicio 1: Mejora este Prompt

**Antes:**
```
a woman in a city
```

**Después:**
```
Professional street photography of a woman in her 20s 
walking through a bustling city street at golden hour, 
natural lighting, shallow depth of field, 
urban background with bokeh, candid moment
```

### Ejercicio 2: Crea un Prompt Completo

Tema: Un paisaje de montaña

**Tu turno:** Escribe un prompt completo usando la estructura aprendida.

## 🔗 Recursos Adicionales

- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [Lexica.art](https://lexica.art/) - Explorador de prompts
- [PromptHero](https://prompthero.com/) - Comunidad de prompts

## 🤝 Contribuye

¿Tienes técnicas o tips adicionales? ¡Contribuye a esta guía!

---

*Última actualización: 2024*
