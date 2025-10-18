# 🤝 Contributing Guide

Thank you for your interest in contributing to **Photo**! This repository grows thanks to the community and all contributions are welcome.

> 📖 **[Versión en Español](./CONTRIBUTING.es.md)** | **English Version**

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Contribution Process](#contribution-process)
- [Style Guide](#style-guide)
- [Prompt Structure](#prompt-structure)
- [Pull Request Review](#pull-request-review)

## 📜 Code of Conduct

This project adheres to a code of conduct. By participating, you are expected to maintain a respectful and collaborative environment.

### Expected Behaviors

- ✅ Be respectful to other contributors
- ✅ Accept constructive criticism
- ✅ Focus on what's best for the community
- ✅ Show empathy towards other members

### Unacceptable Behaviors

- ❌ Offensive or discriminatory language
- ❌ Personal or political attacks
- ❌ Public or private harassment
- ❌ Publishing others' private information

## 🎯 How Can I Contribute?

### 1. Add New Prompts

The most common way to contribute is by adding new, tested prompts.

**Requirements:**
- The prompt must be **tested and functional**
- Include at least **one visual example** of the result
- Follow the [official template](./assets/template-prompt.md)
- Document parameters and configurations used

### 2. Improve Existing Prompts

- Optimize prompts for better results
- Add variations or additional tips
- Update visual examples
- Fix errors or outdated information

### 3. Report Issues

- Prompts that don't work as described
- Documentation errors
- Technical repository issues
- Improvement suggestions

### 4. Improve Documentation

- Fix typos
- Improve explanations
- Translate content
- Add guides and tutorials

## 🔄 Contribution Process

### Step 1: Fork the Repository

```bash
# Click the "Fork" button on GitHub
# Then clone your fork
git clone https://github.com/YOUR-USERNAME/photo.git
cd photo
```

### Step 2: Create a Branch

```bash
# Create a descriptive branch
git checkout -b prompt/model-category-name
# Examples:
# - prompt/nanobanana-portrait-cyberpunk
# - fix/midjourney-landscape-parameters
# - docs/improve-contributing-guide
```

### Step 3: Make Changes

1. **For new prompts:**
   - Copy the template: `cp assets/template-prompt.md prompts/[model]/[category]/[name].md`
   - Fill in all information
   - Add example images in `examples/[model]/`

2. **For improvements:**
   - Edit necessary files
   - Keep formatting consistent

### Step 4: Commit Changes

```bash
# Add your changes
git add .

# Commit with descriptive message
git commit -m "feat: add cyberpunk portrait prompt for NanoBanana"

# Commit types:
# - feat: new prompt or feature
# - fix: bug fixes
# - docs: documentation changes
# - style: formatting, no code changes
# - refactor: code reorganization
# - test: add tests
```

### Step 5: Push and Pull Request

```bash
# Push to your fork
git push origin your-branch

# Go to GitHub and create a Pull Request
# Clearly describe what you're adding or changing
```

## 📝 Style Guide

### File Names

- Use **kebab-case**: `fire-water-portrait.md`
- Be **descriptive**: `cyberpunk-street-night.md`
- Avoid special characters

### Markdown Format

- Use hierarchical headings (`#`, `##`, `###`)
- Include emojis for better readability 🎨
- Use code blocks with syntax: ` ```bash `
- Add tables for parameters

### Images

- Format: **JPG** or **PNG**
- Max size: **2MB** per image
- Recommended resolution: **1024x1024** or similar
- Descriptive names: `nanobanana-fire-water-portrait.jpg`

## 🎨 Prompt Structure

Each prompt should include:

### ✅ Required

1. **General Information**
   - Model used
   - Category
   - Style

2. **Complete Prompt**
   - Exact text used
   - Code format

3. **Negative Prompt**
   - What to avoid in generation

4. **Parameters**
   - Specific configuration
   - Recommended values

5. **Visual Example**
   - At least one image
   - Actual generated result

### 🌟 Recommended

- Tips and variations
- Additional notes
- Relevant tags
- Author information

### ❌ Avoid

- Untested prompts
- Unrelated images
- Incomplete information
- Incorrect parameters

## 🔍 Pull Request Review

### Acceptance Criteria

Your PR will be reviewed based on:

1. **Prompt Quality**
   - Does it work as described?
   - Does it produce consistent results?
   - Is it well documented?

2. **Documentation**
   - Does it follow the template?
   - Does it include all necessary information?
   - Does it have visual examples?

3. **Format**
   - Does it follow the style guide?
   - Are files in the correct folders?
   - Are names descriptive?

### Review Time

- Simple PRs: **1-3 days**
- Complex PRs: **3-7 days**
- You can mention maintainers if there's no response

### Feedback

- Respond to review comments
- Make requested changes
- Keep the conversation professional

## 🏷️ Naming Conventions

### Branches

```
type/model-category-description

Examples:
- prompt/nanobanana-portrait-warrior
- fix/dalle-landscape-parameters
- docs/update-readme
```

### Commits

```
type: brief description

Examples:
- feat: add epic warrior portrait for NanoBanana
- fix: correct CFG scale in cyberpunk prompt
- docs: improve contribution guidelines
```

## 💡 Tips for Contributors

### For New Contributors

1. **Start small**: Add a simple prompt first
2. **Read examples**: Review existing prompts as reference
3. **Ask questions**: Use Discussions if you have doubts
4. **Be patient**: Reviews can take time

### For Experienced Contributors

1. **Help others**: Review PRs from new contributors
2. **Improve existing**: Optimize old prompts
3. **Document**: Add guides and tutorials
4. **Innovate**: Experiment with new techniques

## 🎓 Useful Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [How to Write Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

## 📞 Need Help?

- 💬 [Discussions](https://github.com/webmip/photo/discussions) - General questions
- 🐛 [Issues](https://github.com/webmip/photo/issues) - Report problems
- 📧 Email: [Your contact email]

## 🙏 Acknowledgments

Thank you for contributing to **Photo**. Every prompt, correction, or suggestion helps make this collection more useful for the entire AI creator community.

---

**Ready to contribute?** 🚀

1. Fork the repository
2. Create your branch
3. Add your prompt
4. Open a Pull Request

We look forward to seeing your contributions!
