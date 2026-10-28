# Cat Game Notes

Nothing is built yet. These are notes only.

## Cat
- Name: Mr. Mike
- He's male.
- Looks like (from the photo): a silver-gray colorpoint with lynx/tabby markings. He has a pale cream-gray body, darker gray tabby stripes on his forehead (the "M" mark) and cheeks, grayish ears, a pink nose, long white whiskers, and large gray-blue eyes. His fur looks medium-plush and his face is round.

## Daily routine (in order)
1. Wakes up and eats a tiny bit of salad every morning.
2. Goes into the bathtub and drinks water from it (weirdo).
3. Sunbathes.
4. Naps on the owner's work chair (the owner has to share it with him).

## Habits and quirks
- Knocks things off surfaces.
- Goes crazy (zoomies).
- Runs so fast that he bounces off the walls.
- Loves naps and boxes; obsessed with food (from earlier answers).

## Game direction so far
- 3D game in third person (the camera follows the cat).
- One HTML file that runs in the browser.
- Free roam: no fixed mission order. You can do his routine activities whenever you want.
- Wall crash: running into a wall at full speed becomes a wall-jump trick that scores points.
- The owner is a character in the game (sits at the work chair; you share it or steal it).
- Rooms: kitchen (salad), bathroom (bathtub water), living room with a sunny spot (sunbathing), and the owner's office (work chair).
- He knocks off cups and mugs, pens and small stuff, and plants.
- He loves making biscuits (kneading with his paws) a lot. This should be an action in the game.
- The owner reacts in a funny way to trouble or chair stealing. There's no penalty.
- Goal: the day passes, and the game ends at bedtime.
- Biscuits happen on blankets (like the photo) and on the owner's lap.
- One in-game day lasts about 5 minutes, from waking up to bedtime.
- Bedtime ends with a cozy sleep scene.
- Owner look: brown hair in a mod cut, glasses, jeans or sweatpants, and a t-shirt.

## UI
- Style: pixel art (changed from soft pastels, which the user didn't like). Keep the cozy pink, cream, and wood colors. Draft: ui-draft-pixel.html
- Status bars: Hunger (salad/food), Thirst (bath water), Energy (naps), and Happiness/Chaos.
- Time of day: a sun/moon arc that moves from morning to bedtime.
- Title screen: Mr. Mike sleeping in blankets (like the photo).
- Layout: status bars in the top-left, sun/moon arc at the top center.
- Interaction prompts: a floating bubble over the object (for example, "E: knock off").
- Feedback: pop-up points when Mr. Mike does something fun (for example, "+50!").
- Pause menu: simple pause only, with no settings.
- World look: the whole 3D world is pixelated too. Render at low resolution and scale up with crisp pixels, in a retro PS1-style third-person look. Use pixel textures and a limited color palette that matches the UI.
