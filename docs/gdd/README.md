---
type: doc-index
version: 0.1
date: [วันที่]
---
# [ชื่อเกม] — Documentation Index

## 📖 เอกสารในโปรเจกต์นี้

| ไฟล์                                | เนื้อหา                   | สถานะ |
| --------------------------------------- | -------------------------------- | ---------- |
| [00-concept.md](00-concept.md)             | Game concept, core loop, scope + naming conventions   | ✅         |
| [01-mechanics.md](01-mechanics.md)         | Mechanic flow (state diagram)    | ✅         |
| [02-asset-list.md](02-asset-list.md)       | Asset list + asset pipeline flow | ✅         |
| [03-class-diagram.md](03-class-diagram.md) | Class diagram เบื้องต้น | ✅         |

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
