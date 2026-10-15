# Interpreting Text-to-Image Diffusion Models

Executed notebook with all the experiments of my bachelor's thesis
(Department of Informatics and Telecommunications, NKUA).

The thesis looks at Stable Diffusion v1.4 and asks where a visual concept
(Van Gogh style, nighttime, the color red) is written inside the
cross-attention layers, whether that direction is causal, and whether it
can be used to add or remove the concept.

The notebook is too large for GitHub's preview. To see it with all outputs,
[open it in Google Colab](https://colab.research.google.com/github/GiannisPro153/thesis-sd-cross-attention/blob/main/thesis_experiments.ipynb).

Run on Colab (A100) with diffusers 0.41. The sections follow Chapter 6 of
the thesis. The concept directions are computed once (section 1.1) and
saved in `DATA_DIR`; all results are written to `DRIVE_DIR`.
