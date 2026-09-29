# Résumé Source

`patrick-stock-resume.tex` is the maintainable source for the public résumé linked from the website.

## Build

From the repository root:

```bash
mkdir -p .resume-build
pdflatex -interaction=nonstopmode -halt-on-error \
  -output-directory=.resume-build \
  resume/patrick-stock-resume.tex
pdflatex -interaction=nonstopmode -halt-on-error \
  -output-directory=.resume-build \
  resume/patrick-stock-resume.tex
cp .resume-build/patrick-stock-resume.pdf static/patrick-stock-resume.pdf
```

Running LaTeX twice ensures PDF metadata and links are finalized. The intermediate `.resume-build/` directory is ignored by Git; the generated PDF under `static/` is intentionally versioned and deployed by Zola.

## Maintenance

Keep the résumé consistent with `content/_index.md`. After changing either source:

1. Compare titles, dates, locations, skills, and bullet wording.
2. Rebuild the PDF.
3. Check the LaTeX log for overfull or underfull boxes.
4. Confirm the PDF remains one US Letter page unless a deliberate layout decision changes that constraint.
5. Review the rendered PDF visually and verify its links.
