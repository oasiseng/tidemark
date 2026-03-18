# Elevation Control Notes — Template

## Purpose

The Elevation Control Notes section is the most critical part of the FERE. It tells the contractor:
1. What elevation to hit (FFE)
2. Where to measure from (benchmarks)
3. How accurate they need to be (tolerance)
4. What to do if something doesn't match (call the engineer)

## Template

Customize per project. All [BRACKETED] items are project-specific.

---

### ELEVATION CONTROL NOTES

**FINISHED FLOOR ELEVATION:**
Finished Floor Elevation (FFE) shall be set at **[XXX.XX]' NAVD88** or higher.

**OBSERVED REFERENCE POINTS:**

| ID | Description | Elevation (NAVD88) | Method | Date |
|----|------------|-------------------|--------|------|
| [A] | [Helical screw head, NE corner of property] | [619.50]' | [RTK GPS] | [MM/DD/YYYY] |
| [B] | [Helical screw head, SE corner of proposed building] | [621.00]' | [RTK GPS] | [MM/DD/YYYY] |
| [C] | [Existing electrical post base] | [619.00]' | [RTK GPS] | [MM/DD/YYYY] |

**BENCHMARK METHODOLOGY:**
[Benchmark elevations were determined via RTK GPS observation on [DATE] using [EQUIPMENT]. / Benchmark elevations were interpolated from [COUNTY] GIS [X]-foot contour data dated [YEAR].]

**ELEVATION OFFSET TABLE (For TideMark Stake Use):**

| Benchmark | Benchmark Elev. | Required FFE | Offset | TideMark Setting |
|-----------|----------------|-------------|--------|-----------------|
| [Screw A] | [619.50]' | [621.25]' | [+1.75 ft] | [+21 inches] |
| [Screw B] | [621.00]' | [621.25]' | [+0.25 ft] | [+3 inches] |

> This table directly translates the engineering elevation data into a field-usable TideMark stake setting. The contractor sets the TideMark collar to the inch value shown, at the corresponding benchmark location.

**TOLERANCE:**
Elevation verification tolerance for formwork shall be ±0.05 ft unless noted otherwise.

**CONTRACTOR RESPONSIBILITIES:**
- Contractor shall verify all benchmark elevations prior to use.
- Contractor shall establish final grading, formwork, and elevation control necessary to achieve required FFE.
- Prior to concrete placement, contractor shall provide photo documentation of top-of-form elevations with clear measurement reference for engineer verification.
- Any discrepancies between field conditions and this exhibit shall be reported to the engineer prior to proceeding.

**RECOMMENDED FIELD REFERENCE:**
[Screw B / Benchmark B] may be used as a convenient field reference for establishing minimum FFE, subject to contractor verification. [This benchmark is closest to the proposed building location and provides the smallest offset to FFE.]

---

## Notes on the Offset Table

The **Elevation Offset Table** is what makes the TideMark system work. It converts NAVD88 elevations (which mean nothing to most contractors) into a physical measurement the contractor can execute with the stake.

When preparing this table:
- Always round the inch value conservatively (round up to ensure FFE is met, never round down)
- Include both the decimal-foot offset AND the inch conversion
- Note which benchmark is recommended as the primary field reference
- If the offset exceeds the TideMark stake's measurement range (~24"), note that the contractor may need to establish an intermediate reference point
