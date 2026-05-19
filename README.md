# Blender Expert Skill for Claude AI — Complete 3D Workflow Assistant

> An open-source Claude AI skill that turns Claude into a full Blender expert — covering EEVEE rendering, Cycles, Compositor, Sculpt Mode, Geometry Nodes, 3D modelling, lighting, and PBR texturing.

---

## What is this?

**Blender Expert Skill** is a Claude AI skill that gives Claude deep, structured knowledge of Blender 4.x — so you can ask anything about Blender in plain language and get accurate, step-by-step answers instantly.

Instead of searching through Blender documentation or watching long tutorials, just ask Claude:

- *"How do I set up three-point lighting in EEVEE?"*
- *"My Cycles render has fireflies — how do I fix it?"*
- *"How do I scatter objects on a surface using Geometry Nodes?"*
- *"What's the best way to unwrap UVs for a character?"*

Claude will answer with exact menu paths, node setups, shortcuts, and common pitfalls — like having a Blender expert sitting next to you.

---

## Topics Covered

### 🎬 EEVEE & Cycles Rendering
Real-time rendering with EEVEE Next (Blender 4.2+), physically accurate rendering with Cycles, denoising, sampling, color management, render passes, and GPU optimization.

### 🎛️ Compositor (Post-Processing)
Node-based post-processing: color grading, bloom/glow, depth of field, lens distortion, chromatic aberration, vignette, multi-pass compositing with OpenEXR.

### 🗿 Sculpt Mode
Dyntopo, Multiresolution workflow, all major sculpt brushes, face sets, masking, retopology, normal map baking from high-poly to low-poly.

### 🔷 Geometry Nodes (Procedural Modelling)
Scattering objects on surfaces, procedural arrays along curves, noise displacement, instancing, attribute workflows, and performance optimization.

### 🧊 3D Modelling
Hard-surface modelling with non-destructive modifier stack (Subdivision, Boolean, Bevel, Mirror, Array), organic character modelling, clean topology rules, and essential Edit Mode tools.

### 💡 Lighting
Three-point lighting, HDRI setup, IES lights, light linking (Blender 4.0+), lighting for product renders, architectural visualization, character portraits, and outdoor scenes.

### 🎨 Texturing & Shading (PBR)
Principled BSDF shader, full PBR texture map workflow (Base Color, Roughness, Metallic, Normal, AO), UV unwrapping, texture painting, and Cycles baking for game-ready assets.

### 🐍 Python / bpy Scripting
Automating Blender with Python: creating/transforming objects, managing materials, modifiers, animation keyframes, rendering via script, bmesh editing, and writing custom add-ons.

---

## How to Install

1. Download `blender-expert.skill` from this repository
2. Open Claude → **Settings → Skills → Install Skill**
3. Upload the `.skill` file
4. Done — Claude now has full Blender expertise

---

## Who is this for?

- **Blender beginners** who want fast answers without reading long docs
- **Intermediate artists** who want to speed up their workflow
- **Technical artists** automating Blender with Python
- **Game developers** baking textures and optimizing assets for real-time engines
- **VFX artists** using Blender Compositor for post-processing
- **3D hobbyists** learning sculpting, modelling, and rendering

---

## Why use Claude as a Blender assistant?

| Traditional Method | With Claude + This Skill |
|---|---|
| Search documentation (slow) | Instant answer in plain language |
| Watch 30-min tutorial for one answer | Get exactly what you need |
| Copy-paste from forums | Get answers specific to your version |
| Forget menu paths | Exact paths every time |
| Debug errors alone | Ask Claude what went wrong |

---

## Blender Version

Designed for **Blender 4.x** (4.1 / 4.2 LTS). Notes included for EEVEE Next (4.2+) vs legacy EEVEE differences. Also compatible with Blender 3.6 LTS for most topics.

---

## File Structure

```
blender-expert/
├── SKILL.md                    ← Main skill (topic router + quick reference)
└── references/
    ├── rendering.md            ← EEVEE & Cycles deep reference
    ├── compositor.md           ← Compositor node setups
    ├── sculpt.md               ← Sculpt Mode complete guide
    ├── geometry-nodes.md       ← Geometry Nodes patterns
    ├── modelling.md            ← Hard-surface & organic modelling
    ├── lighting.md             ← Lighting techniques
    ├── texturing.md            ← PBR texturing & shading
    └── bpy-scripting.md        ← Python / bpy automation
```

---

## License

MIT — free to use, modify, and share.

---

## Contributing

Found something missing or incorrect? Open an issue or submit a pull request. More Blender topics (animation, rigging, physics, particles) coming soon.

---

*Made with Claude AI · Blender 4.x · Open Source*
