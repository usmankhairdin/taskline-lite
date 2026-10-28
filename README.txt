TASKLINE LITE — STATIC HTML TEMPLATE
Version 1.0.0 | 25 October 2026

START HERE
Unzip the complete package, then open index.html in a modern browser.
The finished page needs no Node.js, React, Vite, application build, account
or internet connection. Keep index.html and the assets folder together.
If a browser restricts local fonts, its included system-font fallback works;
you can also use a local static server to preview the exact hosted result.

WHAT THIS IS
A free, editable product landing-page template. Taskline is a fictional
demonstration identity, not an operating SaaS product or a trademark/domain
availability claim. The six-card board is illustrative HTML content. There
are no accounts, stored tasks, signup, payments, forms or message delivery.
All on-page CTAs lead to real sections. The footer also links to UKD Store.

FILES
index.html                         Content, board, navigation and native FAQs
assets/css/taskline.css             Editable design tokens and page styles
assets/css/tailwind.css             Ready-to-use compiled utilities/reset
assets/css/tailwind.source.css      Optional Tailwind rebuild input
assets/css/lenis.css                Local smooth-scroll library stylesheet
assets/js/taskline.js               Editable menu, FAQ and scrollbar behavior
assets/js/lenis-1.3.27.min.js        Pinned local Lenis browser distribution
assets/img/taskline-mark.svg        Original Taskline mark and favicon
assets/fonts/                      Local Manrope font, Latin variable weights
licenses/                          Full retained dependency/font notices
LICENSE                            MIT license, including upstream attribution
THIRD_PARTY_NOTICES.txt             Source revision and adaptation provenance

EDITING
1. Edit text directly in index.html. The page sections have stable IDs:
   top, preview, features, workflow, use-cases and faq.
2. The board has exactly six task cards and two Ready cards. If you change
   that content, update its visible counts and each lane's accessible count.
3. Edit the named colors, spacing and font tokens at the top of taskline.css.
   There is no dark theme or hidden alternative design.
4. Change the brand/wordmark and SVG mark for your own product. Replace the
   fictional-product copy when connecting a genuine product.
5. Edit actual CTA href destinations in index.html. Do not replace them with
   empty links or imply signup/payment works unless you implement it.
6. Optional: replace the font with a licensed local font and update @font-face.
   Keep the supplied Manrope license if you distribute that font.
7. Preserve applicable MIT/font notices. See LICENSE for granted rights.

HOSTING AT YOUR DOMAIN ROOT
1. Back up the current site before replacing anything on your hosting account.
2. Upload index.html, assets/, LICENSE, licenses/ and the guide/notices to the
   site's document root, such as public_html/ in cPanel. Upload the CONTENTS
   of the extracted template folder, not an extra nested folder, if you want
   https://your-domain.example/ to open this page.
3. Ensure index.html is the default document and enable HTTPS through your host.
4. Open the domain; check the mark, font, board, menu, FAQ and section links.
No server-side app, database, SPA rewrite or Node process is required.

HOSTING IN A SUBFOLDER
Upload the same files into a folder such as public_html/taskline/ and visit
https://your-domain.example/taskline/ (with the final slash). All local asset
paths are relative, so no source rebuild or base-path change is needed.
The page uses native hash anchors rather than application routes.

STATIC HOSTS
You may upload this folder to a static host such as Netlify or GitHub Pages.
Publish the folder containing index.html. A build command is not required
when using the supplied compiled CSS. Domain/DNS setup belongs to your host.
Preview privately before replacing an existing public site.

OPTIONAL LOCAL HTTP PREVIEW
With Python installed, run in this folder:
  python -m http.server 8080 --bind 127.0.0.1
Then visit http://127.0.0.1:8080/ . Stop the server with Ctrl+C.
This optional command is not required by the template or by your web host.

OPTIONAL TAILWIND DEVELOPMENT
Ordinary edits to taskline.css and page text need no CSS rebuild. If you add
new Tailwind utility classes, install the pinned development tool first:
  npm ci --ignore-scripts
  npm run build:css
This uses Tailwind CSS 3.1.4, the source-compatible major/revision. It does
not introduce an application framework. package-lock.json pins tooling;
node_modules is intentionally excluded from the download and hosting upload.
Use a supported Node LTS/npm environment for optional development tooling.
Do not load a browser Tailwind CDN script over the compiled stylesheet.

INTERACTIONS AND FALLBACKS
- The board stays still and contains no fake task-management controls.
- Normal desktop wheel input uses locally bundled Lenis. One clock serves
  the page and any overflowing mobile menu. Touch remains native.
- Operating-system reduced-motion preference disables smooth travel and
  displacement. No decorative entrance, parallax or perpetual artwork exists.
- FAQs are native details/summary, enhanced with reversible measured height.
- Menu uses a reversible full-screen panel, Escape, focus return, background
  lock and independent overflow. Without JS, a simple native nav stays visible.
- Slim replacement scrollbars appear on activity/hover/focus/drag and support
  pointer dragging and keyboard controls. Native scrollbars remain the fallback
  if enhancement is absent. Arrow keys/PageUp/PageDown/Home/End still work.
- If Lenis fails to load, ordinary page anchors/menu/FAQ remain available.
- A no-JavaScript page remains readable, with native links and disclosures.

TROUBLESHOOTING
Missing styles/images: check that assets/ was uploaded beside index.html,
that filename case is unchanged, and that you extracted the ZIP completely.
Old styles: clear the browser/host cache after replacing files.
Subfolder errors: include the trailing slash and retain relative asset paths.
Anchor covered by header after customization: update --header and root
scroll-padding-top in taskline.css; do not add a second smoothing driver.
Changed FAQ answer: no fixed-height/max-height value needs manual editing.

SOURCE AND LICENSE
This is a Landwind-based adaptation by Usman Khair Din. The Tailwind
foundation originates from Themesberg's MIT-licensed Landwind. Its original
branding, split hero, photos, testimonials, statistics, pricing and Flowbite
behavior are replaced. Taskline's content, HTML task-board artwork, mark,
layout, authored styles and enhancement code are distributed under MIT too.
This is not exclusively owned source code, and the upstream MIT permissions
are not replaced by a store-specific no-redistribution license.

The visible author credit is:
Designed & developed by Usman Khair Din
Only the bold author name links to https://www.usmankhairdin.com/ .
Retain legal copyright and license notices even when adapting visible branding.

Store publication, a temporary paid test and future free download setup are
separate owner tasks. This ZIP has no store/payment integration.
