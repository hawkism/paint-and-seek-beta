# Photo textures

Used when a player picks **Settings → Textures → 📷 Photo**. The game loads them only then, so players who never pick
Photo never download them. If they can't load (the game opened straight from a folder, or no internet), the game keeps
the textures it draws in code.

Made by `node tools/make-photo-textures.cjs <folder of downloads>` from these [Poly Haven](https://polyhaven.com)
textures (1K JPG color + OpenGL normal map). Poly Haven's textures are **CC0** (public domain): free to use, no credit
required. The color photos are turned into near-white grey patterns, because the game tints each texture with the
thing's own color (so colors, and the computer seekers' color checks, stay the same in every texture setting).

| File | Used for | Poly Haven texture |
|---|---|---|
| `noise.jpg` | most things (walls, furniture, toys) | painted_plaster_wall |
| `grass.jpg` | grass | leafy_grass |
| `wood.jpg` | wood floors, fences, tables | wood_floor |
| `tile.jpg` | tiled floors | square_tiles_02 |
| `check.jpg` | checkered floors | checkered_pavement_tiles |
| `carpet.jpg` | carpets and rugs | wool_boucle |
| `panel.jpg` | Space Station metal panels | metal_plate |
| `frosting.jpg` | Candy Town frosting | clay_plaster |
| `hay.jpg` | Farm hay | withered_grass |
| `dirt.jpg` | Farm dirt | farm_soil |

`<name>_n.jpg` is the same texture's normal map (the bumps), used on Detailed and Realistic.
