<div align="center">

<sub>OPEN-SOURCE &nbsp;·&nbsp; GLOBAL &amp; TARGET ANALYSIS &nbsp;·&nbsp; TIME-RESOLVED &nbsp;·&nbsp; SPECTROSCOPY &nbsp;·&nbsp; FLIM &nbsp;·&nbsp; MULTI-WAY DATA</sub>

# Modeling frameworks for *separable* data

Open-source tools for global and target analysis of time-resolved spectroscopy,
fluorescence lifetime imaging, and multi-way data —
from photosynthesis and photovoltaics to photochemistry and beyond.

[**Get started with pyglotaran**](https://glotaran.org/software/pyglotaran) &nbsp;·&nbsp; [Explore the ecosystem](https://glotaran.org/ecosystem) &nbsp;·&nbsp; [Join Discord](https://discord.gg/KfnEYRSTJx)

</div>

---

<table align="center">
  <tr>
    <td align="center"><strong>2007 &nbsp; TIMP</strong></td>
    <td align="center">──→──</td>
    <td align="center"><strong>2012 &nbsp; Glotaran</strong></td>
    <td align="center">──→──</td>
    <td align="center"><strong>2023 &nbsp; pyglotaran</strong></td>
  </tr>
</table>

---

## The Ecosystem

> *Decompose your data. Discover your kinetics.*

### [pyglotaran](https://github.com/glotaran/pyglotaran) &nbsp;·&nbsp; Flagship · Python

[![PyPI version](https://img.shields.io/pypi/v/pyglotaran)](https://pypi.org/project/pyglotaran/)
[![Docs](https://img.shields.io/badge/docs-readthedocs-blue)](https://pyglotaran.readthedocs.io)
[![GitHub Stars](https://img.shields.io/github/stars/glotaran/pyglotaran?style=flat)](https://github.com/glotaran/pyglotaran)
[![Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.4534043-blue)](https://zenodo.org/doi/10.5281/zenodo.4534043)

A Python framework for global and target analysis of time-resolved spectroscopy, microscopy, and other multi-way data. Models are described in composable YAML files, fit with partitioned variable projection, and results visualised directly in Jupyter notebooks.

- **Modular model definitions** — combine kinetic megacomplexes from reusable building blocks
- **Simultaneous multi-dataset fitting** — link parameters across related experiments
- **Partitioned variable projection** — efficient, numerically stable nonlinear least squares
- **Python-native** — results stay in xarray and integrate naturally with matplotlib and Jupyter

---

| Package | Language | Status | Summary |
|---------|----------|--------|---------|
| [**pyglotaran-extras**](https://github.com/glotaran/pyglotaran-extras) | Python | active | Visualization companion — publication-ready overview plots and diagnostic figures |
| [**TIMP**](https://github.com/glotaran/TIMP) | R | stable | Foundational R engine for partitioned variable projection, on CRAN since 2007 |
| [**paramGUI**](https://github.com/glotaran/paramGUI) | R | stable | Shiny app for teaching parameter estimation examples inspired by time-resolved spectroscopy |
| [**Glotaran 1.x**](https://github.com/glotaran/glotaran-legacy) | Java | archived | Original GUI for TIMP — still the most-cited tool in the field (1,500+ citations) |

---

## Publications

| Year | Paper |
|------|-------|
| 2023 | **[pyglotaran: a lego-like Python framework for global and target analysis of time-resolved spectra](https://doi.org/10.1007/s43630-023-00460-y)**<br/><sub>van Stokkum IHM, Weißenborn J, Weigand S, Snellenburg JJ &nbsp;·&nbsp; *Photochemical & Photobiological Sciences*</sub> |
| 2012 | **[Glotaran: A Java-Based Graphical User Interface for the R Package TIMP](https://doi.org/10.18637/jss.v049.i03)**<br/><sub>Snellenburg JJ, Laptenok SP, Seger R, Mullen KM, van Stokkum IHM &nbsp;·&nbsp; *Journal of Statistical Software*</sub> |
| 2007 | **[TIMP: An R package for modeling multi-way spectroscopic measurements](https://doi.org/10.18637/jss.v018.i03)**<br/><sub>Mullen KM, van Stokkum IHM &nbsp;·&nbsp; *Journal of Statistical Software*</sub> |

---

## Community

<table align="center">
  <tr>
    <td align="center">
      <a href="https://discord.gg/KfnEYRSTJx"><strong>💬 Discord</strong></a><br/>
      <sub>Real-time chat for questions,<br/>announcements, and discussion</sub>
    </td>
    <td align="center">
      <a href="https://github.com/glotaran/pyglotaran/discussions"><strong>⬡ Discussions</strong></a><br/>
      <sub>Long-form Q&amp;A, shared results,<br/>and feature ideas</sub>
    </td>
    <td align="center">
      <a href="https://glotaran.org"><strong>🌐 glotaran.org</strong></a><br/>
      <sub>Documentation, publications,<br/>and the full ecosystem</sub>
    </td>
  </tr>
</table>
