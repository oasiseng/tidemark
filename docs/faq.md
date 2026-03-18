# Frequently Asked Questions

## About TideMark

**Q: What is TideMark?**
A: TideMark is an open-source 3D-printable elevation reference stake that helps contractors set formwork to the correct Finished Floor Elevation (FFE). It's designed to be used with a Formwork Elevation Reference Exhibit (FERE) prepared by a licensed Professional Engineer.

**Q: Is TideMark a surveying tool?**
A: No. TideMark is a field reference tool — a ruler with a stringline attachment that clips onto rebar. It helps you execute an elevation that a PE has already determined. It does not measure or establish elevations on its own.

**Q: Can I sell TideMark stakes?**
A: The hardware designs are MIT-licensed — you can print and sell the physical stakes. However, the "TideMark" name and associated branding are trademarks of Oasis Engineering, LLC and cannot be used without permission. If you want to sell them under your own brand, that's fine.

**Q: What printer do I need?**
A: Any FDM printer with at least a 200mm × 200mm × 300mm build volume. The tower is about 12 inches tall — that's the critical dimension. Prusa, Bambu Lab, Creality Ender 3, etc. all work.

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

**Q: What if my offset is more than 24 inches?**
A: The standard TideMark tower measures up to 24 inches. If your offset exceeds this, contact the engineer — you may need an intermediate reference point, a different benchmark, or a taller tower variant.

**Q: Can I use TideMark without a FERE?**
A: You can use it as a general-purpose measuring stake with stringline attachment, but without a PE's elevation determination, you won't know what elevation to set.

**Q: What if I can't find the benchmark?**
A: Stop and call the engineer. Do not estimate or guess. The benchmark may have been disturbed by site activity — the engineer needs to know.

**Q: Does TideMark work on slopes?**
A: Yes, but on steep slopes the rebar must be driven plumb (vertical), not perpendicular to the slope surface. The graduations assume a vertical orientation.

**Q: Can I leave TideMark stakes in the ground permanently?**
A: The rebar will stay, but the printed tower should be removed after formwork is set. UV exposure will degrade the plastic over weeks/months, and it serves no purpose after the pour.

---

## Technical

**Q: Why 3/4" rebar?**
A: It's the most commonly available size on residential job sites, strong enough to drive without bending, and provides a stable base for the tower. The design can be adapted for other sizes by modifying the channel dimension in the CAD source files.

**Q: Why not use a metal stake for everything?**
A: A metal stake doesn't have graduated markings, a stringline notch, a label area, or a sliding target collar. The 3D-printed tower is the "smart" part that turns a dumb stake into a reference tool. Printing it is cheap, fast, and customizable.

**Q: Can I modify the design?**
A: Yes — that's why it's open source. STEP files are provided for editing in any CAD program. See CONTRIBUTING.md for guidelines on submitting improvements back to the project.
