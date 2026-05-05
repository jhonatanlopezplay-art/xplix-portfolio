# Xplix Portfolio

Portfolio personal de Xplix — Mod developer & pixel art enjoyer.

## Stack
- **Astro** — Static site framework
- **CSS** puro con variables
- **Press Start 2P** + **Share Tech Mono** — Fuentes pixel/mono
- **Diseño** — Dark theme, pixel art aesthetic

## Estructura

```
src/
├── components/
│   ├── Nav.astro        — Navegación fija
│   ├── Hero.astro       — Sección principal con avatar
│   ├── About.astro      — Sobre mí con skills
│   ├── Projects.astro   — Mods de Fabric + Launcher
│   └── Contact.astro    — Links y terminal decorativa
├── layouts/
│   └── BaseLayout.astro — HTML base + meta
├── pages/
│   └── index.astro      — Página principal
└── styles/
    └── global.css       — Variables, animaciones, tipografía
public/
├── perfil.png           — Avatar circular (pixel art face)
└── perfil_2.png         — Avatar coding setup
```

## Cómo correr

```bash
npm install
npm run dev
```

## Personalizar

Para agregar más proyectos, edita el array `mods` en `src/components/Projects.astro`.

Cada mod tiene:
```js
{
  id: "id-unico",
  name: "Nombre del Mod",
  type: "Fabric Mod",
  desc: "Descripción...",
  tags: ["fabric", "minigame"],
  icon: "🎮",
  color: "#color-acento",
  status: "released" | "wip",
}
```

## Paleta de colores

| Variable | Color |
|---|---|
| `--purple` | #8b5cf6 |
| `--cyan` | #06b6d4 |
| `--green` | #10b981 |
| `--amber` | #f59e0b |
| `--bg` | #0a0a0f |

---

*Inspirado en Squid Craft Games 4 · Eufonia Studio · Twitch Rivals*
