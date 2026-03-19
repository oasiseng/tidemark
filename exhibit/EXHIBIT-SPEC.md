# Formwork Elevation Reference Exhibit (FERE) — Specification

## Overview

A **Formwork Elevation Reference Exhibit (FERE)** is a PE-stamped engineering document that provides contractors with the elevation context needed to set formwork correctly — without requiring a full boundary or topographic survey.

It is a **pre-construction elevation determination** for FFE purposes, designed for accessory structures, ADUs, and small residential projects where a full survey is not economically justified but the building department still requires documented FFE compliance.

## When a FERE Is Needed

- Accessory structure (barndominium, workshop, detached garage) in or near a Special Flood Hazard Area (SFHA)
- ADU or residential addition requiring FFE above Base Flood Elevation (BFE)
- Slab-on-grade construction where the contractor has no survey and no elevation reference
- Any project where the jurisdiction requires FFE documentation but the scope doesn't warrant a full topographic survey

## Document Components

A complete FERE consists of the following sheets/exhibits:

### 1. Site Plan Exhibit

**Purpose:** Show the property, proposed building location, and installed TideMark benchmark positions in plan view.

**Required elements:**
- Property boundaries with dimensions (from GIS/county records)
- Parcel number and owner of record
- Proposed building footprint with setback dimensions
- Existing structures and improvements
- Installed TideMark stake locations (labeled: Stake A, Stake B, etc.)
- North arrow and graphic scale
- Street names and access

**Data sources:** County GIS, county property appraiser, Google Earth, field observations

### 2. Elevation Control Notes

**Purpose:** Establish the elevation framework and contractor responsibilities.

**Required content:**

```
ELEVATION CONTROL NOTES

• All elevations are referenced to NAVD88 datum unless noted otherwise.

• Reference point elevations are valid at time of observation only and
  may be altered by grading or construction activities. Contractor shall
  verify prior to use.

• Prior to concrete placement, contractor shall provide documentation of
  top-of-form elevations (including photos with clear measurement
  reference) for verification.

• Any discrepancies between field conditions and this exhibit shall be
  brought to the engineer's attention prior to proceeding with construction.

• Finished Floor Elevation (FFE) refers to the top surface of the
  finished slab unless noted otherwise.

• Elevation verification tolerance for formwork shall be ±0.05 ft
  unless noted otherwise.

• This exhibit is intended as a reference tool only and shall not be used
  as a substitute for survey or construction documents. This exhibit is
  prepared for the use of [CLIENT NAME] for elevation reference.
  Use by others is not intended without engineer review.

• TideMark elevation reference stakes were installed on [DATE] at the
  locations shown on the site plan. Stakes were set to the FFE offset
  heights shown in the Elevation Offset Table below. Do not move,
  re-drive, or adjust the installed stakes. If a stake has been
  disturbed, contact the engineer before use.
```

### 3. FEMA FIRM Flood Map Exhibit

**Purpose:** Show the flood zone designation and provide context for the FFE requirement.

**Required elements:**
- FEMA FIRM map panel clipped to project area
- Property location identified on the FIRM
- Flood zone designation (Zone A, AE, X, etc.)
- Base Flood Elevation if published (Zone AE)
- Community panel number and effective date
- Note if Zone A (no published BFE — community may require BFE determination)

**Data source:** FEMA National Flood Hazard Layer (NFHL) via MSC or GIS

### 4. TideMark Stake Photo Exhibits

**Purpose:** Give the contractor a visual reference to confirm each installed stake is undisturbed.

**Required elements per stake:**
- Clear photograph of the installed TideMark stake in its benchmark location
- Stake identifier (Stake A, Stake B, etc.)
- Observed benchmark elevation in NAVD88
- Lock screw position (offset to FFE) visible in photo
- Arrow or annotation pointing to the exact stake and surrounding context
- Description of nearby reference features so the contractor can confirm they're at the right stake

**These photos are taken during the site visit when the stakes are installed.**

### 5. Foundation Detail

**Purpose:** Visually communicate the FFE relationship to existing grade and benchmark elevations.

**Required elements:**
- Cross-section showing existing grade, proposed slab, and FFE
- Vertical dimension showing offset from TideMark benchmark to FFE
- Slab thickness and reinforcement callout
- Grade slope notation if applicable
- Note: "Graphic and callouts shown are for illustrative purposes only to convey relative elevation relationships."

**Note:** This detail may be project-specific or a standard "typical" depending on foundation type. Label accordingly.

### 6. GIS/Contour Exhibit (Optional but Recommended)

**Purpose:** Show approximate topographic context from publicly available data.

**Required elements:**
- County GIS contour data clipped to project area
- Contour interval noted
- Data source and date attributed
- Disclaimer: contour data is approximate

## Benchmark Establishment

### Methodology

The FERE is based on a **differential elevation survey** performed during the site visit. The engineer observes reference elevations and installs TideMark stakes at benchmark locations during the same visit.

| Method | Accuracy | When to Use |
|--------|----------|-------------|
| RTK GPS observation | ±0.05 ft | Best accuracy, requires equipment |
| Differential leveling (auto level + rod) | ±0.01 ft | High accuracy, standard survey method |
| Total station | ±0.02 ft | Good accuracy, versatile |
| Interpolation from survey-grade benchmarks | ±0.1 ft | When nearby NGS/city benchmarks exist |

### TideMark Stake as Benchmark

In the FERE workflow, the TideMark stake serves double duty:
- **It IS the benchmark** — driven at a location with a known observed elevation
- **It IS the reference tool** — the graduation marks and lock screw translate that elevation into a physical target for the contractor

The engineer installs the stakes during the site visit, sets the lock screw to the correct FFE offset, and photographs each one. The contractor's job is simply to confirm the stakes are undisturbed, tie stringline, and set forms.

### Benchmark Documentation

For each installed TideMark stake, record:
- Identifier (Stake A, Stake B, etc.)
- Location description and coordinates
- Observed ground elevation at stake location in NAVD88
- Required FFE offset (in feet and inches)
- Lock screw position set to (in inches)
- Date of installation
- Photograph with annotation

### Tie to Published Benchmark (Recommended)

Where possible, tie at least one observation to a published reference:
- NGS monument (datasheet from [NGS website](https://www.ngs.noaa.gov/))
- City/county benchmark (from local survey control network)
- USGS benchmark

If no published benchmark is accessible, note the method used (e.g., "Elevation determined via RTK GPS observation on [DATE] using [EQUIPMENT/SERVICE]").

**Transparency on methodology is your protection.** State how you got the number. Don't pretend consumer GPS is survey-grade — just disclose it.

## Disclaimers

Every FERE must include the following (adapt to jurisdiction):

```
GENERAL DISCLAIMER

This exhibit is intended as a reference tool only and shall not be used
as a substitute for boundary, topographic, or construction survey.

This exhibit does not constitute a boundary, topographic, or
construction survey.

The contractor is solely responsible for verifying all field conditions,
layout, and elevations prior to construction.

Elevations shown are based on limited site observations and are provided
for reference only.

The engineer of record assumes no responsibility for the contractor's
means, methods, sequencing, or field procedures for achieving the
specified finished floor elevation.

TideMark stakes installed on site are reference tools only. Do not move,
re-drive, or adjust installed stakes. If a stake appears disturbed,
contact the engineer before use.
```

## Deliverable Format

- **Sheet size:** ARCH D (24" × 36") or ANSI D (22" × 34")
- **File format:** PDF (stamped and signed)
- **Stamp:** PE stamp of the engineer of record, dated and signed
- **Project number:** Assigned per firm standards
- **Sheet numbering:** A.1 (Site Plan), A.2 (Details), etc.

## Pricing Guidance

| Service Level | Scope | Suggested Range |
|---------------|-------|-----------------|
| Remote only (GIS/photo-based) | No site visit, GIS contours + client photos, no stakes | $600–$900 |
| Standard FERE | Site visit, elevation survey, TideMark stake installation (2–4 stakes), exhibit | $1,200–$1,800 |
| Full package | Standard FERE + pre-pour photo verification review | $1,500–$2,200 |
| Re-visit (post-grading) | Return to verify/re-set stakes after site grading | $400–$700 per visit |

> The TideMark stake material cost is under $10 per unit — the value is in the site visit, the elevation survey, and the PE-stamped exhibit. The stakes are the delivery mechanism for the engineering judgment.
