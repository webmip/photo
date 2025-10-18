# 📸 Reference Images Guide

> Guide for using reference images with AI image generation prompts.
> 
> 📖 **[Versión en Español](./reference-images-guide.es.md)** | **English Version**

## 📖 What are Reference Images?

Reference images are photographs or illustrations used to guide AI models in generating consistent results, particularly for:
- **Facial features and identity preservation**
- **Pose and composition guidance**
- **Style and aesthetic reference**
- **Lighting and mood inspiration**

## 🎯 Why Use Reference Images?

### Identity Consistency
When creating portrait series or character studies, reference images ensure the AI maintains the same facial features, proportions, and identity across multiple generations.

### Professional Results
Reference images help achieve:
- ✅ Consistent branding photography
- ✅ Character design continuity
- ✅ Professional portfolio coherence
- ✅ Accurate style replication

## 🖼️ Types of Reference Images

### 1. Face Reference
**Purpose:** Preserve exact facial features and identity

**Example from repository:**
- [Pixabay Reference](https://pixabay.com/es/photos/tall-man-entrenador-joven-body-1203884/) - Used for pose and composition in vintage car portrait

**Best practices:**
- Use high-resolution images (minimum 1024px)
- Clear, well-lit face with minimal obstructions
- Frontal or 3/4 view works best
- Multiple angles help for consistency

### 2. Pose Reference
**Purpose:** Guide body positioning and composition

**Characteristics:**
- Clear body language
- Defined posture
- Visible limb positioning
- Contextual environment

### 3. Style Reference
**Purpose:** Establish aesthetic, mood, and artistic direction

**Elements:**
- Lighting setup
- Color palette
- Composition style
- Atmospheric mood

## 💡 How to Use Reference Images in Prompts

### Method 1: Explicit Instruction (NanoBanana)

```
Use the exact facial features from the user's reference photo. 
Preserve all face proportions, skin tone, hairstyle, and expression exactly. 
Do not alter or morph the face. Maintain an ultra-consistent identity 
across all generations.

[Rest of your prompt...]
```

### Method 2: Style Description

```
In the style of [reference image description], capturing the same 
mood, lighting, and composition as seen in [specific details].

[Rest of your prompt...]
```

### Method 3: Technical Specifications

```
Replicate the lighting setup from reference: [describe lighting],
match the color grading: [describe colors],
mirror the composition: [describe framing].

[Rest of your prompt...]
```

## 🎨 Model-Specific Tips

### NanoBanana
- **Strength:** Exceptional at preserving facial identity
- **Tip:** Be explicit about "exact facial features" and "ultra-consistent identity"
- **Best for:** Portrait series, character consistency

### Midjourney
- **Strength:** Artistic interpretation of style references
- **Tip:** Use `--cref` parameter for character reference (if available)
- **Best for:** Stylistic consistency, mood matching

### Stable Diffusion
- **Strength:** Flexible with ControlNet and IP-Adapter
- **Tip:** Use ControlNet for pose guidance, IP-Adapter for face
- **Best for:** Technical control, multiple reference types

### DALL-E / GPT-5
- **Strength:** Natural language understanding of references
- **Tip:** Describe reference in detail within the prompt
- **Best for:** Conceptual similarity, style transfer

## 📋 Reference Image Checklist

Before using a reference image, ensure:

- [ ] **High Quality:** Minimum 1024px resolution
- [ ] **Clear Subject:** No obstructions or blur
- [ ] **Appropriate Lighting:** Well-lit, visible details
- [ ] **Relevant Content:** Matches your intended output
- [ ] **Rights Cleared:** You have permission to use the image
- [ ] **Proper Format:** JPG or PNG format

## ⚖️ Legal and Ethical Considerations

### Copyright
- ✅ Use your own photographs
- ✅ Use royalty-free stock images (Pixabay, Unsplash, Pexels)
- ✅ Use images with proper licenses
- ❌ Don't use copyrighted celebrity photos without permission
- ❌ Don't use others' personal photos without consent

### Ethical Use
- ✅ Respect privacy and consent
- ✅ Credit reference sources when sharing
- ✅ Use for creative and professional purposes
- ❌ Don't create deepfakes or misleading content
- ❌ Don't use for harassment or impersonation

## 🔍 Finding Quality Reference Images

### Free Stock Photo Sites
- **Pixabay** - CC0 license, free for commercial use
- **Unsplash** - High-quality, free images
- **Pexels** - Curated free stock photos
- **Wikimedia Commons** - Public domain images

### Photography Communities
- **Flickr** - Check licenses (CC BY, CC0)
- **500px** - Professional photography (check rights)
- **Behance** - Creative work (contact artists)

### Creating Your Own
- **Self-portraits:** Full control and rights
- **Hired models:** Get proper releases
- **Friends/family:** Obtain clear consent
- **Studio sessions:** Professional reference library

## 📊 Reference Image Best Practices by Category

### Portrait Photography
- **Face:** Clear, well-lit, frontal or 3/4 view
- **Expression:** Neutral or desired emotion
- **Resolution:** 1024x1024 minimum
- **Background:** Simple, non-distracting

### Fashion/Editorial
- **Pose:** Full body or detailed crop
- **Styling:** Clear view of clothing/accessories
- **Lighting:** Studio or natural light reference
- **Composition:** Professional framing

### Landscape/Environment
- **Perspective:** Clear depth and layers
- **Lighting:** Time of day, weather conditions
- **Elements:** Foreground, midground, background
- **Mood:** Atmospheric conditions

### Artistic/Conceptual
- **Style:** Clear artistic direction
- **Color:** Defined palette
- **Composition:** Unique framing or perspective
- **Elements:** Key visual components

## 🛠️ Technical Implementation

### Preparing Reference Images

1. **Crop appropriately:** Focus on relevant areas
2. **Adjust resolution:** Upscale if needed (1024px+)
3. **Enhance clarity:** Sharpen if slightly soft
4. **Normalize exposure:** Ensure good visibility
5. **Save in correct format:** JPG for photos, PNG for graphics

### Organizing References

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

## 💬 Community Examples

Check our repository prompts that use reference images:
- [Vintage Car Night Portrait](../prompts/nanobanana/portrait/vintage-car-night-portrait.md) - Uses Pixabay reference for pose and composition

## 🤝 Contributing

Have tips for using reference images? Share your knowledge:
- Open a Discussion with your technique
- Submit a PR with example prompts
- Share successful reference strategies

## 📚 Additional Resources

- [Prompt Engineering Basics](./prompt-engineering-basics.md)
- [NanoBanana Guide](./nanobanana-guide.md)
- [Contributing Guide](../CONTRIBUTING.md)

---

*Last updated: 2024-10-18*
