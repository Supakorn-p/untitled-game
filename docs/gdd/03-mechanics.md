---
type: gdd-mechanics
version: 0.1
date: [7/14/2026]
---

# Mechanic Design — [ชื่อ Mechanic]

## State Diagram

```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Move : WASD
    Move --> Equip Item : NUM
    Equip Item --> Use Item : C
    Use Item --> Unequip Item : C

```

## Rules

| State | เข้าเงื่อนไข | ออกเงื่อนไข | Note |
|---|---|---|---|
| Idle | เริ่มเกม / หยุดเคลื่อนที่ | กด input ใดๆ | Animation loop |
| Move | กดปุ่มทิศทาง | ปล่อยปุ่ม | Speed = [5] |
| Equip | NUM | Unequip | Each Num Represent a different Item |
| Use | C | Finished | None |
