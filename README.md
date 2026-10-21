# Godot Icon For Obsidian

A custom icon pack that brings the **Godot node icons** (`Node2D`, `Sprite2D`, `CharacterBody3D`, and so on) into Obsidian through the [Iconize](https://github.com/FlorianWoelki/obsidian-iconize) plugin. Handy for game design docs, Godot notes, and class reference vaults.

<!-- TODO: add a screenshot, e.g. ![Preview](docs/preview.png) -->

> **Note:** Iconize is no longer actively maintained, but it still works. The icons in this pack are plain SVG files, so they can also be used with any other Obsidian icon plugin that accepts custom SVG packs.

## Contents

```
Godot-Icon-For-Obsidian/
├── icons/        # SVG icons, one file per Godot class (e.g. Node2D.svg)
├── README.md
└── CREDITS.md    # Source, license and attribution
```

## Installation

### Option A: Download from Releases (easiest)

1. Open the **Releases** page of this repository and download the latest `.zip`.
2. Extract it.
3. In Obsidian, open **Settings → Iconize → Custom icon packs** and create a pack, for example `godot`.
4. Add one icon through the UI first, then check which folder inside your vault it landed in (usually `.obsidian/icons/godot/`, but it can differ by plugin version).
5. Copy all `.svg` files from this pack's `icons/` folder into that folder.
6. Reload Obsidian (`Ctrl/Cmd + P` → **Reload app without saving**).

### Option B: Clone the repository

```bash
git clone https://github.com/sorry2sorry4what/Godot-Icon-For-Obsidian.git
```

Then copy the contents of `icons/` into your Iconize pack folder as described above.

## Usage

- **Manually:** right-click a file or folder → **Change icon** → search for the node name, for example `Node2D`.
- **Inline in notes:** type the icon shortcode, for example `:Node2D:`, if inline icons are enabled in Iconize.
- **Automatically with Rules:** in **Settings → Iconize → Rules**, add a rule so that a note named exactly like a node (for example `Sprite2D`) gets the matching icon.

## Tips

- Icons keep their original colors. If one is hard to see on your theme, you can change the color per icon in Iconize or edit the SVG.
- To keep search results tidy, you can delete icons you do not need (for example editor UI icons that are not nodes).

## Contributing

Issues and pull requests are welcome, especially for:

- Updating the pack to newer Godot versions
- Fixing icons that render incorrectly in Obsidian
- Sharing rule presets or scripts that auto-assign icons

## License and credits

The icons come from the [Godot Engine](https://github.com/godotengine/godot) repository (`editor/icons`). They remain the work of the Godot Engine contributors and are used under the license stated by the Godot project. See [CREDITS.md](CREDITS.md) for the exact license, source version and attribution.

This project is **not affiliated with or endorsed by** the Godot Engine project, Obsidian, or the Iconize author.

---

## Ringkasan (Bahasa Indonesia)

Icon pack kustom berisi ikon node Godot untuk Obsidian lewat plugin Iconize.

1. Download zip dari **Releases**, lalu ekstrak.
2. Di Obsidian: **Settings → Iconize → Custom icon packs**, buat pack bernama `godot`.
3. Salin semua file `.svg` dari folder `icons/` ke folder pack tersebut (biasanya `.obsidian/icons/godot/`; cek dengan menambah satu ikon lewat UI dulu).
4. Reload Obsidian, lalu klik kanan file atau folder → **Change icon** → cari nama node, misalnya `Node2D`.

Untuk pemasangan otomatis lewat Rules, lihat bagian **Usage** di atas.
