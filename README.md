# Binocular Depth Perception

**[Read the write-up (PDF)](binocular-depth-perception.pdf)** · [LaTeX source](binocular-depth-perception.tex)

An early-stage computer vision project exploring how binocular information could support depth estimation and comparisons between artificial and biological vision.

The write-up develops a geometric approach to estimating depth from an object's displacement between two camera views. Training a binocular CNN, interpreting its learned computation, and comparing it with biological vision are proposed next steps; this repository contains the conceptual write-up, rather than a trained model or experimental results.

## What the write-up covers

- Defining camera separation, field of view, depth, and an object's position within each view.
- Relating displacement between the views to depth.
- Connecting angular and linear position under the write-up's camera-projection assumptions.
- Outlining limitations and possible model-training and interpretability work.

## Files

- [binocular-depth-perception.pdf](binocular-depth-perception.pdf): the write-up with the revised abstract.
- [binocular-depth-perception.tex](binocular-depth-perception.tex): the editable LaTeX source, including the revised abstract.
- [Phase I/](Phase%20I/): the three original hand-drawn figure photographs required by the source.

## Build

With a LaTeX installation that includes `babel` (English), `geometry`, `amsmath`, `graphicx`, and `hyperref`, run from this directory:

```sh
pdflatex -interaction=nonstopmode -halt-on-error binocular-depth-perception.tex
```

The original project dates to June 2024; the write-up was revised in October 2026. The source uses the compilation date in its title. The PDF is built from the source above.
