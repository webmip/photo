# 📚 Prompt Engineering Basics

> Basic guide to creating effective prompts for AI image generation models.
> 
> 📖 **[Versión en Español](./prompt-engineering-basics.es.md)** | **English Version**

## 📖 What is Prompt Engineering?

**Prompt Engineering** is the art and science of writing effective instructions so AI models generate exactly what you want.

## 🎯 Fundamental Principles

### 1. Be Specific

❌ **Bad:**
```
a portrait
```

✅ **Good:**
```
Professional studio portrait of a woman in her 30s, 
soft lighting, neutral background, shallow depth of field
```

### 2. Structure Your Prompt

**Recommended order:**
1. Quality/Style
2. Main subject
3. Action/Pose
4. Environment/Background
5. Lighting
6. Technical details

**Example:**
```
[Hyper-realistic photograph] of [a cyberpunk warrior] 
[standing confidently] in [a neon-lit street], 
[dramatic rim lighting], [8k, ultra detailed, bokeh]
```

### 3. Use Quality Descriptors

- `photorealistic`, `hyper-realistic`
- `8k`, `4k`, `ultra detailed`
- `professional photography`
- `high quality`, `masterpiece`
- `sharp focus`, `crisp details`

### 4. Control Lighting

- **Natural:** `golden hour`, `blue hour`, `overcast`
- **Studio:** `softbox lighting`, `rim light`, `key light`
- **Dramatic:** `dramatic lighting`, `chiaroscuro`, `moody`
- **Ambient:** `volumetric lighting`, `god rays`, `atmospheric`

## 🚫 Negative Prompts

As important as what you want is specifying what you **DON'T** want.

### Common Negative Prompts

```
blurry, low quality, distorted, deformed, ugly, 
bad anatomy, bad proportions, extra limbs, 
disfigured, watermark, signature, text
```

### By Category

**For Portraits:**
```
bad anatomy, deformed face, extra fingers, 
missing limbs, asymmetric eyes
```

**For Landscapes:**
```
blurry, low resolution, oversaturated, 
artificial, fake
```

**For Photorealism:**
```
cartoon, anime, painting, drawing, sketch, 
illustration, 3d render
```

## 🎨 Advanced Techniques

### Weights and Emphasis

Some models allow emphasizing words:

```
(word)       - light emphasis
((word))     - medium emphasis
(word:1.5)   - numeric emphasis
```

### Concept Mixing

```
[concept A] and [concept B]
```

**Example:**
```
A portrait that is half fire and half water, 
dramatic contrast, symmetrical composition
```

### Artistic Styles

- `in the style of [artist]`
- `[medium] photography` (film, digital, instant)
- `[era] aesthetic` (vintage, modern, futuristic)

## 📊 Anatomy of a Perfect Prompt

```
[QUALITY] [STYLE] [MEDIUM]
[MAIN SUBJECT] [SUBJECT DETAILS]
[ACTION/POSE]
[ENVIRONMENT] [ENVIRONMENT DETAILS]
[LIGHTING] [ATMOSPHERE]
[COMPOSITION] [CAMERA ANGLE]
[TECHNICAL DETAILS]
```

### Complete Example

```
Hyper-realistic professional photograph
of a female warrior in ornate armor
standing confidently with sword drawn
in an ancient temple with dramatic columns
golden hour lighting streaming through windows, volumetric fog
centered composition, low angle shot
8k ultra detailed, shallow depth of field, bokeh background
```

## 💡 Tips by Category

### Portraits

- Specify age, gender, expression
- Describe facial lighting
- Mention depth of field
- Define background (blur, solid color, etc.)

### Landscapes

- Time of day and weather conditions
- Composition elements (foreground, background)
- Camera/lens type (wide angle, telephoto)
- Atmosphere (misty, clear, dramatic)

### Product Photography

- Background (white background, studio setup)
- Lighting (soft, even, professional)
- Angle (top-down, 45 degrees, front view)
- Context (isolated, lifestyle, in-use)

### Conceptual Art

- Mood and atmosphere
- Fantastical or surreal elements
- Color palette
- Artistic inspirations

## 🔍 Debugging Prompts

### If your results are blurry:

- Add: `sharp focus`, `crisp details`, `high resolution`
- Negative: `blurry`, `soft focus`, `low quality`

### If anatomy is incorrect:

- Be more specific with poses
- Add: `correct anatomy`, `proportional`
- Negative: `deformed`, `bad anatomy`, `extra limbs`

### If colors are bad:

- Specify palette: `warm colors`, `cool tones`, `muted palette`
- Add: `professional color grading`
- Negative: `oversaturated`, `washed out`

### If composition is poor:

- Define: `rule of thirds`, `centered`, `symmetrical`
- Add: `professional composition`, `balanced`
- Specify camera angle

## 📚 Useful Vocabulary

### Quality

- `masterpiece`, `best quality`, `high quality`
- `ultra detailed`, `extremely detailed`
- `8k`, `4k`, `high resolution`

### Photographic Style

- `professional photography`
- `DSLR`, `film photography`
- `editorial`, `commercial`, `documentary`

### Lighting

- `soft lighting`, `hard lighting`
- `backlit`, `rim light`, `key light`
- `natural light`, `studio lighting`

### Composition

- `rule of thirds`, `golden ratio`
- `symmetrical`, `asymmetrical`
- `centered`, `off-center`

### Camera Angles

- `eye level`, `low angle`, `high angle`
- `bird's eye view`, `worm's eye view`
- `dutch angle`, `over the shoulder`

### Depth of Field

- `shallow depth of field`, `deep focus`
- `bokeh`, `background blur`
- `tack sharp`, `selective focus`

## 🎓 Practical Exercises

### Exercise 1: Improve this Prompt

**Before:**
```
a woman in a city
```

**After:**
```
Professional street photography of a woman in her 20s 
walking through a bustling city street at golden hour, 
natural lighting, shallow depth of field, 
urban background with bokeh, candid moment
```

### Exercise 2: Create a Complete Prompt

Topic: A mountain landscape

**Your turn:** Write a complete prompt using the learned structure.

## 🔗 Additional Resources

- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [Lexica.art](https://lexica.art/) - Prompt explorer
- [PromptHero](https://prompthero.com/) - Prompt community

## 🤝 Contribute

Do you have additional techniques or tips? Contribute to this guide!

---

*Last updated: 2024*
