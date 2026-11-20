# 🚀 Ultimate LLM Single-File HTML Stress-Test Prompts

![Format](https://img.shields.io/badge/Output-Single_HTML_File-0ea5e9?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-10b981?style=for-the-badge)
![Benchmarks](https://img.shields.io/badge/Benchmarks-6_Mega_Prompts-8b5cf6?style=for-the-badge)

مجموعة احترافية من **6 اختبارات متقدمة (Mega-Prompts)** مصممة لفحص القوة الحقيقية لنماذج الذكاء الاصطناعي في التفكير المعماري العميق، الرياضيات، الفيزياء، التصميم البصري، وهندسة الصوت البرمجية — بحيث يُطلب من النموذج بناء كل مشروع بالكامل داخل **ملف HTML واحد مستقل** بدون أي مكتبات أو صور أو ملفات صوتية خارجية.

> [!TIP]
> **طريقة الاستخدام والنسخ المباشر:**
> 1. اضغط على **أيقونة النسخ (📋)** الموجودة تلقائياً في الزاوية العلوية اليمنى لأي مطالبة بالأسفل.
> 2. الصقها في النموذج (يُفضّل تفعيل وضع التفكير العميق **Thinking Mode** ورفع حد التوكين **Max Output Tokens** لأعلى قيمة متاحة).
> 3. احفظ الكود الناتج بامتداد `.html` وافتحه مباشرة في متصفحك!

---

## Table of Contents

| # | Benchmark Name | الوصف | Core Skills Tested | Direct Link |
| :-: | :--- | :--- | :--- | :-: |
| **1** | **2D Animated Short Film** | فيلم كرتون قصير ثنائي الأبعاد (قصة + تحريك + صوت) | Canvas Rigging, Keyframes, Web Audio API | [Go to Prompt ↓](#1-2d-animated-short-film) |
| **2** | **Soft-Body & Cloth Physics Sandbox** | مختبر فيزياء الأجسام المرنة والأقمشة القابلة للتمزيق | Verlet Integration, Constraints, 2D Math | [Go to Prompt ↓](#2-soft-body-and-cloth-physics-sandbox) |
| **3** | **Awwwards-Style Luxury Landing Page** | صفحة هبوط تفاعلية فاخرة بمستوى جوائز التصميم | UI/UX, Motion Design, SVG, 3D Tilt | [Go to Prompt ↓](#3-awwwards-style-luxury-landing-page) |
| **4** | **Classic 3D Raycaster Engine** | محرك ثلاثي الأبعاد كلاسيكي من الصفر (أسلوب Doom) | DDA Raycasting, Z-Buffer, Procedural Textures | [Go to Prompt ↓](#4-classic-3d-raycaster-engine) |
| **5** | **Mini Web OS** | نظام تشغيل مصغر متكامل داخل المتصفح | Window Manager, Virtual FS, State Architecture | [Go to Prompt ↓](#5-mini-web-os) |
| **6** | **Isometric City Builder** | لعبة بناء مدن بمنظور أيزومتري ومحاكاة مرورية | Isometric Projection, Painter's Algo, Economy | [Go to Prompt ↓](#6-isometric-city-builder) |

---

## 1. 2D Animated Short Film

**الوصف:** فيلم كرتوني قصير متكامل القصة (50 ثانية / 4 مشاهد) مع تحريك مفصلي للشخصية، وحركة كاميرا سينمائية، وموسيقى ومؤثرات صوتية مولدة برمجياً عبر `Web Audio API`، ومشغل فيديو تفاعلي.  
**اسم الملف المقترح للحفظ:** `orbi-short-film.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as a master creative coder, 2D animator, and Web Audio sound designer. Think deeply and architecturally before writing code, then create a breathtaking, fully choreographed **2D Animated Short Film** that runs entirely inside a **single standalone `.html` file** (HTML + CSS + vanilla JS) with **ZERO external dependencies, libraries, images, or audio files**.

### Film Concept & Storyboard: "ORBI & THE LAST BLOOM" (Duration: ~50 seconds, 4 seamless scenes)
- **Scene 1 (0s–14s) — The Silent Neon Rain:** A moody, rainy night in a ruined futuristic city rendered with multi-layer parallax scrolling, distant flickering neon signs, falling rain streaks, and animated ground puddle splashes. Introduce **Orbi**, an adorable articulated 2D robot (expressive glowing eyes that blink and shift emotion, tilting head, bobbing antenna, hovering thruster/legs, and a volumetric flashlight cone) wandering sadly while scanning the ruins.
- **Scene 2 (14s–26s) — The Discovery:** Orbi stops suddenly upon detecting a warm golden glow in the debris. Execute a smooth cinematic camera zoom-in to reveal a lone bioluminescent flower swaying gently in the wind. Orbi’s eyes morph into wide joyful arcs, emitting cute animated spark/heart glyphs and tilting its head in wonder.
- **Scene 3 (26s–38s) — The Storm:** The storm intensifies—wind gusts slant the rain heavily, lightning flashes illuminate dramatic silhouettes with thunderclaps. Orbi heroically deploys an unfolding energy umbrella / shields the fragile bloom with its body while glowing magical pollen particles swirl defensively around them.
- **Scene 4 (38s–50s) — Dawn of Hope:** The storm clears as a stunning sunrise gradient transforms the entire scene's lighting from deep cyan/indigo to warm gold, coral, and amber. The flower fully blooms, releasing luminous floating seeds into the morning sky. The camera slowly pulls back (zoom out) into a scenic wide shot and fades in a stylized cinematic "THE END" title card.

### Strict Technical & Artistic Requirements:
1. **High-DPI Canvas Animation:** Render on HTML5 Canvas with crisp `devicePixelRatio` scaling, cinematic widescreen letterboxing, smooth easing functions (cubic/elastic/back easing), keyframe-driven character rigging, and `requestAnimationFrame` with clamped `deltaTime`.
2. **100% Procedural Audio (`Web Audio API`):** Synthesize a layered, reactive soundtrack and SFX: continuous filtered-noise rain ambience, thunder rumbles, emotional dynamic synth music (melancholic minor pad -> tense storm pulse -> uplifting warm major arpeggio), and expressive procedural robot chirps/beeps synced to Orbi's reactions. Include a stylish cinematic "Play Film" overlay at startup to cleanly unlock Web Audio.
3. **Theater Player UI:** Translucent cinema control bar at the bottom featuring Play/Pause, an interactive Timeline Scrubber (allowing smooth seeking to any timestamp), Scene Jump buttons (1–4), Mute/Volume toggle, Replay button, and toggleable animated cinematic subtitles.
4. **Completeness:** Take full advantage of your context and output length. Write 100% of the code cleanly from start to finish with NO truncation, NO placeholders, NO `// TODO` comments, and ZERO console errors.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## 2. Soft-Body and Cloth Physics Sandbox

**الوصف:** محرك فيزيائي ثنائي الأبعاد مبني من الصفر (Verlet Integration) لمحاكاة الأقمشة القابلة للتمزيق، والأجسام الهلامية المرنة، والسلاسل، مع أدوات تفاعلية (سحب، مقص ليزر، انفجارات، ثقب أسود) والتحكم بالجاذبية والرياح والزمن البطيء.  
**اسم الملف المقترح للحفظ:** `physics-sandbox.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as a senior physics engine architect and creative technologist. Think deeply about numerical stability and mathematical accuracy before writing code, then build a production-grade **2D Soft-Body & Tearable Cloth Physics Sandbox** from scratch inside a **single standalone `.html` file** with **ZERO external libraries or dependencies** (do NOT use Matter.js or any external physics engine).

### Core Physics Engine Requirements:
1. **Custom Verlet Integration Engine:** Build a rock-solid 2D Verlet integrator running at 60 FPS with fixed-timestep sub-stepping and multi-iteration constraint relaxation (6–10 iterations per frame) to prevent explosions, jitter, or NaN instabilities. Support gravity, air drag, boundary restitution/friction, and circle-to-circle / circle-to-point collisions.
2. **Rich Spawnable Physics Objects:**
   - **Tearable Cloth:** Interconnected spring-mesh curtains/nets with structural and shear constraints that realistically billow in the wind and snap cleanly when tension exceeds a customizable tear threshold.
   - **Soft-Body Jelly Cubes & Squishy Orbs:** Cross-braced elastic polygons/shapes that deform, squish, wobble, and bounce convincingly upon impact.
   - **Heavy Chains, Ropes, & Rigid Steel Balls** that interact physically with cloth and soft bodies.
3. **Interactive Mouse Toolbox:**
   - **Grab & Fling:** Pick up and throw any vertex or body with realistic velocity inheritance.
   - **Laser Cutter / Slice:** Drag across the canvas to draw a glowing cut trail that severs any cloth/rope constraints intersecting the path (using exact 2D line-segment intersection math) with tiny spark particles.
   - **Shockwave Explosion:** Click anywhere to trigger a radial physical impulse with an expanding visual shockwave ring and sparks.
   - **Black Hole (Gravity Well):** Hold mouse down to create a swirling glowing vortex that pulls and orbits all nearby physics vertices inward.
   - **Pin / Unpin Tool:** Click vertices to toggle fixed anchor points in midair.
4. **Visual Polish & Control UI:**
   - Sleek dark engineering/neon-blueprint aesthetic with crisp Retina/DPI canvas rendering.
   - **Dynamic Stress Visualization:** Color-code cloth/spring links dynamically in real time based on physical strain (cool cyan at rest -> amber under load -> glowing crimson right before tearing).
   - Modern glassmorphic HUD panel with interactive sliders for **Gravity**, **Wind Turbulence** (organic gusting waves), **Time Scale (Slow-Motion)**, **Stiffness**, and **Tear Threshold**.
   - One-click **Presets**: "Giant Tearable Curtain", "Suspension Bridge & Boulders", "Jelly Drop Pit", and "Wrecking Ball vs. Cloth".
   - Live telemetry readout (FPS, active points, active constraints), Pause/Step toggle, and Reset button.
5. **Completeness:** Output the ENTIRE, complete, self-contained HTML file with no shortcuts, placeholders, or runtime errors.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## 3. Awwwards-Style Luxury Landing Page

**الوصف:** صفحة هبوط تفاعلية فائقة الفخامة لشركة سياحة فضائية، تشمل خلفية فضائية ثلاثية الأبعاد تستجيب لحركة الماوس والتمرير، ومؤشر ماوس مغناطيسي، ومخطط SVG تفاعلي للمركبة، ومصمم رحلة يولّد بطاقة صعود رقمية ثلاثية الأبعاد.  
**اسم الملف المقترح للحفظ:** `aether-voyages.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as an Awwwards Site-of-the-Day creative director, UI/UX designer, and front-end engineer. Think deeply about layout harmony, typography, motion choreography, and tactile micro-interactions, then build an extraordinary **Luxury Interactive Landing Page** for a futuristic orbital & deep-space tourism brand named **"AETHER VOYAGES"** inside a **single standalone `.html` file**. Use vanilla HTML, CSS, and JavaScript with **ZERO external JS/CSS libraries and ZERO external images** (you may optionally include 1–2 Google Fonts like `Syne` and `Space Grotesk` with clean fallback fonts).

### Visual Direction & Interactive Craft:
1. **Obsidian Luxury Aesthetic:** Deep space obsidian palette (`#05060b`), champagne gold (`#d8b467`), luminous cyan accents, subtle animated film-grain texture overlay, crisp 1px glowing borders, and glassmorphic surfaces with mouse-tracking radial spotlight hover effects.
2. **Interactive 3D-Projected Canvas Background:** A silky-smooth full-viewport HTML5 Canvas rendering a 3D starfield and subtle volumetric nebula particles that react smoothly to mouse parallax and accelerate into subtle "warp-speed streaks" dynamically linked to the user's scroll velocity.
3. **Custom Magnetic Cursor & Micro-Interactions:** A sleek custom trailing cursor ring + center dot that scales and morphs over links/cards, magnetic attraction on primary CTA buttons, smooth scroll progress bar in the sticky navbar, and choreographed `IntersectionObserver` scroll-reveal animations.

### Complete Page Architecture:
1. **Monumental Hero Section:** Staggered kinetic headline reveal, sleek subtitle, magnetic primary CTA button, live animated telemetry stat counters (Altitude, Flights Completed, Zero-G Duration), and an animated scroll cue.
2. **Interactive Spacecraft Blueprint Section:** A finely detailed, multi-layered inline **SVG technical blueprint** of the *Aether-IX* starliner featuring **5 pulsing interactive hotspots** (Fusion Drive, 360° Observatory Dome, Zero-G Suites, Centrifuge Ring, Command Deck). Clicking or hovering any hotspot illuminates that SVG segment and smoothly updates a detailed technical telemetry card.
3. **Interactive Mission Configurator & 3D Holographic Boarding Pass:**
   - Users can type their Passenger Name, select a Destination (*Orbital Sanctuary*, *Lunar Mare*, or *Europa Clipper*), select Cabin Class (*Horizon Suite*, *Sovereign Deck*, *Zero-G Penthouse*), and choose Launch Window.
   - Real-time animated rolling numbers calculate Mission Cost, Travel Time, and Orbit Distance.
   - Simultaneously generates a bespoke **Digital Space Boarding Pass** displaying the user's name, mission code, procedural SVG barcode, and an interactive **3D mouse-tilt perspective effect with a shimmering holographic foil sheen**.
4. **Curated Mission Timeline & Editorial Footer:** Clean vertical timeline showing pre-flight training to splashdown, plus a refined minimalist footer.
5. **Responsiveness & Completeness:** Must look and work flawlessly on both desktop and mobile viewports. Write 100% of the HTML, CSS, and JS in full with no placeholders, no truncated styles, and zero errors.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## 4. Classic 3D Raycaster Engine

**الوصف:** محرك تصويب ثلاثي الأبعاد كلاسيكي مبني بالرياضيات الصرفة (DDA Raycasting + Z-Buffer) بدون Three.js أو WebGL، مع خامات جدران مولدة برمجياً، وأبواب منزلقة، وأعداء بذكاء اصطناعي، وخريطة مصغرة، ومؤثرات صوتية برمجية.  
**اسم الملف المقترح للحفظ:** `raycaster-3d.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as a veteran graphics programmer and retro-modern game engine architect. Think deeply about 3D projection mathematics, DDA raycasting, and Z-buffering before writing code, then build a complete, playable **First-Person 3D Raycasting Engine & Sci-Fi Shooter Game (Doom / Wolfenstein style)** from scratch inside a **single standalone `.html` file** using pure HTML5 2D Canvas and vanilla JavaScript — **ZERO 3D libraries (no Three.js, no WebGL), ZERO external images, and ZERO external audio files**.

### Engine & Graphics Requirements:
1. **True DDA Raycaster Engine:** Implement a high-speed Digital Differential Analyzer (DDA) raycasting renderer drawing textured vertical wall strips onto an HTML5 Canvas with fisheye correction, directional side-shading (N/S vs E/W lighting), and smooth distance-based atmospheric fog into darkness.
2. **Procedural 64×64 Pixel Textures:** Generate crisp, detailed textures procedurally in JavaScript at startup (sci-fi riveted metal bulkheads, hazard-stripe blast doors, illuminated computer panels, mossy stone walls, and glowing exit portals) rendered cleanly onto walls without external image files.
3. **Depth-Buffered 2D Sprites (1D Z-Buffer):** Maintain a per-column depth buffer so 3D-projected sprites properly occlude behind walls. Procedurally draw sprite graphics for:
   - **2–3 Distinct Enemy Types** (e.g., Patrol Drone, Heavy Mech Trooper) with idle, attacking, hit-flash, and defeat animations.
   - **Interactive Pickups & Props:** Glowing Medkits, Energy Cells, and flickering Energy Barrels/Torches.
4. **Interactive World & Gameplay:**
   - Multi-room level layout with **smoothly sliding doors** (press `E` to open) and a locked exit portal requiring a Keycard pickup.
   - **First-Person Weapon Viewmodel:** Procedurally drawn sci-fi Plasma Blaster / Shotgun centered at the bottom with smooth walking bobbing, shooting recoil kick, animated muzzle flash, and momentary dynamic room brightness flash when firing!
   - **Enemy AI:** Enemies detect the player via line-of-sight raychecks, pursue around corners, fire projectiles/attacks, and react with damage flash + particle bursts.
5. **Procedural Audio (`Web Audio API`):** Synthesize punchy sci-fi gunshots, enemy laser hits, hydraulic sliding doors, rhythmic footsteps, pickup chimes, keycard alerts, and a subtle dark ambient sci-fi hum.
6. **Controls & HUD:**
   - Support BOTH **Pointer Lock Mouse Look** (click canvas to lock mouse, ESC to release) AND smooth keyboard controls (`WASD` move/strafe, `Arrow Left/Right` turn, `Left Click` or `Space` shoot, `E` open doors).
   - Crisp retro-modern HUD: **Live Top-Down Minimap** displaying walls, real-time raycast field-of-view cone, enemies, and keycard; Health/Shield bar, Ammo counter, Score, and Keycard status.
   - Clean Start Screen (with controls briefing), Victory Screen, and Game Over Screen with instant Restart.
7. **Completeness:** Write 100% of the complete, optimized, bug-free code in a single HTML file with zero placeholders or truncation.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## 5. Mini Web OS

**الوصف:** نظام تشغيل سطح مكتب متكامل داخل المتصفح ("NovaOS") مع شاشة إقلاع، ونظام نوافذ حقيقي (سحب/تكبير/تصغير)، ونظام ملفات افتراضي محفوظ، و5 تطبيقات تعمل فعلياً (سطر أوامر Terminal، مستكشف ملفات ومحرر نصوص، برنامج رسم Paint، آلة حاسبة علمية، ولعبة كلاسيكية + إعدادات).  
**اسم الملف المقترح للحفظ:** `nova-os.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as a principal front-end systems engineer and UI designer. Think deeply about state management, window stacking, and modular architecture before writing code, then build a remarkably polished, interactive **Mini Desktop Operating System ("NovaOS")** running entirely inside a **single standalone `.html` file** with **ZERO external libraries, frameworks, images, or audio files**.

### OS Shell & Window Manager Requirements:
1. **Boot Sequence & Desktop Experience:**
   - Brief, sleek animated boot splash screen (~1.5s, clickable to skip) leading into a full-screen desktop with a procedural startup chime (`Web Audio API`, muted gracefully if blocked).
   - **Dynamic Procedural Wallpapers:** Built-in animated Canvas/CSS wallpapers (e.g., Aurora Nebula, Geometric Grid, Midnight Ocean) switchable live in Settings.
   - **Taskbar / Dock & System Tray:** Glassmorphic dock with app icons, active-app indicators, minimized window previews/restore, searchable Start Menu / App Launcher, live digital clock & date, audio mute toggle, and Quick Settings popover.
   - **Full Window Manager:** True multi-window support with smooth dragging by title bar, resizing via window edges/corners, Minimize, Maximize/Restore (including double-click title bar), Close, proper Z-index focus management, and custom desktop right-click context menu.
2. **Virtual File System (`localStorage` persisted):**
   - Implement a shared in-memory + `localStorage`-backed virtual file system (folders like `/home`, `/documents`, `/notes`, `/pictures`) pre-populated with realistic welcome files, shared seamlessly across the Terminal, File Explorer, and Text Editor!
3. **5 Fully Functional Built-in Applications:**
   - **1. Nova Terminal (CLI):** Real command parser supporting `help`, `ls`, `cd`, `pwd`, `cat <file>`, `touch <file>`, `mkdir <dir>`, `rm <file>`, `echo <text> > <file>`, `clear`, `date`, `whoami`, `neofetch` (with colored ASCII logo & system specs), and a `matrix` rain easter egg!
   - **2. File Explorer & Notes Editor:** Browse folders, create new files/folders, delete items, and double-click any text file to open, edit, and save it in a clean Notes/Code Editor app.
   - **3. Canvas Paint Studio:** Functional drawing app with freehand brush, line, rectangle, circle, eraser, color swatches, brush size slider, undo history, clear canvas, and "Download PNG" export button.
   - **4. Scientific Calculator:** Crisp responsive calculator supporting mouse and keyboard input, calculation history log, and standard + scientific operations (`sin`, `cos`, `sqrt`, `^`, `%`).
   - **5. Classic Arcade Game (Minesweeper OR Snake):** A complete, super-clean playable mini-game inside its own OS window with score tracking and restart button.
   - *(Plus a **Settings App** to change live animated wallpapers, accent color themes, and system sound effects.)*
4. **Completeness:** Write 100% of the complete, clean, bug-free single-file HTML application with zero placeholders, zero truncation, and rock-solid window interaction handling.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## 6. Isometric City Builder

**الوصف:** لعبة بناء مدن متكاملة بمنظور أيزومتري حقيقي (2:1) مع طرق ذكية تتصل تلقائياً، ومبانٍ تتطور بمرور الوقت، وحركة مرور سيارات ذاتية، ودورة ليل ونهار تضيء فيها النوافذ والمصابيح، واقتصاد حي وحفظ تلقائي.  
**اسم الملف المقترح للحفظ:** `isometric-city.html`

📋 **للنسخ المباشر، اضغط أيقونة النسخ أعلى يمين المربع:**

```text
Act as an expert game developer specializing in isometric engines and simulation games. Think deeply about isometric coordinate math, depth sorting, and game economy balancing before writing code, then create a gorgeous, deeply playable **Isometric City Builder Game** inside a **single standalone `.html` file** using HTML5 Canvas and vanilla JavaScript with **ZERO external libraries, spritesheets, or audio files**.

### Rendering & Isometric Engine Requirements:
1. **True 2:1 Isometric Canvas Engine:** Crisp `devicePixelRatio` rendering with exact screen-to-grid and grid-to-screen isometric math, proper Painter’s Algorithm depth sorting (`x + y`), smooth camera panning (right-click/middle-click drag or `WASD`/Arrow keys), and smooth mouse-wheel zooming centered on the cursor.
2. **Procedural Isometric Art & World:**
   - Procedurally generate an attractive 24×24 (or larger) island/valley map with varied grass elevation/tints, animated sparkling water river/shoreline, and swaying clusters of trees.
   - Draw detailed, shaded multi-story isometric buildings procedurally on Canvas (roofs, wall shading, windows, solar panels, trees in parks, water towers, pop-in construction bounce animation).
   - **Smart Auto-Tiling Roads:** Roads automatically connect seamlessly into straight segments, 90° corners, T-junctions, and 4-way intersections with lane markings!
3. **Dynamic Day/Night Cycle & Ambient Life:**
   - Smooth continuous Day/Night lighting cycle shifting ambient sky colors and shadow directions; at dusk/night, building windows, streetlights, and vehicle headlights automatically illuminate with warm glowing light!
   - **Autonomous Traffic Simulation:** Tiny animated cars spawn and drive smoothly along connected road networks, turning realistically at intersections.
4. **Deep City-Building & Simulation Gameplay:**
   - **Buildable Tools:** Road, Residential Zone (automatically levels up visually from cozy cottages -> townhouses -> mid-rise apartments as happiness & services grow!), Commercial Shop, Solar Power Plant, Water Tower, Park (boosts nearby happiness), and Bulldozer (with dust particle puffs).
   - **Interactive Placement Preview:** Hovering shows a crisp isometric ghost preview tinted green (valid) or red (invalid), live cost tag, and service coverage radius for Parks/Power/Water.
   - **Live Economy & Metrics:** Treasury Funds (`$`), Population, Power Supply vs. Demand, Water Supply, Citizen Happiness (`%`), and periodic tax income pulses with floating `+$` text popups. Floating warning badges appear gently above unpowered or disconnected buildings.
5. **Audio (`Web Audio API`) & Quality of Life UI:**
   - Synthesize satisfying procedural sound effects (tactile building placement thud, road click, bulldozer crunch, gentle tax chime, subtle UI hover/click).
   - Clean, modern floating HUD: top telemetry bar with Simulation Speed controls (Pause / 1x / 2x) + Day/Night indicator, sleek bottom Build Toolbar with icons and prices, Save/Load to `localStorage`, Mute button, and a **"Load Starter Town"** button so players can either build from scratch or instantly watch a thriving city run.
6. **Completeness:** Write 100% of the full, polished, error-free single-file HTML code with NO shortcuts, NO placeholders, and NO truncation.
```

[↑ العودة إلى الفهرس](#table-of-contents)

---

## Evaluation Checklist

يمكنك استخدام هذه القائمة السريعة لتقييم ومقارنة نتائج نماذج الذكاء الاصطناعي المختلفة بعد تشغيل كل ملف:

- [ ] **Zero Console Errors:** افتح أدوات المطور (`F12` → `Console`) وتأكد من عدم وجود أي أخطاء برمجية عند التشغيل أو التفاعل.
- [ ] **One-Shot Completeness:** هل أنجز النموذج المشروع كاملاً من أول محاولة دون بتر الكود أو ترك `// TODO`؟
- [ ] **Visual Craft & Polish:** هل الرسوميات والإضاءة والواجهات متقنة جمالياً أم مجرد أشكال بدائية؟
- [ ] **Physics & Math Accuracy:** هل المحاكاة (الفيزياء، تتبع الأشعة، الإحداثيات الأيزومترية) مستقرة وسلسة بـ 60 FPS؟
- [ ] **Procedural Audio:** هل تعمل المؤثرات الصوتية والموسيقى البرمجية (`Web Audio API`) بنجاح دون ضوضاء مزعجة؟
