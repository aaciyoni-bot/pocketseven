# PocketNine — The Private Card Room

Private-label club poker app (pocketnine.com). "The Press Room" design
language: paper, ink and four registration plates. Same engine family as its
sibling product, fully separate brand, Firebase project and player base.

## Launch checklist
1. Create Firebase project `pocketnine` (Google sign-in only, Firestore,
   Blaze plan) and paste its config into index.html (search: TODO(pocketnine)).
2. Add repo secret FIREBASE_TOKEN; the workflows deploy functions + rules.
3. GitHub Pages: deploy from `main`, custom domain pocketnine.com
   (Cloudflare-fronted like the sibling site).
4. Replace placeholder icons/hero with the Cloud Design "Press Room" asset
   package as it lands.
