# 🎬 PROMPT: CINEMATIC STUDIO PORTRAIT — V1.0

---

## 🎯 Primary Directive

Photorealistic, ultra-high-detail **studio portrait** of the subject from **[Reference Image]**.  
The paramount objective is **1:1 facial identity replication** — preserving **exact facial structure, bone structure, eye shape and color, nose, lips, and unique skin tone**.  
Authenticity is key.

---

## 📸 Camera & Composition

| Parameter | Description |
|------------|-------------|
| **Shot Type** | Medium close-up, framed from the upper chest. |
| **Lens** | 85mm prime lens simulation. |
| **Aperture** | f/1.8 — shallow depth of field with sharp focus locked on the subject’s eyes and soft, pleasing background bokeh. |
| **Angle** | Classic 3/4 portrait view; subject’s body slightly turned away from the camera with the head angled back toward the lens. Chin neutral. |
| **Realism Cues** | Subtle lens imperfections: minimal chromatic aberration on edge highlights and natural lens breathing. |

---

## 💡 Lighting Schema — Three-Point Cinematic Setup

| Light Type | Description |
|-------------|-------------|
| **Key Light** | Large diffused softbox, positioned **45° to the right** of the camera. Warm-toned (tungsten ~3200K). Sculpt cheekbones and create a gentle *Rembrandt triangle* on the shadowed cheek. |
| **Fill Light** | Large reflector or diffused cool-toned light (~5500K) positioned on the left. **4:1 contrast ratio** (-2 stops relative to key). Lifts shadows without flattening features. |
| **Rim Light / Kicker** | Subtle high-angle hair light from behind. Adds a **warm-gold edge highlight** to hair and shoulders, creating separation from the background. |

---

## 👤 Subject & Styling

- **Expression:** Calm, confident, and neutral, with a subtle, almost imperceptible smile. Direct and engaging gaze.
- **Attire:** Clean, well-fitted black suit jacket over a crisp black dress shirt. Top button undone, no tie. Fabric has a natural, non-reflective texture.
- **Grooming:** Natural and clean skin. **Acne removed**, but without over-airbrushing or artificial perfection.

---

## 🎨 Aesthetic & Post-Processing

| Element | Specification |
|----------|----------------|
| **Background** | Seamless studio backdrop in **deep emerald green** (`#00563B`), with a subtle radial gradient darkening toward edges. |
| **Texture & Detail** | Render with **extreme micro-detail**. Preserve all natural skin textures, pores, and fine lines. Avoid digital smoothing or artificial beautification. |
| **Color Grade** | Cinematic teal-and-orange grade: shadows shift toward teal; midtones and highlights preserve warm natural skin tones. Blacks are deep but retain detail in the suit. |
| **Film Emulation** | Add a faint layer of **fine 35mm film grain** to enhance photographic realism. |

---

## ⚙️ Technical Parameters & Negative Prompt

| Parameter | Value |
|------------|--------|
| **Aspect Ratio** | `-ar 2:3` (or `1080x1920` for vertical format) |
| **Style** | `-style raw` (if available; prioritize photorealism over default model aesthetic) |
| **Image Weight** | `-iw 2` (or maximum supported weight for reference image) |
| **Negative Prompt** | `-no 3d render, digital painting, makeup, jewelry, sunglasses, distorted face, unnatural smoothing, plastic skin, illustration, stylized, fantasy, filter` |
