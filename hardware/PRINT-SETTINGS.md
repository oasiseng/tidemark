# Print Settings

## Recommended Slicer Settings

### TideMark Tower (`tidemark-tower-v1.stl`)

| Setting | Value | Notes |
|---------|-------|-------|
| Material | PETG or ASA | See material notes below |
| Nozzle temp | 240°C (PETG) / 250°C (ASA) | Adjust per brand |
| Bed temp | 80°C (PETG) / 100°C (ASA) | |
| Layer height | 0.20mm | Balance of speed and graduation legibility |
| First layer | 0.25mm | Better adhesion |
| Walls/perimeters | 4 | Structural rigidity on triangular faces |
| Top/bottom layers | 5 | Protects graduation face |
| Infill | 50% gyroid | Good omnidirectional strength |
| Print speed | 50mm/s | Slower = better surface on graduation face |
| Supports | None required | Triangular profile is self-supporting |
| Orientation | Vertical, graduation face toward build plate | Best surface quality on measurement face |
| Brim | 8mm recommended | Tall part (16") — brim prevents warping and tip-over |

> **Build volume check:** The tower is 16" (406mm) tall. Verify your printer's Z-height can accommodate this. Most standard printers (Ender 3, Prusa MK3/MK4, Bambu P1/X1) have 250mm+ Z, but 406mm may require a tall-format printer or printing at an angle. If your Z is under 400mm, consider printing in two halves with a threaded or friction-fit joint in the middle.

### TideMark Ground Stake (`tidemark-groundstake-v1.stl`)

| Setting | Value | Notes |
|---------|-------|-------|
| Material | PETG (preferred) or PLA | Needs impact resistance for driving |
| Layer height | 0.20mm | |
| Walls/perimeters | 5 | Extra walls for hammer impact strength |
| Infill | 80% gyroid | Near-solid for driving loads |
| Supports | Minimal (for pointed tip only) | |
| Orientation | Horizontal (on its side) | Layer lines parallel to driving force |

> **Critical: print the ground stake with layers running lengthwise (horizontal orientation).** If printed vertically, layer adhesion is the weak link and the stake will split along layer lines when hammered. Horizontal orientation means the hammer force runs parallel to layers, not perpendicular.

### TideMark Lock Screw + Nut (`tidemark-lockscrew-v1.stl`)

| Setting | Value | Notes |
|---------|-------|-------|
| Material | PLA | PLA prints sharper threads than PETG |
| Layer height | 0.16mm | Finer layers for clean thread profile |
| Walls/perimeters | 4 | |
| Infill | 50% | |
| Supports | None required | |
| Orientation | Bolt vertical (head up), nut flat | |

> **Thread pitch:** Use 3–4mm coarse pitch for all printed threads. Fine threads (≤2mm pitch) will strip on FDM prints. Test thread fit before committing to a full batch — you may need to adjust horizontal expansion in your slicer by -0.1 to -0.2mm for clean thread engagement.

## Material Recommendations

### PETG (Recommended for Tower + Ground Stake)

- Good UV resistance
- Impact resistant — won't shatter when dropped or driven
- Prints easily on most FDM printers
- Withstands vehicle interior temperatures (~85°C glass transition)
- Slight flex prevents brittle cracking
- Available in safety orange and bright yellow

### PLA (Recommended for Threaded Hardware Only)

- Prints the sharpest threads of any common filament
- Rigid — threads hold form under clamping pressure
- Fine for lock screws and nuts (not exposed to sun/heat for long periods)
- ⚠️ **Do not use for tower or ground stake** — deforms at ~60°C

### ASA (Best for Extended Outdoor Use)

- Excellent UV resistance (better than PETG)
- Higher temperature resistance
- Requires enclosed printer (warping sensitive)
- Slightly more brittle than PETG
- Best choice if stakes will be left on site for days/weeks

### Nylon / PA6 (Premium Option)

- Extremely tough and impact resistant
- Excellent chemical resistance
- Requires dry box storage and enclosed printer
- More expensive but nearly indestructible
- Good option for production runs if selling kits

## Color Strategy

| Part | Recommended Color | Why |
|------|------------------|-----|
| Tower body | Safety orange or bright yellow | Field visibility, OSHA-adjacent |
| Ground stake | Same as tower or black | Visual unity or practical (gets dirty anyway) |
| Lock screw + nut | Red or white | Contrast against tower — visible lock position in photos |
| Eye bolt | Metal (hardware store) or white PLA | Contrast at top for stringline visibility |

> **For photo verification:** high contrast between the tower graduation face and the lock screw position is critical. A red lock screw on an orange tower reads clearly in a job site photo from 15+ feet away.

## Post-Processing

- **Graduation marks:** If embossed marks aren't deep/visible enough, fill recessed numbers with black acrylic paint and wipe excess with a rag. This creates high-contrast filled lettering.
- **Label area:** Light sanding with 220-grit improves Sharpie adhesion on PETG.
- **Thread fit:** Test-thread the tower onto the ground stake before going to the field. If too tight, run the male thread through the female thread a few times to wear in. If too loose, wrap one layer of Teflon tape on the male thread.
- **Eye bolt:** If using a hardware store eye bolt, drill the receiver hole to match and thread or epoxy in place. If printing the eye bolt, reinforce the loop with a small zip tie as a safety backup.
