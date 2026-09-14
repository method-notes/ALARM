# ALARM project page

Static research project website. No build step or JavaScript dependency is required.

## Local preview

Run `python3 -m http.server 8765` in this directory, then open http://localhost:8765.

## GitHub Pages deployment

Copy this directory's contents into a public repository's root, or into its `docs/` directory. In the repository's Pages settings, select the relevant branch and folder as the publishing source. All local asset URLs are relative, so the site works beneath a repository path as well as at a domain root.

The deployment repository is method-notes/ALARM. The project URL is https://method-notes.github.io/ALARM/ after GitHub Pages deployment succeeds.

## Before adding the URL to the manuscript

- Confirm the deployed page is accessible without signing in.
- Verify the linked anonymous code repository remains accessible.
- Replace the resource preparation labels after code and data are actually released.
- Add a public manuscript link when appropriate; no manuscript PDF is included here.
- Add the final citation only after bibliographic details are available.
- Confirm author names, affiliations, and all public-facing claims.

The overview image comes from the manuscript. The pipeline description presents the proposed method, not a claim that the current code package has been fully validated. No new experimental results are asserted. Google Fonts is optional: local fallback fonts keep the page usable without network font access.
