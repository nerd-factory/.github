# .github

Org-level plumbing. Nothing in here is a project.

| Path | What GitHub does with it |
|---|---|
| `profile/README.md` | Rendered as the organisation landing page at [github.com/nerd-factory](https://github.com/nerd-factory) |
| `profile/assets/` | The wordmark and video poster used by that page |
| `CODE_OF_CONDUCT.md` | Org-wide default — applies to every repo that does not ship its own |

The landing page and the [website](https://nerd-factory.github.io/nerd-lab/) carry the same
copy on purpose. If you change one, change the other; the website source lives in
[nerd-lab](https://github.com/nerd-factory/nerd-lab).

## The video

`profile/README.md` currently shows a poster frame that links to the site, because a
repo-relative `.mp4` path renders as a download link rather than a player. To get a real
inline player, drag `assets/video/nerd-lab-intro.mp4` from the `nerd-lab` repo into any
GitHub comment box, copy the `github.com/user-attachments/assets/…` URL it produces, and
paste that bare URL on its own line in place of the poster block. The marker comment in
the file says the same thing at the point where it matters.
