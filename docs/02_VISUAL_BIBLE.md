# MISERIA AETERNA: Visual Bible (draft v0)

**Status: IN PROGRESS.** Three of four reference images have been analyzed. Reference One (cruelty, brutality, loneliness, the quasi-VHS character) is still awaited. The camera technique cannot be chosen until a prototype runs on the God's PC (constitution 6.4). Everything here is provisional until those two gates pass.

**About the images themselves:** they are not stored in this repository. Ref A carries a third-party watermark (`@abbadonart.deviantart.com`), and the others are of unknown origin. They are mood and craft references only: never traced, never shipped, never used as assets. Keep them locally, outside version control (for example in a git-ignored `references/` folder under `C:/games`).

Measurements were made in this session with a small Python script (value histograms, k-means dominant colors, warm-pixel sampling). Numbers are approximate; JPEG compression shifts colors slightly.

---

## Ref A · "The Lit Street"

*A Gothic city at dusk. From high above the roofs, a narrow cobbled street runs away from the viewer toward a colossal twin-spired cathedral. Lanterns and windows burn along the street like a trail of coals. Tiny figures walk in the lamplight. A raven sits on a near rooftop. Behind the cathedral, a skyline of towers wrapped in scaffolding and cranes fades into blue haze under a peach-and-slate dusk sky.*

**Role: camera and space; the Lights of the Living; the city of Advanced Gothic.**

**Format and camera.** Portrait, 1121×2000. The camera is high and pitched down, yet still looks *forward*: the street is a strong one-point-perspective corridor from the bottom center to the cathedral, and the horizon sits high, roughly in the top quarter. This is a perspective camera, not an orthographic or top-down map.

**Composition.**
- Focal point: the cathedral, a near-black mass against the lightest part of the sky.
- Leading line: the warm lanterns along the street carry the eye from the bottom of the frame up to the cathedral doors.
- Framing (repoussoir): dark buildings press in from the left and right edges.
- Secondary focal points: the raven at upper left; the scaffolded towers in the haze.

**Depth layers** (each one lighter and bluer than the one before it):
1. Foreground roofs and walls, almost black.
2. The street and houses, dark slate, with warm windows.
3. The cathedral, a dark mass with a few lit windows.
4. The distant skyline in haze blue.
5. The sky.

**Values (measured).** 75% of pixels are below 30% luminance and 46% are below 15%. Mean luminance by horizontal band, top to bottom: **0.50 → 0.25 → 0.15 → 0.10 → 0.09**. Light lives in the distance and the sky; darkness pools toward the viewer.

**Warm light (measured).** Only **about 0.5% of the pixels** are warm lamp and window light, and those few pixels define the image. Their color is **not gold but a muted coral ember**: core `#dc8d70`, body `#a86050`, edge `#7f4136`.

**Dominant colors (measured):**

| Share | Hex | Role |
|---|---|---|
| 24% | `#08060e` | violet-black abyss |
| 14% | `#131420` | night slate |
| 17% | `#222635` | blue slate |
| 12% | `#2f3342` | lit slate |
| 7% | `#3f4351` | stone in light |
| 14% | `#637986` | distance haze blue |
| 5% | `#f0cdb3` | peach dusk sky (the only large warm area) |
| 1% | `#7f514c` | warm stone in lamplight |

**Pixel craft.** Small, dense clusters. Stone and roof tiles are rows of one-to-two-pixel marks. Windows are tiny lit rectangles. Edges are defined by value contrast; there are no black outlines on the architecture. Haze is done with flat value steps rather than smooth gradients. In places the pixel scale seems inconsistent (some areas read finer than others); MISERIA AETERNA must hold one pixel grid.

**Story without text.** A living city: people out at dusk, every window a household. A raven watches. The towers in the background are still being built, cranes and scaffolding against the sky: a cathedral that has been under construction for generations, and the first hint of the proto-industrial summit (D-016).

---

## Ref B · "The Bridges in the Clouds"

*From a high balcony where a stone figure stands in silhouette, the eye falls into an abyss of cloud. Viaducts and arched bridges leap from cliff to cliff. Gothic spires rise layer behind layer. Through a rent in the clouds, shafts of light pour down upon the dead city like a judgment or a blessing. Everything is the color of rust and old blood, and the edges of the world are black.*

**Role: OPEN, to be named by the God.** Proposed uses:
1. The doctrine of **holy light**: rare, overwhelming, unsettling, light from nowhere.
2. **The sublime summit of Advanced Gothic**: what Cinerea's greatest cities might become.
3. A **monochrome treatment** for special states: memories in the Ledger, high Tenebrae, the Strepitus.

**Format.** Portrait, 335×597, low resolution. A soft, grainy, painterly image, closer to an engraving or a degraded print than to clean pixel art.

**Composition.**
- A giant black frame on the left and bottom: the viewer stands in darkness, looking out at light.
- The statue on the balcony is a *Rückenfigur*-like sentinel that gives scale and witness.
- The bridges make diagonals that lead the eye into depth.
- The light source is upper center, partly hidden.

**Values (measured).** 75% of pixels below 30% luminance; 54% below 15%. The brightest band is the upper middle (the clouds and the rays), not the very top. The foreground is darkest.

**Color (measured).** Effectively monochrome. Mean saturation 0.22. No warm accents at all. A tonal ramp of rust and oxblood: `#131516`, `#282121`, `#40302e`, `#5c3f3b`, `#6d514b`, `#7c665e`, `#8e7c72`, `#ad998d`, `#c9b9ac`, `#dfdad2`.

**Lineage** (for study, not imitation): Gustave Doré's light in darkness; Piranesi's imaginary prisons, with their impossible bridges and stairs; the scale of John Martin.

---

## Ref C · "The Knight at the Graves"

*An overgrown churchyard under a white, overcast sky. A knight in a ragged black cloak stands with his back to us, sword point resting in the grass, among leaning crosses and rounded stones. Beyond him, through mist, rises the silhouette of a great spired church or castle. Old trees arch over the scene. A carved stone and broken steps lie in the foreground, and among them grow a few small red mushrooms. Crows cross the sky.*

**Role: melancholy and remembrance** (the constitution's Reference Two).

**Format and camera.** Square, 554×554. A near-eye-level camera, slightly elevated, standing just behind the knight. The figure seen from behind (the *Rückenfigur* of Caspar David Friedrich) invites the viewer to look where he looks.

**Composition.**
- The focal point is the black cloak, the darkest and most solid mass, set against pale grass and mist.
- The distant spire is a second focal point, aligned with the knight's gaze.
- Trees frame the left and right (repoussoir). The carved stone and broken steps anchor the foreground.

**Depth layers:**
1. Foreground stone, steps, mushrooms.
2. The knight and the graves in the grass.
3. Trees and the mist band.
4. The castle silhouette, a flat pale gray.
5. The white sky.

The mist is made of **stacked flat silhouettes**, each step lighter: classic layered atmospheric perspective.

**Values (measured).** Brighter than A and B: mean 0.34, with 26% of pixels above 50% (the overcast sky). Band means top to bottom: 0.39, **0.54** (the sky behind the castle), 0.34, 0.22, 0.19. Again the foreground is darkest and the light lives in the distance.

**Color (measured).** Very desaturated: mean saturation 0.13. Graphite `#1f2022` and `#343533`, stone gray `#4c5253` and `#5e656b`, cool lavender-gray sky `#aaa9b5`, `#c3c4d4`, `#dbdcea`, muted ochre grass `#867d57` to `#a08d51`. The only true color is the **red mushrooms (`#b0505c`), about 0.03% of the image**, a few pixels of life among the graves.

**Light.** Diffuse overcast. No cast shadows. Form comes from silhouette and value, not from direct light.

**Pixel craft.** Medium resolution, clean clusters. Foliage is clumped leaf shapes. The cloak has jagged, tattered edges. There are no outlines on the background. Mist and distance are flat value bands, not gradients.

**Story without text.** One survivor at the graves of others, looking toward the place they served or died for. The crows say death has been here. The mushrooms say life continues on it.

---

## Laws drawn from the references (R-series, PROPOSED)

These are the first reusable rules. Each is observed in at least two of the three references.

- **R-01 · Backlight the monumental.** Great architecture reads as a dark silhouette against the brightest part of the sky (A, B, C).
- **R-02 · Darkness pools toward the viewer.** The foreground is the darkest band and the distance the lightest. Measured in all three.
- **R-03 · Depth by stacked values.** Build depth in three to five layers, each a flat step lighter (and in A and C, bluer) than the one before. Fog and distance use value steps, not smooth gradients (A, C).
- **R-04 · Frame with darkness.** Dark masses at the frame's edges (buildings, trees, balconies) push the eye inward to the focal point (A, B, C).
- **R-05 · The half-percent law.** The warm light of human life covers about half a percent of the image and carries most of its emotion (A). Saturated color is spent in specks: lamps, mushrooms, a scarf (A, C). This confirms and sharpens the constitution's saturation budget.
- **R-06 · The Lights of the Living make paths.** Warm lights cluster into lines and constellations (a street, a row of windows) that lead the eye to what matters (A).
- **R-07 · Figures are silhouettes first.** A walker on a lit street, a knight against pale grass: people read by shape and value contrast before any detail (A, C).
- **R-08 · No outlines on the world.** Architecture and landscape are separated by value, not by drawn lines (A, C).
- **R-09 · Stone is texture in rows.** Masonry, tiles, and cobbles are rendered as small regular marks that follow perspective (A, C).
- **R-10 · Crows mean death has passed.** Both pixel references place crows or ravens in the sky or on roofs. In MISERIA AETERNA crows are a simulation signal, not decoration (constitution 5.11).
- **R-11 · Two lights only.** Each scene has a cool ambient world light (sky, haze, overcast) and, at most, one warm human light family. Holy light (B) is a third kind, reserved for rare events.
- **R-12 · The forward gaze.** Both pixel references look *into* depth toward a distant monumental focus, from above (A) or from behind a figure (C). The camera must be able to do both.

---

## Palette v0.1 (measured from the references; replaces constitution 5.6 where they disagree)

| Role | Hex | Source |
|---|---|---|
| Abyss (violet-black) | `#08060e` | A |
| Night slate | `#131420` | A |
| Blue slate | `#222635` | A |
| Lit slate | `#2f3342` | A |
| Stone in light | `#3f4351` | A |
| Distance haze | `#637986` | A |
| Graphite | `#1f2022` | C |
| Overcast stone | `#5e656b` | C |
| Overcast sky | `#aaa9b5` → `#c3c4d4` → `#dbdcea` | C |
| Dry grass ochre | `#867d57` → `#a08d51` | C |
| **Ember light, core** | `#dc8d70` | A |
| **Ember light, body** | `#a86050` | A |
| **Ember light, edge** | `#7f4136` | A |
| Dusk sky glow | `#f0cdb3` | A |
| Grave-red accent | `#b0505c` | C |
| Rust-sepia ramp (holy light, memory) | `#282121` → `#5c3f3b` → `#8e7c72` → `#dfdad2` | B |

**The key correction:** the constitution proposed a bright candle gold (`#e8a33d`) for human light. The references use a **muted coral ember** (`#dc8d70` fading to `#7f4136`): fire seen through soot and old glass. It is warmer than the world but never cheerful. It fits a world named for ash: the light of embers, not of sunshine.

---

## Implications for the camera (hypotheses, to be tested on the God's PC)

- Ref A's forward, downward, perspective street view, with real depth and haze, suggests a **3D scene with a tilted perspective camera** (the HD-2D family in constitution 6.4), or a 2.5D hybrid with many depth layers. A purely flat, layered 2D approach would struggle to move *forward* down that street.
- Ref C's eye-level view behind a figure is a natural frame for the **Vigil** tier.
- Ref A's fine pixel density suggests a high internal resolution, or sprites drawn at a fine scale, for the Diorama. Tiny figures in A are only about 10 to 15 pixels tall in a 2000-pixel-tall image. At a 640×360 internal resolution, people that small would be only two or three pixels tall. The scale conflict between immense architecture and readable people (constitution 5.13) is real and must be solved by the camera tiers and zoom.
- Both references are **portrait**, and the game will be landscape (16:9). Their vertical drama (spires, bridges) has to be kept by letting the camera lift its gaze toward the sky, not by copying their framing.

---

## Open

- Reference One (cruelty): awaited.
- The God's naming of Ref B's role.
- Camera prototype, internal resolution, and character height: need the God's PC.
- A first *style test* (one small scene drawn in this language) once tools are available.
