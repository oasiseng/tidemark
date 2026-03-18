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

**Purpose:** Show the property, proposed building location, and benchmark positions in plan view.

**Required elements:**
- Property boundaries with dimensions (from GIS/county records)
- Parcel number and owner of record
- Proposed building footprint with setback dimensions
- Existing structures and improvements
- Benchmark locations (labeled: Screw A, Screw B, Electrical Post, etc.)
- North arrow and graphic scale
- Street names and access

**Data sources:** County GIS, county property appraiser, Google Earth, client-provided site photos

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
  prepared for the use of [CLIENT NAME], Inc. for elevation reference.
  Use by others is not intended without engineer review.

• Finished Floor Elevation (FFE) shall be set at [XXX.XX] or higher.

• Observed reference points include:
  - [BENCHMARK A]: [ELEVATION] NAVD88
  - [BENCHMARK B]: [ELEVATION] NAVD88
  - [BENCHMARK C]: [ELEVATION] NAVD88

• Contractor shall establish final grading, formwork, and elevation
  control necessary to achieve required FFE in accordance with project
  documents.

• No representation is made regarding existing or future site grading
  conditions.

• [BENCHMARK] may be used as a convenient field reference for
  establishing minimum FFE, subject to contractor verification.
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

### 4. Benchmark Photo Exhibits

**Purpose:** Give the contractor a physical thing to find on site.

**Required elements per benchmark:**
- Clear photograph of the benchmark location
- Benchmark identifier (Screw A, Screw B, etc.)
- Observed elevation in NAVD88
- Description of what the benchmark is (helical screw head, concrete nail, existing post base, etc.)
- Arrow or annotation pointing to the exact reference point in the photo

**Field methodology:** See [Benchmark Establishment](#benchmark-establishment) below.

### 5. Foundation Detail

**Purpose:** Visually communicate the FFE relationship to existing grade and benchmark elevations.

**Required elements:**
- Cross-section showing existing grade, proposed slab, and FFE
- Vertical dimension showing offset from reference benchmark to FFE
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

The FERE is based on **limited field observations** — not a full survey. Benchmarks are established using one or more of the following methods:

| Method | Accuracy | When to Use |
|--------|----------|-------------|
| RTK GPS observation | ±0.05 ft | Best accuracy, requires equipment |
| Interpolation from survey-grade benchmarks | ±0.1 ft | When nearby NGS/city benchmarks exist |
| GIS contour interpolation | ±0.5–1.0 ft | Screening-level only |
| Relative measurement from known point | Varies | When one benchmark is established and others are measured relative to it |

### Benchmark Types

Acceptable field benchmarks include:
- **Helical screw/anchor heads** — durable, semi-permanent, low profile
- **Concrete nails or masonry screws** driven into existing hardscape
- **Existing infrastructure** — electrical post bases, fire hydrant flanges, manhole rims
- **Survey monuments** — if accessible (NGS, city benchmarks)

### Benchmark Documentation

For each benchmark, record:
- Identifier (Screw A, Screw B, Post Base, etc.)
- Elevation in NAVD88
- Method of determination
- Date of observation
- Photograph with annotation

### Tie to Published Benchmark (Recommended)

Where possible, tie at least one field benchmark to a published reference:
- NGS monument (datasheet from [NGS website](https://www.ngs.noaa.gov/))
- City/county benchmark (from local survey control network)
- USGS benchmark

If no published benchmark is accessible, note the method used (e.g., "Elevation determined via RTK GPS observation on [DATE] using [EQUIPMENT/SERVICE]" or "Elevation interpolated from [COUNTY] GIS 1-foot contour data dated [YEAR]").

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
| Remote only (GIS/photo-based) | No site visit, GIS contours + client photos | $600–$900 |
| Field observation (1 visit) | Site visit, benchmark establishment, photos | $1,000–$1,500 |
| Field + TideMark kit | Site visit + 4-stake TideMark kit | $1,200–$1,800 |
| Full package | Field + kit + pre-pour verification review | $1,500–$2,200 |

> These are suggested ranges for the service as described. Adjust for local market, complexity, and travel costs. The TideMark kit material cost is ~$29 for a 4-pack — the value is in the service, not the plastic.
