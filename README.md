# Currency Converter Pro information site

Five static pages with shared local CSS. No build step or JavaScript is required.

- `index.html`: app overview
- `privacy.html`: information use and service providers
- `terms.html`: use of reference rates and purchase guidance
- `support.html`: contact and troubleshooting
- `delete-account.html`: account deletion request instructions

All local links are relative, so the site works under a GitHub Pages repository path. `.nojekyll` serves the files without Jekyll processing.

## Local preview

From this checkout, run `python -m http.server 8000 --bind 127.0.0.1` and open `http://127.0.0.1:8000/`. A Python installation is needed only for this optional local preview.

## Publication

Publish only this information-site repository. Review and approve the page content before pushing or enabling GitHub Pages. Account-deletion handling, retention practices and legal operator information must be confirmed before publication. This site does not implement account deletion, billing or an application backend.

Do not add app source, credentials, ignored app configuration, private evidence or device photos to this repository.
