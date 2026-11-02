# TexGen Studio

TexGen Studio is a self-contained procedural texture generator for creating square graphics, materials, abstract patterns, and stylized effects directly in a web browser. I created it to bring a flexible, layer-based workflow inspired by procedural noise and shader tools into a portable app that does not need installation.

## Highlights

- GPU-accelerated procedural generation with WebGL
- Layer stack, adjustment groups, blend modes, opacity, masks, and solo/lock controls
- Noise, geometric, organic, textile, terrain, space, graph, light, and stylized pattern families
- Per-layer transforms, vector mapping, color ramps, levels, and randomization controls
- Chained mirroring and deformation, bloom, chromatic aberration, outlines, blur/sharpening, vignette, grain, glitch, and other effects
- Built-in texture gallery stored locally in the browser
- Project, individual-layer, and gallery import/export using JSON
- PNG, JPEG, and WebP image export with selectable resolution, supersampling, background, and quality
- English interface by default, with an optional Czech interface using the `CS` button

## Requirements

- A current desktop browser with WebGL support
- No Node.js, package manager, internet connection, or additional dependency is required

## Quick start

1. Extract the complete ZIP to a folder.
2. Double-click **Start TexGen.bat**, or open **index.html** in a modern browser.
3. Add a layer and choose a procedure from the preview grid.
4. Adjust its parameters, mapping, colors, masks, and effects.
5. Combine more layers or adjustment groups as needed.
6. Use **Export** to save the final image.

## Saving your work

TexGen automatically keeps the current session and gallery in the browser's local storage. For a durable backup or transfer to another browser/computer, export the project settings as JSON. Gallery entries can also be exported and imported as JSON.

When importing a full project into a non-empty document, the English interface asks for `REPLACE` or `ADD`. Older Czech commands remain accepted for compatibility.

[Detailed documentation](README-DETAILS.md) · [All releases](https://github.com/FajkPes/TexGen-Studio/releases)

## Credits

**Idea, concept and design:** FajkPes  
**Coding:** ChatGPT Codex, Claude and Google Antigravity
