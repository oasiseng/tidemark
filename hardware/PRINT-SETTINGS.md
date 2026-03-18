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
| Walls/perimeters | 4 | Impact resistance on rebar channel |
| Top/bottom layers | 5 | Protects graduation face |
| Infill | 50% gyroid | Good omnidirectional strength |
| Print speed | 50mm/s | Slower = better surface on graduation face |
| Supports | None required | Designed for supportless printing |
| Orientation | Vertical, graduation face up | Best surface quality on measurement face |
| Brim | 5mm recommended | Tall narrow part — brim prevents warping |

### TideMark Collar (`tidemark-collar-v1.stl`)

| Setting | Value | Notes |
|---------|-------|-------|
| Material | PETG or TPU | Contrasting color (red, white) |
| Layer height | 0.20mm | |
| Walls/perimeters | 3 | |
| Infill | 30% gyroid | Lighter is fine — no impact loads |
| Supports | None required | |
| Orientation | Flat (ring axis vertical) | |

### TideMark Cap (`tidemark-cap-v1.stl`)

| Setting | Value | Notes |
|---------|-------|-------|
| Material | Same as tower | |
| Layer height | 0.20mm | |
| Walls/perimeters | 3 | |
| Infill | 30% | |

## Material Recommendations

### PETG (Recommended for Most Users)

- Good UV resistance
- Impact resistant — won't shatter when dropped
- Prints easily on most FDM printers
- Withstands vehicle interior temperatures (~85°C glass transition)
- Slight flex prevents brittle cracking
- Available in safety orange and bright yellow

### ASA (Best for Extended Outdoor Use)

- Excellent UV resistance (better than PETG)
- Higher temperature resistance
- Requires enclosed printer (warping sensitive)
- Slightly more brittle than PETG
- Best choice if stakes will be left on site for days/weeks

### PLA (Prototyping Only)

- ⚠️ **Do not use for field stakes**
- Deforms at ~60°C — a truck dashboard in Florida exceeds this
- Brittle on impact — will crack if stepped on
- Fine for testing fit, tolerances, and ergonomics before committing to PETG

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
| Collar | Red or white | Contrast against tower for photo readability |
| Cap | Same as tower | Visual unity |

> **For photo verification:** high contrast between tower and collar is critical. A red collar on an orange tower reads clearly in a job site photo from 15+ feet away.

## Post-Processing (Optional)

- **Graduation marks:** If embossed marks aren't deep/visible enough, fill recessed numbers with black acrylic paint and wipe excess with a rag. This creates high-contrast filled lettering.
- **Label area:** Light sanding with 220-grit improves Sharpie adhesion on PETG.
- **Rebar channel:** Test fit with actual rebar. If too tight, a single pass with a round file opens it up. If too loose, a strip of electrical tape on the rebar adds friction.
