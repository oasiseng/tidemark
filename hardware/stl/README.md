# STL Files

Print-ready STL files for all TideMark v1 components.

## Parts List

| File | Description | Material | Print Orientation |
|------|-------------|----------|-------------------|
| `TrianglePiece.STL` | Graduated triangular tower, 16" tall, 3" faces | PETG (orange) | Vertical, graduation face toward bed |
| `GroundStake.STL` | Auger-style ground stake with threaded top | PETG | Horizontal (layers parallel to length) |
| `HookBolt.STL` | Eye bolt for stringline attachment | PLA | Vertical |
| `LockBut.STL` | Lock nut for height clamping | PLA | Flat |
| `TopCap.STL` | Triangular cap — holds bubble level + sticker | PETG (white or contrasting) | Flat, top face up |

## Full Assembly STEP

The complete assembly as a single STEP file is in `../source/TideMark.STEP`. Open in any CAD program (FreeCAD, Fusion 360, SolidWorks, OnShape) to modify or inspect.

## Print Notes

See `/hardware/PRINT-SETTINGS.md` for detailed slicer settings per part.

**Build volume warning:** The TrianglePiece is 16" (406mm) tall. Check your printer's Z-height. If under 400mm, the tower can be printed in two halves with a threaded joint.

**Critical:** Print the GroundStake with layers running lengthwise (horizontal). Vertical orientation will split along layer lines when hammered.
