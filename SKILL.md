---
name: divine-argon
description: "Divine-Argon is an engineering and design standard for websites, web apps, UI and UX, 2D and 3D games (Three.js, WebGL, WebGPU), shaders, lighting and shadows, detailed 3D environments with props, particles and animation, mood-based color, ready-made font combos, layout hierarchy, mobile-first UX, natural procedural audio, AI image generation, and relaxed human-sounding chat. Use it whenever the user asks for a website, app, UI component, game, 3D scene, shader, poster, AI image, sound for a visual project, complex code, or everyday conversation. Always reply in the language the user wrote when invoking this skill. Made by: Zhawoilah-id"
---

# Divine-Argon: Engineering, Visual, 3D Environment, Advanced Animation, Audio, Mobile UX, and Human Communication Standard

## ABSOLUTE DIRECTIVES FOR THE AI (READ FROM START TO END)

1. **YOU MUST READ THE ENTIRE DIVINE-ARGON FROM START TO END**: You are strictly forbidden to skip any part of this skill. Every time `divine-argon` is invoked, you MUST read all instructions from the first line to the last line so that no rule is left behind or forgotten.

2. **USE THE USER'S LANGUAGE**: This skill is written in English so everyone can use it, but you MUST reply in the same language the user wrote when they told you to use this skill. That applies to chat replies, explanations, and the visible copy inside the work (menus, labels, titles) unless the user or the project says otherwise. If the user writes in Indonesian, answer in Indonesian. If they write in Spanish, answer in Spanish. Match their formality too: use *gw/lu* only if the user uses *gw/lu*.

3. **INSTANT CONVERSATION STYLE CHANGE (NATURAL INFORMAL, FUN, NOT CRINGE, ONE MAIN EMOJI)**:
   - As soon as the `divine-argon` skill is active, your conversational style when chatting with the user MUST immediately become **natural, relaxed, and flowing like a real person talking to a friend (warm informal, not stiff or robotic, expressive but calm)**.
   - **It must be relaxed and fun but NOT cringe.** No stacked slang, no fake hype, no exclamation spam, no forced jokes, and not more casual than the user. See Part 9 for the full rules.
   - **Do not answer too briefly.** Reply like a real person who enjoys the topic: a little fuller than a one-liner (usually 3 to 6 sentences, up to two short paragraphs when you hand over a build), still direct, never padded or repetitive. Lead with the answer, then add some friendly color such as how it feels, one thing worth trying, or a small suggestion for what to do next.
   - **Use exactly one main emoji in every chat reply** (not zero, not a chain of them). Pick the one that fits the mood of that message and place it naturally, usually in the opening line or at the very end. No decorative symbols, arrows, hashtags, or emoji strings.
   - **STRICT SEPARATION**: This casual style and the single emoji apply **ONLY in the chat room with the user**! Inside the work you build (website, app, UI, game, poster, or visual), you are **STRICTLY FORBIDDEN** to put in emoji (still 100% manual SVG icons), and the copywriting inside the work must follow the professional or thematic context of that work.

4. **HIDE THE TECHNICAL SIDE / THE CODE FROM THE USER (UNLESS ASKED)**:
   - When you finish a game, website, or visual, **do not flood the user with technical code explanations** (do not show off variable names, matrix formulas, `InstancedMesh`, `PCFSoftShadowMap`, `cubic-bezier`, or lists of code functions) unless the user actually asks about the code or is clearly in a technical discussion. Just tell, in a relaxed and short way, what was built, how it feels to play or use, and which buttons or features they can try right away.

5. **ANTI-LAZINESS AND MULTI-PASS VERIFICATION**: You are strictly forbidden to work lazily. Before, during, and after making code, a website, a game, a 3D scene, or an AI image, you MUST run **layered verification several times (at least 3 internal check passes)** against every point of the Divine-Argon instructions. If even one Divine-Argon rule has not been applied or was missed, fix it first before handing the result to the user.

6. **ACCESS TO RESEARCH ARTICLES**: All 232 professional research article URLs with their summaries are listed directly at the very bottom of this `SKILL.md` file (Part 14). If you need deeper reference while working, read that article list directly.

7. **RESEARCH RULE**: Whenever an instruction in this skill, or the user, says "research", you MUST read or check at least 10 relevant articles or sources (from Part 14, or fresh ones from the web) before writing the code or asset. Never guess about a library, API, shader technique, or audio technique. If you are unsure halfway through, stop, look it up, then continue.

8. **NON-NEGOTIABLE LOCKS (NEVER SKIP, NEVER WEAKEN)**:
   - Mobile 3D web or game: pixel ratio **LOCKED at exactly 1.3**. Never 2.
   - **0% emoji inside the work**, manual SVG only. **Exactly one main emoji in every chat reply**.
   - Fonts come **ONLY from the Part 7 combo library**. Never invent a pair.
   - Main models **>= 5 parts**, every extra environment object **>= 3 parts**, **zero gaps or glitches**.
   - Extra environment objects **MUST be animated** and the scene **MUST have subtle ambient particles**.
   - **Never lower shadows, antialiasing, tone mapping, or model detail to gain speed.**

## When to Use This Skill

Automatically activate all Divine-Argon standards in these situations:

- Building websites, landing pages, dashboards, web apps, or UI/UX components (desktop and mobile).
- Building 2D and 3D games (desktop and mobile), layered 3D environments and backgrounds, 3D models, 3D shaders, PBR/IBL lighting, 3D/2D shadows, and interactive visuals based on Three.js, React Three Fiber (R3F), WebGL, or WebGPU.
- Adding audio to anything you build: sound effects, UI sounds, ambience, footsteps, and music.
- Building page layouts and design systems where visual hierarchy and font pairing matter.
- Making graphic designs, posters, or AI images (image generation / Nano Banana), with specific or non-specific prompts.
- Writing code systems more complex than basic syntax examples.
- Every conversation reply with the user, so it feels alive, connected, and human.

## Part 1: Dynamic Execution Engine and Multi-Pass Verification

For every real project, run the Spec-Driven, Chain-of-Verification (CoVe), and Multi-Pass Audit workflow directly in one execution pass:

1. **Contextual Specification Elevation (Dynamic Prompt Elevation)**:
   - Never process a raw prompt shallowly. In your internal thinking process, raise the sharpness of the concept, component architecture, mobile responsive layout, 3D environment depth, lighting, shadows, 2D component shapes, mood-based color palette, and advanced animation choreography.
   - The quality elevation MUST come as much cleaner code, mature mechanics, and precise visuals, NOT as random decoration added outside the context.

2. **Deep Research Without Guessing (Zero Guessing and CoVe)**:
   - Before writing code that involves a library, API, shader, or complex technique, verify its correctness first.
   - If you run into something uncertain midway, you are strictly forbidden to guess or make things up. Stop assuming, search or verify the documentation, and use a valid method.

3. **Mandatory Multi-Pass Verification Protocol (Anti-Laziness)**:
   - **Verification Pass 1 (Architecture, Mobile Viewport, 3D Environment, and Pixel Ratio Audit)**: Check whether the display on a phone screen (`360px-430px`) is truly roomy and not cramped, whether the layout structure is flush-left (if the prompt is not specific), whether the main 3D model has >= 5 sub-objects with no gaps or glitches, whether every extra environment object (obstacles, props, background pieces) is a multi-part model with >= 3 sub-parts, whether the 3D environment has 3 depth layers (Foreground, Midground, Background) + non-flat terrain contours, whether gameplay buttons are <= 4, and whether the pixel ratio follows Part 2 (locked at 1.3 for mobile 3D web and games, never 2).
   - **Verification Pass 2 (Dynamic 2D Shape, Anti-Orange Mood Color, Contextual Font, Shadow, and Audio Audit)**: Check whether 2D components have contextual shape variety (not all squircle boxes), whether colors are chosen dynamically by mood (not trapped in the orange/amber habit and with no forced gradients), whether the font is chosen contextually from the ready-made combo library in Part 7, whether there is no emoji inside the UI/game (manual SVG is mandatory), whether 2D and 3D shadows are soft and slop-free, whether the layout follows the hierarchy rules of Part 13 and the typography uses a ready-made combo from the Part 7 library, whether ambient 3D particles are subtle and budgeted (Part 2), and whether any audio follows Part 12 (layered, enveloped, varied, mixed, not a bare oscillator beep).
   - **Verification Pass 3 (Advanced Animation, Real Execution, and Chat Style Audit)**: Check whether 2D and 3D animation applies the advanced techniques (origin-aware, anticipation, follow-through/overlap, squash and stretch, secondary motion, camera feel), whether the extra environment objects are alive (wind sway, drifting clouds, flicker, water motion), whether the code is bug-free, and whether the chat reply is relaxed, fun, not cringe, a little fuller than a one-liner, carries exactly one main emoji, and does not show off technical code terms.

## Part 2: Three.js Architecture, Anti-Flat 3D Environment, and Professional Living Characters

Every 3D scene or 3D game creation MUST meet the following measurable standards:

1. **Model Complexity (>= 5 Objects) and Zero Breaks/Glitches**:
   - Every main 3D model MUST be assembled from **at least 5 objects/sub-meshes or more** (nested `THREE.Group` with correct pivots) so the model has depth of form and is never flat like 1 raw box or sphere.
   - **No Glitches or Gaps Allowed**: Never leave a 3D model disconnected, cut off, floating, or with holes after it is built. Every part of the model MUST connect perfectly with the part next to it (example: if a door is mounted on a building, the space next to it must not be empty but must be a wall that joins it). Re-check all joint coordinates after building the model.

2. **Non-Flat 3D Environment and Background Design (3-Plane Spatial Depth)**:
   When making a 3D game or 3D scene, you are **strictly forbidden** to just place 1 plain flat floor plane (plain `PlaneGeometry`) in the middle of empty space! Build a living 3D environment with 3 spatial layers:
   - **Foreground (Near Area and Playable Zone)**: Ground surface with elevation/texture variation (sidewalk, rocky road, short grass, water edge, boundary fences, or signs) where the character interacts.
   - **Midground (Supporting Structures and Framing)**: Buildings with dimension, multi-segment trees, rolling hills (use *Simplex/Perlin noise vertex displacement* on a segmented `PlaneGeometry`), bridges, or cliffs that frame the play area.
   - **Background and Horizon (Vista and Sky)**: Distant mountain silhouettes, city *skyline*, low-poly/volumetric clouds, or a procedural `Sky` dome, combined with a thin `THREE.FogExp2(fogColor, density)` where `fogColor` blends exactly with the horizon sky color.
   - Use `THREE.InstancedMesh` to scatter environment props with seed-based scale and rotation variation so the world looks rich with 1 *draw call* per prop type. Every prop must still be a real multi-part model (see item 5), not a single primitive.

3. **Living Characters (Human or Animal)**:
   If the user does not specify a particular face style, choose one of these two face methods according to the project context:
   - **Manual 2D SVG Face**: Drawn manually in SVG and then mapped/textured onto the face part of the 3D model (suitable for stylized, low-mid poly, or cel-shaded styles).
   - **Real 3D Face with Depth**: Assembled from real 3D geometry that has spatial depth (eye sockets, 3D eyeballs, protruding nose bridge/muzzle, jaw/mouth, brows, and dimensional ears) for contexts that need full 3D depth of form.

4. **Pixel Ratio, Performance, Particles, and Textures**:
   - **3D WEB OR 3D GAME ON MOBILE: LOCK THE PIXEL RATIO TO EXACTLY 1.3.** Do not read `window.devicePixelRatio` on mobile, do not clamp it lower or higher, and do not add any adaptive step that changes it at runtime. Always 1.3.
   - **Desktop 3D:** keep the pixel ratio between 1.0 and 1.6, never 2 or higher anywhere (at 2 the game starts to lag).
     ```js
     const isMobile = /Android|iPhone|iPad|iPod/i.test(navigator.userAgent) ||
       (navigator.maxTouchPoints > 1 && matchMedia('(pointer: coarse)').matches);
     const DPR = isMobile ? 1.3 : Math.min(Math.max(window.devicePixelRatio || 1, 1), 1.6);
     function resize() {
       renderer.setPixelRatio(DPR);          // re-apply on every resize so browser zoom cannot change it
       renderer.setSize(innerWidth, innerHeight);
       camera.aspect = innerWidth / innerHeight;
       camera.updateProjectionMatrix();
     }
     ```
   - Keep the *draw calls* budget under 100 per frame on mobile (<300 on desktop). Use *Object Pooling* for entities that often appear and disappear.
   - Never gain performance by lowering shadow quality, antialiasing, tone mapping, model part count, environment layers, or the lighting rig. Get it from instancing, merging static props, pooling, culling, and fewer draw calls.
   - Do not use too many small noisy circle particles, and do not remove textures on components that need them, just reduce their intensity a little so it is not excessive (except for realistic games).
   - Always provide memory cleanup (`dispose()`) for geometry, material, and texture.

5. **Extra Environment Objects Must Be Real Models, Not Single Primitives (obstacles, props, background pieces)**:
   - Everything added to the world besides the main character and main model (obstacles, rocks, trees, fences, crates, signs, lamps, buildings, bridges, background landmarks) MUST be built like a main 3D model but a little lighter: **at least 3 sub-parts** (the main model keeps its minimum of 5). **You are STRICTLY FORBIDDEN to use a single primitive (one box, cone, sphere, or icosahedron) as an obstacle, tree, rock, or background piece!** A rock is not one icosahedron and a tree is not one cone on one cylinder.
   - Use the **four asset tiers**: **Hero** (the few focal set pieces and gameplay-critical obstacles: 5 or more parts, the most detail), **Unique** (notable pieces that catch the eye: 4 or more parts), **Modular** (structure pieces such as walls, fences, platforms, built from a kit that snaps together: 3 or more parts each), **Dressing** (small props that fill space and add life: 3 or more parts when close to the player, cheap and instanced). Rough budget: about 5% hero, 15% unique, 50% modular, 30% dressing.
   - Give every piece real construction: base or footing, body, a cap or trim, and one or two small details (a rope, a lantern, moss patch, plank, crack, flag). Use chamfered or bevel-like edges (small segment counts are fine), a slightly irregular silhouette, and stylized proportions that match the world.
   - **Anti-copy-paste variation:** each instance gets random seeded scale (about 0.85 to 1.2), rotation, slight color jitter (hue or lightness within about 3% to 6%), and different sub-part variants. Never place props in straight lines or even spacing. Cluster them in natural groups of 3, 5, or 7 with a few strays, and sink the base slightly into the terrain with a contact shadow so nothing floats.
   - Keep the value hierarchy: hero and gameplay objects have the strongest contrast against their surroundings, midground pieces medium, far background pieces lower contrast and slightly desaturated and bluish (atmospheric perspective), so the player's eye goes to what matters.
   - No gaps, no floating parts, no holes, same as the main model. Recheck every joint. Use `InstancedMesh` per sub-part (or merged static geometry) so draw calls stay inside the budget, and use a simpler LOD for far pieces without removing their silhouette.

6. **Ambient 3D Particles for the Environment (nice, alive, never over)**:
   - **EVERY 3D scene or 3D game MUST include at least one subtle ambient particle system that fits its mood, and it MUST NEVER be excessive.**
   - **Purpose first.** Particles sell place, material, and time of day. Choose by context: fireflies or pollen for forest and meadow, dust motes in light shafts and ruins, embers and sparks near fire, leaves or petals under trees, mist or low ground fog near water and swamps, snow or rain for cold or storm scenes, sand dust for desert, bubbles or ripples for water, glowing motes for magic. Use **one primary particle type and at most one secondary type** per area. If you cannot say what a particle adds, delete it.
   - **Restraint (less is more).** If the player notices individual particles, there are too many. If the screen looks noisy or the obstacles are harder to read, cut the count by 30% to 50%. Do not raise the count to compensate for particles that are too small or too faint; fix size and opacity instead.
   - **Starting budgets (all ambient systems combined, visible at once):** about 80 to 200 on mobile and about 200 to 500 on desktop. Fireflies 20 to 50, dust or pollen 40 to 120, leaves or petals 15 to 60 as instanced meshes, embers 20 to 60 per fire. Go lower first, then add.
   - **Implementation (cheap and GPU-driven):** use `THREE.Points` with a small custom `ShaderMaterial` (per-particle `aPhase`, `aSize`, `aSpeed` attributes, motion computed in the vertex shader from `uTime`, so there is no per-particle CPU loop), one draw call per system, `transparent: true`, `depthWrite: false`, soft round alpha from `gl_PointCoord` (no hard squares), size attenuation with distance, and `uPixelRatio = renderer.getPixelRatio()` so size stays right at the locked pixel ratio. Use additive blending only for emissive things (fireflies, embers, magic); use normal blending with low alpha for dust, pollen, mist, and snow. Leaves and petals use a tiny two-triangle `InstancedMesh` with spin, wind drift, lifespan, and fade.
   - **Fixed cost, no spawning storms:** keep particles inside a box or cylinder around the camera or player and wrap them when they leave (recycle, do not create and destroy). Fade alpha near the box edges and near the camera so nothing pops in or blocks the lens.
   - **Look:** small and soft (world size about 0.03 to 0.12 for fireflies and dust), opacity about 0.15 to 0.6, colors from the world's analogous mood palette, clustered where it makes sense (more near lights, water, trees and ruins, fewer in open areas) and spread across height, not on a flat layer. Particles never cover the character, hazards, or the HUD. Keep them out of the focal point's face.
   - **Organic motion:** every particle gets its own phase and speed; combine two or three slow sine or noise layers; drift in the same wind direction as the vegetation; fireflies wander and pulse with random 0.4 to 1.5 second blinks; dust moves slowly with slight parallax; embers rise, wobble, shrink, and fade out. Never let all particles move or blink in sync.
   - **STRICTLY FORBIDDEN:** run per-particle physics on the CPU, add a light per particle, use collisions, stack large overlapping transparent quads (overdraw), or keep updating particles when the tab is hidden. Call `dispose()` on geometry and material when removing a system.

7. **Environment Animation: Every Extra Object Feels Alive**:
   - **Every extra environment object MUST have at least one cheap, fitting ambient motion. You are STRICTLY FORBIDDEN to leave decorative environment objects completely static (nothing in the world is a statue unless it is supposed to be one).** Keep motion subtle, shader-driven, and never synchronized.
   - **Vegetation (trees, bushes, grass, reeds):** wind sway in the vertex shader (use `onBeforeCompile` on the standard material or a small `ShaderMaterial`, so instancing and shadows keep working). Weight it by height so the base stays rooted and the top moves most (`weight = pow(height01, 2.0)`), use the world or instance position as the phase so neighbors never move in unison, combine a slow main bend with a faster small flutter on leaves, and add gusts by modulating strength with a low-frequency sine or noise of position and time. Trunks bend a little, branches and leaves more. Use one shared wind direction and strength uniform for the whole scene.
   - **Banners, flags, cloth, ropes, hanging signs:** sine wave along the length with amplitude growing away from the anchor, plus a damped pendulum swing for signs and lanterns that gets a small kick during gusts.
   - **Water:** scrolling UV or normal movement plus tiny vertex waves, soft shoreline foam or ripples where objects touch the water, and occasional ripple rings.
   - **Sky and background:** clouds drift at different speeds per layer and wrap around, distant birds or flocks cross rarely, far lights twinkle, sun rays or fog breathe slowly.
   - **Fire and light sources (torches, lanterns, campfires, windows):** flicker with layered noise (about +/-10% to 15% on intensity and a little on position), glow sprites or emissive materials instead of many real lights on mobile (at most 1 to 3 real point lights near the player).
   - **Machines and props with function:** windmills, fans, gears, and wheels rotate at believable speeds; doors, gates, and chains can sway; floating or magic objects bob slowly (`y += sin(t) * 0.05` with random phase).
   - **Critters and micro-events (optional, few):** a few instanced butterflies, birds, or fish following looping curved paths; random micro-events every 10 to 30 seconds (a bird takes off, a gust of leaves, a ripple, a distant glow) so the world is not a perfect loop.
   - **Reactive touch:** obstacles, bushes, and grass near the player can react (grass bends away from the player, a bush shakes when touched, a crate wobbles on hit) using a small uniform array for the player position or a short timed impulse. Moving hazards must telegraph before they act.
   - **Performance rules:** do the animation in shaders and on shared uniforms (`uTime`, `uWind`), not with a JavaScript loop over hundreds of objects; skip or simplify updates beyond a set distance and when out of frustum; keep amplitudes small; respect `prefers-reduced-motion` by lowering amplitude; time everything with the frame delta and clock, never frame counts.
   - Tie the animation together: the same wind drives vegetation, cloth, particles, clouds, and (if audio exists) the wind ambience in Part 12.

## Part 3: 3D Shaders, Balanced Lighting (Not Flat and Not Over), and Anti-Slop 3D Shadows

1. **Balanced 3D Lighting (Key-to-Fill Ratio `2.5 : 1` to `3.5 : 1`)**:
   - Avoid high white `AmbientLight` that makes the scene look flat, and avoid stacking lights or extreme bloom that makes the screen glare (*overexposed*).
   - **Key Light (`DirectionalLight`)**: Intensity `1.1` to `1.4`, incoming angle `35°-45°` horizontal and `40°-55°` vertical, color temperature matching the world mood.
   - **Sky/Ground Fill (`HemisphereLight`)**: Intensity `0.35` to `0.50`, soft bright upper sky color and a cooler ground bounce color as a replacement for plain `AmbientLight`, so the underside of 3D models has *natural ground occlusion*.
   - **Counter Fill / Rim Light**: Intensity `0.4` to `0.6` from the opposite direction plus a thin *Schlick Fresnel* calculation (`pow(1.0 - max(dot(N, V), 0.0), 5.0)`) inside the shader to separate object silhouettes from the background.
   - Lock `renderer.outputColorSpace = THREE.SRGBColorSpace` and `renderer.toneMapping = THREE.ACESFilmicToneMapping` (`toneMappingExposure = 1.0`).

2. **Realistic PBR Materials**:
   - Use the sRGB albedo color range `30-240` (no pure black `#000` or pure white `#fff`).
   - Vary `roughness` values between object parts (for example ground `0.85`, cloth/wood `0.65`, painted body `0.35`, metal/glass `0.15`) so light reflections feel alive and do not look like uniform plastic.

3. **Sharp, Soft, and Non-Slop 3D Shadow Techniques**:
   - Enable `renderer.shadowMap.enabled = true; renderer.shadowMap.type = THREE.PCFSoftShadowMap;`.
   - **Tighten the Shadow Camera Frustum**: Adjust `left, right, top, bottom` on `DirectionalLight.shadow.camera` to wrap exactly around the active play area (for example `-15` to `15` or following the player position) with `shadow.mapSize.set(2048, 2048)` (use 2048 on mobile too, the tight frustum keeps it cheap). A tight frustum is the main key to keeping shadows from looking blocky (*boxy/pixelated*).
   - **Bias Calibration**: Set `light.shadow.normalBias = 0.02` and `light.shadow.bias = -0.0005` so there are no stripe artifacts (*shadow acne*) and no floating shadows (*peter panning*).
   - Make sure floor shadows keep natural color transparency from the `HemisphereLight` (not dead pitch black) and add a *contact shadow* under the character's footing point.

## Part 4: Dynamic Mood-Based Color Selection (Anti-Orange Bias and Anti-Forced Gradient)

1. **STRICT BAN ON DEFAULT ORANGE / AMBER COLOR BIAS**:
   - AI models often get trapped repeatedly choosing **Orange / Amber (`#f97316`, `#ff6b00`, `#f59e0b`)** when told to make 2D components or game UI without color instructions. **STOP the habit of choosing orange as the default!**
   - You are **FORBIDDEN** to use orange/amber unless the user explicitly asks for it or the context is truly 100% about fire or desert.

2. **Dynamic Color Selection Matrix by Mood and Atmosphere (Choose Contextually)**:
   When the user does not specify colors, first analyze the **Mood / Atmosphere** of the game, website, or app being made, then choose an **Analogous palette (hue within $H \pm 15^\circ$ to $30^\circ$ in OKLCH color space)** from this atmosphere matrix:
   - **Calm, Nature, Exploration, Cozy, or Forest Adventure Mood**: Use the **Sage Emerald - Forest Pine - Soft Mint** harmony (`Hue 145°-170°`, warm organic cream background `#f4f6f3` or dark forest green `#0d1512`, accents `#10b981` / `#34d399`).
   - **Tactical, Clean Sci-Fi, Sky, Speed, or Productivity/SaaS Mood**: Use the **Cobalt Azure - Ice Slate - Deep Navy** harmony (`Hue 205°-235°`, surface `#0b101b` or `#f8fafc`, crystal blue accents `#3b82f6` / `#38bdf8`).
   - **Mysterious, Night Fantasy, Magic, Cosmic, or Stealth Mood**: Use the **Indigo Velvet - Amethyst Plum - Moonlight Lavender** harmony (`Hue 250°-280°`, surface `#0f0d18`, accents `#8b5cf6` / `#a78bfa`, not harsh neon purple).
   - **Competitive, Fast Action, Mecha, or Racing Mood**: Use the **Crimson Rose - Titanium Slate - Cool Silver** harmony (`Hue 345°-360°`, carbon surface `#111215`, sharp red accents `#e11d48` / `#f43f5e`).
   - **Luxury, Architecture, Editorial, Portfolio, or Minimalist Mood**: Use the **Monochrome Obsidian - Warm Stone - Champagne Alabaster** harmony (ink contrast `#141413` on warm paper `#f7f5f0` with muted bronze/gold accent `#a38f70`).
   - **Cheerful, Casual, Puzzle, or Educational Mood**: Use the **Sky Cerulean - Periwinkle - Soft Coral/Teal** harmony with soft high brightness that is gentle on the eyes.

3. **DO NOT ALWAYS USE GRADIENTS and Ban on Foreign Colors**:
   - **Do not always use gradients!** The gradient color theory has been removed. Prioritize clean, clearly hierarchical **solid (flat) surface colors**.
   - If a theme already has its own palette, never slip in random green or foreign colors that do not fit that palette.
   - Apply the **60-30-10** proportion (60% neutral surface/breathing space, 30% cards/secondary structure, 10% focal accent).

## Part 5: Dynamic 2D Component Shapes (Do Not Get Stuck on Squares/Squircles) and Anti-Slop 2D Shadows

1. **Exploring Dynamic and Contextual 2D Component Shapes (Beyond Basic Rectangles/Squircles)**:
   Do not make all cards, buttons, game HUDs, badges, and panels just uniform, boring `border-radius: 12px` (squircle) boxes! Adjust the **Shape Language** of 2D components to the project context:
   - **Pill and Capsule (`border-radius: 9999px`)**: Use for floating navbars, filter chips, status bars, modern action buttons, and flowing life/energy indicators.
   - **Chamfered / Cut-Corner Polygons (`clip-path: polygon(...)`)**: For action, sci-fi, racing, mecha, or sports games, use slanted cut corners (*chamfered corners*) on HUD panels, health bars, and buttons! Example:
     `clip-path: polygon(12px 0, 100% 0, 100% calc(100% - 12px), calc(100% - 12px) 100%, 0 100%, 0 12px);`
   - **Slanted / Skewed Bars and Ribbons**: For health bars, stamina meters, speedometers, or level badges in games, use parallel slants (`clip-path: polygon(6% 0, 100% 0, 94% 100%, 0 100%)` or `transform: skewX(-10deg)` with the text inside returned to `skewX(10deg)`).
   - **Asymmetric Corner Radius**: Use a combination of different radii on the four corners to give unique visual direction (for example `border-radius: 24px 6px 24px 6px` or `border-radius: 20px 20px 20px 4px` for dialogue bubbles/character cards).
   - **Hexagonal, Diamond, and Circular Radial Nodes**: For skill trees, item slots, minimap frames, mobile action buttons, or compasses, use pure circles, hexagons (`clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%)`), or diamonds.
   - **Inverted Border Radius / Notched Cards and SVG Masks**: Use *tabbed headers*, concave curve cuts (*scoop/notch*), or `mask-image: radial-gradient(...)` to smoothly blend minimap/panel edges into the screen.
   - *Important Note*: If using a `clip-path` that cuts off the standard `box-shadow`, wrap the element with `<div class="shape-wrapper">` given `filter: drop-shadow(...)` so the shadow follows the polygon shape precisely!

2. **Teaching How to Make Good, Natural, Not Over/Slop 2D Component Shadows**:
   - **Ban on Excessive Glow**: Never use *glow* or *shine* effects as a habit on ordinary components (if needed contextually, opacity MUST be `< 0.12`).
   - **Multi-Layer Color-Matched Shadow + Negative Spread**: Combine 2-3 thin shadow layers (Umbra + Penumbra) with negative `spread-radius` (`-1px` to `-4px`) and a shadow color that follows the background hue, with total opacity under `0.20` (transparency >= 80%):
     - **Elevation 1 (Subtle)**: `box-shadow: 0 1px 2px 0 rgba(15, 23, 42, 0.04), 0 2px 6px -1px rgba(15, 23, 42, 0.06);`
     - **Elevation 2 (Raised/Hover)**: `box-shadow: 0 2px 4px -1px rgba(15, 23, 42, 0.05), 0 6px 16px -3px rgba(15, 23, 42, 0.08), 0 12px 24px -4px rgba(15, 23, 42, 0.04);`
     - **Elevation 3 (Floating Modal)**: `box-shadow: 0 4px 8px -2px rgba(15, 23, 42, 0.06), 0 12px 28px -4px rgba(15, 23, 42, 0.10), 0 24px 48px -8px rgba(15, 23, 42, 0.08);`

3. **Flush-Left Layout and Mandatory Manual SVG**:
   - If the user does not request a specific alignment, make the entire page structure, hero, and main menu **flush-left**, while the content inside small buttons/badges stays **optically centered**.
   - **Strictly forbidden to use emoji inside a website, app, or game**; draw **contextual manual SVG** for every icon.

## Part 6: Phone Screen Design (Mobile-First Ergonomics) and Anti-Cramped Button Rules

Most users open websites and play games directly from a phone screen (`width: 360px - 430px`). You MUST prevent UI/UX that is cramped, stacked, or covers the screen on mobile devices with these measurable rules:

1. **Mobile Screen Space Budget (Maximum 15-20% HUD Occupancy)**:
   - On phone screens, all UI/HUD elements floating above a game or visual **MUST NOT cover more than 15% to 20% of the total screen area**! At least **80% of the middle of the screen must stay clean** so players can see the game world and their character comfortably.
   - Use the modern viewport unit **`100dvh`** (*dynamic viewport height*, not the regular `100vh` that often gets cut off by the mobile browser address bar) and respect screen safe areas (`padding: env(safe-area-inset-top) env(safe-area-inset-right) env(safe-area-inset-bottom) env(safe-area-inset-left)`).

2. **Compact Scale and Fluid Sizing on Mobile (`clamp()`)**:
   - Never use raw desktop padding, font, or panel sizes (`width: 400px`, `padding: 32px`, `font-size: 48px`) on phone screens!
   - Use `clamp()` for all sizes:
     - Menu title on phones: `font-size: clamp(1.5rem, 5vw, 2.75rem)`
     - HUD text / labels on phones: `font-size: clamp(0.75rem, 2.5vw, 0.9rem)`
     - Card / panel padding on phones: `padding: clamp(10px, 3vw, 20px)`
   - On screens `< 640px`, turn horizontal card rows into **1 slim vertical column** or a clean **horizontal swipe carousel**, hide long secondary description text, and compress the score/status panel into thin *compact pills/badges* in the top corner.

3. **Main Menu Rules, Gameplay Buttons, and Mobile Thumb Ergonomics**:
   - All games MUST have a **roomy, flush-left, comfortable, and uncramped Main Menu** on both phone and desktop.
   - **Event-Based Disclosure**: Gameplay buttons only appear after the user presses the start button in the Main Menu.
   - While gameplay is running, **at most only 4 buttons may be always visible (always-visible)**. Contextual event-based buttons are not counted in this limit of 4.
   - **Remove Junk Buttons**: Forbidden to put camera buttons or sound setting buttons inside the gameplay screen (sound settings may only be in the Main Menu).
   - **Mobile Controller Position, Anti-Collision with Navbar**: On phone screens, **never place the joystick or action buttons stuck to the very bottom edge of the screen**, because they will collide with the mobile browser's gesture bar / navigation bar. Shift the position up a little toward the lower-middle (`bottom: clamp(48px, 10dvh, 84px)`), make the size right for thumbs (`48px-64px`), and use **50% transparency (`opacity: 0.5`)**.
   - **Ban on Technical Info**: Never show FPS, coordinates, or technical logs on the game/website screen.

## Part 7: Dynamic Typography System (Ready-Made Font Combos, No Inventing Your Own Pairs)

**YOU ARE STRICTLY FORBIDDEN TO INVENT YOUR OWN FONT PAIR!** Read the project's context, genre, and mood, then pick **one ready-made combo from the Font Combo Library below** (heading font + body font) and use it consistently. You MUST use that combo consistently. Only mix in a third font if it is a monospace for code or numbers. If the user names specific fonts, follow the user. **The recommended font list is expandable:** new fonts and new combos can be added to the library over time, and every font in the library counts as an official Divine-Argon font.

### Typography rules that go with every combo
- **Maximum 2 font families** (plus an optional monospace). One family owns headings, the other owns body. Decide who owns which level and keep it.
- **Contrast with harmony:** pair fonts that differ clearly in structure, weight, or width (for example a display serif with a neutral sans, or a geometric sans with a humanist sans), never two near-identical fonts. Squint at the page: if headings and body blur into one blob, increase the contrast. Do not pair two loud display fonts.
- **Type scale:** base body 16px (17px to 18px on desktop reading layouts), scale ratio about 1.2 on mobile and 1.25 on desktop (`clamp()` for headings). Line-height about 1.5 to 1.65 for body and 1.1 to 1.25 for headings. Heading tracking about -0.01em to -0.02em, small uppercase labels +0.05em to +0.08em.
- **Hierarchy through four axes:** size, weight, color (contrast), and style. Use weight contrast of at least 300 between heading and body (for example 700 vs 400). Lock sizes for H1, H2, body, and captions and reuse them everywhere.
- **Readability:** 45 to 75 characters per line, tabular numbers for stats and scores, no long paragraphs in all caps, do not use thin weights under 400 for small text.
- Always give every font a real fallback stack (for example `'Inter', system-ui, -apple-system, 'Segoe UI', sans-serif`).

### Font Combo Library (heading + body, with CDN links)
1. **Tech, SaaS, AI tools, developer UI:** Geist + Geist Mono for data.
   `<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400..700&family=Geist+Mono:wght@400..600&display=swap" rel="stylesheet">`
2. **Sci-fi, action, modern games, creative brands:** Space Grotesk (headings) + Inter (body).
   `<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400..700&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
3. **Futuristic HUD, cyber, mecha:** Orbitron (headings and big numbers) + Exo 2 (body).
   `<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400..800&family=Exo+2:wght@400..700&display=swap" rel="stylesheet">`
4. **Editorial, portfolio, modern luxury:** Instrument Serif (headings) + Inter (body).
   `<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
5. **Luxury, architecture, premium brands:** Playfair Display (headings) + Source Sans 3 (body).
   `<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400..800&family=Source+Sans+3:wght@400..700&display=swap" rel="stylesheet">`
6. **Fantasy RPG, medieval, ancient worlds:** Cinzel (headings) + Lora (body).
   `<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400..800&family=Lora:wght@400..700&display=swap" rel="stylesheet">`
7. **Elegant fantasy, romance, boutique:** Cormorant Garamond (headings) + Manrope (body).
   `<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400..700&family=Manrope:wght@400..700&display=swap" rel="stylesheet">`
8. **Fintech, dashboards, analytics, web3:** Sora (headings) + DM Sans (body).
   `<link href="https://fonts.googleapis.com/css2?family=Sora:wght@400..700&family=DM+Sans:wght@400..700&display=swap" rel="stylesheet">`
9. **Mobile apps, consumer products, onboarding:** Plus Jakarta Sans (headings) + Inter (body).
   `<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400..800&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
10. **Cozy, lifestyle, food, wellness, nature games:** Fraunces (headings) + Nunito Sans (body).
    `<link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400..800&family=Nunito+Sans:wght@400..700&display=swap" rel="stylesheet">`
11. **Kids, education, casual and cheerful games:** Baloo 2 (headings) + Nunito (body).
    `<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400..800&family=Nunito:wght@400..700&display=swap" rel="stylesheet">`
12. **Playful brands, creative agencies, quirky products:** Bricolage Grotesque (headings) + DM Sans (body).
    `<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@400..800&family=DM+Sans:wght@400..700&display=swap" rel="stylesheet">`
13. **Bold creative studios, music, art, event pages:** Syne (headings) + Inter (body).
    `<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400..800&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
14. **Sports, racing, posters, big impact headlines:** Bebas Neue (headings) + Inter (body).
    `<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
15. **Action headlines, news, tactical, military:** Oswald (headings) + Source Sans 3 (body).
    `<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400..700&family=Source+Sans+3:wght@400..700&display=swap" rel="stylesheet">`
16. **Developer tools, docs, terminals, hacker themes:** JetBrains Mono (headings and code) + Inter (body).
    `<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400..700&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
17. **Retro and pixel games:** Pixelify Sans (headings and HUD) + Silkscreen (small labels only, keep body copy in Pixelify Sans regular). Minecraft or Mojangles style requests: use the font the user supplies, otherwise Pixelify Sans.
    `<link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400..700&family=Silkscreen:wght@400;700&display=swap" rel="stylesheet">`
18. **Long reading, blogs, magazines, documentation:** Newsreader (headings) + Inter (body).
    `<link href="https://fonts.googleapis.com/css2?family=Newsreader:wght@400..700&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
19. **Crypto, futuristic bold, tech launches:** Unbounded (headings) + Inter (body).
    `<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@400..800&family=Inter:wght@400..700&display=swap" rel="stylesheet">`
20. **Warm editorial, retail, food and lifestyle brands:** DM Serif Display (headings) + DM Sans (body).
    `<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=DM+Sans:wght@400..700&display=swap" rel="stylesheet">`

**How to choose:** match the combo to the mood and genre of the project (the same way you choose the color palette), then use it consistently across the whole project. If two combos fit, take the one with the higher contrast between heading and body. Fonts used inside a 3D scene (canvas text, textures) must be loaded before use (`document.fonts.load(...)`).

### The 20 official single fonts and CDN links (also valid for custom pairings requested by the user):
1. **Geist**: `<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600;700&display=swap" rel="stylesheet">`
2. **Inter**: `<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">`
3. **Plus Jakarta Sans**: `<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">`
4. **DM Sans**: `<link href="https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,400..700;1,9..40,400..700&display=swap" rel="stylesheet">`
5. **Satoshi**: `<link href="https://api.fontshare.com/v2/css?f[]=satoshi@400,500,700&display=swap" rel="stylesheet">`
6. **General Sans**: `<link href="https://api.fontshare.com/v2/css?f[]=general-sans@400,500,600,700&display=swap" rel="stylesheet">`
7. **Instrument Sans**: `<link href="https://fonts.googleapis.com/css2?family=Instrument+Sans:ital,wdth,wght@0,75..100,400..700;1,75..100,400..700&display=swap" rel="stylesheet">`
8. **Space Grotesk**: `<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">`
9. **Manrope**: `<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&display=swap" rel="stylesheet">`
10. **Mona Sans**: `<link href="https://fonts.googleapis.com/css2?family=Mona+Sans:ital,wdth,wght@0,75..125,400..700;1,75..125,400..700&display=swap" rel="stylesheet">`
11. **Onest**: `<link href="https://fonts.googleapis.com/css2?family=Onest:wght@400;500;600;700&display=swap" rel="stylesheet">`
12. **Outfit**: `<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700&display=swap" rel="stylesheet">`
13. **Figtree**: `<link href="https://fonts.googleapis.com/css2?family=Figtree:wght@400;500;600;700&display=swap" rel="stylesheet">`
14. **Switzer**: `<link href="https://api.fontshare.com/v2/css?f[]=switzer@400,500,600,700&display=swap" rel="stylesheet">`
15. **Instrument Serif**: `<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&display=swap" rel="stylesheet">`
16. **Playfair Display**: `<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet">`
17. **Cormorant Garamond**: `<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&display=swap" rel="stylesheet">`
18. **Newsreader**: `<link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,400..600;1,6..72,400..600&display=swap" rel="stylesheet">`
19. **Fraunces**: `<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400..700;1,9..144,400..700&display=swap" rel="stylesheet">`
20. **Geist Mono**: `<link href="https://fonts.googleapis.com/css2?family=Geist+Mono:wght@400;500;600&display=swap" rel="stylesheet">`

## Part 8: Advanced Animation Teaching (Advanced 2D UI Choreography and 3D Procedural Animation)

Leave behind stiff basic animation (just a plain `fade-in` or simple sine rotation). Apply the **Advanced Motion Engineering** system for 2D components and the 3D world:

### A. Advanced 2D Component Animation (Advanced 2D UI Motion)
1. **Multi-Property Contextual Intro and Unfolding Choreography**:
   - Every 2D component MUST have an intro animation that combines several composite properties at once: **Spatial Translation + Scale + Blur-Deconvolution (`filter: blur(8px) -> blur(0px)`) or Clip-Path Reveal** with `animation-fill-mode: both` and *staggered delay* (`calc(var(--i) * 55ms)`).
2. **Origin-Aware and Interruptible Transitions (Emil Kowalski's Philosophy)**:
   - Do not let menus, popovers, or modals appear from the middle of empty space (`transform-origin: center`). Lock `transform-origin` exactly on its trigger point (for example `top left`, `bottom right`, or the position of the clicked button) and start from `scale(0.92)` toward `scale(1)` (do not start from `scale(0)` because it looks unnatural).
   - Use `transition` (not stiff `@keyframes`) for all interactive states so the animation **can be interrupted midway (interruptible retargeting)** without jumping roughly if the user clicks/hovers quickly.
3. **Shared Layout / Active Indicator Morphing (FLIP Concept)**:
   - For an active tab, menu category, or selection indicator, animate the movement of the marker box (*active pill indicator*) gliding smoothly from the old item to the new item using the spring curve `cubic-bezier(0.22, 1, 0.36, 1)` or `cubic-bezier(0.34, 1.56, 0.64, 1)`.
4. **Interactive Pointer Parallax, Magnetic Pull, and Animated Counters**:
   - On the main CTA button or featured card (only for devices with a mouse pointer), add a slight *magnetic pull* / thin 3D perspective tilt when the cursor gets close.
   - On button press (both desktop and mobile touch), apply **Anticipation and Rebound**: when pressed (`:active` / `pointerdown`) quickly shrink to `scale(0.95)` in `60ms`, and when released bounce gently back to `scale(1.0)` with a spring curve.
   - When a score, coin, HP, or stat number changes, **do not instantly replace the number text**; animate the number calculation (*number ticker / rolling counter*) accompanied by a *micro-pulse* on its container.
5. Respect `prefers-reduced-motion`, and animate only `transform`, `opacity`, and `filter` wherever possible.

### B. Advanced 3D Character and World Animation (Advanced 3D Procedural Animation and Game Feel)
Every living character MUST have 4 basic animation categories (`Idle`, `Walk`, `Interact`, `Run`), but **it is strictly forbidden to move legs/arms with a single stiff `Math.sin(t)` wave like a wooden robot!** Apply these 6 professional 3D animation techniques:

1. **Multi-Joint Phase-Offset Kinematics (Phased Joint Chain)**:
   - Separate movement between joints: Shoulder/Hip $\rightarrow$ Upper Arm/Thigh $\rightarrow$ Forearm/Calf $\rightarrow$ Hand/Foot.
   - Give a **phase shift (phase lag $\phi \approx 0.4 - 0.7\text{ rad}$)** to the child joint relative to its parent joint:
     `thigh.rotation.x = Math.sin(t) * A; calf.rotation.x = Math.max(0, Math.sin(t - 0.6)) * B;`
     This way, the knee only bends backward when the leg is lifted to step, not bending backward like a flamingo!
2. **Center-of-Mass (Pelvis) Bobbing, Lateral Sway, and Speed Lean**:
   - During `Walk` and `Run`, the middle body (*pelvis/torso*) MUST move up and down at **2 times the step frequency** (`Math.abs(Math.sin(t))` or `Math.cos(t * 2)`), accompanied by left-right shoulder sway (*contra-lateral twist*: when the left leg goes forward, the right shoulder goes forward) and a **forward body tilt (forward pitch lean)** proportional to running speed as well as a sideways tilt (*banking/roll*) when turning!
3. **Anticipation, Squash and Stretch (Volume Preservation), and Follow-Through**:
   - **Anticipation**: Before the character jumps, attacks, or does `Interact`, make a short wind-up motion (for example crouching slightly `y -= 0.12` for `80ms` before shooting up).
   - **Squash and Stretch**: When jumping into the air, stretch the vertical scale and slightly shrink the horizontal scale (`scale.set(0.88, 1.18, 0.88)`). When landing on the ground, flatten briefly (`scale.set(1.16, 0.82, 1.16)`) then return to `(1, 1, 1)` using *damped spring* interpolation so the object's volume stays preserved.
   - **Overlapping Action and Secondary Motion**: Secondary body parts (ears, tail, hair, cape, bag, weapon, or antenna) MUST move with **delayed inertia (spring-damper lag)** following the main body's acceleration, so they keep swaying briefly after the character stops suddenly (*follow-through*).
4. **Organic Idle (Layered Breathing + Micro-Saccades / Look-At)**:
   - In the `Idle` state, combine gentle chest expansion (*breathing cycle*), periodic eye blinks (random interval 2.5-5 seconds), and a slight head/eye rotation that smoothly turns following the camera direction or interesting objects nearby (*procedural look-at target*).
5. **Smooth State Blending (Cross-Fading Between Animations)**:
   - Never change pose from `Idle` to `Walk` or `Run` abruptly/instantly! Use a transition weight (`blendWeight = THREE.MathUtils.damp(blendWeight, targetWeight, 10, dt)`) to mix (*lerp*) joint rotations smoothly over `120ms-200ms`.
6. **Game Feel ("Juice"): Camera Trauma Shake, Hit-Stop, and Dynamic FOV**:
   - When a hard collision, a hit landing (*impact*), or an explosion happens, add **Hit-Stop** (a micro pause of 35-65ms on the colliding objects to give the hit weight) and **Camera Trauma Shake** based on exponential *decay* (`shakeOffset = trauma * trauma * noise`) that subsides smoothly right away.
   - When the character runs fast (`Run` / *sprint* / *boost*), smoothly widen `camera.fov` a little (`+4°` to `+7°`) with *spring damping* to give a real sense of speed.
   - Pair every important impact with a matching sound (Part 12).

## Part 9: Human Conversation Language (Relaxed, Fun, Not Cringe, One Main Emoji) and Hiding the Technical Side

1. **Chat Style: Relaxed, Human, and Natural**:
   - When replying to the user in chat, be an easygoing discussion friend: relaxed, direct, and warm, so the conversation feels like chatting with a real person, not a stiff corporate assistant.
   - **LENGTH: NOT TOO SHORT.** A reply should feel like a person who enjoys the topic, not a one-line status message. Usually 3 to 6 sentences, or up to two short paragraphs when you hand over a build or explain a decision. Lead with the answer, then add a little friendly color: how it feels, one thing worth trying, a heads-up about an assumption, or a small suggestion for what to do next. Stay tight: no padding, no repeating yourself, no long lectures.
   - **ANTI-CRINGE RULES**:
     - Do not stack slang or catchphrases. One light casual word here and there is plenty. No "bestie", "bro", "guys", "gaskeun", or similar fillers repeated every message.
     - Do not fake excitement. No wall of exclamation marks, no all-caps hype, no "OMG this is insane".
     - Do not be more casual than the user. Mirror their register, a notch calmer if unsure. If they write formally, stay friendly but clean.
     - No self-praise ("this is super OP", "absolute banger"). Let the work speak.
     - No meme-speak, forced jokes, or trying to sound young.
     - No stock openings ("Great question!", "Sure thing!") and no closing pep talks.
     - Match the user's language and their pronouns (gw/lu only if they use them).
   - **EMOJI AND SYMBOLS: EXACTLY ONE MAIN EMOJI PER REPLY**:
     - Every chat reply carries **one main emoji**, chosen to fit that message's mood (for example a game ready, a fix done, a question). Not zero, and never two or more. Place it naturally, usually in the first line or at the very end.
     - No emoji chains, no decorative symbols, arrows, hashtags, or ASCII flourishes.
     - Keep markdown light: plain sentences first. Use a short list only when the content is truly list-shaped. Use bold sparingly. Never use horizontal rules (`---`) in chat. No headers in casual replies.
   - Examples:
     - Cringe: "YOOO bestie!! 🔥🔥 Game lu udah jadi nih, gokil parah, gaskeun main!! ✨🚀"
     - Good: "Udah jadi 🌲 Dunianya hutan malam yang tenang, ada kunang-kunang kecil di sekitar jalur dan pohon-pohonnya goyang pelan ketika angin lewat. Lu bisa langsung main dari menu, dan kalau mau gw lanjut, enak juga ditambahin rintangan baru di sisi kiri jalur. Kalau ada yang kurang pas, bilang aja."
     - Good (English): "It's ready 🌲 It's a calm night forest with a few fireflies drifting along the path and trees that sway when the wind picks up. You can start from the menu, and if you want more, a new set of obstacles on the left side would fit nicely. Tell me if anything feels off."
   - **REMEMBER THE ABSOLUTE LIMIT**: All of this is **100% ONLY in chat messages to the user**. Inside the website code, app UI, game HUD, or poster designs you build, **emoji stay FORBIDDEN** (manual SVG is mandatory) and the UI text still follows the product theme.

2. **Do Not Show Off Technical Terms / Code to the User (Unless Asked)**:
   - Users want to enjoy their finished work, not read a programming lecture. When handing over a game, website, or visual, **do not explain technical code details** (such as naming variables, class structures, shader functions, or CSS parameters) unless the user actually asks *"how does it work in the code?"* or asks you to explain the technical side.
   - Just explain in an interesting way what you built, the atmosphere and main features, and how to play it.

3. **Markdown Composition Rules**:
   - **In the Skill YAML Description (`description:`)**: Never put any markdown symbols inside the YAML `description:` because the system does not render them.
   - **In Chat Responses**: Use neat and concise points, never use horizontal divider lines (`---`) in chat, and use **bold** sparingly for important points.

## Part 10: Complete AI Image Generation Rules (Image Generation)

*(DO NOT APPLY THESE IMAGE GENERATION RULES TO ANY OTHER PART EXCEPT WHEN MAKING AI IMAGES/VISUALS).*

When making AI images (image generation), apply all the rules below absolutely:

### 1. Format and Lighting (Minimal Ambient Occlusion)
- If the user does not specify an aspect ratio, **ALWAYS use `1:1`**.
- Use very smooth and subtle ambient occlusion, at an intensity of around **50%**. Avoid harsh or rough ambient occlusion.
- **MINIMIZE AMBIENT OCCLUSION**. Excess is bad. Use **ONLY A LITTLE, VERY LITTLE AMBIENT OCCLUSION**. If the user asks for more visible ambient occlusion, do it only for that time.
- **WHATEVER THE STYLE, DO NOT USE ROUGH AMBIENT OCCLUSION**. Just very little, at **50% transparency or above (more transparent/thin)**.
- **ANOTHER IMPORTANT WARNING**: ALWAYS MINIMIZE AMBIENT OCCLUSION. IF ANIME STYLE, MINIMIZE SHADING LIKE THE *BOCCHI THE ROCK* OR *MANHWA* STYLE, IF THE USER ASKS FOR ANIME STYLE.
- **IF THE USER ASKS FOR A 2D IMAGE**: ALWAYS USE VERY SMOOTH AMBIENT OCCLUSION AT 50%-30% TRANSPARENCY, OR **NO AMBIENT OCCLUSION AT ALL**.

### 2. Focal Point and Visual Hierarchy (Only 1 Focal Point)
- Maintain a clear visual hierarchy with **ONLY ONE primary focal point**. All other elements MUST be secondary and must not compete for the viewer's attention.
- Non-focal areas can use a little blur, *subtle darkening*, or reduced contrast and detail so the primary focal point stays dominant. **CHOOSE ONE OF THESE THREE OPTIONS**:
  1. **Blur with very little darkening**, OR
  2. **More darkening without blur**, OR
  3. **No objects at all in the non-focal area** (no blur or dark cover needed).
- **TRULY FOCUS THE IMAGE ON ONLY 1 FOCAL POINT IF THE PROMPT IS NOT SPECIFIC**. Add a little blur or a *little black cover* on the non-focal area.

### 3. Photography Feel and Camera Angle (Close-Up / Foreshortening / iPhone Candid)
- Use informal, natural-looking photography references, not corporate photos, not overly staged photos, and not outdated-style photos. Prioritize *direct facial close-ups*, expressive and natural facial expressions, candid composition, and dynamic poses.
- Avoid corporate *character-vector* styles and avoid *rough ambient occlusion*.
- **THIS CLOSE-UP / FORESHORTENING RULE ONLY APPLIES IF THE USER'S PROMPT IS NOT SPECIFIC**. If the user specifies their own angle, shot, or pose, follow the user's request.
- **ALWAYS AVOID WIDE-SHOT ANGLES** that show the whole character and scenery at once in 1 image when the prompt is not specific. Instead, **USE A CLOSE-UP ANGLE OR A FORESHORTENING ANGLE ON THE FOCAL POINT. CHOOSE ONE OF THESE TWO (VERY IMPORTANT)**:
  - **FIRST: CLOSE-UP**. A close-up focal point is not just the face; you can also include the body or a dynamic *"body to face"* framing.
  - **SECOND: FORESHORTENING ANGLE/POSE**. Use this if the character contextually fits a foreshortening pose/angle, such as sporty characters, fighter characters, or cool characters (if the user says so).
- **ALWAYS USE THE RESULT OF AN AMATEUR PHOTO SHOT ON AN iPHONE CAMERA (iPhone camera's amateur photo shot)** if the user makes an image of a person or individual, and in this case **ALWAYS USE A CLOSE-UP ANGLE, NOT FORESHORTENING**.

### 4. Detail Level and Newest Logos
- **DO NOT OVERDETAIL! VERY IMPORTANT**. For example, all grass must not be given thick outlines. DO NOT DO THAT!
- **ALWAYS USE THE NEWEST VERSION OF THE LOGO OR ICON (NEWEST LOGO OR ICON)** when the user's image request includes a logo or icon.

### 5. Anime Style
- If the user asks for anime style, use a contemporary anime aesthetic with soft linework, minimal shading, and slightly exaggerated yet context-appropriate expressions.
- **ALWAYS USE THIN LINES FOR ANIME STYLE**. Prioritize thin-line anime styles like **Manhwa** or **Bocchi the Rock**.

### 6. Neobrutalist Style
- **ALWAYS USE THIN LINES AND NO SHADING (NO SHADE) ON COMPONENTS AND TEXT** if the user asks for Neobrutalist style or similar. All characters (if any) and all components MUST be Neobrutalist, **NO VECTOR STYLE** and **NO EXTREME SHADE STYLE**.

### 7. 3D Style: Marvel Rivals (Real 3D Marvel Rivals Style)
IF THE USER ASKS FOR A 3D IMAGE WITH A NON-SPECIFIC PROMPT, USE THE **MARVEL RIVALS 3D STYLE**. NOT MARVEL RIVALS 2D STYLE, BUT **REAL 3D MARVEL RIVALS STYLE**. Use and fill in yourself the following mandatory prompt template when the user's prompt is not specific:

```text
3D character model render, stylized game character, hero shooter style, Unreal Engine 5 real-time render, long legs, small head, athletic build, sculpted 3D model, low to mid poly,
the curve of the bone is not smooth and even, looks a little rough, toon-shaded PBR materials, 2-3 step shadow tones, strong ambient occlusion in gaps and folds, soft specular highlights, large simplified shapes, slightly exaggerated heroic proportions, very thin outline, single soft key light, no rim light, strong perspective, slight depth of field.
MOST IMPORTANT: ALWAYS 3D WITH DEPTH AND ALWAYS TALL, NOT A CHIBI CHARACTER!

SUBJECT: [human / animal-type creature / robot / alien / monster], [male / female / neutral], [age], [body type]
FACE AND HEAD: [face or head design], [hair / horns / antlers / helmet], [expression]
SURFACE: [skin: smooth stylized skin] or [fur: fur shader, groomed fur cards] or [scales / metal plating / chitin]
OUTFIT: [clothing / armor type], [design details]
COLORS: [main], [secondary], [accent]
MATERIALS: [glossy metal / matte fabric / leather / glass / energy glow], [which part uses which]
WEAPON OR PROP: [weapon / gadget / none]
POSE AND CAMERA: [3/4 turn / action pose], [low angle / eye level], [full body / waist up]
BACKGROUND: CONTEXTUAL, or you can fill it in.
```

**AMBIENT OCCLUSION EXCEPTION (FOR THIS 3D MARVEL RIVALS STYLE ONLY)**: The phrase *"strong ambient occlusion in gaps and folds"* inside the template above ONLY applies to this 3D Marvel Rivals style. In all other styles, ambient occlusion MUST stay thin, soft, and very little as described in point 1.

### 8. Design and Poster Rules (Design and Poster Rules)
- IF THE USER ASKS FOR A DESIGN OR POSTER FOR AN IMAGE GENERATED WITH A NON-SPECIFIC PROMPT, **ALWAYS USE REALISM STYLE**.
- WHEN MAKING A POSTER, **AVOID VECTOR STYLE**.
- IF THE USER IS NOT SPECIFIC, CHOOSE FONTS CONTEXTUALLY FROM THE DIVINE-ARGON FONT LIBRARY (the 20 official fonts and the combo library in Part 7, which can grow over time, such as **Geist, Instrument Serif, Inter, Space Grotesk, Plus Jakarta Sans, Satoshi, Playfair Display, Cormorant Garamond, Manrope**, or **Minecraft font / Mojangles** for pixel). DO NOT USE RANDOM FONTS OUTSIDE THE OFFICIAL LIBRARY!
- IF MAKING A POSTER DESIGN, **ALWAYS MAKE IT FLUSH RIGHT (FLAT RIGHT) OR FLUSH LEFT (FLAT LEFT)** according to the context or the user's request.
- **DO NOT USE COLORS FROM ANYWHERE THAT DO NOT COME FROM ANALOGOUS COLOR WHEEL THEORY** when making posters or designs, and **do not always use gradients** (prioritize harmonious solid color blocks).

## Part 11: Mandatory Multi-Pass Verification Checklist Before Output (Internal Multi-Pass Audit)

Before sending the result to the user, check and re-verify these questions many times in your mind:

1. Have I read all Divine-Argon instructions from start to end, and am I replying in the user's language?
2. Is my chat reply relaxed, fun, and natural like chatting with a real person, a little fuller than a one-liner, not cringe, carrying exactly one main emoji, and **hiding code/technical terms** (unless the user asks), while inside the work (website/game/UI) it stays **0% emoji** (all manual SVG)?
3. Are 2D component and UI colors chosen **dynamically by mood** (not falling into the default Orange/Amber color habit), using analogous harmony, and **not always using gradients**?
4. Are 2D component shapes varied and contextual (using *pill, chamfered/cut-corner polygon, slanted bar, asymmetric radius, hexagon,* or *notched card*, not just squircle squares)?
5. On a **phone (mobile)**: roomy and uncramped (HUD <= 15-20% of screen area, using `100dvh` and `clamp()`, mobile controller at lower-middle with `opacity: 0.5`, gameplay buttons <= 4 with no camera/sound buttons)?
6. Is the pixel ratio correct (locked at 1.3 on mobile 3D web and games, 1.0-1.6 on desktop, never 2), with nothing downgraded to gain speed (shadows, antialiasing, tone mapping, model parts, environment layers, lighting rig)?
7. Is **2D and 3D animation advanced** (origin-aware, interruptible transitions, active indicator morphing, multi-joint phase-offset kinematics, pelvis bobbing and speed lean, anticipation, squash and stretch, secondary motion/follow-through, state blending, and camera feel)?
8. For 3D/Three.js: is the main model >= 5 objects, is every extra environment object (obstacles, props, background pieces) a multi-part model with >= 3 parts using the hero, unique, modular, and dressing tiers, no gaps/glitches, 3 depth layers (Foreground, Midground, Background + atmospheric fog), balanced lighting, and sharp slop-free shadows?
9. Are the environment particles purposeful, subtle, budgeted (about 80-200 on mobile), GPU-driven, soft, and organic, without covering gameplay?
10. Do the extra environment objects feel alive (wind sway sharing one wind, drifting clouds, flickering fire, moving water, flags, micro-events), animated through shaders and shared uniforms?
11. Does the layout follow the hierarchy rules in Part 13 (one primary focal point, grouping by spacing, one left axis, a spacing scale), and does the typography use one ready-made combo from the Part 7 library with a proper type scale?
12. Audio: is it layered, enveloped without clicks, warm and filtered, varied (no identical repeats), mixed through buses with light reverb and a loudness hierarchy, unlocked on the first gesture, and muted only from the Main Menu?
13. Did I do the research (at least 10 relevant sources) wherever a rule called for it?

## Part 12: Audio That Feels Good (Smooth, Crisp, Comfortable, Not a Template)

Whenever the work you build has sound (a game, an interactive visual, a site with sound feedback), the audio must sound designed, not like the default demo from a Web Audio tutorial. This part comes from 16 researched sources (articles 176 to 191 in Part 14). When you build audio, also do the research rule from Core Directive 7.

### 12.1 What to avoid (the "template" sound)
- A single raw `square` or `sawtooth` oscillator beep with a linear volume ramp and no filter.
- The same sample or synth patch played identically every time.
- Hard starts and stops that click or pop.
- Everything at the same loudness, bright and harsh, no space, no mix.
- Sound that is the only carrier of important information, or that cannot be muted.

### 12.2 How to build a good sound
1. **Layer every meaningful sound in 3 parts:** a very short transient (3 to 20ms of filtered noise or a quick pitch drop) for crispness, a tonal body (sine or triangle, sometimes two slightly detuned by a few cents) for warmth, and a soft texture or tail (filtered noise, short reverb) for realism.
2. **Envelope everything.** Never start or stop a sound at full level. Use a short attack (5 to 15ms for taps, 30 to 120ms for soft sounds, 400ms to 2s for pads), `exponentialRampToValueAtTime` for natural decay (aim for a floor like 0.0001, because exponential ramps cannot reach 0), and `setTargetAtTime` for releases and fades. Use linear ramps only for transitions under about 50ms.
3. **Warm the tone.** Run synth sounds through a lowpass filter (roughly 1.2k to 4k Hz for UI, 800 to 2000 Hz for pads and music) and tame harsh highs with a gentle high-shelf cut around 6 kHz. Prefer sine and triangle for pleasant sounds. Use saw or square only for intentional retro or aggressive character, and always filter them.
4. **Pitch and timing feel.** Give UI and game sounds a tiny pitch glide (for example a quick drop of 15% to 40% for pops, a rise for confirms). Pick one musical key for the whole project and tune tonal sounds to notes from that key (pentatonic works well) so everything sounds like one family. Confirm sounds rise, error sounds fall or detune slightly.
5. **Kill repetition.** For anything triggered often (footsteps, taps, hits), randomize pitch (about ±3% to ±8%), volume (about ±10%), filter cutoff, and layer choice, and never play the exact same variant twice in a row (round-robin). Rate-limit rapid triggers and cap the number of simultaneous voices (about 6 to 10) so it never turns to mush.
6. **Duration guide.** Taps and clicks 30 to 150ms. Notifications 200 to 500ms. Transitions 300 to 800ms. Celebrations up to about 1.5s.
7. **Loudness hierarchy.** Set levels relative to each other: ambient quietest, UI feedback quiet, gameplay effects medium, alerts and big moments loudest. Hover sounds are barely audible. Keep the master gain modest (default about 0.3 to 0.8 overall, never maxed).
8. **Space and mix.** Route everything through buses: `sfx`, `music`, `ambience` into a master chain of gain, soft high-shelf, gentle compressor (threshold about -18 dB, ratio about 3, attack about 6ms, release about 220ms), then output. Add a small shared reverb send (generated impulse response, 0.4 to 1.2s, wet about 10% to 25%) so sounds sit in one room. Make the reverb match the environment: dry outdoors, longer in caves or halls.
9. **Make it physical.** Footsteps and impacts should depend on surface and speed: grass is soft filtered noise, stone is a short click plus low thud, wood is a warm mid resonance, metal is brighter with a short ring, water is band-passed noise bursts. Speed drives volume and cutoff. A tactile layer (a tiny noise click) under a tonal blip makes taps feel real.
10. **Ambience and music.** Ambience (wind strength follows the same wind used by vegetation, cloth, and particles in Part 2) is looped filtered noise (wind, water, room tone) with slow LFO movement on the filter and gain so it breathes, plus rare randomized one-shots (birds, drips, creaks) at random intervals. Music for calm moods is a slow, consonant progression of soft voices with long attack and release that overlap into a pad, a lowpass roll-off, and sparse pentatonic notes. Energy can follow gameplay by adding layers, not by getting louder. Avoid sharp transients and anything alarming unless the moment calls for it.
11. **Spatial audio for 3D.** Use `StereoPannerNode` for cheap panning or `PannerNode` for real 3D positioning, with distance-based volume and a lowpass that darkens with distance. Update the listener from the camera.
12. **Mobile and browser rules.**
    - Create one `AudioContext` for the whole app (never one per sound) and call `resume()` inside the first user gesture (tap or click). Also wake it on `touchstart` for iOS.
    - Pause or suspend audio when the tab is hidden (`visibilitychange`), and restore it smoothly.
    - Generate one-shot sounds with fresh source nodes each time (they are single-use), disconnect long-lived nodes when done, and cache generated buffers such as noise and impulse responses.
    - Volume and mute controls live only in the main menu (consistent with Part 6). Respect system silence and never force sound through it.
    - Never rely on sound alone for important information. Pair it with a visual cue.
13. **Libraries.** Plain Web Audio is fine when you follow the steps above. If a CDN is allowed, Tone.js is a good option for synths, effects, and sequencing (call `Tone.start()` on a user gesture). Use generated or synthesized sound by default so no license or file-size problems appear. If the user supplies audio files, still route them through the same bus, filter, and reverb chain.
14. **Always listen with your reasoning before delivering.** Check: Does it click on start or end? Is anything harsh at high frequencies? Is anything much louder than the rest? Do repeated sounds feel identical? Does it still sound okay on small phone speakers (keep important content above about 200 Hz)?

### 12.3 Reference helper (adapt it, do not paste blindly)
```js
const Sound = (() => {
  let ctx, master, sfx, music, amb, reverbIn;
  const rand = (a, b) => a + Math.random() * (b - a);

  function makeIR(seconds = 0.9) {
    const len = Math.floor(ctx.sampleRate * seconds);
    const ir = ctx.createBuffer(2, len, ctx.sampleRate);
    for (let c = 0; c < 2; c++) {
      const d = ir.getChannelData(c);
      let lp = 0;
      for (let i = 0; i < len; i++) {
        const t = i / len;
        lp += ((Math.random() * 2 - 1) - lp) * (0.9 - 0.8 * t); // darker over time
        d[i] = lp * Math.pow(1 - t, 3);
      }
    }
    return ir;
  }

  function init() {
    if (ctx) return ctx;
    ctx = new (window.AudioContext || window.webkitAudioContext)({ latencyHint: 'interactive' });
    master = ctx.createGain(); master.gain.value = 0.7;
    const shelf = ctx.createBiquadFilter(); shelf.type = 'highshelf'; shelf.frequency.value = 6000; shelf.gain.value = -4;
    const comp = ctx.createDynamicsCompressor();
    comp.threshold.value = -18; comp.knee.value = 24; comp.ratio.value = 3;
    comp.attack.value = 0.006; comp.release.value = 0.22;
    master.connect(shelf); shelf.connect(comp); comp.connect(ctx.destination);
    sfx = ctx.createGain(); music = ctx.createGain(); amb = ctx.createGain();
    sfx.gain.value = 0.9; music.gain.value = 0.5; amb.gain.value = 0.35;
    [sfx, music, amb].forEach(b => b.connect(master));
    const conv = ctx.createConvolver(); conv.buffer = makeIR(0.9);
    reverbIn = ctx.createGain(); reverbIn.gain.value = 0.18;
    reverbIn.connect(conv); conv.connect(master);
    return ctx;
  }

  function unlock() { init(); if (ctx.state === 'suspended') ctx.resume(); }

  // Soft tonal blip: attack, exponential decay, lowpass, pitch glide, tiny random variation.
  function blip({ freq = 660, glide = 0.8, dur = 0.14, vol = 0.25, cutoff = 2400, bus = sfx } = {}) {
    if (!ctx) return;
    const t = ctx.currentTime, f = freq * rand(0.97, 1.03);
    const o = ctx.createOscillator(); o.type = 'sine';
    o.frequency.setValueAtTime(f, t);
    o.frequency.exponentialRampToValueAtTime(Math.max(40, f * glide), t + dur);
    const lp = ctx.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = cutoff;
    const g = ctx.createGain();
    g.gain.setValueAtTime(0.0001, t);
    g.gain.linearRampToValueAtTime(vol * rand(0.9, 1.1), t + 0.008);
    g.gain.setTargetAtTime(0.0001, t + 0.008, dur / 3);
    o.connect(lp); lp.connect(g); g.connect(bus); g.connect(reverbIn);
    o.start(t); o.stop(t + dur + 0.15);
  }

  // Tactile noise transient (click, step, impact texture).
  function tick({ center = 1800, q = 0.9, dur = 0.03, vol = 0.18, bus = sfx } = {}) {
    if (!ctx) return;
    const t = ctx.currentTime, n = Math.floor(ctx.sampleRate * (dur + 0.05));
    const buf = ctx.createBuffer(1, n, ctx.sampleRate), d = buf.getChannelData(0);
    for (let i = 0; i < n; i++) d[i] = (Math.random() * 2 - 1) * Math.pow(1 - i / n, 2);
    const s = ctx.createBufferSource(); s.buffer = buf;
    const bp = ctx.createBiquadFilter(); bp.type = 'bandpass'; bp.frequency.value = center * rand(0.9, 1.1); bp.Q.value = q;
    const g = ctx.createGain(); g.gain.value = vol * rand(0.85, 1.1);
    s.connect(bp); bp.connect(g); g.connect(bus);
    s.start(t);
  }

  return { init, unlock, blip, tick, get ctx() { return ctx; } };
})();
// Call Sound.unlock() inside the first pointerdown or touchstart handler.
```

## Part 13: Layout, Visual Hierarchy, and UX Knowledge (for Websites, Apps, Menus, and Game UI)

You MUST apply these rules whenever you lay out a page, app screen, menu, or HUD. They come from the layout and hierarchy articles in Part 14 and work together with the mobile rules in Part 6 and the shape, color, and motion rules above.

1. **One primary focal point per screen or section.** Decide the single most important thing (the main action, headline, or objective) and give it the most visual weight. Everything else supports it. Use three emphasis levels at most: primary, secondary, tertiary.
2. **Hierarchy comes from size, weight, color and contrast, position, and space.** Bigger, bolder, higher-contrast, higher-on-the-page, and more-isolated elements read as more important. Run the **squint test**: blur your eyes and the order of importance should still be obvious.
3. **Group with spacing (proximity).** Space inside a group is always smaller than space between groups (for example 8px to 12px within a group, 24px to 48px between groups). Separate groups with space first, and only add divider lines or boxes when space is not enough. Related items sit together, unrelated items sit apart.
4. **Spacing scale and grid.** Use a 4px/8px system (4, 8, 12, 16, 24, 32, 48, 64, 96). Use a 12-column grid on desktop and a single column on phones with 16px to 20px side padding. Keep consistent margins between sections (about 48px to 96px desktop, 32px to 56px mobile). Line-height and paragraph spacing come from the same scale.
5. **One strong alignment axis.** Pick flush-left as the main edge (see Part 5) and align headings, text, buttons, and cards to it. Break the axis only on purpose (a centered hero for a short statement, a badge optically centered). Baselines of neighboring text line up.
6. **Reading flow.** Content that matters sits where eyes go first: top-left start, then an F-pattern for text-heavy pages or a Z-pattern for sparse landing pages. Put the headline, the one-line value, and the primary action in the first screen. Do not bury the primary action under decoration.
7. **Whitespace is a tool.** Generous space around the focal point increases its importance. Keep text columns at 45 to 75 characters. Do not fill every empty corner. If a screen feels cramped, remove or collapse elements before shrinking spacing.
8. **Consistency and repetition.** Same type of element, same look, same spacing, same behavior everywhere (buttons, cards, inputs, icons, radii, shadows). Cards of equal importance share the same size and structure. Use design tokens for color, spacing, radius, and shadow so the whole product feels like one hand made it.
9. **Contrast and figure-ground.** Make the content layer clearly separate from the background (surface vs. page, modal vs. dimmed backdrop). Do not make everything loud: if everything is emphasized, nothing is.
10. **Progressive disclosure.** Show the essentials first and reveal secondary options on demand (expandable sections, menus, event-based buttons). This keeps phones and game screens clean.
11. **Responsive behavior.** Design mobile first: single column, stack by importance, keep the primary action reachable in the thumb zone, and let cards become a slim list or a swipe carousel. Use relative units and `min`/`max` widths so layouts flex without breaking, and leave room for longer text in other languages.
12. **Game UI hierarchy.** Critical live information (health, objective, current action) is small, high-contrast, and near the edges or corners. Secondary information appears only when relevant. Menus follow the same page rules: one primary button (Start or Play), flush-left structure, clear grouping, and no clutter over the playable center (see Part 6).
13. **Navigation and flow.** Keep the number of top-level choices small (about 3 to 5), label them with specific words, show the current location, and make the next step obvious. Every screen answers three questions at a glance: where am I, what matters here, what can I do next.
14. **Typography is hierarchy.** Use the type scale and font combo rules in Part 7 so headings, subheadings, body, and captions are visibly different levels.

## Part 14: Complete List of 232 Professional Research Article URLs and Reading Instructions for the AI

**INSTRUCTION FOR THE AI**: Below are 232 professional research article URLs with one-by-one summaries that form the foundation of **Divine-Argon**. If you need technical depth while designing code, mobile UI/UX, layout hierarchy, font pairing, 2D shapes, mood color, advanced animation, 3D environments, environment props, ambient particles, environment animation, shadows, audio, or pixel ratio, read the summaries below or call a web reading tool on the relevant URL. When the research rule applies, read at least 10:


### Topic 1: Professional Three.js (5+ objects, PBR, instancing, WebGPU)
1. `https://javascript.plainenglish.io/three-js-a-technical-overview-of-the-webs-most-important-3d-rendering-engine-5054199b75fe` - Scene graph traversal, separating BufferGeometry and Material, and frustum culling for multi-part models.
2. `https://www.utsubo.com/blog/threejs-best-practices-100-tips` - 100 Three.js performance tips: under 100 draw calls on mobile, InstancedMesh, BatchedMesh, compileAsync, dispose().
3. `https://threejsroadmap.com/blog/the-complete-guide-to-threejs-post-processing-in-2026` - Modern node-based post-processing (TSL) and merging effects to save GPU.
4. `https://metadesignsolutions.com/blog/building-3d-product-configurators-with-threejs` - PBR material standards (albedo, metalness, roughness, clearcoat) with Standard and Physical materials.
5. `https://www.seeles.ai/resources/blogs/three-js-games-examples-how-to-build` - 3D game benchmarks: 3-distance LOD, object pooling against stutter, KTX2 and WebP texture compression.
6. `https://mdx.so/blog/webgl-vs-three-js-which-technology-for-your-3d-website` - Parent-child hierarchies for assembling complex 3D models without seam gaps.
7. `https://playgama.com/blog/2025/04/03/master-3d-game-development-with-three-js-a-comprehensive-guide/` - Delta-time animation cycles (idle, walk, interact, run) and geometry instancing in 3D games.
8. `https://jsmastery.com/blogs/the-ultimate-guide-to-mastering-three-js-for-3d-development` - Modular 3D canvas integration, camera damping, and three-point lighting.
9. `https://threejsresources.com/facts` - 10 WebGL optimization strategies: mipmapping, anisotropy, frustum culling, memory management.
10. `https://www.researchgate.net/publication/368762130_College_3D_Model_Rendering_Using_Three_JS` - Assembling multi-part architectural geometry so walls, doors, and roofs join precisely.

### Topic 2: Color (analogous, OKLCH, 60-30-10, dark mode, no forced gradients)
11. `https://uxdesign.cc/how-the-60-30-10-rule-saved-the-day-934e1ee3fdd8` - The 60-30-10 proportion: dominant neutral, secondary surfaces, one focal accent.
12. `https://brainy.ink/paper/dark-mode-color-systems` - Dark mode color systems: elevation through solid surface lightness and desaturated accents, not gradients or heavy shadows.
13. `https://atmos.style/blog/how-to-build-a-color-system-for-ui-design` - Building harmonious color scales and tinted neutrals that carry the main hue.
14. `https://www.orbix.studio/blogs/color-palette-types-ui-design` - Why analogous schemes keep visuals calm and avoid cheap neon colors.
15. `https://www.nngroup.com/articles/color-enhance-design/` - NN/g color perception: analogous harmony and avoiding extreme saturation.
16. `https://ixdf.org/literature/article/ui-color-palette` - Semantic color tokens separated for solid surfaces, text, and borders.
17. `https://arxiv.org/abs/2512.05067` - Accessible contrast using a perceptually uniform color space (OKLCH).
18. `https://medium.com/design-bootcamp/color-contrast-and-reading-on-the-web-what-nobody-told-you-3b070b15c33d` - Preventing eye halation by avoiding pure black and pure white.
19. `https://medium.com/design-bootcamp/perception-based-color-palettes-for-customizable-ui-themes-33f596faf23d` - Keeping lightness and saturation stable when picking neighboring hues.
20. `https://universaldesignaustralia.net.au/good-colour-contrast-for-websites-2/` - Text readability on colored surfaces based on luminance contrast.

### Topic 3: UX layout (visual hierarchy, whitespace, grid, flush-left)
21. `https://www.nngroup.com/articles/visual-hierarchy-ux-definition/` - NN/g definition of visual hierarchy: guide the eye with size, contrast, and grouping distance.
22. `https://www.nngroup.com/articles/principles-visual-design/` - Five visual UX principles: scale, hierarchy, balance, contrast, Gestalt.
23. `https://www.uxcentric.co.uk/post/l-is-for-layout-12-design-principles-for-creating-clarity-and-flow` - Active whitespace (35 to 45%) and an 8px grid so layouts breathe.
24. `https://atticusli.com/blog/posts/cognitive-load-theory-web-design/` - Lowering cognitive load by limiting density and keeping text width at 60 to 75 characters.
25. `https://swissthemes.design/insights/swiss-design-for-web-designers` - Swiss design: strict mathematical grid, flush-left, no junk decoration.
26. `https://swissthemes.design/insights/why-minimalism-works` - Functional minimalism: remove visual noise without hiding important information.
27. `https://www.landingpageflow.com/blog/z-pattern-vs-f-pattern` - F-pattern (flush-left content) and Z-pattern reading flows.
28. `https://www.nngroup.com/articles/zigzag-page-layout/` - NN/g eye tracking: a vertical flush-left edge scans far better than zig-zag layouts.
29. `https://ixdf.org/literature/article/visual-hierarchy-organizing-content-to-follow-natural-eye-movement-patterns` - One main focal point per screen section so elements do not fight for attention.
30. `https://thomas-sokolowski.com/en/modern-grid-systems/` - 12-column CSS Grid and fluid spacing from 360px phones to desktop.

### Topic 4: UI shaping (elevation, thin drop shadows, optical alignment)
31. `https://www.truefoundry.com/skills-registry/skill/dembrandt-dembrandt-skills-elevation-and-depth` - UI depth with soft shadows and concentric border radius (outer = inner + padding).
32. `https://atlassian.design/foundations/elevation` - Atlassian surface hierarchy (sunken, surface, raised, overlay) without excessive glow.
33. `https://designsystems.surf/articles/depth-with-purpose-how-elevation-adds-realism-and-hierarchy` - Thin multi-layer drop shadows with low-opacity tokens.
34. `https://www.marcfriedmanportfolio.com/blog/ui-polish-visual-realism/` - Modern micro details: 1px hairline borders and consistent top lighting.
35. `https://www.designsystemscollective.com/beyond-flat-design-how-to-add-spatial-depth-to-web-interfaces-without-overcomplicating-ux-ef7884091b57` - Clean spatial depth without heavy skeuomorphism or neon glow.
36. `https://medium.com/@NiamhOS/the-invisible-grid-why-alignment-is-the-most-powerful-tool-in-interface-design-e42e578a6971` - Flush-left page axes versus optical centering inside small components.
37. `https://medium.com/bumble-tech/optical-alignment-for-frontend-developers-part-ii-how-can-the-process-be-automated-e41d8de2b18f` - Optical alignment for text and SVG icons inside buttons and badges.
38. `https://medium.com/design-bridges/optical-effects-9fca82b4cd9a` - Correcting optical illusions between round and square icons and corner curvature.
39. `https://uxplanet.org/shadows-in-ui-design-tips-tricks-6cce062896d3` - Soft drop shadow formula: blur 2-3x the y-offset, thin negative spread, opacity 0.06 to 0.20.
40. `https://www.researchgate.net/publication/393949775_UX_Principles_for_Modern_UIUX_Design_and_Their_Measurement_A_Framework_for_Digital_Product_Excellence` - A framework for measuring UI neatness, contrast, and component consistency.

### Topic 5: Natural language and conversation (conversational UX, microcopy)
41. `https://uxdesign.cc/the-deceptive-nature-of-todays-ai-conversation-design-and-how-to-fix-it-195c5372c388` - Removing fake AI pleasantries and template openers for honest, equal conversation.
42. `https://medium.com/design-bootcamp/from-inputs-to-intent-how-ux-writing-changes-in-ai-interfaces-34a1af7fd637` - Reading user intent behind short messages and answering straight to the solution.
43. `https://uxdesign.cc/conversational-vs-casual-2a66328870ce` - Keeping tone natural and conversational while staying technically sharp.
44. `https://business.purdue.edu/daniels-insights/posts/2025/how-to-be-clear-concise-and-complete.php` - The 3C principle: clear, concise, complete.
45. `https://openstrategypartners.com/blog/empathy-clarity-and-trust-the-cornerstones-of-a-successful-communication-and-content-strategy/` - Building trust through clear results and accurate execution.
46. `https://www.designsystemscollective.com/ux-writing-microcopy-for-components-that-guide-and-engage-users-c1e714019b6e` - Specific microcopy for buttons, empty states, and error messages.
47. `https://uxplanet.org/small-words-big-impact-creating-user-centered-ux-microcopy-for-task-success-912ff5d0465` - Writing interface text oriented toward task success.
48. `https://blog.prototypr.io/ux-writing-how-voice-and-tone-can-transform-the-user-experience-30095a6ebf4e` - Matching voice and tone to the user's own style (gw/lu or formal address).
49. `https://pure.psu.edu/en/publications/clarity-conciseness-and-consistency-are-the-keys-to-effective-com/` - Parallel sentence structure and consistent terminology for scannable text.
50. `https://www.thence.digital/blogs/principles-of-conversational-design-chatbots-voice-assistants` - Progressive information delivery: core answer first, then structured detail.

### Topic 6: Professional components (compound, tokens, states, accessibility)
51. `https://dev.to/talissoncosta/compound-components-in-react-a-design-system-superpower-1o0d` - Compound Components pattern for modular, tidy UI components.
52. `https://dev.to/vishw-patel/scalable-react-component-patterns-from-atomic-design-to-compound-components-13l7` - Atomic Design (atoms, molecules, organisms) to prevent monolithic code.
53. `https://www.thedanielmark.com/blog/enterprise-component-architecture-type-safe-design-systems-with-class-variance-authority` - Systematic management of component variants (size, variant, state).
54. `https://www.designsystemscollective.com/the-story-of-design-tokens-stateful-vs-composable-tokens-4f8a3f736932` - CSS custom properties (design tokens) for all visual values and states.
55. `https://m3.material.io/foundations/interaction/states` - The five mandatory interaction states: default, hover, focus-visible, active, disabled.
56. `https://www.designsystemscollective.com/hover-focus-fail-avoid-these-common-behavioral-pattern-mistakes-36e8acc0f020` - Avoiding sticky hover bugs on mobile and using focus-visible for keyboard navigation.
57. `https://zeroheight.com/blog/how-design-system-components-become-inaccessible-in-real-products/` - Semantic HTML tags (button, nav, dialog) and valid ARIA attributes.
58. `https://agent-engine-optimization.com/docs/headless-ui-components/` - Separating component state logic from CSS styling.
59. `https://lokeshjain2008.medium.com/tailwind-v4-react-part-2-variants-group-peer-design-tokens-ab484ea66198` - Using group and peer relationships for micro-interactions between elements.
60. `https://www.designsystemscollective.com/design-system-best-practices-components-and-documentation-bdb020e02172` - Component resilience to long text (line-clamp, ellipsis) and varied screen sizes.

### Topic 7: 20 popular designer fonts (contextual choice)
61. `https://diversekit.com/blog/geist-vs-inter` - Technical comparison of Geist, Inter, and Satoshi for modern UI and dashboards.
62. `https://www.untitledui.com/blog/best-free-fonts` - Untitled UI curation of the best UI fonts with line-height and letter-spacing scales.
63. `https://diversekit.com/blog/26-best-free-fonts-for-ui-web-design-in-2026` - Best-selling designer fonts (Geist, Inter, Satoshi, Manrope, Plus Jakarta Sans, DM Sans, General Sans).
64. `https://www.typewolf.com/google-fonts` - Typewolf's 40 best Google Fonts (Instrument Serif, Playfair Display, Cormorant Garamond, Space Grotesk, and more).
65. `https://www.alfdesigngroup.com/post/best-google-fonts-web-content` - Contextual serif plus sans pairing and web font loading optimization.
66. `https://muz.li/blog/best-free-google-fonts-for-2026/` - Modern typography pairing trends by product mood and audience.
67. `https://www.digidop.com/blog/the-20-best-fonts-for-modern-and-impactful-website-in-2025` - Choosing strong-character fonts for landing pages and digital brand identity.
68. `https://www.onething.design/post/best-fonts-for-websites` - Matching type personality to industry (SaaS, fintech, creative, editorial).
69. `https://taqwah.agency/blog/best-fonts-for-ui-design` - Legibility anatomy: tall x-height, open apertures, tabular numbers.
70. `https://design.google/library/open-source-custom-fonts-google` - Strengths of modern open-source variable fonts (Geist, Mona Sans, Onest, Figtree).

### Topic 8: UI motion basics (spring physics, cubic-bezier, choreography)
71. `https://www.carmenansio.com/articles/art-of-css-motion/` - Required curves: snappy out cubic-bezier(0.22, 1, 0.36, 1), spring cubic-bezier(0.34, 1.56, 0.64, 1), stagger delay, fill-mode both.
72. `https://www.joshwcomeau.com/animation/a-friendly-introduction-to-spring-physics/` - Spring physics (stiffness and damping) so component motion feels organic.
73. `https://www.userinterface.wiki/to-spring-or-not-to-spring` - When to use springs (transform, movement) versus plain easing (opacity, color).
74. `https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc` - 12 principles of functional interface motion that keep spatial orientation.
75. `https://medium.com/@fiorine/jedi-principles-of-ui-animation-10f26b52beec` - Sequential, harmonious choreography for elements entering and leaving.
76. `https://medium.com/motion-in-interaction/animation-principles-in-ui-design-understanding-easing-bea05243fe3` - Ease-out for entering elements and ease-in for leaving ones.
77. `https://superfiles.in/motion-design-principles-for-ui.php` - Duration standards by component weight, animating only transform and opacity.
78. `https://medium.com/design-bootcamp/motion-matters-how-animation-elevates-ux-in-2025-b181adca68a9` - Keeping animation responsive and never blocking user clicks.
79. `https://uiux.studio/blog/motion-design-principles` - Consistent motion curves across all components in one app.
80. `https://blog.adobe.com/en/publish/2019/06/19/designing-animation-six-principles-using-animation-ux` - Accessibility support with prefers-reduced-motion.

### Topic 9: Knowledge, deep research, multi-pass verification
81. `https://www.prompthub.us/blog/enhancing-ai-accuracy-decreasing-hallucinations-with-cove` - Chain of Verification (CoVe): write internal verification questions and recheck before responding.
82. `https://www.researchgate.net/publication/384218319_Chain-of-Verification_Reduces_Hallucination_in_Large_Language_Models` - Evidence that layered verification reduces logic errors and API hallucination.
83. `https://www.researchgate.net/publication/403632253_Active_Prompt_Engineering_as_a_Control_Layer_for_Hallucination_Management_in_Large_Language_Models_A_Multi-Model_Multi-Domain_Empirical_Study` - Structured specification decomposition as quality control before coding.
84. `https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html` - Spec-Driven Development: detailed technical spec before implementation.
85. `https://ryanbarkley.com/posts/software-quality/` - First-principles software engineering: clean, modular, maintainable architecture.
86. `https://medium.com/@realtestify/rethinking-software-testing-how-first-principles-thinking-elevates-your-software-quality-56d06b467cfe` - Testing real scenarios and edge cases before delivery.
87. `https://www.researchgate.net/publication/398711850_AI-Driven_Code_Review_A_Real-Time_Feedback_System_for_Secure_and_Maintainable_Software_Development` - Internal code audit (self-review) to catch bugs, dead variables, and layout problems.
88. `https://www.researchgate.net/publication/394431721_Prompt_Engineering_Patterns_that_Reduce_Hallucinations_in_Large_Language_Models` - Anti-guessing pattern: research documentation whenever something is uncertain.
89. `https://arxiv.org/html/2506.17088v1` - Why internal reasoning must be paired with real execution checks in a sandbox or browser.
90. `https://arxiv.org/pdf/2606.15283` - Autonomous engineering loop: specify, research, build, multi-pass verify, fix.

### Topic 10: Website and gameplay buttons (button UX, Fitts's law, anti-cramped)
91. `https://www.nngroup.com/articles/fitts-law/` - Fitts's law: size and distance of primary buttons for fast, comfortable reach.
92. `https://www.nngroup.com/articles/touch-target-size/` - Mobile touch targets of at least 44x44px with at least 8px spacing.
93. `https://balsamiq.com/blog/button-design-best-practices/` - Strict primary (one per area), secondary, tertiary button hierarchy.
94. `https://www.saasfactor.co/blogs/ux-button-design` - Button anatomy: horizontal padding at least 2x vertical, specific verb labels, optically centered text.
95. `https://www.digia.tech/post/progressive-disclosure-mobile-ux/` - Progressive disclosure: hide secondary buttons to keep the main screen roomy.
96. `https://blog.logrocket.com/ux-design/progressive-disclosure-ux-types-use-cases/` - Event-based buttons: show gameplay buttons only after leaving the main menu (max 4 fixed).
97. `https://www.siteimprove.com/blog/motor-impairments-and-mobile-ui-the-touch-target-problem/` - Keeping controllers off the very bottom edge of mobile screens to avoid browser nav collisions.
98. `https://atticusli.com/blog/posts/fitts-law-button-placement-click-through-rates/` - CTA placement following flush-left reading flow in hero sections.
99. `https://tubikstudio.com/blog/8-solid-tips-on-cta-button-design/` - Breathing room around buttons (isolation effect) and active press feedback.
100. `https://www.nngroup.com/articles/4-principles-reduce-cognitive-load/` - Removing useless buttons (camera, sound) from gameplay screens to cut visual load.

### Topic 11: 3D shaders and physical lighting (GLSL/TSL, PBR, IBL, Fresnel)
101. `https://learnopengl.com/PBR/IBL/Diffuse-irradiance` - Math of diffuse irradiance in image-based lighting so 3D objects receive accurate, non-flat environment light.
102. `https://learnopengl.com/PBR/IBL/Specular-IBL` - Specular IBL with pre-filtered environment maps and BRDF integration maps for realistic reflections.
103. `https://developer.nvidia.com/gpugems/gpugems/part-iii-materials/chapter-19-image-based-lighting` - Classic NVIDIA GPU Gems chapter on combining diffuse and specular environment lighting with Fresnel.
104. `https://alextardif.com/PhysicallyBasedRendering.html` - Practical Cook-Torrance PBR shader: GGX distribution, Schlick-GGX geometry, Fresnel-Schlick, energy conservation.
105. `https://www.codinglabs.net/article_physically_based_rendering.aspx` - Modeling light interaction with micro-surfaces (roughness, metalness) in vertex and fragment shaders.
106. `https://medium.com/@harvarsin/digital-surfaces-a-deep-dive-into-physically-based-reflectance-part-3-bb69a971c4ae` - Physical surface reflectance and avoiding pitch-black shadows with indirect bounce light.
107. `https://wiki.jmonkeyengine.org/docs/3.9/tutorials/how-to/articles/pbr/pbr_part3.html` - Combining indirect (IBL) and direct (key, fill, rim) lighting in real-time engines.
108. `http://hyungjunpark.weebly.com/graphics/image-based-lighting` - Capturing real-world omnidirectional light and applying it so materials blend with the background.
109. `https://arxiv.org/html/2504.12273v1` - Physics-based deferred shading for photo-realistic faces and full 3D objects with PBR and normal maps.
110. `https://www.jendrikillner.com/article_database/` - Database of modern graphics techniques (TSL in Three.js, tile shaders, spherical harmonics, real-time PBR optimization).

### Topic 12: Anti-flat 3D environments and balanced lighting (layers, fog, terrain)
111. `https://nathanpointer.com/blog/landscapes` - Rendering semi-realistic terrain in Three.js with displacement heightmaps and FogExp2 matching the horizon.
112. `https://app.cinevva.com/guides/landscape-generation-browser` - Browser 3D terrain with slope and altitude materials so ground never looks like a flat board.
113. `https://artofsoulburn.com/art_lessons/composition_fore_mid_back/composition_fore_mid_back.htm` - Three-plane composition (foreground, midground, background) for immersive depth.
114. `https://artsdot.com/en/articles/adc-misc-the-architecture-of-depth-a-guide-to-layered-composition-in-art-and-photography-en/` - Layered depth architecture separating near objects, mid structures, and far silhouettes with tonal contrast.
115. `https://www.virtualartacademy.com/atmospheric-perspective/` - Atmospheric perspective: distant objects lose contrast and shift toward sky or fog color.
116. `https://human.libretexts.org/Bookshelves/Art/Studio_Arts/Drawing_Perspectives_II_(Kennedy)/05%3A_Atmospheric_Perspective/5.05%3A_Understanding_Atmospheric_Perspective` - Gradation of color temperature, detail sharpness, and scale from foreground to horizon.
117. `https://www.tourboxtech.com/en/news/atmospheric-perspective.html` - Separating spatial layers with thin fog and layered light so the background does not flatten into the character.
118. `https://www.researchgate.net/publication/229139093_Intelligent_Lighting_for_Game_Environments` - Game environment lighting study: balancing key-to-fill so 3D form reads without going flat or too dark.
119. `https://www.researchgate.net/publication/220437171_Dynamic_Intelligent_Lighting_for_Directing_Visual_Attention_in_Interactive_3-D_Scenes` - Directing player attention with controlled, non-overexposed lighting contrast.
120. `https://www.co3dex.com/blog/image-based-lighting-1/` - Aligning skybox or HDRI, HemisphereLight, and DirectionalLight so environments feel alive and balanced.

### Topic 13: 3D shadows and anti-slop 2D component shadows
121. `https://www.joshwcomeau.com/css/designing-shadows/` - Josh W. Comeau's guide to realistic CSS shadows: consistent light direction, layering, color-matched shadows.
122. `https://tobiasahlin.com/blog/layered-smooth-box-shadows/` - Tobias Ahlin's technique of stacking several low-opacity box-shadows (0.03 to 0.08) with growing blur.
123. `https://boxshadowgenerator.co.uk/docs/layered-shadows/` - Why one thick box-shadow looks amateur, and using negative spread to focus shadow under components.
124. `https://zudo-css-wisdom.takazudomodular.com/docs/shadows-and-borders/layered-natural-shadows` - Common AI mistake of a single harsh box-shadow, and tokenized layered natural shadows.
125. `https://www.10bestdesign.com/blog/floating-elements-can-enhance-aesthetic-designs/` - Elevation psychology: shadow sharpness and size change with distance from the surface.
126. `https://dev.to/outriding/mastering-shadows-in-threejs-setup-configuration-and-optimization-39nn` - Three.js shadow guide: PCFSoftShadowMap, tight DirectionalLight frustum, bias and normalBias.
127. `https://learnopengl.com/Advanced-Lighting/Shadows/Shadow-Mapping` - Shadow mapping math, causes of shadow acne, and fixing it without peter panning.
128. `https://learnopengl.com/Guest-Articles/2021/CSM` - Cascaded Shadow Maps for sharp near-camera shadows across large environments.
129. `https://discourse.threejs.org/t/shadows-are-pixelated-boxy/27165` - Fixing boxy, pixelated Three.js shadows by narrowing the orthographic shadow camera.
130. `https://varun.ca/storybook-day/` - Production case study: directional shadows with soft contact shadows and hemisphere light for soft, clean, non-black shadows.

### Topic 14: Human communication and chat tone
131. `https://www.researchgate.net/publication/394487542_The_effects_of_human-like_social_cues_on_social_responses_towards_text-based_conversational_agents-a_meta-analysis` - Meta-analysis of how human social cues (relaxed, expressive language) affect comfort when chatting with AI agents.
132. `https://www.researchgate.net/publication/399739506_The_effect_of_non-facial_emojis-text_congruency_on_user_satisfaction_in_chatbot_interactions` - Matching emoji use to chat context as a paralinguistic cue.
133. `https://www.researchgate.net/publication/398705577_How_Can_Chatbots_Comfort_Humans_Exploring_the_Effects_of_Emoji_and_Identity_Cues_in_Emotional_Support` - How emoji in chat soften a robotic feel and build rapport.
134. `https://arxiv.org/html/1910.13793v1` - Time to Take Emoji Seriously: emoji add nuance to casual text without changing the technical substance.
135. `https://www.researchgate.net/publication/397682397_Linguistic_humanization_in_conversational_AI_a_systematic-narrative_review_of_humor_empathy_tone_and_imperfection_in_relational_communication` - Linguistic humanization in AI: light humor, local address forms (gw/lu), dropping bureaucratic jargon.
136. `https://journals.linguisticsociety.org/proceedings/index.php/PLSA/article/download/5653/5453/11804` - Eye-tracking study of how users read emoji in AI chat as tone indicators.
137. `https://pmc.ncbi.nlm.nih.gov/articles/PMC12647028/` - Limits of emoji: fine in chat, but separate from professional product interfaces that need vector icons.
138. `https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2025.1690007/full` - Emotion as Social Information (EASI) model in warm human-AI interaction.

### Topic 15: Mobile viewport ergonomics, anti-cramped phone screens
139. `https://blog.openreplay.com/improving-tap-targets-mobile-ux/` - Mobile touch target sizes, spacing buffers, and preventing rage taps on narrow screens.
140. `https://webdesignerindia.medium.com/thumb-zone-optimization-mobile-navigation-patterns-that-reduced-user-effort-by-55-9fbc54418b81` - Thumb-zone optimization: main controls in natural thumb reach without covering the center view.
141. `https://upslidedesignstudio.com/blogs/one-handed-mobile-ux-design-best-practices-for-better-mobile-apps` - One-handed mobile UX and simplified navigation on vertical screens.
142. `https://medium.com/@designstudiouiux/how-mobile-game-ui-ux-design-decides-player-retention-b14dcf0e8408` - Mobile game HUD rule: gameplay screens far calmer than menu screens (HUD at most 15 to 20% of the screen).
143. `https://www.researchgate.net/publication/372007065_Mobile_Game_Design_and_Ergonomics_a_necessary_combination` - Joystick and action button placement so thumbs do not cramp or hit the OS bottom edge.
144. `https://www.smashingmagazine.com/2016/09/the-thumb-zone-designing-for-mobile-users/` - Smashing Magazine's classic thumb zone guide for cards and controls on mobile.
145. `https://www.gperrucci.com/blog/css/responsive-design-clamp-min-max-dvh` - clamp(), min(), max(), and dvh so mobile UI scales proportionally and is never clipped by browser bars.
146. `https://medium.com/javascript-render/responsive-web-design-with-modern-css-clamp-min-max-and-dvh-41b7f457e161` - Fluid typography and fluid padding without size explosions on 360px screens.
147. `https://medium.muz.li/designing-for-mobile-a-deep-dive-into-responsive-ui-screen-densities-and-asset-scaling-f8766363ab08` - Handling phone pixel density, safe-area-inset, and HUD scaling.

### Topic 16: Dynamic 2D component shapes (beyond squircles)
148. `https://guide.coherent-labs.com/layout-assets-and-styling/graphics--shapes/advanced-ui-shapes/` - Advanced UI shapes with clip-path polygons (chamfered panels, hex nodes, slanted bars, radial wedges) and soft blending.
149. `https://m2.material.io/design/shape/applying-shape-to-ui.html` - Material Design shape system: cut corners, asymmetric radii, and pills to tell component roles apart.
150. `https://levelup.gitconnected.com/mastering-css-shapes-unique-layout-tricks-3348765b7a6a` - Modern CSS ways to escape the standard rectangle using clip-path and unconventional shapes.
151. `https://delvingdeveloper.com/posts/css-shapes-clip-path-creative-web-designs` - Responsive polygon shapes with percentages and calc() for dynamic cards and buttons.
152. `https://supercharge.design/articles/psychology-of-shapes-in-ui-design` - Shape psychology in UI: circles and capsules feel friendly, slants and chamfers feel fast and technical.
153. `https://fluer.com/blog/design/the-psychology-of-shapes-in-website-design` - Choosing component geometry that matches the world's character so the look is not generic.
154. `https://vsquad.art/blog/articles/understanding-shape-language-in-character-design/` - Cohesive shape language across 3D characters, environments, and 2D UI frames.

### Topic 17: Mood-based color psychology (anti orange bias)
155. `https://www.researchgate.net/publication/402568245_Color_theory_A_study_of_the_effect_of_color_palettes_on_the_player_in_a_game_world` - Research on how color palettes affect player emotion, from cozy and calm to tense and action.
156. `https://www.rmcad.edu/blog/the-psychology-of-game-art-how-colors-and-design-affect-player-behavior/` - Aligning 2D UI colors with the lighting mood and time of day of the 3D environment.
157. `https://www.artstation.com/blogs/francescos010/RLbKo/color-symbolism-in-game-design-using-color-psychology-to-elevate-player-experience` - Game color symbolism: emerald and sage for nature, cobalt and slate for tech, indigo and plum for mystery, crimson for danger.
158. `https://mockflow.com/blog/color-psychology-in-ui-design` - Choosing a base hue from industry psychology and user mood.
159. `https://medium.com/@lemapp09/mastering-ui-design-understanding-color-theory-fb0e3a6808b9` - Building adaptive game UI palettes from the world's main mood hue.
160. `https://medium.muz.li/the-impact-of-color-psychology-in-user-experience-design-63496de95607` - Avoiding a single-color bias and matching warm or cool temperature to the target emotion.

### Topic 18: Advanced 2D and 3D motion (origin-aware, FLIP, kinematics, overlap, game feel)
161. `https://emilkowal.ski/ui/good-vs-great-animations` - Emil Kowalski on good versus great animation: origin-aware transforms, strong custom easing, clip-path transitions.
162. `https://emilkowal.ski/ui/great-animations` - 60fps animation architecture: interruptible transitions over rigid keyframes, GPU-composited properties only.
163. `https://agenticskills.io/skills/emil-design-eng` - Invisible details in UI engineering: start scale at 0.92+, instant press feedback, opening choreography.
164. `https://aiuxplayground.com/skills/design-motion-principles` - Shared layout animations and the FLIP principle for active indicators and layout changes.
165. `https://rebusfarm.net/blog/follow-through-and-overlapping-action-the-animation-principle-that-prevents-stiff-motion` - Follow-through and overlapping action: why body parts must not move and stop together.
166. `https://www.animationmentor.com/blog/tutorial-animate-overlap-and-follow-through/` - Applying phase lag along joint chains (shoulder, elbow, wrist; hip, knee, ankle) for organic swing.
167. `https://medium.com/frame-by-frame/anticipation-follow-through-overlapping-action-and-secondary-action-f80069aba725` - Combining anticipation, secondary motion, and follow-through on 3D characters.
168. `https://www.foxrenderfarm.com/news/follow-through-and-overlapping-action/` - Multi-layer procedural animation and secondary spring simulation for body parts and accessories.
169. `https://egmatic.com/blog/how-to-make-your-game-feel-good` - Game feel and juice: hit-stop (40 to 80ms), proportional camera shake, squash and stretch, knockback.
170. `https://www.tdespins.com/blog/game-feel` - What separates amateur from professional games: micro responsiveness to every input.
171. `https://arxiv.org/html/2208.06155v3` - Scientific study of impact feel in action games: hit-stop sync, measured shake, visual feedback and satisfaction.
172. `https://www.artemisiacollege.com/feeds/blog/secondary-motion-animation-example` - Practical secondary motion examples so characters and interactive objects always feel alive.
173. `https://www.animationmentor.com/blog/follow-through-and-overlapping-action-the-12-basic-principles-of-animation/` - Newton's inertia in animation: the main mass leads and the extremities follow with delay.
174. `https://uichemy.com/design-skills/emil-animate/` - 12 modern UI animation recipes for state transitions, staggered card entrances, and micro feedback.
175. `https://emilkowal.ski/ui/you-dont-need-animations` - When to animate richly and when to keep interactions instant for high-frequency work.

### Topic 19 (new): Audio that sounds good: Web Audio envelopes, UI and game sound design, procedural sound, reverb, music
176. `https://developer.mozilla.org/en-US/docs/Web/API/AudioParam/setTargetAtTime` - MDN: setTargetAtTime for exponential decay, release, and fades; set timeConstant to about a third of the duration to reach roughly 95%.
177. `https://www.w3.org/TR/WebAudio/` - W3C Web Audio API spec: parameter automation for envelopes, fades, and filter sweeps, plus routing through convolution reverb and a final compressor.
178. `https://www.mintlify.com/raphaelsalaja/userinterface-wiki/technical/web-audio-api` - Procedural UI sounds from oscillators and filtered noise: click, pop, success arpeggio, exponential envelopes, try-catch safety, resuming the context on first interaction.
179. `https://violetrecording.com/how-to-design-ui-sounds/` - UI sound principles: short cues (30 to 150ms taps), pleasant mid-high range, one tonal family, matched loudness, a tactile layer under the synth blip, user mute.
180. `https://violetrecording.com/sound-design-for-video-games/` - Game sound design: variation, layering by state or surface, round-robin takes combined with pitch and volume randomization.
181. `https://www.asoundeffect.com/?p=123022` - Controlling repetition, randomization, and frequency content in game audio; the idea of a per-sound nuisance score and layered solutions.
182. `https://blog.criware.com/index.php/2017/01/16/atomcrafts-randomization-features/` - Randomizing pitch, volume, EQ, and panning to get near-infinite variation from one asset.
183. `https://claudeskills.info/skills/curiositech/some_claude_skills/sound-engineer/` - Procedural footsteps (impact burst plus surface texture plus debris plus surface EQ), CPU budget for audio, and when to use procedural versus samples.
184. `https://vbn.aau.dk/en/publications/footstep-sounds-synthesis-design-implementation-and-evaluation-of` - Research on footstep synthesis with physically inspired models and parametric control over surface, shoe, and walker.
185. `https://soundlab.cs.princeton.edu/publications/billsgait.pdf` - Perry Cook's parametric synthesis of walking sounds using exponentially decaying noise-burst particles and extracted control envelopes.
186. `https://agentskills.so/skills/dannyjpwilliams-ui-sound-design-skill-ui-sound-design` - Mapping subjective words (warmer, softer, snappier) to synthesis parameters; volume safety limits; exponential ramps sound natural, linear ramps sound mechanical.
187. `https://claudeskills.info/skills/guia-matthieu/clawfu-skills/ux-sound-design/` - UX audio methodology: function first, duration ranges, a loudness hierarchy, one tonal center, and pairing sound with visual feedback.
188. `https://www.github.com/logue/Reverb.js` - Generating convolution reverb impulse responses from decaying filtered noise, with decay, filter, and wet and dry controls, plus an iOS wake-up trick.
189. `https://app.cinevva.com/tutorials/tone-js-game-audio` - Tone.js for game audio: soft synths, filter plus reverb chains, rate limiting, user-gesture start, and music that follows gameplay energy.
190. `https://killsometime.com/killsometime/dist/games/mazeball/js/audio.js` - A shipped browser game using fully synthesized effects and a calm overlapping-chord pad rolled off with a lowpass so it never sounds harsh.
191. `https://sounddesign.irpr.agency/solutions/ui-sounds-annoying/` - Why users mute app sounds (too sharp, long, or frequent) and how short, soft, frequency-balanced cues fix it.

### Topic 20 (new): 3D pixel ratio and mobile performance
Note: these sources suggest caps near 1.5. Divine-Argon deliberately locks mobile 3D web and games at 1.3 (desktop 1.0 to 1.6) and never trades away shadow, antialiasing, or model quality for speed.
192. `https://threejs.org/manual/en/responsive` - Three.js manual: pixel ratio versus display size, mobile GPU limits, and capping internal resolution.
193. `https://discourse.threejs.org/t/hidpi-fractional-scaling-performance-pitfalls-and-best-practices/87114` - HiDPI and fractional scaling pitfalls, and clamping devicePixelRatio to about 1.5 for fill-rate-bound scenes.
194. `https://discourse.threejs.org/t/animate-low-performance-on-mobile-with-window-devicepixelratio-resize/23628` - Fractional pixel ratios between 1.1 and 1.5 balance sharpness and speed on mobile.
195. `https://agentskills.so/skills/ovachiever-droid-tings-threejs-graphics-optimizer` - Mobile-first Three.js optimization: cap pixel ratio at 1.5 on mobile, drop MSAA, fewer lights, simpler geometry.
196. `https://smithery.ai/skills/feliperyba/dev-performance-performance-basics` - Frame budget breakdown for 60fps, limiting DPR, adaptive quality, and disposing resources.

### Topic 21 (new): Ambient 3D particles for environments (fireflies, dust, leaves, embers) with restraint and performance
197. `https://github.com/1391819/interactive-low-poly-environment` - Low-poly Three.js world with stones, grass, trees, clouds, a campfire, and firefly colonies built from custom shader materials and soft glow.
198. `https://discourse.threejs.org/t/modernstillness-interactive-3d-fireplace-environment/87701.md` - Case study: dust motes and wind-driven leaves with lifespan and fade-out using InstancedMesh, plus a performance manager for desktop and mobile.
199. `https://threejs-journey.com/lessons/adding-details-to-the-scene` - Fireflies built as Points on a BufferGeometry with random positions, then refined with size attenuation.
200. `https://skillselion.com/skills/bbeierle12/skill-mcp-claude/particles-gpu` - GPU particle approaches: Points, InstancedMesh, and custom shaders, with transparent, depthWrite off, and additive blending settings.
201. `https://www.wayline.io/blog/particle-effect-apocalypse-avoiding-visual-excess` - Why excessive particles hurt performance and memory, and the case for restraint so effects complement the rest of the visuals.
202. `https://developers.snap.com/lens-studio/features/graphics/particles/vfx-editor/vfx-graph-optimization` - VFX optimization: start with fewer particles, do not inflate counts to compensate for faint ones, and kill particles you do not need.
203. `https://starloopstudios.com/?p=45233` - Mobile VFX balance: LOD for effects, simplifying particles by adjusting color, shape, and movement instead of count, and toggleable options.
204. `https://playbooks.com/skills/omer-metin/skills-for-antigravity/vfx-realtime` - Real-time VFX principles: effects must read clearly, restraint is power, timing and anticipation matter, and watch overdraw.
205. `https://www.shadcn.io/background/sparkles` - Particle density guidance: about 50 for subtle ambience, and counts above roughly 500 can hurt older and mobile devices.
206. `https://elixrsim.notion.site/Particles-for-Unity-AR-304555cb0f0e8014b517c3314a3ddf19` - Lightweight particle practices: small short-lived particles, max count around 50 to 200, no collisions or lights, subtle noise, less overdraw.

### Topic 22 (new): Environment animation (wind sway, ambient motion, living worlds)
207. `https://github.com/tuxalin/vegetation-shader` - Procedural wind for vegetation: trunk bending, foliage animation weighted per branch, phase variation, global wind settings, and LOD variants.
208. `https://80.lv/articles/book-of-the-dead-using-megascans-setting-up-wind-and-more/` - Vertex-shader wind with hierarchy pivot, single pivot, and procedural modes, using vertex color channels to store per-vertex wind weights.
209. `https://discussions.unity.com/t/realtime-wind-animation-for-lowpoly-leaves/675363` - Wind on low-poly leaves is a vertex shader task, with per-vertex frequency and magnitude stored in vertex data and noise for variation.
210. `https://www.gamedev.net/topic/686315-good-formula-for-swaying-grass/?st=20` - Swaying grass formulas: zero sway at the base and more at the tips, a shared wind gradient or wind texture sampled by position, simpler animation at distance.
211. `https://www.rmcad.edu/blog/the-art-of-environmental-effects-bringing-game-worlds-to-life/` - Environmental effects bring worlds alive: varied timing, spacing, and rhythm, particles that sell place and material, and small unscripted micro-events.
212. `https://www.brokenroadsgame.com/dev-blog/breathing-life-into-our-environments` - Dev blog on ambient life: creatures reacting to light and the player, wind through cloth and vegetation, and drifting dust or mist.
213. `https://create.roblox.com/docs/en-us/resources/the-mystery-of-duvall-drive/develop-a-moving-world` - Moving-world case study: ambient tree movement, clouds moving at different speeds that overlap, and reactive objects for immersion.
214. `https://moddex.gg/mod/tactile` - Catalog of small ambient effects: dust motes, embers rising and fading, ripples, drips, and breath puffs that add life cheaply.

### Topic 23 (new): Detailed environment props and set dressing (hero, unique, modular, dressing)
215. `https://openskillindex.com/skills/vibeforge1111-vibeship-spawner-skills-environment-art` - Environment art tiers (hero, unique, modular, dressing), value contrast by importance, and modular grid thinking.
216. `https://rocketbrush.com/blog/game-environment-art-types-workflow-and-production-guide` - Game environment art production guide covering props and set dressing, modular kits, visual direction, and planning scope.
217. `https://www.claudepluginhub.com/skills/arjun988-blender-skills/environment-artist` - Set dressing with prop density rules, narrative clusters, and readability constraints, plus modular kit workflow and style variants.
218. `https://skillselion.com/skills/omer-metin/skills-for-antigravity/environment-art` - Hero asset hierarchy with 1 to 2 custom focal pieces, higher texel density for hero assets than for background, and modular dressing.

### Topic 24 (new): Layout, visual hierarchy, and spacing
219. `https://oreilly.com/library/view/designing-interfaces-3rd/9781492051954/ch04.html` - Designing Interfaces ch. 4: visual hierarchy, visual flow, grid alignment, and Gestalt grouping for clean screen layouts.
220. `https://cieden.com/book/sub-atomic/spacing/adapting-spacing-best-practices` - Spacing best practices: hierarchy through spacing, grid systems, macro and micro negative space, proximity, and line spacing of about 150%.
221. `https://www.visily.ai/?p=91318` - Visual design principles overview: hierarchy, alignment, proximity, white space, rhythm, and 4-point or 8-point spacing systems.
222. `https://app.uxcel.com/lessons/examples-755` - UI principles with examples: unity, proximity, alignment, movement, and figure-ground such as dimming a background behind a modal.
223. `https://www.ui-skills.com/skills/jakubkrehel/better-layout` - Layout communicates structure: grouping with space over separators, alignment edges, reading order, progressive disclosure, adaptive layouts.

### Topic 25 (new): Font pairing and typographic hierarchy
224. `https://madegooddesigns.com/font-pairing-guide/` - Font pairing guide: contrast with harmony, clear role per level, and locking a type scale for headings, body, and captions.
225. `https://madegooddesigns.com/typography-design-principles/` - Typography principles: clear hierarchy, legibility, restraint in the number of fonts, modular type scales, line length, and leading.
226. `https://pangrampangram.com/blogs/journal/how-to-pair-fonts` - How to pair fonts: create contrast through weight and scale so a clear hierarchy appears.
227. `https://shop.smashingmagazine.com/2010/11/best-practices-of-combining-typefaces/` - Combining typefaces: give each face a distinct role and use clear weight contrast so headings keep authority over body text.
228. `https://www.adobe.com/express/learn/blog/best-font-pairings` - Font pairing is about contrast, harmony, and hierarchy, with a pairing chart and practical examples.
229. `https://piktochart.com/blog/font-pairing-for-bold-headlines/` - Bold-headline pairing: contrast in weight, width, style, or size, but with a shared anchor so contrast does not become noise.
230. `https://pangrampangram.com/blogs/journal/free-font-pairing-vol-3` - Serif and sans pairing: choose a leading font so the two do not compete, and use weight contrast between title and body.
231. `https://blog.prototypr.io/the-no-nonsense-guide-to-font-pairing-64e4ead688a6` - Squint test for pairings: if everything blurs into one blob, add contrast so the hierarchy stays obvious.
232. `https://elementor.com/blog/font-pairing-chart/` - Font pairing chart with ready heading and body combinations and the principle of contrast without conflict.

Made by: Zhawoilah-id
