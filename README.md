<<<<<<< HEAD
# East Asia Trading – Modernized static website

## Run locally
Open `index.html` in a browser or serve this directory using `python -m http.server 8080` and visit http://localhost:8080.

## Scope
- Rebuilt all 17 core root-level HTML pages with modern responsive HTML/CSS and navigation.
- Original files are retained under `legacy/` for reference and functionality comparison.
- Original images remain under `images/`. Some product images are unavailable in the source archive, so neutral branded placeholders are used instead of inventing photographs.
- Ancillary guestbook, order, legacy and server-side paths are retained as-is; no claim is made that historical CGI scripts work on a new host.
- `contactus.html` retains the original CGI form destination and original field names. This endpoint must be tested on the actual hosting environment. Historical address/email should be confirmed before production launch.
- Historical order form may collect payment details and is **not** recommended for live use until replaced with a secure, PCI-compliant payment provider.
- Third-party Google Fonts is optional; system fallback fonts are provided.

## Before going live
1. Confirm current contact details, address, domain and business copy.
2. Verify CGI form handler and end-to-end email delivery, or replace with a supported backend.
3. Audit archived `legacy/`, `Guestbook/`, `order.htm`, and server-side directories before public deployment; remove unsafe legacy scripts from the live server only after approval.
4. Test every link and form in browser and across device sizes.
5. Review product descriptions for outdated claims and dates.
=======
# eastasiatrading
>>>>>>> 12906b250d41b9d346637f8ab0a4a8f0f7048847
