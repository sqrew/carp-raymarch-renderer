# Examples
This directory contains practical examples of how to use the Carp modular raymarching stack.

### 1. Simple Render (`red_sphere.carp`)
Shows the "Hello World" of raymarching: a shaded, reflective sphere on a floor.
- **Key Concepts**: Basic pipeline setup, recursive reflections, simple material definitions.

### 2. CSG Gallery (`csg_gallery.carp`)
Demonstrates complex geometry using Boolean operations from `carp-sdf`.
- **Key Concepts**: `Sdf.subtract`, `Sdf.union`, mapping multiple objects to different materials.

### 3. Multi-Light Scene (`multi_light.carp`)
Shows how to accumulate energy from multiple light sources for more dynamic lighting.
- **Key Concepts**: Accumulating results from `Renderer.shade-hit`, using colored lights.

## Running the Examples
You can run any example using the Carp REPL:
```bash
carp -x examples/simple_render.carp
```
Each example generates a `.ppm` image file in the current directory.
