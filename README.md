# door

Shell for a judgment Front Door — a single-file PWA served via GitHub Pages.

This repo is a publish target only. The source of truth lives in the owner's
engine repo at `surface/index.html`; changes land there first and are copied
here. The shell carries no repository coordinates or credentials — the owner
points it at their own engine repo with a fine-grained PAT at setup time.
