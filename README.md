# Public portfolio export

This folder is a sanitized static export package for Quentin McClellan's public portfolio site.

## Intended destination

Copy only the files in this folder into a separate public GitHub repository named `quentinmcclellan.com`.
GitHub Pages will host that public repository, and the `quentinmcclellan.com` domain will point to the public GitHub Pages site.

## Files included

- `index.html` — public personal portfolio homepage.
- `starkgrid.html` — sanitized public StarkGrid case study/demo page.
- `styles.css` — static stylesheet shared by both pages.
- `README.md` — copy/export guidance.

## Safety rules

Do not include private StarkGrid repository files in the public site. This export is intentionally limited to static, public-safe files.
Do not copy runtime evidence files, internal notes, private machine details, operational commands, secrets, tokens, passwords, SSH material,
or private network details into the public repository.

The StarkGrid source repository remains private. The public site should present only the sanitized case study and portfolio narrative.
