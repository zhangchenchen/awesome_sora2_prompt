# Awesome Sora 2 Prompts ✨

> A curated collection of high-quality prompts for OpenAI's Sora and Sora 2 video generation models, with deep analysis and practical guidance for prompt engineering.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Table of Contents

- [What is Sora?](#what-is-sora)
- [Core Principles](#core-principles)
- [Prompt Collections](#prompt-collections)
- [Prompt Engineering Guide](#prompt-engineering-guide)
- [Contributing](#contributing)
- [Resources](#resources)

## 🎬 What is Sora?

Sora is OpenAI's text-to-video generation model that acts as a "world simulator," capable of creating realistic and imaginative videos from text prompts. **Sora 2**, released on September 30, 2025, introduces:

- **Synchronized Audio**: Natural sound effects and dialogue generation
- **Enhanced Physics**: Improved realism in motion and object interactions
- **Self-Insertion Cameos**: Ability to insert custom avatars
- **Advanced Controllability**: More precise camera work and cinematic control

## 🎯 Core Principles

### The Five Pillars of Effective Sora Prompts

Based on analysis of official and viral prompts, every effective Sora prompt should include:

1. **Subject & Character**: Define WHO or WHAT (appearance, clothing, emotions)
2. **Action & Motion**: Describe WHAT IS HAPPENING (verbs, movements, interactions)
3. **Environment & Setting**: Establish WHERE and WHEN (location, time, atmosphere)
4. **Cinematic Framing**: Define HOW IT'S SEEN (camera angles, movements, shots)
5. **Aesthetic & Style**: Determine LOOK and FEEL (photorealistic, animated, film stock)

### The "World Simulator" Paradigm

Sora isn't just generating videos—it's simulating miniature, self-consistent worlds. Effective prompts should:

- Provide initial conditions and physical laws
- Specify how objects interact with each other
- Define environmental properties (gravity, lighting, reflections)
- Guide the physics implicitly or explicitly

### Prompt Length Strategy

- **Creative Exploration** (< 120 words): Best for imaginative, story-driven scenes
- **Precision Execution** (> 200 words): Best for cinematic control and technical accuracy

## 📚 Prompt Collections

### Official OpenAI Showcase Prompts

These represent the "gold standard" - official demonstrations of Sora's capabilities:

| Name | Prompt Preview | Video Link | Analysis |
|------|---------------|------------|----------|
| **Tokyo Walk** | "A stylish woman walks down a Tokyo street filled with warm glowing neon..." | [View Video](https://cdn.openai.com/sora/videos/tokyo-walk.mp4) | [Full Analysis](./prompts/official-prompts.md#tokyo-walk) |
| **Wooly Mammoths** | "Several giant wooly mammoths approach treading through a snowy meadow..." | [View Video](https://cdn.openai.com/sora/videos/wooly-mammoth.mp4) | [Full Analysis](./prompts/official-prompts.md#wooly-mammoths) |
| **Mitten Astronaut** | "A movie trailer featuring the adventures of the 30 year old space man..." | [View Video](https://cdn.openai.com/sora/videos/mitten-astronaut.mp4) | [Full Analysis](./prompts/official-prompts.md#mitten-astronaut) |
| **Papercraft Reef** | "A gorgeously rendered papercraft world of a coral reef..." | [View Video](https://cdn.openai.com/sora/videos/origami-undersea.mp4) | [Full Analysis](./prompts/official-prompts.md#papercraft-reef) |
| **Dragon over Glacier** (Sora 2) | "Primary Target & Visuals: a dragon slicing past serrated ice spires..." | [View Video](https://openai.com/index/sora-2/) | [Full Analysis](./prompts/official-prompts.md#dragon-glacier) |

[→ See all official prompts](./prompts/official-prompts.md)

### Viral Community Prompts

#### Sora 2 Specific (September 2025)

| Prompt | Description | Video Link |
|--------|-------------|------------|
| "a group of people playing volleyball" | Demonstrates enhanced physics in group activities | [View](https://x.com/mattshumer_/status/1973083840689156207) |
| "create a luxury ad for a black Mercedes Class G" | High-production car commercial with smooth camera work | [View](https://x.com/LudovicCreator/status/1973236674659492236) |
| "open Sora, type a prompt in, and generate video!" | Recursive "Soraception" showing the app interface | [View](https://x.com/elder_plinius/status/1973116259693949357) |
| "Photorealistic werewolf transformation at campfire..." | Transformation scene with audio and cinematic effects | [View](https://x.com/JeffSynthesized/status/1973198469943927089) |

[→ See all Sora 2 viral prompts](./prompts/sora2-viral-prompts.md)

### Prompts by Category

- [🌄 Hyperrealism & Landscapes](./prompts/hyperrealism-landscapes.md)
- [🎨 Surreal & Imaginative](./prompts/surreal-imaginative.md)
- [👤 Character-Driven Narratives](./prompts/character-narratives.md)
- [🎭 Stylized & Animation](./prompts/stylized-animation.md)
- [📜 Historical & Archival](./prompts/historical-archival.md)
- [🎬 Cinematic & Director Styles](./prompts/cinematic-styles.md)

## 📖 Prompt Engineering Guide

Want to create your own amazing prompts? Check out our comprehensive guides:

- [**Getting Started**](./guides/getting-started.md) - Basic principles and your first prompt
- [**The Five Pillars Framework**](./guides/five-pillars.md) - Deep dive into the core framework
- [**Cinematic Techniques**](./guides/cinematic-techniques.md) - Camera angles, movements, and framing
- [**Style Replication**](./guides/style-replication.md) - Mimic famous directors and artists
- [**Physics & Motion**](./guides/physics-motion.md) - Implicit physics instructions
- [**Sora 2 Audio Guide**](./guides/audio-guide.md) - Working with synchronized audio

## 🤝 Contributing

We welcome contributions from the community! Whether it's a new prompt, analysis, or improvement, please see our [Contributing Guidelines](CONTRIBUTING.md).

### Quick Contribution Guide

1. Fork this repository
2. Add your prompt using the template
3. Include video link and source
4. Submit a pull request

## 📊 Prompt Analysis Insights

Based on community analysis of 32+ experiments:

- ✅ **Prompts under 120 words** perform better for creative content
- ✅ **Specific camera instructions** dramatically improve visual impact
- ✅ **Animal-focused prompts** have high success rates
- ✅ **Sensory details** (textures, lighting, reflections) enhance realism
- ⚠️ **Overly complex physics** may cause artifacts
- ⚠️ **Vague descriptions** lead to inconsistent results

## 🔗 Resources

### Official Resources
- [Sora 2 Official Announcement](https://openai.com/index/sora-2/)
- [Video Generation Models as World Simulators](https://openai.com/index/video-generation-models-as-world-simulators/)
- [Sora Technical Report](https://openai.com/index/sora/)

### Community Resources
- [Best Sora Prompts](https://bestsoraprompts.com/)
- [Prompt Sora Community](https://prompts-sora.com/)
- [Sora Prompt Engineering Guide](https://www.promptingguide.ai/models/sora)

### Related Repositories
- [awesome-sora-prompts](https://github.com/xjpp22/awesome--sora-prompts)
- [Awesome-Open-AI-Sora](https://github.com/Curated-Awesome-Lists/Awesome-Open-AI-Sora)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Star History

If you find this repository useful, please consider giving it a star! It helps others discover these resources.

---

**Maintained by the community** | **Last Updated**: October 2025 | [Report Issues](https://github.com/yourusername/awesome-sora2-prompt/issues)

