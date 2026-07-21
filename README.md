# MemBridge landing page

One file, zero build step. Drop `index.html` at the domain root (or any static host:
GitHub Pages, Netlify, Vercel, nginx — anything that serves files).

- All CSS/JS/logo are inline. No external requests except the waitlist form,
  which POSTs to our Supabase (`waitlist` table, public insert-only key — safe to ship).
- Before announcing: submit one test email on the live site and check the row
  lands in Supabase (Andrew has access).
- Two content checks still open: the `membridge why` demo output format, and the
  e2e-encryption wording in the Team section — confirm both match the real product.
