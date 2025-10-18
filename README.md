# Awesome Sora 2 Prompts ✨

> A curated collection of high-quality prompts for OpenAI's Sora and Sora 2 video generation models, with deep analysis and practical guidance for prompt engineering.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 💎 Sponsor

> **[Sora2Api](https://www.sora2api.org/)** - Unified API for watermark-free Sora2 video generation. Fast, simple, and scalable text-to-video and image-to-video API with synchronized audio support.

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

<table>
<thead>
<tr>
<th>Name</th>
<th>Prompt Preview</th>
<th align="center">Video</th>
<th align="center">Analysis</th>
</tr>
</thead>
<tbody>

<tr>
<td><strong>🌃 Tokyo Walk</strong></td>
<td>"A stylish woman walks down a Tokyo street filled with warm glowing neon..."</td>
<td align="center">
  <a href="https://cdn.openai.com/sora/videos/tokyo-walk.mp4">
    <img src="https://img.shields.io/badge/▶️_Play-Video-red?style=for-the-badge" alt="Play Video"/>
  </a>
</td>
<td align="center">
  <a href="./prompts/official-prompts.md#tokyo-walk">📖 Details</a>
</td>
</tr>

<tr>
<td><strong>🦣 Wooly Mammoths</strong></td>
<td>"Several giant wooly mammoths approach treading through a snowy meadow..."</td>
<td align="center">
  <a href="https://cdn.openai.com/sora/videos/wooly-mammoth.mp4">
    <img src="https://img.shields.io/badge/▶️_Play-Video-red?style=for-the-badge" alt="Play Video"/>
  </a>
</td>
<td align="center">
  <a href="./prompts/official-prompts.md#wooly-mammoths">📖 Details</a>
</td>
</tr>

<tr>
<td><strong>🚀 Mitten Astronaut</strong></td>
<td>"A movie trailer featuring the adventures of the 30 year old space man..."</td>
<td align="center">
  <a href="https://cdn.openai.com/sora/videos/mitten-astronaut.mp4">
    <img src="https://img.shields.io/badge/▶️_Play-Video-red?style=for-the-badge" alt="Play Video"/>
  </a>
</td>
<td align="center">
  <a href="./prompts/official-prompts.md#mitten-astronaut">📖 Details</a>
</td>
</tr>

<tr>
<td><strong>🐠 Papercraft Reef</strong></td>
<td>"A gorgeously rendered papercraft world of a coral reef..."</td>
<td align="center">
  <a href="https://cdn.openai.com/sora/videos/origami-undersea.mp4">
    <img src="https://img.shields.io/badge/▶️_Play-Video-red?style=for-the-badge" alt="Play Video"/>
  </a>
</td>
<td align="center">
  <a href="./prompts/official-prompts.md#papercraft-reef">📖 Details</a>
</td>
</tr>

<tr>
<td><strong>🐉 Dragon over Glacier</strong><br/><sub>Sora 2</sub></td>
<td>"Primary Target & Visuals: a dragon slicing past serrated ice spires..."</td>
<td align="center">
  <a href="https://openai.com/index/sora-2/">
    <img src="https://img.shields.io/badge/▶️_Play-Video-red?style=for-the-badge" alt="Play Video"/>
  </a>
</td>
<td align="center">
  <a href="./prompts/official-prompts.md#dragon-glacier">📖 Details</a>
</td>
</tr>

</tbody>
</table>

[→ See all official prompts](./prompts/official-prompts.md)

### Viral Community Prompts

Curated from high-engagement X posts, showcasing Sora 2's diverse capabilities from anime to advertising, meta-humor to motivational content.

<table>
<thead>
<tr>
<th>Prompt</th>
<th>Description</th>
<th align="center">Video</th>
</tr>
</thead>
<tbody>

<tr>
<td><strong>"cctv footage of sam stealing gpus at target for sora inference"</strong></td>
<td>CCTV-style video of Sam Altman shoplifting GPUs; meta-humor on AI compute needs with grainy security camera aesthetics</td>
<td align="center">
  <a href="https://x.com/GabrielPeterss4/status/1973120058907041902">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"I tested the AI model Sora 2 on classic anime, the result is hardly believable..."</strong></td>
<td>Classic anime recreation; long clip mimicking styles like Dragon Ball or Naruto with exceptional fidelity</td>
<td align="center">
  <a href="https://x.com/naegiko/status/1973171308868542578">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Rick and Morty generated by Sora 2 my god"</strong></td>
<td>Rick and Morty episode clip; faithful to show's chaotic style with dialogue and character voices</td>
<td align="center">
  <a href="https://x.com/atbeme/status/1973127491033375044">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"used Sora 2 to generate this video. the audio is great but the movement is still not very realistic."</strong></td>
<td>Generic action scene; highlights audio strengths but motion limitations, often shared for critique</td>
<td align="center">
  <a href="https://x.com/Andr3jH/status/1973171921899626966">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"the most 80's thing ever"</strong></td>
<td>Over-the-top 80s montage with neon, synth music, and retro fashion; uncanny valley vibes in a nostalgic package</td>
<td align="center">
  <a href="https://x.com/anatelorenzen/status/1973138258705183068">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Sora 2 can also do chaotic Japanese ads if you ask it to"</strong></td>
<td>Frenetic Japanese commercial style; fast cuts, exaggerated expressions, and cultural tropes</td>
<td align="center">
  <a href="https://x.com/cloud11665/status/1973115723309515092">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"generate the greatest hype video of all time"</strong></td>
<td>Epic motivational montage with dramatic music and visuals; AI-generated dialogue adds hype</td>
<td align="center">
  <a href="https://x.com/SantsPliego/status/1973206657682514069">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Generate a modern Japanese anime video of a hero fighting a villain on a rainy night..."</strong></td>
<td>Anime hero-villain fight; image-to-video with dynamic weather, flashes, swords, and blood effects</td>
<td align="center">
  <a href="https://x.com/KomikoAI/status/1973167598134333479">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"a group of people playing volleyball"</strong></td>
<td>Demonstrates enhanced physics in group activities</td>
<td align="center">
  <a href="https://x.com/mattshumer_/status/1973083840689156207">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"create a luxury ad for a black Mercedes Class G"</strong></td>
<td>High-production car commercial with smooth camera work</td>
<td align="center">
  <a href="https://x.com/LudovicCreator/status/1973236674659492236">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"open Sora, type a prompt in, and generate video!"</strong></td>
<td>Recursive "Soraception" showing the app interface</td>
<td align="center">
  <a href="https://x.com/elder_plinius/status/1973116259693949357">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Photorealistic werewolf transformation..."</strong></td>
<td>Transformation scene with audio and cinematic effects</td>
<td align="center">
  <a href="https://x.com/JeffSynthesized/status/1973198469943927089">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"un pangolín surfeando en Hawai (bueno y Sam)"</strong></td>
<td>A pangolin surfing in Hawaii with Sam Altman cameo; whimsical animal animations with realistic waves</td>
<td align="center">
  <a href="https://x.com/DotCSV/status/1973133251121160212">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Cartman reporting live the Genz Protests"</strong></td>
<td>South Park's Cartman in a news report parody; satirical take on protests with characteristic humor</td>
<td align="center">
  <a href="https://x.com/marouane53/status/1973295289923739936">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"a funny music video with corgis shaking their behinds"</strong></td>
<td>Corgi dance music video; cute and rhythmic, part of animal-themed viral series</td>
<td align="center">
  <a href="https://x.com/theteriyu/status/1973086774546125155">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Pink fluffy unicorns dancing on rainbows"</strong></td>
<td>Whimsical unicorn dance; nostalgic and colorful, fulfilling a repeated prompt challenge</td>
<td align="center">
  <a href="https://x.com/drewdil/status/1973238424627978451">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"lmao sora 2 is funny af"</strong></td>
<td>Unspecified funny clip shared for humor; likely absurd scenario showcasing Sora 2's entertainment value</td>
<td align="center">
  <a href="https://x.com/AGJimmi/status/1973141639347708003">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"@sama getting angry over a D&D game. he's being very nerdy about some specific rule of the game"</strong></td>
<td>Sam Altman in a heated Dungeons & Dragons session; captures nerdy frustration with detailed expressions and tabletop elements</td>
<td align="center">
  <a href="https://x.com/WesRothMoney/status/1973125953871397332">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Please use the characters in the image to generate a Japanese anime trailer in the style of Ghost in the Shell (Production I.G Studio)"</strong></td>
<td>Ghost in the Shell-style trailer; anime aesthetic with cyberpunk elements and character references from uploaded images</td>
<td align="center">
  <a href="https://x.com/chenshaoju/status/1973285480071569711">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Crazy sora 2. Is this real or AI??"</strong></td>
<td>Blurry, ambiguous scene questioning reality; plays on deepfake fears and AI authenticity with Sam Altman reference</td>
<td align="center">
  <a href="https://x.com/iamskorer/status/1973254528133898578">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"A cheerful and charming young Japanese idol live-streams a gaming session, dressed in a stylish and comfortable camisole..."</strong></td>
<td>Japanese idol gaming stream with ultra-realistic details; features lip-sync, interactive elements, cinematic lighting, and RGB gaming setup</td>
<td align="center">
  <a href="https://x.com/iX00AI/status/1973360047301468493">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"a pirate girl materializing laying on the red bed and saying: 'Poof! Hello guys, how do I look? I was generated in Sora 2...'"</strong></td>
<td>Pirate girl appearance with synchronized dialogue; combines materialization effects, character speech, and pirate flair with muscle flexing</td>
<td align="center">
  <a href="https://x.com/Jakub_AI_Art/status/1973127879006494968">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Advertisement for a gourmet cheese wheel, slow-motion rolls down alpine hills pursued by eager goats in chef hats..."</strong></td>
<td>Humorous cheese advertisement with slow-motion chase scene; playful and absurd concept with triumphant picnic finale</td>
<td align="center">
  <a href="https://x.com/Gdgtify/status/1973314782989263039">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"skateboarder does a kickflip"</strong></td>
<td>Simple skateboarding trick; tests physics accuracy with motion capture-like precision in athletic movement</td>
<td align="center">
  <a href="https://x.com/name__0_i_0/status/1973213801924403315">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"simulate me trying to gain access to Sora2 but failing"</strong></td>
<td>Meta simulation of access denial; ironic commentary on invite-only rollout and user frustration</td>
<td align="center">
  <a href="https://x.com/LordSecretive/status/1973209293601251476">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Two students whisper nervously while cheating during an exam"</strong></td>
<td>Classroom cheating scene; captures subtle tension and realistic student interactions with nervous body language</td>
<td align="center">
  <a href="https://x.com/airina_xyz/status/1973351766780682440">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Un viajero del tiempo intentando evitar la caída de la bomba de Hiroshima"</strong></td>
<td>Time traveler attempting to prevent Hiroshima bombing; dramatic historical reimagining with tension and moral weight</td>
<td align="center">
  <a href="https://x.com/Leroysmer/status/1973341723733721550">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"A short hair cute influencer is trying to sell to the camera a smooth cylindrical object..."</strong></td>
<td>Influencer product pitch with subtle humor; iPhone-style recording with polished minimal design aesthetic</td>
<td align="center">
  <a href="https://x.com/name__0_i_0/status/1973368893080215888">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"I asked SORA 2 to create a 90s Toy Ad of Epstein's Island"</strong></td>
<td>Retro 90s-style toy advertisement parody; surreal and controversial concept with upbeat narration and toy-like visuals</td>
<td align="center">
  <a href="https://x.com/Solopopsss/status/1973363399234052232">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"star in a musical using American Revolution style. Topic of rap is 'The Innovator's Dilemma'"</strong></td>
<td>Historical rap musical with cameo avatar; blends American Revolution aesthetics with modern rap about business innovation</td>
<td align="center">
  <a href="https://x.com/firstadopter/status/1973126057227383219">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"the gang discovers Waymo"</strong></td>
<td>South Park episode about Waymo self-driving cars; generates full episode clip with dialogue faithful to the show's style</td>
<td align="center">
  <a href="https://x.com/venturetwins/status/1973158674899280077">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

<tr>
<td><strong>"Love Island reveal scene. A young woman sits on a plush villa sofa during 'Movie Night'..."</strong></td>
<td>Reality TV parody with Ronald McDonald and Wendy; surreal Love Island scene mixing brand mascots with dramatic reactions</td>
<td align="center">
  <a href="https://x.com/Ror_Fly/status/1973220869318013399">
    <img src="https://img.shields.io/badge/▶️_Watch-X/Twitter-1DA1F2?style=for-the-badge&logo=x" alt="Watch on X"/>
  </a>
</td>
</tr>

</tbody>
</table>

[→ See all Sora 2 viral prompts with detailed analysis](./prompts/sora2-viral-prompts.md)

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

**Maintained by the community** | **Last Updated**: October 2025 | [Report Issues](https://github.com/zhangchenchen/awesome-sora2-prompt/issues)

