---
type: gdd-concept
version: 0.1
date: [7/7/2026]
team: [Vunique Inc.]
---

# [WONDERLAND] — Game Concept

## Elevator Pitch
[เป็นเกม Action 2D Top-Down ที่ผู้เล่นต้องผ่านโดยการแก้ปริศนาต่างๆที่หลอกตาและไม่คุ้นเคย โดยการไปสถานที่ต่างๆที่ดูผิดปกติ ด้วยทั้ง Gameplay, Puzzle, Atmosphere, etc.]

## Genre & Platform
- **Genre:** [2D Action Top-Down]
- **Platform:** PC (Windows)
- **Engine:** MonoGame (C#)
- **Target Audience:** [วัยรุ่น]

## Inspiration & References
| เกม/สื่อ | แรงบันดาลใจที่นำมาใช้ |
|---|---|
| [Silent Hill] | [Puzzle, Atmosphere] |
| [2D Zelda Games] | [Mechanics, Level Design] |
| [Searching for a world that doesn't exist] | [World Building, Atmosphere] |

___

## 🏷️ Naming Convention

| Prefix   | ประเภท     |
| -------- | ---------------- |
| `spr_` | Sprite / Texture |
| `sfx_` | Sound Effect     |
| `bgm_` | Background Music |
| `font_` | Font             |
| `data_` | Data / Config    |

**เอกสาร:** ไฟล์ใน `docs/01_GDD/` เรียงลำดับด้วย prefix ตัวเลข 2 หลัก (`00-`, `01-`, ...) ตามลำดับที่สร้างขึ้นในแต่ละ Lab — ห้ามสลับเลขไฟล์ที่มีอยู่แล้ว เพิ่มไฟล์ใหม่ให้ต่อเลขถัดไป

## Asset Naming Convention

| Prefix   | ประเภท     | ตัวอย่าง        |
| -------- | ---------------- | ----------------------- |
| `spr_` | Sprite / Texture | `spr_player_idle.png` |
| `sfx_` | Sound Effect     | `sfx_jump.wav`        |
| `bgm_` | Background Music | `bgm_stage_01.mp3`    |
| `font_` | Font             | `font_ui_main.ttf`     |
| `data_` | Data / Config    | `data_enemies.json`    |

## 📁 ใครดูแลส่วนไหน

| คนที่ | รับผิดชอบ  | โฟลเดอร์ staging                |
| ---------- | ------------------- | --------------------------------------- |
| 1          | Sprites / Textures  | `docs/assets/_candidates/sprites/` |
| 2          | Sound Effects (SFX) | `docs/assets/_candidates/sfx/`     |
| 3          | Music / BGM         | `docs/assets/_candidates/music/`   |
| 4          | Fonts + Data        | `docs/assets/_candidates/fonts/`   |
