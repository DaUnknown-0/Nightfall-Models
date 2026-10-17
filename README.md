# Nightfall-Models

3D map models for [Nightfall](https://github.com/DaUnknown-0/Nightfall)'s GPU world, one file per map
(`<map>.nfm`). Nightfall downloads them automatically into `BepInEx/nightfall-models` and checks every
file against the size and SHA-256 in its built-in catalogue (`catalog.json` here, tag = catalogue version).

Maps: the Unknown's Atlas maps Museum, Forest (`wald`) and Carnival (`park`), built from their own artwork.
The vanilla Among Us maps are deliberately not published here.

Format NFM2 (little endian): textures (PNG), materials, triangles in 8 m tiles with normals and baked
shading, and a floor height raster. Coordinates are Among Us world units (x east, y north, z height).
