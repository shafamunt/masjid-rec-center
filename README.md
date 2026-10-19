# Masjid Recreation Center

A concept plan and fundraising package for a community recreation center at
2452 E 12 Mile Rd, Warren, Michigan, next to DUM (Dar-ul-Mustafa).

Fundraising target: $300,000.

## What is in this repo

- `floorplan.html`: the scaled site plan (one full basketball court at
  94 x 50 ft, one shared multi-use net court sized for tennis at 78 x 36 ft
  with painted overlays for pickleball, volleyball, and racquetball, plus a
  parking estimate, future building placeholder, setbacks, and the donor
  tier structure for the $300,000 campaign). Self-contained, no build step.
- `lot-research.md`: what is known about the parcel. The lot dimensions are
  currently UNVERIFIED; the plan uses a labeled working assumption until
  the real parcel card is pulled from the City of Warren Assessor.
- `grants.md`: verified grant prospects in Michigan and nationally that
  could plausibly fund youth recreation and court construction.
- `README.md`: this file.

Hosted artifact slug: `masjid-rec-center-concept-plan` (web_static). Open and share it from its artifact card in Muse.

## How to view the plan locally

Open `floorplan.html` in any web browser. No server, no dependencies.

## Continuing this work

Another AI picking this up should:

1. Read `lot-research.md` first. If the real lot dimensions are still
   unverified, that is the top priority: the numbers in `floorplan.html`
   depend on them.
2. Edit `floorplan.html` directly for plan changes (it is one
   self-contained file: SVG drawing plus the fundraising section).
3. Edit `grants.md` to add new prospects; only list programs you have
   verified to exist, with a real link each.
4. Edit `lot-research.md` when the parcel card, zoning, or ownership is
   confirmed; remove the working assumption and update the plan to match.
5. Commit your changes with a clear message.
6. Hand the result back to Shafayet's Muse to rebuild and redeploy the
   hosted artifact. Do not publish or share the plan publicly on your own.

## Design notes from Shafayet

- Any spare space on the site would become either a weight room or another
  use to be decided (recorded Oct 19, 2026). When the real lot dimensions
  are known, size the weight room after the two courts and parking are
  placed.

## Status

- [ ] Confirm lot dimensions and zoning (City of Warren Assessor)
- [ ] Board approves donor tier names and amounts
- [ ] Confirm masjid 501(c)(3) status for grant applications
- [ ] First grant application filed
