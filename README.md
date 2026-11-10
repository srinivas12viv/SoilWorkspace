# SoilWorkspace showcase

Open **SoilWorkspace.html** directly in a modern browser. This self-contained file
includes all styling, screenshots, the narrated 90-second overview, and English
captions. It needs no internet connection or installation. Its size is about
22 MB because the video is embedded.

For web hosting, extract **SoilWorkspace-website.zip** and upload `index.html`
and the `assets` folder together. This version keeps media in separate files
for efficient loading. No build, backend, analytics, external fonts, or services
are required. Nothing has been published automatically.

The page includes responsive layouts, keyboard-operable hub tabs, full-size
screenshots, an expandable video transcript, reduced-motion support, and print
styles. Full-size screenshots open in an accessible overlay; press Escape or
select Close to return to the page.

## Editing

Edit the text, styles, and interactions in `index.html`. Then run from the
repository root:

```powershell
python Presentations/SoilWorkspace-showcase/package_showcase.py
```

Packaging uses Pillow to create the video poster and the Python standard library
for embedding and ZIP creation. The page itself has no dependencies.

## Content and provenance

- Brand identity and approved positioning: `docs/BRANDING.md`.
- Latest promotional narrative/video: `Presentations/SoilWorkspace-promo-v9`.
- Experimental screenshot: `build/promo-v2/captures/07-critical-state.png`.
- Calibration, assessment, and modeling screenshots: `build/promo-v4/captures`.
- New copy connects these workflows to the current material-model handoff vision.
- Under active development; coming soon; no announced date or public download.
- Native simulation, optimization, and PLAXIS compilation are demonstrated research
  capabilities and disabled in the installed pilot. Other platform targets are
  explicitly identified as planned.

No mailing-list form or contact address was added because no destination was
provided. Add those only when you have a working endpoint or public contact.

## Verification

Checked in headless Chrome at desktop (1440 px) and mobile (390 px) widths.
Verified no horizontal overflow, loaded screenshots, tab clicks and arrow-key
navigation, screenshot overlay opening/closing, transcript expansion, and release
messaging. The standalone file loaded the full 90-second 1920 × 1080 video and
all 23 English caption cues. Desktop and mobile previews are saved alongside
the source. Video narration was reused from promo v9 without modification.
