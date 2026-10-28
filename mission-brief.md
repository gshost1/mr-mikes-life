# Mission Brief: "Mr. Mike's Life"

Build a third-person 3D browser game about my cat, Mr. Mike. The full details are in `cat-notes.md` in this folder, and the UI style reference is `ui-draft-pixel.html` (screenshots: `ui-pixel-hud.png`, `ui-pixel-title.png`). Read both before planning.

## Hard requirements
- Replace the placeholder `index.html` (a "coming soon" page) with the game. The repo deploys to Vercel on every push to `main`. Keep `vercel.json` out unless it's needed; this is a static site.
- `reference/mr-mike.jpeg` is a real photo of Mr. Mike. Use it to match his look.
- Make one self-contained `index.html` that runs by opening it in Chrome. Use Three.js (CDN import is fine) and no build step.
- The whole game is pixel art. Render the 3D scene at low resolution (about 320x180) and scale it up with nearest-neighbor filtering, for a PS1-style look. Use pixel textures and a limited palette that matches `ui-draft-pixel.html`.
- Use a third-person camera that follows Mr. Mike. Controls: WASD to move, mouse to look (pointer lock), Space to jump, Shift for zoomies, E to interact, and Esc for a simple pause screen.
- Mr. Mike: a male silver-gray colorpoint/tabby with a cream body, gray face with forehead stripes, a striped tail, blue-gray eyes, and a pink nose.

## World (free roam)
The house has a kitchen, a bathroom, a living room with a sunny spot, and the owner's office.

## Activities (any order)
- Eat a tiny bit of salad (kitchen).
- Drink water from the bathtub (bathroom).
- Sunbathe in the sunbeam (living room).
- Steal and nap on the owner's work chair (office).
- Make biscuits on blankets and on the owner's lap.
- Knock cups and mugs, pens and small items, and plants off tables. They fall with physics.
- Zoomies: a speed burst with Shift, fed by a meter.
- Wall-jump: running fast into a wall turns into a wall-jump trick that scores points.

## Owner NPC
The owner has brown hair in a mod cut, glasses, jeans or sweatpants, and a t-shirt. They work at the office desk and react in funny speech bubbles (for example, "MR. MIKE! THAT WAS MY COFFEE!"). There's no penalty.

## UI (match ui-draft-pixel.html)
- Top-left: a portrait of Mr. Mike with a mood face, and block-style bars for Food, Water, Energy, and Chaos. A low bar shows a warning label.
- Top center: a sun/moon arc clock with the time and the current phase.
- Top-right: an arcade-style "Chaos Points" score with a combo multiplier.
- Right side: the "Mr. Mike's Day" sticker book of habits. Each one turns green when he does it.
- Floating "E: action" bubbles over nearby objects you can use.
- Pop-up points (for example, "+50!" and "WALL JUMP +100").
- Bottom: a room name tag, the zoomies meter, and a controls hint that fades after about a minute.
- Pixel font (Press Start 2P) with hard pixel borders.

## Flow
1. Title screen: Mr. Mike sleeping in white and pink blankets, with the logo, a "Wake up Mr. Mike" button, and a "How to play" button.
2. One day lasts about 5 minutes, from morning to bedtime. The lighting changes over the day.
3. At bedtime, play a cozy sleep scene.

## Validation
The game must load with no console errors. All of these must work: every room is reachable, every activity can be triggered and updates its sticker and bars, knocked objects fall, the wall-jump scores points, the day clock runs out to the bedtime scene, and pause works.
