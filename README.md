https://human77777.github.io/cgai-results/

## A2a

Default

<img src="A2a/default_scene_frame.jpg" width="720">

Sphere, box, and plane distance fields, joined by union, intersection, and subtraction, then ray marched and lit with Phong.

Creative

<img src="A2a/creative_scene_frame.jpg" width="720">

A small Blue Side Nexus: a cut crystal on stacked rings, with orbiting supports. The parts are smooth distance fields, moved by time.

## A2b

Default

<img src="A2b/default_scene_frame.jpg" width="720">

A small sine network stores the bunny and cow as distance fields. The same marcher sets both on a ground plane.

Creative

<img src="A2b/creative_scene_frame.jpg" width="720">

Mid-Autumn scene. The moon is a sphere, the rabbit is the trained bunny, and a second network is the Poro, with a few primitive features on top.

## A3a

Default

<img src="A3a/default_scene_frame.jpg" width="720">

Procedural cloud as an absorption-emission volume. Rays take jittered steps and composite color by transmittance. The clip also passes through the cube, with the same integrator.

Creative

<img src="A3a/creative_scene_frame.jpg" width="720">

Nebula Eye: a slow rotating ring of mist, two ribbons, and a bright core, accumulated over a thin starfield.

## A3b

Lego

<img src="A3b/lego_page_preview.png" width="720">

A compact NeRF, two narrow ReLU layers, reconstructs the Lego truck. A held-out view reaches 23.15 dB. The shader runs the exported weights.

Ship

<img src="A3b/ship_page_preview.png" width="720">

The same volume renderer on the synthetic ship, with a higher-frequency encoding. Held-out PSNR is 27.58 dB. Thin rigging stays slightly soft.

## A4

Synthetic

<img src="A4/results/synthetic-result.png" width="720">

Forty 2D Gaussians fit the original Spiral Bloom. Left is the render, middle the splats, right the target. The clip is that optimization.

Mona Lisa

<img src="A4/results/mona-lisa-result.png" width="720">

One hundred sixty additive Gaussians approximate the Mona Lisa. Smooth splats cannot keep every edge.

Creative

<img src="A4/results/creative-result.png" width="720">

Four hundred Gaussians fit Van Gogh's sunflowers. The clip is the fit over time.

Sunflowers

<img src="A4/results/sunflowers-comparison.png" width="720">

Final sunflower reconstruction beside the F455 painting. Petals stay softer than the source because each splat is smooth.

## A4 Photo

<img src="A4_Photo/results/photo-800-three-panels.png" width="720">

A photograph fit with 800 Gaussians: the result, the splat field, and the photo. This count is higher than the usual shader budget.

## A5

Default

<img src="A5/default-preview.png" width="720">

XPBD rope. Each frame predicts positions, solves springs, a wavy ground, and particle contacts, then rebuilds velocity.

Creative

<img src="A5/creative-preview.png" width="720">

Newton's cradle. Five hanging bobs pass a released swing through contact. The motion is simulated, not keyframed.

## A6

Bee

<img src="A6/bee/comparison.png" width="720">

Bee points sampled from the source image, next to points drawn by the trained reverse process. Small strokes stay a little soft.

<img src="A6/bee/webgl-preview.png" width="720">

The same bee model in the browser: 8,000 points and a 400-step noise schedule, with the network packed into the shader. The clip forms the shape, then lets it dissolve.

Creative

<img src="A6/creative/comparison.png" width="720">

A separate model learns a five-petal bloom from noise, without pulling points toward stored target positions.

<img src="A6/creative/webgl-preview.png" width="720">

That bloom in the same WebGL viewer, cycling between noise and the flower.
