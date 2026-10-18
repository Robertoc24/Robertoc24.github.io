---
title: "OverEngineered: Engineering Sandbox Game"
excerpt: "Current sole developer of a Roblox engineering sandbox with 40K+ total visits, spanning 3D models, programmable systems, gameplay code, and save-system integration."
collection: "portfolio"
permalink: "/portfolio/overengineered/"
order: 6
share: false
comments: false
---

**December 2025–present · Current sole developer · 40K+ total game visits**

OverEngineered is a Roblox engineering sandbox where players combine physical building components and programmable logic to create their own machines and systems. I continue development of the existing open-source game and now develop it independently, working across 3D modeling, gameplay code, interface design, and persistent data.

## From model to playable component

My work spans the asset and software sides of a building component: creating or refining its 3D model, defining its behavior, and integrating it into the game's building system. Examples in the repository include cone and bezel pieces, a tank sprocket, and updated sensor models.

I use Blender for models and decals, Roblox Studio for asset integration, and TypeScript with roblox-ts for game development.

## Programmable engineering systems

I expand the tools players can use to build and control their creations. One update added five matrix operations—inverse, vector transformation, transpose, determinant, and scaling—alongside a dedicated matrix-logic block model. Other work includes configurable wire-visualization limits and improvements to the in-game programming interface, including customizable editor colors.

These features connect mathematical operations, user interaction, and the game's visual building workflow.

## Saving and maintaining player creations

I work on external save-storage integration, save metadata, and migration between storage systems. This includes a non-destructive migration implementation designed to preserve existing data while transferring it, along with updates to backend selection and save handling.

Maintaining the game also involves debugging player-facing issues and incorporating upstream improvements while preserving contributor credits. The project builds on the work of its original developers and other open-source contributors; my current role covers its continued development across assets and code.

## Reach and development history

The game has **over 40,000 total visits**.

Selected examples from the public development history:

- [Matrix-operation expansion](https://github.com/space-cee/overengineered/commit/2662a3644893fae98c53d89a5f810d709ece7f7e)
- [Cone and bezel model additions](https://github.com/space-cee/overengineered/commit/5746ec0ab59ce9c69001de691f04748ce8664160)
- [Non-destructive save migration](https://github.com/space-cee/overengineered/commit/cde647022caff099cf1f6e63cfd5137cee8f0b26)
- [Customizable editor colors](https://github.com/space-cee/overengineered/commit/6f4213fc0a9e83dfc29d289d972528bde12f4894)

[View the project repository](https://github.com/space-cee/overengineered)

**Tools:** TypeScript, roblox-ts, Roblox Studio, Blender, SQL, Git.
