# 🎨 Midjourney Guide

> **Note:** This guide is under development. Contribute with your knowledge and experiences.
> 
> 📖 **[Versión en Español](./midjourney-guide.es.md)** | **English Version**

## 📖 Introduction

Midjourney is known for its ability to create **conceptual art and exceptional visual creativity**. This guide will help you master its unique features.

## 🎯 Key Features

- **Conceptual art**: Excellent for creative and unique ideas
- **Artistic style**: Artistic interpretation of prompts
- **Versatility**: From photorealism to abstract art
- **Composition**: Natural sense of visual composition

## 💡 Best Practices

### Prompt Structure

```
[Subject Description] + [Artistic Style] + [Lighting/Atmosphere] + [Parameters]
```

**Example:**
```
Cyberpunk street scene at night, rain-soaked neon reflections, 
volumetric fog, moody lighting, cinematic composition --ar 16:9 --v 6
```

### Midjourney Parameters

- `--ar [ratio]`: Aspect ratio (e.g., `--ar 16:9`, `--ar 1:1`)
- `--v [version]`: Model version (e.g., `--v 6`)
- `--style raw`: For more photorealistic results
- `--stylize [0-1000]`: Stylization control (default: 100)
- `--chaos [0-100]`: Result variability
- `--quality [.25, .5, 1]`: Rendering quality

## 🚫 Negative Prompts

In Midjourney, use `--no` to exclude elements:

```
--no blur, distortion, low quality, watermark
```

## ⚙️ Recommended Settings

### For Photorealism

```
[your prompt] --style raw --v 6 --ar 16:9
```

### For Conceptual Art

```
[your prompt] --stylize 250 --v 6 --ar 16:9
```

### For Experimentation

```
[your prompt] --chaos 50 --stylize 500 --v 6
```

## 🎨 Popular Styles

### Cinematic

```
cinematic lighting, movie still, dramatic composition, 
professional color grading
```

### Editorial/Fashion

```
editorial photography, high fashion, studio lighting, 
vogue style, professional photography
```

### Architecture

```
architectural photography, golden hour lighting, 
ultra wide angle, professional real estate photography
```

## 💡 Advanced Tips

1. **Use artist references** (with respect)
   - `in the style of [artist name]`

2. **Specify the medium**
   - `photograph`, `digital art`, `oil painting`

3. **Control composition**
   - `centered composition`, `rule of thirds`, `symmetrical`

4. **Adjust lighting**
   - `golden hour`, `blue hour`, `studio lighting`, `natural light`

## 📊 Aspect Ratio Table

| Ratio | Common Use | Command |
|-------|------------|---------|
| 1:1 | Instagram, square | `--ar 1:1` |
| 16:9 | Widescreen, YouTube | `--ar 16:9` |
| 9:16 | Vertical, Stories | `--ar 9:16` |
| 4:3 | Classic | `--ar 4:3` |
| 21:9 | Ultra wide | `--ar 21:9` |

## 🔄 Recommended Workflow

1. **Generate variations** with `/imagine`
2. **Upscale** the best option
3. **Refine** with `/vary` or `/remix`
4. **Adjust parameters** as needed

## 📚 Additional Resources

- [Official Midjourney Documentation](https://docs.midjourney.com/)
- [Community Examples](../../prompts/midjourney/)
- [Discussions](https://github.com/webmip/photo/discussions)

## 🤝 Contribute

Do you have tips or techniques that work well with Midjourney? Contribute to this guide!

---

*Last updated: 2024*
