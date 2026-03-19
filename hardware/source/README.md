# Source CAD Files

## Status: Awaiting Initial Design

This directory will contain editable CAD source files (STEP format) for all TideMark components.

## Planned Files

| File | Description |
|------|-------------|
| `tidemark-tower-v1.step` | Triangular graduated tower — editable source |
| `tidemark-groundstake-v1.step` | Threaded ground stake — editable source |
| `tidemark-lockscrew-v1.step` | Lock screw + nut — editable source |
| `tidemark-assembly-v1.step` | Full assembly for visualization |

## Why STEP Format

STEP (Standard for the Exchange of Product Data) is a vendor-neutral CAD format that can be opened in virtually any CAD program: FreeCAD, Fusion 360, SolidWorks, OnShape, CATIA, Inventor, etc.

This ensures the design remains accessible regardless of what software contributors use.

## Modifying the Design

1. Open the STEP file in your preferred CAD tool
2. Make modifications
3. Export updated STEP file
4. Export STL at 0.1mm tolerance for printing
5. Test print and verify: thread engagement between tower and stake, lock screw clamping, eye bolt fit
6. Submit PR with both files + photos of test print
