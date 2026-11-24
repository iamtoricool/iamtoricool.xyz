# iamtoricool.xyz — Portfolio

Personal portfolio & blog for **Torikul Islam** (handle `iamtoricool`), built as a static site for strong SEO.

## SEO checklist (do after deploying)
- [ ] Point DNS for `iamtoricool.xyz` to GitHub Pages (A/AAAA or CNAME).
- [ ] In repo settings → Pages → Custom domain: `iamtoricool.xyz`, enforce HTTPS.
- [ ] Replace placeholder content (bio, projects, skills, contact email, Formspree id).
- [ ] Add real images: `/images/profile.jpg`, `/images/og-cover.png` (1200×630), favicon.
- [ ] Verify site in Google Search Console, submit `sitemap.xml`.
- [ ] Request indexing for `/` and key pages.
- [ ] Add `sameAs` social URLs (already in JSON-LD) — make sure they resolve.
- [ ] Publish a few blog posts mentioning "Torikul Islam" and "iamtoricool".
- [ ] Build backlinks (dev.to, LinkedIn, GitHub READMEs).

## Local preview
```bash
python3 -m http.server 8080
# open http://localhost:8080
```
