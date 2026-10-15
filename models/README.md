# Real 3D characters (optional)

The tour builds its own people from code. For photo-real people, drop rigged 3D models here and they replace the built-in ones automatically.

1. Get `.glb` characters — e.g. from a 3D artist, **Character Creator**, **MetaHuman** (export via Blender), **Meshy** / **Tripo** (AI), or **Mixamo** for animation. Dress them per the descriptions in the tour (kohanim in white linen, Kohen Gadol in the eight garments, etc.).
2. Each file should contain a skeleton with animations named **`Walk`** and **`Idle`** (Mixamo naming works).
3. Put the files in this folder and create `manifest.json`:

```json
{
  "_heightAmot": 3.6,
  "israelite": "man.glb",
  "woman": "woman.glb",
  "child": "child.glb",
  "kohen": "kohen.glb",
  "kohenGadol": "kohen-gadol.glb",
  "levi": "levi.glb",
  "sheep": "sheep.glb",
  "goat": "goat.glb",
  "calf": "calf.glb",
  "ox": "ox.glb"
}
```

Any type you leave out keeps the built-in figure. This works when the site is served over http (GitHub Pages), not when opening the file directly from disk.
