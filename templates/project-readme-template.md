<!--
PROJECT README TEMPLATE
=======================

This is a slimmed-down version of the structure used in well-presented research repos
(see e.g. https://github.com/athowes/multi-agyw).

Fill in the placeholders. Aim for one screen of content. Delete this comment block
before publishing.
-->

# Project title

Code for [your paper / dissertation chapter title] ([your name] et al., year, journal).

> [Status: *working draft / under review / published*]

## Summary

[2–4 sentences. What is the research question? What method did you use? What did you find?]

[Embed your key figure below.]

![A short caption describing the figure.](figures/key-figure.png)

*This figure is produced by `code/02-make-figure.R`.*

## File structure

| Directory | Contains |
| --- | --- |
| `data/` | Raw and processed input data (gitignored — see Data section below). |
| `code/` | Analysis scripts. Run in numerical order. |
| `output/` | Tables, figures, model outputs. |
| `docs/` | Methods notes, supplementary material. |

## Data

[Where does the data come from? Public source with a link? Restricted? If restricted, how can a reader request access? If you ship a small synthetic sample for reproducibility, say so here.]

## Reproducibility

- Software: [R 4.x / Stata 17 / SAS 9.4 / Python 3.11]
- Key packages / dependencies: [list 3–5 main ones]
- To reproduce the analysis: `[one-line instruction, e.g. source("code/00-run-all.R")]`

## Citation

If you use this code, please cite:

```
[your bibtex or formatted citation]
```

## Contact

- [Your name] — your.email@institution.ac.uk
- [ORCID](https://orcid.org/your-orcid)

## Licence

[MIT / CC-BY-4.0 / GPL-3.0 — see `LICENSE`]
