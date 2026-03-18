# TideMark™

### Open-source formwork elevation reference stake system

**The thing you're protecting isn't the plastic.** Anyone with calipers and a printer can clone a stake in an afternoon. The IP is the *system* — the PE-stamped elevation exhibit, the field methodology, the service bundle, the brand. None of that lives in an STL file.

---

TideMark is a 3D-printable field tool that helps contractors set formwork to the correct elevation — without a surveyor on site. It turns a dumb rebar stake into a precision elevation reference with integrated ruler, stringline attachment, and sliding target marker.

Designed by [Oasis Engineering, LLC](https://oasisengineering.com) — a structural engineering firm specializing in wind load analysis, residential permwork, and pre-construction elevation services.

## The Problem

Contractors building slabs, accessory structures, and ADUs near flood zones need to hit a specific Finished Floor Elevation (FFE). Today, the typical workflow is:

1. Engineer specifies FFE on plans (e.g., "621.25' NAVD88")
2. Contractor stares at the number
3. Contractor eyeballs it with a tape measure off... something
4. Forms get set wrong
5. Everyone has a bad day

There is no affordable, standardized field tool that bridges the gap between a PE's elevation determination and the contractor's formwork.

**TideMark fixes that.**

## The System

TideMark is not just a stake — it's a field reference system with three components:

| Component | What It Does | Where It Lives |
|-----------|-------------|----------------|
| **TideMark Stake** | Physical elevation reference tool | This repo (open source) |
| **Formwork Elevation Reference Exhibit (FERE)** | PE-stamped elevation determination document | [Service from Oasis Engineering](https://oasisengineering.com) |
| **Field Methodology Guide** | Step-by-step photo-documented workflow | [`/docs/field-guide.md`](docs/field-guide.md) |

The stake is the delivery mechanism. The exhibit is the product. The methodology ties them together.

## How It Works

```
┌─────────────────────────────────────────────────────┐
│                   PRE-CONSTRUCTION                   │
│                                                      │
│  1. PE establishes reference elevations (field obs   │
│     + GIS contours + FEMA FIRM data)                 │
│                                                      │
│  2. PE produces Formwork Elevation Reference Exhibit  │
│     with benchmark locations, FFE, and offset dims   │
│                                                      │
│  3. PE ships exhibit + TideMark stake kit to site    │
└──────────────────────┬──────────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────────┐
│                   FIELD EXECUTION                    │
│                                                      │
│  4. Contractor drives rebar at benchmark location    │
│                                                      │
│  5. Clips TideMark tower onto rebar                  │
│                                                      │
│  6. Sets sliding collar to PE-specified offset       │
│     (e.g., "+6 inches above Screw B")               │
│                                                      │
│  7. Ties stringline through top V-notch              │
│                                                      │
│  8. Sets forms to stringline                         │
│                                                      │
│  9. Photos TideMark stake for documentation          │
└─────────────────────────────────────────────────────┘
```

## Repository Structure

```
tidemark/
├── README.md                    # You are here
├── LICENSE                      # MIT License
│
├── hardware/
│   ├── stl/                     # Print-ready STL files
│   │   ├── tidemark-tower-v1.stl
│   │   ├── tidemark-collar-v1.stl
│   │   └── tidemark-cap-v1.stl
│   ├── source/                  # Editable CAD source files
│   │   ├── tidemark-tower-v1.step
│   │   ├── tidemark-collar-v1.step
│   │   └── tidemark-cap-v1.step
│   ├── BOM.md                   # Bill of materials
│   └── PRINT-SETTINGS.md        # Recommended slicer settings
│
├── docs/
│   ├── field-guide.md           # Step-by-step field usage
│   ├── photo-verification.md    # How to photograph for documentation
│   ├── elevation-basics.md      # FFE, BFE, NAVD88 primer for contractors
│   └── faq.md                   # Common questions
│
├── exhibit/
│   ├── EXHIBIT-SPEC.md          # What goes into a Formwork Elevation
│   │                            #   Reference Exhibit (FERE)
│   ├── SCOPE-OF-SERVICE.md      # Standard scope language for proposals
│   ├── general-notes.md         # Standard general notes for exhibits
│   ├── elevation-control.md     # Elevation control note templates
│   ├── disclaimers.md           # Legal disclaimer language
│   └── examples/
│       └── README.md            # Description of example exhibits
│                                #   (actual exhibits are client work
│                                #    and not included)
│
├── branding/
│   ├── tidemark-logo.svg
│   ├── color-palette.md
│   └── label-template.svg       # Printable adhesive label for stake
│
├── templates/
│   ├── proposal-template.md     # Proposal language for FERE service
│   └── transmittal-template.md  # Client transmittal for exhibit + kit
│
└── CONTRIBUTING.md              # How to contribute
```

## Hardware

### What You Need

| Item | Source | Est. Cost |
|------|--------|-----------|
| TideMark Tower (3D printed) | Print from `/hardware/stl/` | ~$3 in filament |
| TideMark Collar (3D printed) | Print from `/hardware/stl/` | ~$0.50 in filament |
| 3/4" rebar stake, 18" long | Local hardware store | ~$2 |
| Hammer | You already have one | — |
| Sharpie | For labeling | ~$1 |

**Total cost per stake: ~$6.50**

### Print Settings

See [`hardware/PRINT-SETTINGS.md`](hardware/PRINT-SETTINGS.md) for detailed slicer settings.

**Quick reference:**
- **Material:** PETG (preferred for UV/impact) or ASA (best durability)
- **Layer height:** 0.2mm
- **Infill:** 50% gyroid
- **Walls:** 4 perimeters
- **Orientation:** Tower prints vertically (graduation face up for best surface quality)
- **Color:** Safety orange or bright yellow recommended for field visibility
- **Avoid:** PLA (warps in sun, brittle on impact)

### Design Specifications

- **Tower body:** ~12" tall, 1.5" × 1.0" rectangular cross-section
- **Rebar channel:** Sized for 3/4" (#6) rebar with friction fit
- **Graduations:** Embossed inch marks on front face, 1" major / 1/2" minor ticks
- **Stringline notch:** V-notch saddle at top, 1/4" wide × 3/8" deep
- **Collar:** Sliding ring, bright red/contrasting color, friction fit with thumb tab
- **Label window:** 1.5" × 0.75" recessed flat area for Sharpie notation
- **Branding:** "TIDEMARK" and "OASISENGINEERING.COM" embossed on rear face

## The Exhibit (FERE)

The **Formwork Elevation Reference Exhibit** is the engineering document that makes TideMark useful. Without it, TideMark is just a ruler on a stick. With it, it's a precision field reference system.

A FERE includes:

- **Site plan** with proposed building location and benchmark positions
- **Observed reference elevations** (field-measured benchmarks in NAVD88)
- **FEMA FIRM map exhibit** showing flood zone and BFE (if applicable)
- **Photo exhibits** of physical benchmark locations
- **Foundation detail** showing FFE relationship to existing grade
- **Elevation control notes** specifying FFE, tolerances, and contractor responsibilities
- **General notes and disclaimers** clarifying scope limitations

See [`exhibit/EXHIBIT-SPEC.md`](exhibit/EXHIBIT-SPEC.md) for the full specification.

### What a FERE Is NOT

- ❌ Not a boundary survey
- ❌ Not a topographic survey
- ❌ Not a construction survey
- ❌ Not a substitute for field verification by the contractor

It is a **reference tool** based on limited field observations and publicly available GIS/FEMA data, prepared by a licensed Professional Engineer, intended to assist the contractor in establishing formwork elevation.

## Professional Services

**Need a FERE for your project?**

Oasis Engineering provides Formwork Elevation Reference Exhibits as a standalone service for contractors, builders, and homeowners working on:

- Accessory structures (barndominiums, workshops, detached garages)
- ADUs (accessory dwelling units)
- Residential additions in or near flood zones
- Slab-on-grade structures requiring FFE compliance

**What's included:**
- Site visit or remote assessment (GIS/photo-based)
- PE-stamped Formwork Elevation Reference Exhibit
- TideMark stake kit (4 stakes + 4 collars)
- Field methodology guide

📞 **813-694-8989**
🌐 **[oasisengineering.com](https://oasisengineering.com)**
🌐 **[windcalculations.com](https://windcalculations.com)**

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

We welcome:
- CAD improvements and ergonomic refinements
- Field testing feedback and photos
- Alternative print material recommendations
- Translations of the field guide
- Integration ideas (QR codes, NFC tags, digital level adapters)

## License

The TideMark hardware designs are released under the [MIT License](LICENSE).

**TideMark™** is a trademark of Oasis Engineering, LLC. The open-source hardware license covers the physical designs. The TideMark name, logo, and branding are not included in the open-source license.

The Formwork Elevation Reference Exhibit service, methodology, and associated professional engineering deliverables are proprietary services of Oasis Engineering, LLC.

---

*Designed in Tampa, FL by [Oasis Engineering](https://oasisengineering.com) — Structural Engineering · Wind Load Analysis · Elevation Services*
