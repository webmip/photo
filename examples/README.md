# 🖼️ Examples Directory

This folder contains example images generated using the repository's prompts.

> 📖 **[Versión en Español](./README.es.md)** | **English Version**

## 📂 Structure

```
examples/
├── nanobanana/        # Examples generated with NanoBanana
├── gpt-5/             # Examples generated with GPT-5
├── midjourney/        # Examples generated with Midjourney
├── dalle/             # Examples generated with DALL-E
└── stable-diffusion/  # Examples generated with Stable Diffusion
```

## 📝 Naming Conventions

Example files should follow this format:

```
[category]-[brief-description].[extension]
```

**Examples:**
- `portrait-fire-water-duality.jpg`
- `portrait-vintage-car-night.png`
- `landscape-cyberpunk-street.jpg`
- `artistic-abstract-geometry.png`

## 🎨 Image Specifications

### Format
- **Preferred**: JPG for photographs, PNG for graphics
- **Max size**: 2MB per image
- **Recommended resolution**: 1024x1024 or similar

### Quality
- High-quality images that demonstrate the prompt
- No watermarks (unless from the model)
- Real results, not post-edited

## 📸 Adding Examples

When contributing a new prompt:

1. **Generate** the image using your prompt
2. **Save** in the corresponding model folder
3. **Name** according to conventions
4. **Reference** in your prompt file

**Example in your prompt:**
```markdown
## 🖼️ Visual Examples

![Fire Water Portrait](../../examples/nanobanana/portrait-fire-water-duality.jpg)
*Description of the result*
```

## ⚠️ Considerations

- **Rights**: Only upload images you have generated yourself
- **Content**: Keep content appropriate and professional
- **Relevance**: The image must correspond exactly to the prompt

## 🔍 Explore Examples

Browse the folders to see examples from each model and category. Each image should have its corresponding prompt in the `/prompts` folder.

---

[← Back to main README](../README.md)
