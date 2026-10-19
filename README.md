# Binocular Depth Perception

**[Read the write-up (PDF)](binocular-depth-perception.pdf)** · [LaTeX source](binocular-depth-perception.tex)

An early-stage computer vision project exploring how binocular information could support depth estimation and comparisons between artificial and biological vision. Specifically, I seek to better understand how monocular and binocular visual systems differ, and apply insights to enhance computer vision pipelines and draw more-accurate comparisons between biological and artificial visual systems. 

The write-up develops a geometric approach to estimating depth from an object's displacement between two camera views. Training a binocular CNN, interpreting its learned computation, and comparing it with biological vision are proposed next steps; this repository contains the conceptual write-up, rather than a trained model or experimental results.

## What the write-up covers

- Defining camera separation, field of view, depth, and an object's position within each view.
- Relating displacement between the views to depth.
- Connecting angular and linear position under the write-up's camera-projection assumptions.
- Outlining limitations and possible model-training and interpretability work.

## Files

- [binocular-depth-perception.pdf](binocular-depth-perception.pdf): the write-up pdf.
- [binocular-depth-perception.tex](binocular-depth-perception.tex): the editable LaTeX source.
- [Phase I/](Phase%20I/): the three original hand-drawn figure photographs required by the source.

## Build

With a LaTeX installation that includes `babel` (English), `geometry`, `amsmath`, `graphicx`, and `hyperref`, run from this directory:

```sh
pdflatex -interaction=nonstopmode -halt-on-error binocular-depth-perception.tex
```

The original project dates to June 2024; the write-up has been revised since. The PDF is built from the source above.
