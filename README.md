# archive-redirector-js

**Repository Description:** JavaScript redirector that reads a JSON list of URLs and redirects visitors to a random archived copy (Wayback Machine, GhostArchive, Megalodon, Archive.today). Lightweight, configurable and SEO-optimized for link preservation workflows.

---

## Meta Description (SEO)
A minimal client-side tool that loads a JSON file containing URLs and redirects users to a randomly selected web archive such as web.archive.org, archive.today, ghostarchive.org or megalodon.jp. Designed for link preservation, random archive routing, and distributed archive access.

**Keywords:** web archive, archive redirector, Wayback Machine redirect, archive.today redirect, ghostarchive, megalodon, JavaScript redirect tool, link preservation, SEO, random archive.

---

# Overview
`archive-redirector-js` is a lightweight redirect utility that:
- Fetches a `links.json` file on page load
- Selects a random URL from the list
- Chooses a random archive provider
- Redirects the visitor to the archived version

Ideal for:
- Distributing traffic across multiple archive mirrors
- Generating random archive destinations for links
- Preserving content using multiple archive sources
- SEO and link-rot protection

---

# Features
- Automatic fetch of JSON link lists
- Random archive provider selection
- Safe URL encoding for all redirects
- Optional interstitial display
- Can be embedded in any static website
- SEO-optimized documentation

---

# JSON Format
The tool supports simple and extended JSON formats.

**Simple list:**
```json
[
  "https://example.com/article-1",
  "https://example.com/article-2"
]
```

**Extended format:**
```json
[
  { "url": "https://example.com/page", "title": "Example Page" }
]
```

---

# Configuration Options
- **links.json path** — specify the JSON file containing URL entries
- **archive providers** — customize provider templates such as:
  - web.archive.org
  - ghostarchive.org
  - megalodon.jp
  - archive.today
- **interstitial delay** — optionally show a message before redirect
- **analytics hook** — optional event trigger before redirect

---

# SEO Recommendations
To maximize discoverability:
1. Keep the repository name readable and keyword-relevant
2. Add GitHub topics:
   - `web-archive`
   - `wayback-machine`
   - `archive-today`
   - `ghostarchive`
   - `megalodon`
   - `redirect`
   - `seo`
3. Use clear headings and descriptive text
4. Include JSON examples and configuration notes
5. Add a demo GIF or screenshot (recommended)
6. Use standard search terms like:
   - "redirect to Wayback Machine"
   - "archive.today redirect"
   - "web archive randomizer"

---

# Suggested One-Line Description (for GitHub)
> JavaScript redirector that reads a JSON URL list and redirects users to a random archived copy (Wayback, GhostArchive, Megalodon, Archive.today).

---

# Ethical Notes
- Ensure you have permission to reference and archive URLs
- Avoid violating archive provider rate-limits or terms
- Provide transparency to users about redirection to archived snapshots

---

# Contributing
Contributions are welcome. Potential additions:
- More archive providers
- Timestamp-specific archive templates
- Configurable UI interstitials
- Optional server-side version

Submit PRs with clear descriptions.

---

# License
MIT License recommended — add a LICENSE file.

---

# Troubleshooting
- Check that `links.json` is accessible and served with the correct MIME type
- Ensure the hosting server allows fetching JSON (CORS if remote)
- Verify URLs in the JSON file are valid and correctly formatted

---

# FAQ
**Q:** Does this script create heavy load on archive providers?  
**A:** It sends only one redirect request per visitor, but high-traffic deployments should consider caching.

**Q:** Can specific timestamps be used?  
**A:** Yes — customize templates using provider-specific timestamp syntax.

---

# Final Notes
Add your project website, demo page, or deployment example once available.
