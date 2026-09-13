# Slopcannon — brand & interface concepts

**[Explore the interactive preview](https://bonejohnson8.github.io/slopcannon-concepts/)**

A cinematic splash page, two approaches to conversational production, a full Studio concept, and an interactive brand lab. This is a design prototype, separate from the live Slopcannon product.

## Explore version 2

Use the bottom navigation:

- **[Splash](https://bonejohnson8.github.io/slopcannon-concepts/#splash):** the original Chrome Club landing-page direction.
- **[Chat](https://bonejohnson8.github.io/slopcannon-concepts/#chat):** the original conversation-first concept.
- **[Studio](https://bonejohnson8.github.io/slopcannon-concepts/#studio):** dark production workspace with project assets, player, sequence, and scene inspector.
- **[Chat + controls](https://bonejohnson8.github.io/slopcannon-concepts/#director):** a second chat design, with editable scene cards and generation controls inside the conversation, plus a persistent film overview.
- **[Brand lab](https://bonejohnson8.github.io/slopcannon-concepts/#brand):** four snout silhouettes, ear spacing and height sliders, contrast samples, motion, and downloadable SVGs. The original three brand directions remain available in an expandable section.

## Take the walkthrough

Choose **Play walkthrough** in Studio or Chat + controls. Nine animated steps cover audio and references, visual direction, scene controls, cost review, clip generation, take selection, and assembly. Pause, step forward/back, or take over any control. Starting the walkthrough or using Reset resets the sample project.

The two new workspaces share one project in browser memory. Changes to scene selection, prompts, camera, framing, lip sync, duration, order, takes, and export settings carry across modes. A run started in chat remains the same run in Studio. Changing the cut makes an existing export stale.

Try a custom chat direction such as **“Lock the camera in scene 2”**, **“Make scene 3 more intimate”**, or **“Turn lip sync off in scene 1.”** These are scripted local interactions. Other messages are saved verbatim as the selected scene's direction.

## What is simulated

No accounts, model calls, production services, payments, uploads, or customer data are connected. All credits and generation/assembly progress are illustrative. Selected files contribute filenames only. The sample waveform does not represent analyzed audio. Playback is a silent animated storyboard using fictional concept artwork; it is not a generated film. A second take demonstrates a warmer color grade. The export demo downloads a real JSON shot list, not an MP4.

Changes last until the page is reloaded. The original Chat is a separate design example from the shared Studio / Chat + controls project.

## Brand system

The recommended mark uses shorter, outward-splayed ears and a wider gap. The other candidates use wide low ears, compact ears, or just the snout. The twin nostrils have transparent cutouts. Ear adjustments update marks across the concept; the full 3D mascot is a separate asset. The snout-only favicon stays optically optimized for small sizes.

## Design and performance

Plain HTML/CSS/JavaScript with relative assets, no framework or WebGL runtime, no external fonts, and reduced-motion support. Original generated artwork and a compact vector mark. The prototype is marked `noindex,nofollow`; SEO copy and application metadata remain drafts.

Serve this directory with any static HTTP server. GitHub Pages publishes the root of `main`; `.nojekyll` preserves the static files.

## Files

- `index.html`, `styles.css`, `app.js`: original splash, Chat, and brand directions
- `studio.js`, `studio.css`: shared Studio and Chat + controls experience
- `brand-lab.js`, `brand-lab.css`: logo exploration and motion studies
- `mascot.webp`, `worlds.webp`, `frog-storyboard.webp`: original concept artwork
- `marks/`: standalone vector candidates
- `image-prompts.md`: artwork direction and generation provenance

No production application code or customer records are included.
