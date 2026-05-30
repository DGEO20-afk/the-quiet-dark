# 🌲 The Quiet Dark

> *A short atmospheric walking simulator set in a mysterious, foggy forest at night.*

![Status](https://img.shields.io/badge/status-in%20development-6b9fff)
![Engine](https://img.shields.io/badge/engine-Unity%20URP-white)
![Platform](https://img.shields.io/badge/platform-Android%20%28Mobile%29-3ddc84)
![Phase](https://img.shields.io/badge/phase-2%20%E2%80%94%20Unity%20Setup-5DCAA5)

---

## 🎮 Concept

You walk alone through a dark, foggy forest at night.  
No enemies. No objectives. Just atmosphere.

The goal is to create an immersive, slightly unsettling experience through  
environmental storytelling — dense trees, moonlight patches, distant fog,  
and the sounds of a forest that feels just slightly *wrong*.

---

## 🎨 Art Style

- **Asset-Pack based** — der Style wird über ein gewähltes Pack definiert (Wechsel weg von eigenen Blender-Assets)
- **URP** optimiert für **Mobile (Android)** — Ziel: stabil 30 FPS
- **Color Palette** — cold blues, dark greens, near-black
- **Mood** — Blair Witch meets Firewatch, without the horror clichés
- **Atmosphere** — Nebel, Mondlicht, minimale Wind-Bewegung *(geplant)*

---

## 🗂️ Project Structure

```
The Quiet Dark/
├── Assets/
│   ├── 3D/          # Blender source files (.blend)
│   ├── Exports/     # FBX exports for Unity
│   ├── Textures/    # Textures & images
│   └── Audio/       # Sounds & ambient audio
├── Unity/           # Unity project (URP)
├── Docs/
│   ├── devlog.html           # Dev session log
│   ├── the_quiet_dark_checklist.html  # Phase checklist
│   └── screenshots/          # Session screenshots
├── .gitignore
└── .gitattributes   # Git LFS config
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Unity (URP)** | Game engine & rendering — Mobile-optimiert (Android) |
| **Blender 5.1** | 3D Asset creation (Unique-Assets für später) |
| **FMOD** | Audio middleware — interaktive Sound-Events & Reverb *(geplant)* |
| **Git + Git LFS** | Version control (large files via LFS) |

> **Zielplattform:** Primär **Android (Mobile)** — getestet auf Samsung S23.
> Sekundär: Laptop (Razer Blade Stealth 13), Steam Deck, High-End PC.

---

## 📋 Development Phases

| Phase | Description | Status |
|-------|-------------|--------|
| **Phase 1** | Blender Assets | ✅ Done |
| **Phase 2** | Unity Setup & Asset-Packs | 🟡 In Progress |
| **Phase 3** | Scene Building | ⬜ Planned |
| **Phase 4** | Atmosphere & Mood (Fog, FMOD, Wind) | ⬜ Planned |
| **Phase 5** | Polish & Demo | ⬜ Planned |

---

## 🌲 Assets (Phase 1 → Phase 2)

**Phase 1 (Blender, abgeschlossen):**
- 4x Tree variants (Tall, Gnarled, Young, Dead)
- Pine trees with tiered cone geometry
- 3x Rock variants + large boulder formations
- Ferns, grass tufts, fallen log
- Procedural ground & path textures
- Full forest scene — 70 unit long pathway with tree tunnel

**Phase 2 (Strategiewechsel):** Szene wird ab jetzt mit einem Asset-Pack als Basis
aufgebaut statt komplett selbst in Blender. Blender bleibt für spätere Unique-Assets.
Evaluierte Packs: Joshua Pearson *Environmental Asset Pack* (free), ALP *Environment Vegetation Bundle*.

---

## 📸 Screenshots

**Session 001 — Blender Scene**

![Blender Scene](Docs/screenshots/session-001/blender_scene_overview.png)

**Session 002 — GitHub Setup**

![GitHub Repo](Docs/screenshots/session-002/github_repo.png)

---

## 📝 Dev Log

Full session notes available in [`Docs/devlog.html`](Docs/devlog.html)

---

## 👤 Author

**Geoffrey Da Rosa** — LifeOn Digital  
Solo indie project — started May 2026
