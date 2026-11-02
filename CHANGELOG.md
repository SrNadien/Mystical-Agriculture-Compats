## 1.0.5

- Compat con los 62 cultivos de UMC: añadidos azure_silver, crimson_iron, darkstone, unexplored_wood y las esencias lightium, ornium, ouranium y tornium al Sag Mill (EnderIO), Enriching (Mekanism) y Botany Pots.
- Las recetas de Mystical Extended Tier y Mystical Agradditions nuevas cargan solo con `neoforge:mod_loaded` de su mod.
- Quitadas las recetas de los cultivos que no existen en UMC (`sky_steel` y `xychronium`); sus semillas reales son `sky_steel_ingot` y `xychorium_gem`.

## 1.0.4

- Añadidas al Sag Mill (EnderIO) las recetas de los cultivos base de Mystical Agriculture que faltaban (136), con el mismo formato que las demás.

## 1.0.3

- Corregido el slug de Botany Pots - Mystical Agriculture Compat en las dependencias opcionales de la publicación a CurseForge (la subida fallaba con el slug anterior).

## 1.0.2

- Añadidas las recetas de Sag Mill (EnderIO) y Enriching (Mekanism) de las semillas que faltaban: UMC, Mystical Agradditions y Mystical Extended Tier.
- Las recetas de cultivos custom ahora usan el namespace `umc:` en lugar de `mysticalcustomization:`.
- Compat con Botany Pots: 66 recetas `botanypotsmystical:mystical_crop` (54 de UMC y 12 de Mystical Extended Tier).
- Añadido el paso de publicación a CurseForge al workflow: marca la versión de Minecraft, NeoForge, Java 21, cliente y servidor, requiere Mystical Agriculture y deja EnderIO, Mekanism y Botany Pots como dependencias opcionales.
