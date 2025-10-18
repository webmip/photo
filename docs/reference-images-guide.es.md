# 📸 Guía de Imágenes de Referencia

> Guía para usar imágenes de referencia con prompts de generación de imágenes con IA.
> 
> 📖 **Versión en Español** | **[English Version](./reference-images-guide.md)**

## 📖 ¿Qué son las Imágenes de Referencia?

Las imágenes de referencia son fotografías o ilustraciones usadas para guiar a los modelos de IA en generar resultados consistentes, particularmente para:
- **Preservación de características faciales e identidad**
- **Guía de pose y composición**
- **Referencia de estilo y estética**
- **Inspiración de iluminación y atmósfera**

## 🎯 ¿Por qué Usar Imágenes de Referencia?

### Consistencia de Identidad
Al crear series de retratos o estudios de personajes, las imágenes de referencia aseguran que la IA mantenga las mismas características faciales, proporciones e identidad a través de múltiples generaciones.

### Resultados Profesionales
Las imágenes de referencia ayudan a lograr:
- ✅ Fotografía de marca consistente
- ✅ Continuidad en diseño de personajes
- ✅ Coherencia en portafolios profesionales
- ✅ Replicación precisa de estilos

## 🖼️ Tipos de Imágenes de Referencia

### 1. Referencia Facial
**Propósito:** Preservar características faciales exactas e identidad

**Ejemplo del repositorio:**
- [Referencia Pixabay](https://pixabay.com/es/photos/tall-man-entrenador-joven-body-1203884/) - Usada para pose y composición en retrato de auto vintage

**Mejores prácticas:**
- Usar imágenes de alta resolución (mínimo 1024px)
- Rostro claro, bien iluminado con mínimas obstrucciones
- Vista frontal o 3/4 funciona mejor
- Múltiples ángulos ayudan para consistencia

### 2. Referencia de Pose
**Propósito:** Guiar posicionamiento corporal y composición

**Características:**
- Lenguaje corporal claro
- Postura definida
- Posicionamiento de extremidades visible
- Entorno contextual

### 3. Referencia de Estilo
**Propósito:** Establecer estética, atmósfera y dirección artística

**Elementos:**
- Configuración de iluminación
- Paleta de colores
- Estilo de composición
- Atmósfera ambiental

## 💡 Cómo Usar Imágenes de Referencia en Prompts

### Método 1: Instrucción Explícita (NanoBanana)

```
Usa las características faciales exactas de la foto de referencia del usuario. 
Preserva todas las proporciones faciales, tono de piel, peinado y expresión exactamente. 
No alteres ni modifiques el rostro. Mantén una identidad ultra-consistente 
a través de todas las generaciones.

[Resto de tu prompt...]
```

### Método 2: Descripción de Estilo

```
En el estilo de [descripción de imagen de referencia], capturando la misma 
atmósfera, iluminación y composición como se ve en [detalles específicos].

[Resto de tu prompt...]
```

### Método 3: Especificaciones Técnicas

```
Replica la configuración de iluminación de la referencia: [describe iluminación],
coincide con la gradación de color: [describe colores],
refleja la composición: [describe encuadre].

[Resto de tu prompt...]
```

## 🎨 Tips Específicos por Modelo

### NanoBanana
- **Fortaleza:** Excepcional en preservar identidad facial
- **Tip:** Sé explícito sobre "características faciales exactas" e "identidad ultra-consistente"
- **Mejor para:** Series de retratos, consistencia de personajes

### Midjourney
- **Fortaleza:** Interpretación artística de referencias de estilo
- **Tip:** Usa parámetro `--cref` para referencia de personaje (si disponible)
- **Mejor para:** Consistencia estilística, coincidencia de atmósfera

### Stable Diffusion
- **Fortaleza:** Flexible con ControlNet e IP-Adapter
- **Tip:** Usa ControlNet para guía de pose, IP-Adapter para rostro
- **Mejor para:** Control técnico, múltiples tipos de referencia

### DALL-E / GPT-5
- **Fortaleza:** Comprensión de lenguaje natural de referencias
- **Tip:** Describe la referencia en detalle dentro del prompt
- **Mejor para:** Similitud conceptual, transferencia de estilo

## 📋 Checklist de Imagen de Referencia

Antes de usar una imagen de referencia, asegúrate de:

- [ ] **Alta Calidad:** Resolución mínima 1024px
- [ ] **Sujeto Claro:** Sin obstrucciones o desenfoque
- [ ] **Iluminación Apropiada:** Bien iluminada, detalles visibles
- [ ] **Contenido Relevante:** Coincide con tu salida deseada
- [ ] **Derechos Claros:** Tienes permiso para usar la imagen
- [ ] **Formato Apropiado:** Formato JPG o PNG

## ⚖️ Consideraciones Legales y Éticas

### Derechos de Autor
- ✅ Usa tus propias fotografías
- ✅ Usa imágenes de stock libres de regalías (Pixabay, Unsplash, Pexels)
- ✅ Usa imágenes con licencias apropiadas
- ❌ No uses fotos de celebridades con derechos de autor sin permiso
- ❌ No uses fotos personales de otros sin consentimiento

### Uso Ético
- ✅ Respeta privacidad y consentimiento
- ✅ Acredita fuentes de referencia al compartir
- ✅ Usa para propósitos creativos y profesionales
- ❌ No crees deepfakes o contenido engañoso
- ❌ No uses para acoso o suplantación de identidad

## 🔍 Encontrar Imágenes de Referencia de Calidad

### Sitios de Fotos de Stock Gratuitas
- **Pixabay** - Licencia CC0, gratis para uso comercial
- **Unsplash** - Imágenes de alta calidad gratuitas
- **Pexels** - Fotos de stock gratuitas curadas
- **Wikimedia Commons** - Imágenes de dominio público

### Comunidades de Fotografía
- **Flickr** - Verifica licencias (CC BY, CC0)
- **500px** - Fotografía profesional (verifica derechos)
- **Behance** - Trabajo creativo (contacta artistas)

### Crear las Tuyas Propias
- **Autorretratos:** Control total y derechos
- **Modelos contratados:** Obtén liberaciones apropiadas
- **Amigos/familia:** Obtén consentimiento claro
- **Sesiones de estudio:** Biblioteca de referencia profesional

## 📊 Mejores Prácticas de Imagen de Referencia por Categoría

### Fotografía de Retrato
- **Rostro:** Claro, bien iluminado, vista frontal o 3/4
- **Expresión:** Neutral o emoción deseada
- **Resolución:** Mínimo 1024x1024
- **Fondo:** Simple, no distrae

### Moda/Editorial
- **Pose:** Cuerpo completo o recorte detallado
- **Estilismo:** Vista clara de ropa/accesorios
- **Iluminación:** Referencia de estudio o luz natural
- **Composición:** Encuadre profesional

### Paisaje/Entorno
- **Perspectiva:** Profundidad y capas claras
- **Iluminación:** Hora del día, condiciones climáticas
- **Elementos:** Primer plano, plano medio, fondo
- **Atmósfera:** Condiciones atmosféricas

### Artístico/Conceptual
- **Estilo:** Dirección artística clara
- **Color:** Paleta definida
- **Composición:** Encuadre o perspectiva única
- **Elementos:** Componentes visuales clave

## 🛠️ Implementación Técnica

### Preparar Imágenes de Referencia

1. **Recorta apropiadamente:** Enfócate en áreas relevantes
2. **Ajusta resolución:** Aumenta escala si es necesario (1024px+)
3. **Mejora claridad:** Enfoca si está ligeramente suave
4. **Normaliza exposición:** Asegura buena visibilidad
5. **Guarda en formato correcto:** JPG para fotos, PNG para gráficos

### Organizar Referencias

```
references/
├── faces/
│   ├── frontal/
│   ├── profile/
│   └── three-quarter/
├── poses/
│   ├── standing/
│   ├── sitting/
│   └── action/
└── styles/
    ├── lighting/
    ├── composition/
    └── mood/
```

## 💬 Ejemplos de la Comunidad

Revisa nuestros prompts del repositorio que usan imágenes de referencia:
- [Retrato Nocturno Auto Vintage](../prompts/nanobanana/portrait/vintage-car-night-portrait.es.md) - Usa referencia de Pixabay para pose y composición

## 🤝 Contribuir

¿Tienes tips para usar imágenes de referencia? Comparte tu conocimiento:
- Abre una Discusión con tu técnica
- Envía un PR con prompts de ejemplo
- Comparte estrategias exitosas de referencia

## 📚 Recursos Adicionales

- [Fundamentos de Prompt Engineering](./prompt-engineering-basics.es.md)
- [Guía de NanoBanana](./nanobanana-guide.es.md)
- [Guía de Contribución](../CONTRIBUTING.es.md)

---

*Última actualización: 2024-10-18*
