---
type: jam-workflow
version: 0.1
date: [7/21/2026]
team: [Vunique Inc.]
---

# Git Workflow Rules — [ชื่อทีม]

> ปรับจาก branching workflow ปกติให้ "เร็วพอ" สำหรับ 48 ชม. — ตกลงกติกาให้ครบก่อนเริ่ม แล้วห้ามเปลี่ยนกลางทาง

## Branching Model

- รูปแบบ branch: `main` + `feature/<module>` (อายุสั้นไม่เกิน [2-3] ชม. ต่อกิ่ง)
- สิทธิ์ merge เข้า `main` โดยไม่ต้องรอ review: [ทุกคน / เฉพาะเจ้าของ module นั้น / อื่นๆ]
- ถ้าไม่มี branch protection แบบเต็มรูปแบบ ใครเป็นคน spot-check ว่า `main` build ผ่านอยู่เสมอ: [ชื่อ]

## Branch Protection ขั้นต่ำ

- `main` ต้อง build ผ่านเสมอ เพราะอาจต้อง submit จาก `main` ได้ทุกเมื่อ
- วิธีการันตี: [เช่น "ทดสอบรันก่อน push ทุกครั้ง" / "ตั้ง GitHub Action build check" / อื่นๆ]

## Merge Conflict — เมื่อเกิดขึ้นกลางดึก

1. คนที่เจอ conflict แจ้งใน group chat ทันที พร้อมชื่อไฟล์
2. ถ้าเจ้าของไฟล์ (ดู [02-roles.md](02-roles.md)) ออนไลน์ → ให้เจ้าของไฟล์ตัดสินใจ
3. ถ้าเจ้าของไฟล์ไม่อยู่ ผู้ตัดสินใจสำรองคือ: [Tokyo]
4. ห้ามแก้ conflict แบบเดาเอง — ถ้าไม่แน่ใจให้รอผู้ตัดสินใจ แม้จะเสียเวลารอ [5] ก็ตาม
