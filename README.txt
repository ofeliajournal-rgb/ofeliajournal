PARASHAT HASHAVUA — WEBSITE, FIRST VERSION
================================================

What this is
------------
A small static website: one page per weekly Torah portion, each holding
the reading PDFs, the full Hebrew audio, and the nine one-page extras.
Built November 1, 2026. NOT published yet — these files are the upload
package, nothing here is live on the internet until you upload it.

Contents
--------
index.html                  Home page, list of portions
vayera.html                 Parashat Vayera page (example portion)
vayera/                     Vayera kit files
  vayera-reading-large-print.pdf    (18 pages, pointed Hebrew)
  vayera-reading-compact-print.pdf  (7 pages, print version)
  vayera-full-reading.mp3           (17:12, all 147 verses)
  extras/                   Nine one-page PDFs
images/vayera-illustration.png      Artwork shown on the Vayera page

How to publish it free (Cloudflare Pages)
------------------------------------------
1. Create a free account at dash.cloudflare.com (no card needed).
2. Go to Workers & Pages, then "Create application", then Pages,
   then "Upload assets".
3. Drag this whole folder (or the zip) in, give the project a name,
   and deploy. You get a free address like your-site.pages.dev.
4. Later, a custom domain can be added free in the same dashboard.

Adding a new portion each Friday
--------------------------------
1. Create a folder for the portion (for example: chayei-sara/).
2. Put its two reading PDFs, audio, and nine extras inside.
3. Copy vayera.html to the new portion's page and change the title,
   dates, verses, and file links.
4. Add one entry to the Portions list in index.html.
5. Re-upload the folder to Cloudflare Pages.

Notes
-----
- Vayera carries the October 31 kit: quiz in English, words page with
  written translations, Chicago candle-lighting. From Chayei Sara
  onward, kits follow the updated format: quiz in Hebrew, word
  meanings as sketches, Jerusalem candle-lighting times.
- Total size of this package: about 17 MB. Largest single file is
  the audio at about 7 MB — well under Cloudflare Pages' 25 MB
  per-file limit. No bandwidth cap applies to static files.
