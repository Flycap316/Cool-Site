# Cool & Unusual studio website – MOCKUP v2.4 (not published)
This is static HTML/CSS for GitHub Pages: relative links, no JavaScript, built mobile-first. It's for Fly to review and hasn't been pushed or published anywhere.

## Pages
- index.html: proposed hero (Option B), Sarah's hero line and intro, PAM and CUTTS cards, Discord block
- pam.html: proposed hero (Option A) and all of Sarah's PAM copy
- cutts.html: Sarah's CUTTS copy (Rachel reviewed it 10/23)
- press.html: short and long blurbs, logo thumbnails, key art, fact sheet, project blurbs
- style.css: Monica's tokens as CSS variables (--cu-void/amethyst/violet/gold/parchment, --cu-void-90, --cu-line). Spacing scale is 4/8/16/24/40/64, max width 1200 px, corner radius 8 on buttons and 12 on cards, and pixel art uses `.pixel { image-rendering: pixelated }`.

## Assets (assets/)
- hero-A-clean-desktop-1920x1080.png and hero-A-clean-mobile-1080x1920.png: PAM page hero
- hero-B-clean-plate-desktop-1920x1080.png and hero-B-clean-plate-mobile-1080x1920.png: front page hero background
- PAM-lantern-row-hub-v1.1-full-1920x1080.png: PAM card and press key art
- cu-logo-horizontal.png, cu-logo-stacked.png, cu-mark.png: logos, only scaled down from the kit's 4096 px files
- archive/: v2 and v2.1 assets that are no longer used

## Version notes
### v2.4 (2026-10-23)
- **Fonts** (Google Fonts, set as CSS variables):
  - `--font-display`: Cinzel Decorative 700, used for the hero and big titles (h1)
  - `--font-heading`: Cinzel Bold, used for h2 and h3
  - `--font-body`: Inter
  - `--font-accent`: Cormorant Garamond Italic, used once, for the Fly quote
- **18+ wording:**
  - The banner and footer short line is now "Cool & Unusual is an 18+ community."
  - The notice heading and the Discord rule now read "Grown folks only (18+)".
  - All NSFW / "not NSFW" phrasing is removed. Here "adult" means grown folks only.
- **Discord:** every invite link points to the placeholder `#discord-invite-TBD`, marked "Invite link coming soon".
- **Copy:** pages re-pulled from Sarah's updated copy doc and matched word for word on the new 18+ wording: the notice, the Discord rule line, the long press blurb, and the fact sheet's Audience and Community rows. The "grown-ups who never stopped playing" tagline is unchanged. The pages and Sarah's doc no longer differ.
- The top banner shows only the short line "Cool & Unusual is an 18+ community." I took that from the brief, because Sarah's doc doesn't have a separate banner line.
### v2.3 (2026-10-23)
- Both hero labels now say "Chosen hero (Fly via Monica)" instead of "Proposed hero, pending Fly's pick": hero B on the front page, hero A on the PAM page.
- The CUTTS card art is still a placeholder. Monica's goblin art for CUTTS is on its way and will replace it.
- Nothing else changed.
### v2.2 (2026-10-23)
- Monica has confirmed `--cu-gold-dk` #E6A100 (Gold hover) and `--cu-crimson` #C0353F (danger only) as provisional kit tokens, pending Fly's review.
- Swapped in Monica's clean art (now in assets/):
  - Front page uses hero-B-clean-plate-{desktop,mobile}. The real logo, h1 and buttons sit over it in HTML on a 60% Void overlay.
  - PAM page uses hero-A-clean-{desktop,mobile}, with "Concept art – not gameplay" as live text on the image.
  - Both keep the "Proposed hero, pending Fly's pick" label.
- The PAM card and press key art now use the full PAM-lantern-row-hub-v1.1-full-1920x1080.png. The browser fits it to 16:9 with object-fit: cover, and it carries a live-text concept label. The crop placeholder label is removed.
- The old baked-in hero PNGs and the Sorting House crop are no longer used. They've moved to assets/archive/, not deleted.
- CUTTS card art is still TBD.
### v2.1 (2026-10-23)
- Switched fully to Monica's Visual Kit v1.0:
  - Primary buttons now use Gold (`--cu-gold` #FFB300) with Void text, a contrast of about 10.9:1 (WCAG AAA). On hover they turn #E6A100, still with Void text, at about 8.8:1.
  - Headings use Cinzel and body text uses Inter, both from Google Fonts.
- Removed the `--cu-teal` override and Pixelify Sans.
- Crimson (`--cu-crimson`) is kept for danger states only.
- The PAM card crop is labelled "Placeholder, Lantern Row frame pending".
- Nothing else changed from v2. v2 is archived in Drive at Studio Website/Archive/v2.
### v2 (2026-10-23)
- Copy is word for word from Sarah's revised "Studio Website Copy - Draft v1":
  - CUTTS now reads "in development, closed beta coming", and the tags and badges say the same.
  - Added the line "Run it in any world you like. Nexus is just a place to start."
  - Updated the fact sheet (Cool and Unusual Studio, Texarkana TX, proposed press contact).
  - Each front-page teaser name now sits on its own heading line.
  - Placeholder-copy labels are gone wherever real copy went in.
- Footer legal links now go to the Privacy, Terms and Delete account pages.
- Applied Monica's Visual Kit §4: slot sizes (header logo 240/150 px, cards 16:9 at 800×450, press thumbnails 480×270, Discord mark 96 px, footer logo 120 px), tokens, spacing, corner radius, pixel-art rendering, concept-art captions, and a Violet focus ring.
- Fixed the nested <p> in pam.html.
### v1
- Layout skeleton with placeholder copy. It's archived in Drive at Studio Website/Archive/v1.

## Conflicts (RESOLVED in v2.1 per Monica's kit)
- Primary buttons: Teal (brief) vs Gold (kit). Resolved: Gold.
- Fonts: Pixelify Sans (brief) vs Cinzel/Inter (kit). Resolved: Cinzel headings, Inter body.

## Still TBD (shown in dashed [TBD] boxes)
- Discord invite link from Madison (href is `#discord-invite-TBD`, labelled "Invite link coming soon")
- How to get the CUTTS beta (Fly to decide)
- Fact sheet: PAM release date, founded, team size, social links (all Fly), and the logos and screenshots package
- Press contact lenn@coolunusualstudio.com is only proposed until Fly confirms it
- Gaps: CUTTS key art, gameplay screenshots, OG image, favicon (uses cu-mark.png until the cu-app-icon PNGs arrive)
