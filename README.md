# WaveBack

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24511297.svg)](https://doi.org/10.5281/zenodo.24511297)

**Tsunami flow speed, depth and run-up from tsunami deposits, in your web browser.**

![WaveBack](https://storeassets.im-cdn.com/media-manager/1302352/41f766e04f444eb1b5cb31e22efe8283_WaveBack_Free_cover_1024.jpg)

WaveBack is uniquely designed for ease of use: it needs no coding, runs offline in a browser, takes grain-size tables straight from GrainLab and writes the methods paragraph.

## Download
| Edition | What it includes | Where |
|---|---|---|
| **WaveBack (Free)** v1.3.1 | Flow speed, flow depth and run-up from deposits, paleotsunami settings, checks, figures, tables, methods paragraph | [Zenodo](https://doi.org/10.5281/zenodo.24511298) · [Store](https://twmglobal.myinstamojo.com/product/waveback-free-tsunami-flow-speed-from-sandy-) |
| **WaveBack Pro** v1.3.1 | Everything in Free, plus tsunami or storm screening, boulder transport, Monte Carlo uncertainty and ground-profile flow depths | [![WaveBack Pro, India (₹)](https://img.shields.io/badge/WaveBack%20Pro-India%20%28%E2%82%B9%29-e07b00?style=for-the-badge)](https://twmglobal.myinstamojo.com/product/waveback-pro) [![WaveBack Pro, International ($)](https://img.shields.io/badge/WaveBack%20Pro-International%20%28%24%29-1f6feb?style=for-the-badge)](https://geomantle.com/waveback) |

WaveBack is a single HTML file: save it, open it in Chrome, Edge or Firefox, and start. No installation, no account and no internet connection are needed, and your data never leaves your computer.

## What it does
- Flow speed from deposit thickness and grain size: the inverse model of Jaffe and Gelfenbaum (2007), with Gelfenbaum and Smith (1986), parabolic or linear eddy viscosity
- Unknown flow depth solved from a Froude number, with a warning when no depth reaches the target
- Minimum flow speed from the advection model of Moore et al. (2007)
- Water run-up from the landward limit of sand (Soulsby et al. 2007)
- Paleotsunami settings: deposit age with a compaction correction, and a mud cut-off that keeps silt and clay out of the inversion
- Checks before you interpret: mud-dominated samples, Froude numbers, input ranges
- Exports: methods and results paragraphs written from your settings, CSV tables, SVG and PNG figures, project files and a one-click zip
- Grain-size tables can be pasted straight from GrainLab or any spreadsheet

## How to use
1. Download WaveBack from Zenodo or the store, save WaveBack_v1.3.1.html anywhere and open it in Chrome, Edge or Firefox.
2. Look at the built-in demo (the published benchmark of Jaffe and Gelfenbaum 2007), then click New project.
3. Follow the steps: Project, Deposits, Flow speed, Run-up & checks, Results, Export.

The User Guide (PDF, in the download) explains each step, how to choose settings and how to read the results.

## Validation
- Jaffe and Gelfenbaum (2007) base case: 8.96 m/s against the published 9.1 m/s (Gelfenbaum and Smith profile), 8.62 against 8.8 (parabolic) and 7.67 against 7.8 (linear), all within 2%
- Published sensitivity tests (flow depth, thickness, resuspension coefficient) reproduced within 3 percentage points
- The engine matches an independent Python reference implementation to within 4 × 10⁻¹⁵
- Details: WaveBack_v1.3.1_validation.md and WaveBack_v1.3.1_benchmark.csv in the download

## WaveBack Pro
- **Tsunami or storm screening:** 29 deposit criteria and 10 wave and flow characteristics from seven published studies, each with its source; suggestions from your own data count only after you confirm them; the result is a leaning, never a verdict
- **Boulder transport:** minimum flow speed to slide, overturn or lift a boulder (Nandasena et al. 2011)
- **Monte Carlo uncertainty:** median speed and Froude number with 95% ranges and histograms, from a reproducible random seed
- **Ground profile and water surface:** flow depth at every point from surveyed elevations, without assuming a Froude number

Pro features are left out of the free file itself.

**Get WaveBack Pro:**

[![WaveBack Pro, India (₹)](https://img.shields.io/badge/WaveBack%20Pro-India%20%28%E2%82%B9%29-e07b00?style=for-the-badge)](https://twmglobal.myinstamojo.com/product/waveback-pro) [![WaveBack Pro, International ($)](https://img.shields.io/badge/WaveBack%20Pro-International%20%28%24%29-1f6feb?style=for-the-badge)](https://geomantle.com/waveback)

Questions or issues: open an [issue](../../issues) or write to twmglobals@gmail.com

## How to cite
GitHub's **Cite this repository** button (right-hand panel) gives the same citation in APA and BibTeX.

In text: Khan, A. (2026)

Reference: Khan, A. (2026). WaveBack: tsunami flow speed, depth and run-up from tsunami deposits, version 1.3.1 [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24511298

Please also cite the models you used; the methods paragraph on the Export step lists them.

Results support, and do not replace, the judgment of a qualified specialist.

## Licence
WaveBack is distributed under the Creative Commons Attribution-NoDerivatives 4.0 International licence (CC BY-ND 4.0); see [LICENSE.md](LICENSE.md).

Afzal Khan (ORCID [0000-0001-8844-122X](https://orcid.org/0000-0001-8844-122X)) · Developed by an IIT alumnus and GATE UPSC qualifier
