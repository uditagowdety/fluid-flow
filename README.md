# 🌊 Fluid Flow — p5.js Sketch

An organic, fluid, and evolving **creative coding** sketch built with [p5.js](https://p5js.org/).  
The visuals use **Perlin-noise flow fields** and thousands of particles to generate liquid-like, smoke-like trails that are continuously evolving — never static.  
Control the flow with sliders or a MIDI controller, and randomize seeds for infinite variations.

---

## ✨ Features

- **Fluid particle trails** driven by a Perlin-noise vector field  
- **Real-time controls** via on-screen sliders or MIDI knobs:
  - 🎨 Hue / Color Shift
  - ⏩ Flow Speed
  - 🌪️ Distortion Intensity
  - ♾️ Symmetry multiplier
- **Randomize seed** with a key press (`R`) or button for endless variation  
- **Save frames** as PNG with `S`  
- **Collapsible sidebar** for fullscreen visuals  
- **Expandable structure** (Controller / Flow / Particles modules) so you can easily add:
  - Audio-reactivity  
  - More parameters  
  - Custom rendering styles  

---

## 🎛️ Controls

### Keyboard
- `R` → Randomize noise seed  
- `S` → Save a frame as PNG  
- `Toggle Sidebar` button (top-right) → Show/hide control panel  

### Sliders
- **Hue / Shift**: base color rotation  
- **Flow Speed**: how quickly the flow field evolves  
- **Distortion**: turbulence intensity in the field  
- **Symmetry**: number of rotational symmetries applied  

### MIDI (if supported in browser)
- CC 1 → Hue  
- CC 2 → Speed  
- CC 3 → Distortion  
- CC 4 → Symmetry  

---

## 🛠️ Installation & Usage

Clone this repo and open the HTML file in your browser:

```bash
git clone https://github.com/yourusername/fluid-flow.git
cd fluid-flow
