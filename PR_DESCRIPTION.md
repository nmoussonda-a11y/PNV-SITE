## Changes in branch new-site

- Created backup-before-new-site branch (snapshot of previous state)
- Created new-site branch with preserved assets: CNAME, Index.html, admin.html, test-simple.html, images/*.jpeg
- Replaced temporary index redirect with a servable index.html (copied Index.html to index.html)

### Recommended next steps

- Run HTML validation, link checking, and accessibility scanning (htmlhint, linkinator, pa11y)
- Fix any encoding artifacts and missing alt attributes
- Optionally optimize images for web to reduce page weight

---

This PR was created by the repository automation script. Please review changes before merging.
