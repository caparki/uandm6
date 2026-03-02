# Unity & Motion Cloudflare Pages V6

This version is tightened to be closer to the live site, with a proper drop-in logo image slot.

## Main logo
Put your site logo here:

- `assets/images/logo.png`

If `logo.png` is missing, the site shows a simple placeholder box.

## Main page images
Put these into `assets/images/`:

- `home-hero.jpg`
- `showreel.jpg`
- `work-1.jpg`
- `work-2.jpg`
- `clients-hero.jpg`

## Optional client logos
If you want to replace the text placeholders on the Clients page with actual logo files later, create this folder:

- `assets/images/client-logos/`

Then add PNG files with these exact names:

- `slazenger.png`
- `stella-artois.png`
- `tefal.png`
- `amazon-advertising.png`
- `wimbledon.png`
- `kpmg.png`
- `watches-of-switzerland.png`
- `english-heritage.png`
- `harrods.png`
- `rosewood-london.png`
- `chanel.png`
- `shaftesbury-plc.png`
- `innovate-uk.png`
- `reebok.png`
- `heathrow.png`
- `vsu.png`
- `tesco.png`
- `rbs.png`
- `41-digital.png`
- `ukri.png`
- `airbus.png`
- `oneweb.png`
- `ses.png`
- `thales.png`

If any client logo file is missing, the site automatically falls back to text for that brand.

## Deploy
Upload to GitHub, then connect the repo to Cloudflare Pages with:
- Framework preset: None
- Build command: blank
- Output directory: /

## V7 changes
- Replaced the Work page showreel image with the provided Vimeo embed
- Removed Instagram from the header
- Tightened the header/nav spacing to be closer to the live site

## V8 desktop layout update
- Home page now matches the desktop screenshot much more closely
- Logo moved to the top-left with navigation on the top-right
- Mission section rebuilt as a two-column layout
- Main image moved below the mission block, matching the screenshot order
- Showreel embed retained on the Work page

## V9 homepage correction
- Removed the left-side EST / THE FUTURE / dash block
- Replaced OUR MISSION with UNITY & MOTION
- Kept the same heading style while simplifying the homepage structure

## V10 work page update
- Replaced placeholder work items with embedded videos
- Added these projects in order:
  - Reebok
  - The Ritz London
  - Plum Valley : Faces of Chinatown Campaign : Shaftesbury Plc
  - #LifeAtHeathrow Presents The Extraordinaires
  - Visit London: England Originals: Western Wonders tour

## V11
- Removed the footer from all pages

## V12 clients page update
- Replaced the clients text/logo grid with a single supplied logo-wall image
- Added `assets/images/clients-logos-wall.png`

## V13 nav hover update
- Added Squarespace-style nav hover behaviour
- When hovering a nav item, the other menu items fade grey and the hovered item stays black

## V14 work page layout update
- Reworked the Work page to match the supplied screenshot more closely
- Larger top spacing and centred SHOWREEL section
- Each project title now sits underneath the corresponding video, aligned bottom-left

## V15 homepage title update
- Removed the mission paragraph under UNITY & MOTION
- Added the small dash underneath the heading

## V16 asset + showreel fix
- Added the supplied logo to `assets/images/logo.png`
- Added the supplied clients hero image to `assets/images/clients-hero.jpg`
- Added the supplied home hero image to `assets/images/home-hero.jpg`
- Fixed the Work page showreel sizing bug