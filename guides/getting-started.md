# Getting Started with Sora Prompt Engineering

A beginner-friendly guide to creating effective prompts for Sora and Sora 2.

## Table of Contents

- [What is Prompt Engineering?](#what-is-prompt-engineering)
- [The World Simulator Mindset](#the-world-simulator-mindset)
- [Your First Prompt](#your-first-prompt)
- [Common Mistakes](#common-mistakes)
- [Quick Reference](#quick-reference)

## What is Prompt Engineering?

Prompt engineering for Sora is the practice of crafting text instructions that guide the AI to generate specific video content. Unlike simple image generation, video prompts must consider:

- **Time**: How things change and move
- **Physics**: How objects interact with each other and the environment
- **Narrative**: What story unfolds over the duration
- **Cinematography**: How the scene is captured and presented

Think of yourself as a **virtual film director** communicating with an AI cinematographer.

## The World Simulator Mindset

### Key Concept: Sora as a World Simulator

Sora doesn't just "draw moving pictures"—it **simulates miniature worlds**. This means:

✅ **DO**: Describe a world with internal logic
```
"A coffee cup sits on a wooden table. Steam rises from the hot liquid,
creating swirling patterns that catch the morning sunlight streaming
through a nearby window. The liquid ripples gently."
```

❌ **DON'T**: Just list visual elements
```
"coffee cup, steam, wood, window, sun"
```

### The Difference

The first prompt gives Sora:
- Physical properties (hot liquid → steam rises)
- Environmental context (morning sunlight)
- Material interactions (steam catching light)
- Dynamic elements (ripples, swirling)

The second prompt is too sparse and disconnected.

## Your First Prompt

Let's build a simple but effective prompt step-by-step using the **Five Pillars Framework**.

### Step 1: Define Your Subject

**What or who is in the scene?**

```
A golden retriever
```

Add specificity:
```
A young golden retriever with fluffy fur and bright, curious eyes
```

### Step 2: Add Action

**What is happening?**

```
A young golden retriever with fluffy fur and bright, curious eyes
running and jumping
```

Make it more dynamic:
```
A young golden retriever with fluffy fur and bright, curious eyes
running joyfully across an open field, occasionally leaping into the air
to catch floating dandelion seeds
```

### Step 3: Establish Environment

**Where and when is this taking place?**

```
A young golden retriever with fluffy fur and bright, curious eyes
running joyfully across an open field, occasionally leaping into the air
to catch floating dandelion seeds. The field is filled with wildflowers
under a clear blue sky on a sunny spring afternoon.
```

### Step 4: Add Cinematic Framing

**How should this be filmed?**

```
A young golden retriever with fluffy fur and bright, curious eyes
running joyfully across an open field, occasionally leaping into the air
to catch floating dandelion seeds. The field is filled with wildflowers
under a clear blue sky on a sunny spring afternoon. Shot with a tracking
camera following the dog's movement, with shallow depth of field keeping
the dog in sharp focus while the background softly blurs.
```

### Step 5: Define Aesthetic

**What should it look and feel like?**

```
A young golden retriever with fluffy fur and bright, curious eyes
running joyfully across an open field, occasionally leaping into the air
to catch floating dandelion seeds. The field is filled with wildflowers
under a clear blue sky on a sunny spring afternoon. Shot with a tracking
camera following the dog's movement, with shallow depth of field keeping
the dog in sharp focus while the background softly blurs. Photorealistic,
shot on 35mm film with warm, vibrant colors.
```

### ✅ Final Result

You now have a complete, well-structured prompt that:
- Describes a clear subject with personality
- Includes dynamic, natural action
- Establishes a vivid environment
- Specifies camera work
- Defines the visual style

**This is a solid foundation for generating high-quality video.**

## Common Mistakes

### ❌ Mistake 1: Too Vague

**Bad:**
```
"A person walking in a city"
```

**Why it's bad:** No specifics about person, walking style, city type, time, mood

**Better:**
```
"A businesswoman in a gray suit walks briskly down a rainy New York street
at dusk, dodging puddles while checking her phone. Neon signs reflect in
the wet pavement."
```

---

### ❌ Mistake 2: Physically Impossible or Unclear

**Bad:**
```
"A basketball explodes through the hoop"
```

**Why it's bad:** Vague physics—does it explode before, during, or after? What causes explosion?

**Better:**
```
"A basketball passes through the hoop with a swish. As it hits the ground,
it suddenly bursts into thousands of orange and black confetti pieces that
scatter across the court."
```

---

### ❌ Mistake 3: Too Many Conflicting Ideas

**Bad:**
```
"A medieval knight riding a motorcycle through a futuristic city while
dragons fly overhead and underwater scenes show fish and also there's
a concert happening"
```

**Why it's bad:** Too many disconnected concepts; model can't establish coherent world logic

**Better:** Pick ONE core concept and develop it fully
```
"A medieval knight in full armor rides a sleek motorcycle through a neon-lit
cyberpunk city. Holographic dragons created by street performers fly overhead,
their translucent forms flickering in the rain. Medieval meets future aesthetic."
```

---

### ❌ Mistake 4: Forgetting Motion

**Bad:**
```
"A beautiful mountain landscape with snow and trees"
```

**Why it's bad:** No movement specified—video needs dynamic elements

**Better:**
```
"A majestic mountain landscape where fresh snow falls gently, dusting the
pine trees. Wind causes branches to sway, and a bird takes flight from a
tree in the foreground. Camera slowly pans across the vista."
```

---

### ❌ Mistake 5: Ignoring Lighting

**Bad:**
```
"A person reading a book in a library"
```

**Why it's bad:** No lighting context—drastically affects mood and quality

**Better:**
```
"A person reads a leather-bound book in an old library. Warm afternoon
sunlight streams through tall windows, creating dramatic shafts of light
through floating dust particles. The lighting creates a cozy, scholarly
atmosphere."
```

## Quick Reference

### Prompt Length Guidelines

| Length | Best For | Example Use Case |
|--------|----------|-----------------|
| **Short (< 50 words)** | Clear concepts with strong style keywords | "A papercraft coral reef", "Historical footage of gold rush" |
| **Medium (50-120 words)** | Balanced creative prompts | Most character-driven and landscape scenes |
| **Long (120-300+ words)** | Precision control, technical specs | Cinematic productions, director-style prompts |

### Essential Keywords by Category

#### Camera Work
- `drone view`, `aerial shot`, `bird's eye view`
- `close-up`, `extreme close-up`, `wide shot`
- `tracking shot`, `dolly zoom`, `pan across`
- `POV shot`, `over-the-shoulder`, `low angle`, `high angle`

#### Film & Style
- `shot on 35mm film`, `shot on 70mm film`
- `cinematic style`, `movie trailer`
- `photorealistic`, `realistic 3D animation`
- `depth of field`, `bokeh effect`, `lens flare`

#### Lighting
- `golden hour`, `morning light`, `sunset glow`
- `high-key lighting`, `low-key lighting`
- `dramatic lighting`, `soft natural light`
- `neon lights`, `candlelight`, `moonlight`

#### Motion & Physics
- `slow motion`, `time-lapse`
- `floating`, `falling`, `spinning`
- `gently swaying`, `violently shaking`
- `rippling water`, `blowing in the wind`

#### Mood & Atmosphere
- `cozy atmosphere`, `tense mood`, `peaceful ambiance`
- `mysterious`, `joyful`, `melancholic`
- `ethereal`, `gritty`, `whimsical`

### Sora 2 Specific: Audio Keywords

With Sora 2's audio capabilities, you can now include:

- `calling out loudly`, `whispering softly`
- `footsteps echoing`, `wind howling`
- `music playing`, `birds chirping`
- `engine roaring`, `water splashing`
- `dialogue: "..."` (specify exact words)

## Template for Quick Start

Copy and fill in this template:

```
[SUBJECT: Who/what with specific details]
[ACTION: Dynamic verb and movement]
[ENVIRONMENT: Location, time, weather/atmosphere]
[CAMERA: Angle, movement, shot type]
[STYLE: Film stock, aesthetic, lighting]
[AUDIO (Sora 2): Sounds, dialogue, music] (optional)
```

**Example:**
```
A young chef in a white uniform
flips a crepe in a copper pan with expert precision, the crepe spinning in mid-air
in a sunlit French bistro kitchen with copper pots hanging overhead, morning light
streaming through windows
Shot with a close-up tracking shot following the crepe's arc through the air,
shallow depth of field, high frame rate for slow-motion effect
Warm, inviting cinematography with soft golden light, shot in cinematic style
Sound of the pan sizzling, crepe landing with a soft thump, ambient kitchen sounds
```

## Next Steps

Now that you understand the basics:

1. **Practice**: Start with simple prompts and gradually add complexity
2. **Study Examples**: Analyze [Official Prompts](../prompts/official-prompts.md)
3. **Learn the Framework**: Deep dive into the [Five Pillars](./five-pillars.md)
4. **Explore Techniques**: Check out [Cinematic Techniques](./cinematic-techniques.md)
5. **Experiment**: Try different combinations and variations

Remember: **Good prompts are specific, physically coherent, and tell a mini-story.**

---

**Next Guide**: [The Five Pillars Framework](./five-pillars.md) - Master the core prompt structure

