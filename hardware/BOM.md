# Bill of Materials (BOM)

## TideMark Stake — Single Unit

| # | Item | Specification | Source | Est. Cost |
|---|------|--------------|--------|-----------|
| 1 | TideMark Tower | 3D printed, PETG, triangular 3"×3"×3" × 16" tall, ~65g | Print from `/hardware/stl/tidemark-tower-v1.stl` | $3.00 |
| 2 | TideMark Ground Stake | 3D printed, PLA/PETG, 8" spike + 2" handle + 1" male thread, ~30g | Print from `/hardware/stl/tidemark-groundstake-v1.stl` | $1.50 |
| 3 | Lock Screw + Nut | 3D printed, PLA, threaded bolt + nut for sliding height lock | Print from `/hardware/stl/tidemark-lockscrew-v1.stl` | $0.50 |
| 4 | Eye Bolt | 1" loop, threaded into top of tower for stringline | Hardware store or 3D printed | $1.00 |
| 5 | Label (optional) | Printed adhesive label from `/branding/label-template.svg` | Inkjet on weatherproof label stock | $0.25 |

**Total per stake: ~$6.25**

## TideMark Contractor Kit (4-Pack)

| # | Item | Qty | Est. Cost |
|---|------|-----|-----------|
| 1 | TideMark Tower | 4 | $12.00 |
| 2 | TideMark Ground Stake | 4 | $6.00 |
| 3 | Lock Screw + Nut sets | 4 | $2.00 |
| 4 | Eye Bolts (1" loop) | 4 | $4.00 |
| 5 | Adhesive labels | 4 | $1.00 |
| 6 | Instruction card (laminated) | 1 | $2.00 |
| 7 | Canvas zip pouch (branded, optional) | 1 | $5.00 |

**Total per kit: ~$32.00**

## Print Plate Breakdown

The TideMark system is designed to print on **2–3 build plates:**

| Plate | Parts | Material | Notes |
|-------|-------|----------|-------|
| **Plate 1** | Triangular tower with graduations | PETG (orange/yellow) | Longest print — tower prints vertically |
| **Plate 2** | Lock screws, lock nuts, eye bolt (if printed) | PLA | PLA prints sharper threads than PETG |
| **Plate 3** | Ground stake | PETG or PLA | Stake prints horizontally |

## Thread Specifications

| Connection | Type | Pitch | Notes |
|-----------|------|-------|-------|
| Tower base ↔ Ground stake | Female (tower) / Male (stake) | 3–4mm coarse pitch | Coarse pitch for FDM printability — fine threads strip |
| Lock screw ↔ Tower wall | Through-bolt + nut | 3mm pitch | Bolt passes through hole in tower wall, nut on inside |
| Eye bolt ↔ Tower top | Threaded insert or printed thread | Per eye bolt spec | If using hardware store eye bolt, print matching receiver hole |

## Ground Stake Dimensions

| Segment | Length | Purpose |
|---------|--------|---------|
| Driven section (pointed) | 8" | Penetrates ground |
| Handle/grip section | 2" | Stays above grade, allows hand-tightening or wrench grip |
| Male thread | 1" | Threads into tower base |
| **Total** | **11"** | |

> **Driving the stake:** Use a hammer or small sledge on the handle section. The pointed tip self-starts in most residential soils. For hard or rocky ground, pre-drill a pilot hole with a rebar spike or use a rubber mallet to avoid cracking the printed handle.

## Filament Estimates (Per Complete Stake Assembly)

| Part | Material | Weight | Cost/kg | Cost |
|------|----------|--------|---------|------|
| Tower (PETG) | PETG | ~65g | $20/kg | $1.30 |
| Ground stake (PETG) | PETG | ~30g | $20/kg | $0.60 |
| Lock hardware (PLA) | PLA | ~10g | $18/kg | $0.18 |
| Eye bolt (if printed, PLA) | PLA | ~5g | $18/kg | $0.09 |
| **Total filament** | | **~110g** | | **~$2.17** |

> Hardware store eye bolts are recommended over printed ones for durability under stringline tension. Budget ~$1 per bolt.

## Material Notes

> **Do not use PLA for the tower or ground stake.** PLA deforms at ~60°C (140°F), which is easily reached inside a vehicle or on a sun-exposed job site in Florida/Texas. PETG is the minimum for field use. PLA is acceptable for the lock screw and nut since they don't bear structural loads or sit in direct sun for extended periods.
