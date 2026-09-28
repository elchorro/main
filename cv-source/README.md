# CV source

LaTeX source for `assets/pdf/SzymonSacher_CV.pdf` (linked from the site's CV page).
Previously lived in the `elchorro/szymon-cv` repository.

- Edit `SzymonSacher_CV.tex` on a branch and push: the **Build CV** workflow compiles it and
  commits the refreshed PDF to that branch, so it goes live when the branch is merged.
- Local build: `latexmk -pdf SzymonSacher_CV.tex && cp SzymonSacher_CV.pdf ../assets/pdf/`
