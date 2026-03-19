# Frequently Asked Questions

## About TideMark

**Q: What is TideMark?**
A: TideMark is an open-source 3D-printable elevation reference stake that helps contractors set formwork to the correct Finished Floor Elevation (FFE). It consists of a triangular graduated tower, a threaded ground stake, a lock screw, and an eye bolt for stringline. It's designed to be used with a Formwork Elevation Reference Exhibit (FERE) prepared by a licensed Professional Engineer.

**Q: Is TideMark a surveying tool?**
A: No. TideMark is a field reference tool — a graduated stake with a stringline attachment. It helps you execute an elevation that a PE has already determined. It does not measure or establish elevations on its own.

**Q: Can I sell TideMark stakes?**
A: The hardware designs are MIT-licensed — you can print and sell the physical stakes. However, the "TideMark" name and associated branding are trademarks of Oasis Engineering, LLC and cannot be used without permission. If you want to sell them under your own brand, that's fine.

**Q: What printer do I need?**
A: Any FDM printer with sufficient Z-height. The tower is 16" (406mm) tall — most standard printers (Ender 3, Prusa MK3/MK4, Bambu P1/X1) top out around 250mm Z, which is too short. You'll need a tall-format printer (CR-10, Ender 5 Plus, Voron 350, or similar) OR print the tower in two 8" halves that thread together (planned v1.1 feature). The ground stake and lock hardware fit on any printer.

**Q: Why is it triangular?**
A: Three reasons. First, a triangular cross-section is inherently more rigid than rectangular for the same wall thickness — it resists bending and twisting better. Second, three points of contact mean the tower won't wobble on uneven ground. Third, the flat faces provide clean surfaces for graduation marks, branding, and label windows — one function per face.

**Q: Why not injection mold these?**
A: At the volumes we're talking about (tens to hundreds per year, not thousands), 3D printing is more economical and allows rapid design iteration. If demand grows to thousands of units, injection molding becomes viable — the design is intentionally simple enough to mold.

---

## About the FERE Service

**Q: What is a Formwork Elevation Reference Exhibit?**
A: A PE-stamped document that tells the contractor what elevation to build to, where to measure from, and provides the reference framework to execute it in the field. It's a pre-construction elevation determination for FFE purposes.

**Q: Who needs a FERE?**
A: Contractors building slab-on-grade structures (accessory buildings, ADUs, garages, workshops) in or near flood zones where the building department requires FFE documentation but a full survey isn't justified by the project scope.

**Q: How is this different from a topographic survey?**
A: A topo survey maps the entire site with precision. A FERE establishes a few key reference points and tells the contractor what to do with them. It's faster, cheaper, and sufficient for the specific purpose of setting formwork elevation.

**Q: How much does a FERE cost?**
A: Typically $600–$1,800 depending on whether a site visit is included and whether a TideMark kit is bundled. See the exhibit specification for pricing guidance.

**Q: Can any PE prepare a FERE?**
A: Yes. The FERE methodology documented in this repository can be used by any licensed Professional Engineer. The templates, notes, and disclaimers are provided as a starting point. Each PE is responsible for their own professional judgment and compliance with their state's licensing requirements.

---

## Field Use

**Q: What if my offset is more than 16 inches?**
A: The standard TideMark tower measures up to 16 inches. If your offset exceeds this, contact the engineer — you may need an intermediate reference point, a different benchmark, or a taller tower variant.

**Q: Can I use TideMark without a FERE?**
A: You can use it as a general-purpose measuring stake with stringline attachment, but without a PE's elevation determination, you won't know what elevation to set.

**Q: What if I can't find the benchmark?**
A: Stop and call the engineer. Do not estimate or guess. The benchmark may have been disturbed by site activity — the engineer needs to know.

**Q: Does TideMark work on slopes?**
A: Yes, but the ground stake must be driven plumb (vertical), not perpendicular to the slope surface. The graduations assume a vertical orientation.

**Q: Can I leave TideMark stakes in the ground permanently?**
A: The ground stake can stay, but the printed tower should be removed after formwork is set. UV exposure will degrade PETG over weeks/months. Unthread the tower, clean it, and store it for the next job.

**Q: The threads are stiff / won't engage. What do I do?**
A: Clean both threads with a brush — dirt and grit cause binding. If still stiff, thread them together and apart a few times to wear in. If the male thread is slightly oversized (common with FDM), lightly sand the outer diameter with 220-grit. A wrap of Teflon tape can also smooth engagement.

---

## Technical

**Q: Why printed threads instead of metal hardware?**
A: Printed threads keep the entire system self-contained and 3D printable — no hardware store run required (except the optional eye bolt). Coarse-pitch printed threads (3–4mm pitch) are surprisingly strong and hold up well for this application. The lock screw sees minimal load, and the tower-to-stake connection is hand-tight only.

**Q: What thread pitch should I use?**
A: 3–4mm coarse pitch for all connections. Fine threads (≤2mm) strip easily on FDM prints. The exact pitch isn't critical as long as the tower and stake match — they're always used as a set.

**Q: Can I modify the design?**
A: Yes — that's why it's open source. STEP files are provided for editing in any CAD program. See CONTRIBUTING.md for guidelines on submitting improvements back to the project.
