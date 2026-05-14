# SD Invoice V11.10.4 DB Safe Customer Product Fix

Replace BOTH:
- server.js
- public/index.html

Fixed:
- Customer save uses DB-safe dynamic insert
- Product save uses DB-safe dynamic insert
- Auto-checks and adds missing customer/product columns
- Added Master Debug button to show table columns/counts
- Better backend error logging

Render:
Upload server.js and public/index.html, commit, then Manual Deploy latest commit.
