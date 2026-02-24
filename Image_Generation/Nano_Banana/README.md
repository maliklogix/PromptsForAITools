# Nano Banana Pro — Prompt Guide

## Overview
Nano Banana Pro is a cutting-edge AI image generation model built on Google's Gemini architecture. It creates hyper-realistic, cinematic-quality images from text and structured JSON prompts. The model excels at photorealistic portraits, fashion editorial photography, product advertising, 3D Pixar-style animation, cinematic stills, food photography, and much more.

## What's Inside
- **`System_Prompt.txt`** — Comprehensive system prompt defining Nano Banana Pro's identity, behavioral rules (camera simulation, material rendering, lighting expertise), tone guidelines, and response strategies across all visual domains.
- **`User_Prompts.txt`** — **9,800+ curated prompts** organized into 15 categories, sourced from the community-curated [awesome-nano-banana-pro-prompts](https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts) library.

## Categories
| Category | Prompts | Description |
|---|---|---|
| 📸 Photorealistic Portraits | 3,427 | Studio, candid, editorial, beauty, expression grids |
| 👗 Fashion & Editorial | 1,597 | High-fashion, streetwear, magazine, glamour |
| 🎬 Cinematic & Film Stills | 981 | Movie scenes, storyboards, documentary, noir |
| 🎯 General & Miscellaneous | 749 | Multi-domain and unique prompts |
| 🏷️ Product & Commercial | 683 | Luxury products, ads, skincare, beverages |
| 🎨 Art & Illustration | 399 | Concept art, digital painting, sketch, abstract |
| 📷 Lifestyle & Candid | 356 | Morning selfies, couple shots, travel, party |
| 🧊 3D & Pixar-Style | 316 | Pixar/Disney characters, 3D renders, emoji |
| 🦸 Cosplay & Character | 258 | Superhero, anime, mythological recreation |
| 🏛️ Architecture & Environment | 254 | Interiors, cityscapes, abandoned locations |
| ✨ Surreal & Fantasy | 218 | Magical, futuristic, ethereal, holographic |
| 🏺 Sculpture & Diorama | 160 | Miniature worlds, jade bowls, figurines |
| 🌍 Cultural & Traditional | 154 | Traditional attire, cultural scenes |
| 🍰 Food & Culinary | 127 | Food photography, macro, floating compositions |
| 🎥 Video & Motion | 126 | Vlog-style, reels, cinematic sequences |

## Prompt Format
Nano Banana Pro accepts prompts in **three formats**:

### 1. Plain Text
```
A hyper-realistic portrait of a woman in a red silk dress, golden hour lighting,
shot on Canon EOS R5 with 85mm f/1.4 lens, shallow depth of field.
```

### 2. Structured JSON
```json
{
  "meta": { "quality": "8K ultra-detailed", "camera": "Sony A7R V", "lighting": "golden hour" },
  "scene": { "location": "rooftop garden", "atmosphere": "warm, romantic" },
  "subject": { "gender": "female", "outfit": "red silk gown", "expression": "serene smile" },
  "effects": { "depth_of_field": "shallow", "grain": "minimal" }
}
```

### 3. Hybrid (Text + JSON fields)
Mix descriptive text with JSON for precision on specific attributes.

## Tips for Best Results
1. **Be specific with camera and lens** — "85mm f/1.4" gives different results than "24mm f/2.8"
2. **Describe lighting explicitly** — "Rembrandt lighting with a 3:1 ratio" beats "good lighting"
3. **Include material details** — "silk with soft sheen" or "leather with visible grain"
4. **Use negative prompts** — Exclude unwanted elements like watermarks, extra limbs, or airbrushed skin
5. **Specify aspect ratio** — Match your output needs: 9:16 for mobile, 16:9 for cinematic
6. **Layer your description** — Camera → Lighting → Subject → Environment → Post-processing

## Source
Prompts curated from [YouMind-OpenLab/awesome-nano-banana-pro-prompts](https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts) — a community library with 8,000+ stars on GitHub.
