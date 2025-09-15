# Implementation Playbook — Profile & GitHub Sites
1. **Repo structure (Jekyll/Pages or static site)**  
```
/ (root)
├─ /_data/menus.yaml
├─ /resources/ (markdown content)
├─ /use-cases/
├─ /demo/ (sandbox index + warning banner)
├─ /assets/ (img, css, icons)
├─ /components/ (includes/partials)
├─ /roadmap/
├─ /contribute/
├─ /privacy-safety/
└─ index.md
```
2. **Menus:** `_data/menus.yaml` drives top/secondary/footer nav.  
3. **Templates:** shared layout with partials for CTAs and “proof” blocks.  
4. **Wireframes:** implement placeholders first; don’t block on final art.  
5. **Issues Board:** create epics for MVP pages; label-first-issues to invite community.  
6. **Deployment:** GitHub Pages with CNAME; add lightweight CI for broken links.
7. **Sandbox:** host under `/demo` or a subdomain; banner “Experimental, data may reset.”