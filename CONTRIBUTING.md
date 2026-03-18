# Contributing to TideMark

Thanks for your interest in improving TideMark. This project is maintained by [Oasis Engineering, LLC](https://oasisengineering.com).

## How to Contribute

### Report Field Experience

The most valuable contributions are real-world field testing reports. If you've printed and used a TideMark stake on a job site, we want to hear about it.

Open an issue with:
- What you printed (material, settings, printer)
- Soil conditions (soft fill, compacted, rocky, etc.)
- How the rebar fit worked
- Whether the collar held position
- Photos of the stake in use (huge bonus)
- What broke or didn't work

### Hardware Improvements

If you've modified the design and it works better, submit a PR with:
- Updated STL and STEP files in `/hardware/`
- A brief description of what changed and why
- Photos or test results if possible

Please maintain backward compatibility with 3/4" rebar unless proposing a new size variant.

### Documentation

Improvements to the field guide, FAQ, and elevation primer are welcome. Contractors are the primary audience — write for someone who knows concrete but not geodetic datums.

### Translations

The field guide in particular would benefit from Spanish translation for crews in FL, TX, AZ, and other states with large Spanish-speaking contractor workforces.

## Design Principles

When proposing changes, keep these in mind:

1. **Field-first.** If it doesn't survive a muddy job site and a contractor who doesn't read instructions, it's not ready.
2. **Printable on consumer FDM.** No SLA, no multi-material, no supports-required geometries if avoidable.
3. **Readable from 10 feet.** Numbers, marks, and the collar position should be visible in a job site photo taken from a reasonable distance.
4. **Cheap per unit.** The goal is under $10 total cost per stake including hardware. Don't optimize for elegance at the expense of accessibility.
5. **Compatible with the FERE workflow.** The stake exists to execute the information on a Formwork Elevation Reference Exhibit. Design decisions should support that workflow.

## What We Won't Merge

- Designs that require proprietary or expensive materials
- Features that make the stake harder to use, not easier
- Branding modifications (the TideMark name and Oasis Engineering branding are trademarks)
- Changes that compromise structural integrity for aesthetics

## Code of Conduct

Be professional. This is an engineering tool — treat discussions with the same rigor and respect you'd bring to a plan review meeting.

## Questions?

Open an issue or contact Oasis Engineering directly at 813-694-8989.
