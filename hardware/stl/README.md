# STL Files

## Status: Awaiting CAD Modeling

The STL files for TideMark v1 are in development. This directory will contain print-ready files once the CAD design is finalized and tested.

## Planned Files

| File | Description | Status |
|------|-------------|--------|
| `tidemark-tower-v1.stl` | Triangular graduated tower (16" tall, 3" faces) | In progress |
| `tidemark-groundstake-v1.stl` | Ground stake with pointed tip + male thread | In progress |
| `tidemark-lockscrew-v1.stl` | Lock screw bolt + nut for height clamping | In progress |

## Design Parameters (For CAD)

### Tower Body (Triangular)
- Overall height: 16 inches (406mm)
- Cross section: equilateral triangle, 3 inches (76mm) per face
- Female threaded receiver at base: 1" diameter × 2" deep, 3–4mm coarse pitch
- Eye bolt receiver at top: threaded hole sized to accept 1" loop eye bolt
- Lock screw through-hole: located on one face, perpendicular to graduation face, positioned to allow tool access when tower is in the ground
- Wall thickness: minimum 4mm throughout
- Graduation marks: embossed 0.5mm deep on one flat face
  - Major ticks (full face width) at every 1"
  - Minor ticks (half face width) at every 0.25"
  - Numbers at every 1" mark, 4mm minimum height
  - Scale runs 0" to 16" from base to top
- Label window: 38mm × 19mm recessed 0.3mm on one face (not the graduation face)
- Branding: "TIDEMARK" and "OASISENGINEERING.COM" embossed 0.3mm on remaining face

### Ground Stake
- Total length: 11 inches (279mm)
- Driven section: 8 inches (203mm) with tapered/pointed tip
- Handle/grip section: 2 inches (51mm) — flat or knurled for hand-tightening
- Male thread: 1 inch (25mm), matches tower base female thread, 3–4mm coarse pitch
- Cross section: circular or triangular (triangular preferred for anti-rotation when threading tower on)
- Tip geometry: 4-sided taper, ~30° included angle

### Lock Screw + Nut
- Bolt: threaded shaft, 3mm pitch, length sufficient to pass through tower wall + 5mm engagement
- Bolt head: 1" (25mm) diameter knurled disc for hand-tightening (no tools needed)
- Nut: matching internal thread, sits on inside of tower wall
- The bolt passes through a smooth hole in the tower wall; the nut on the inside provides the clamping force

### Eye Bolt (If Printing)
- Loop: 1" (25mm) internal diameter — large enough for standard stringline
- Shaft: threaded, matches tower top receiver
- Neck: 0.5" (12mm) minimum between loop and thread for strength
- Note: hardware store eye bolts are preferred for durability — printed version is a backup

## Printing Notes

- **Tower prints on Plate 1** in PETG, vertically, graduation face toward build plate for best surface
- **Lock hardware prints on Plate 2** in PLA for sharp threads
- **Ground stake prints on Plate 3** in PETG, horizontally (layers parallel to length)
- See `/hardware/PRINT-SETTINGS.md` for full slicer settings

## Build Volume Warning

The tower is 16" (406mm) tall. Standard printer Z-heights:
- Ender 3: 250mm ❌ (too short)
- Prusa MK3S/MK4: 210mm ❌ (too short)
- Bambu X1/P1: 256mm ❌ (too short)
- Voron 2.4 350: 350mm ⚠️ (close)
- CR-10 / Ender 5 Plus: 400mm ⚠️ (close)
- Custom/tall builds: 500mm+ ✅

**If your printer can't reach 406mm Z:** The tower can be designed as two 8" halves with a threaded or press-fit joint in the middle. This is a planned v1.1 feature.

## Contributing CAD Work

If you'd like to contribute CAD designs:
1. Work in STEP format (universal exchange format)
2. Also export STL at 0.1mm tolerance
3. Follow the dimensions above
4. Submit PR with both STEP and STL files
5. Include a screenshot or photo of a test print for review

Preferred CAD tools: FreeCAD (open source), Fusion 360, SolidWorks, OnShape
