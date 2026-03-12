# Logo Artboard Generator by Color
### Adobe Illustrator Script — JSX

Automatically generates artboards for each logo asset × color combination, named and organized in a grid layout. Built for brand designers who need to export logo variants efficiently.

---

## Preview

```
[Black_badge]  [Black_full]  [Black_vertical]  [Black_horizontal]
[White_badge]  [White_full]  [White_vertical]  [White_horizontal]
[Blue_badge]   [Blue_full]   [Blue_vertical]   [Blue_horizontal]
```

Each artboard is sized exactly to its asset + your defined padding, and named `ColorName_AssetName`.

---

## Features

- Detects all visible items in the document automatically
- Supports any number of assets and color variants
- Accepts **HEX** (`#003DA5`) and **CMYK** (`100,72,0,6`) color input
- Applies color to fill, stroke, or both
- Grid layout: one row per color, one column per asset
- Artboards named and sized precisely per asset
- Non-destructive: always works on duplicates, originals untouched

---

## Requirements

- Adobe Illustrator CS6 or later (CC compatible)
- No plugins or extensions needed

---

## How to Use

**Run once:**
`File > Scripts > Other Script...` → select `logo_pranchetas_por_cor.jsx`

**Install permanently:**
Copy the `.jsx` file to your Illustrator scripts folder and restart:

```
Windows: C:\Program Files\Adobe\Adobe Illustrator [version]\Presets\en_US\Scripts\
Mac:     /Applications/Adobe Illustrator [version]/Presets/en_US/Scripts/
```

Then access it via `File > Scripts > logo_pranchetas_por_cor`.

---

## Setup Tips

- Each logo asset should be a **separate group or path** in the document
- Name your layers clearly — the script uses layer names as default asset names
- Keep all layers **visible** before running (hidden layers are ignored)
- Work from a **clean original file** — running the script again will replace existing artboards

---

## Color Format Reference

| Color | HEX | CMYK |
|---|---|---|
| Black | `#000000` | `0,0,0,100` |
| White | `#FFFFFF` | `0,0,0,0` |
| 50% Gray | `#808080` | `0,0,0,50` |
| Pantone 286 Blue | `#003DA5` | `100,72,0,6` |

---

## Files

| File | Description |
|---|---|
| `logo_pranchetas_por_cor.jsx` | The script |
| `tutorial_logo_artboard_generator_EN.txt` | Full guide in English |
| `tutorial_logo_pranchetas.txt` | Guia completo em Português |

---

## License

Free to use and modify. Credit appreciated but not required.
