# Peak Detection — Early Project Scaffold

## Status

**On hold / superseded.** This repository is an early project scaffold from the chromatography peak-detection work that later developed into Peak-a-boo. It does not contain a runnable implementation: the Python source files and notebooks currently tracked in this repository are empty placeholder files. Active development moved to the later Peak-a-boo repositories listed below.

If someone needs to continue from this repository specifically, the first step is to decide whether there is a historical reason to reconstruct this early structure. Otherwise, use the current Peak-a-boo repositories instead. Reconstructing this repository would require implementing the data-loading, preprocessing, peak-detection, comparison, and zoom components, adding an environment/requirements file, adding example data or clear data-access instructions, and adding tests and runnable examples.

## Introduction

This repository appears to have been created as an early code structure for chromatographic peak-detection work. Its directory names suggest planned components for loading reference data, preprocessing signals, detecting peaks, comparing detections with references, and examining local signal regions. However, the tracked source files and notebooks are empty, so the repository does not preserve an executable method or enough code to reproduce an analysis. The current Peak-a-boo repositories should be treated as the maintained continuation of this line of work.

## Repository Structure

```text
peak-detection/
├── LICENSE
├── notebooks/
│   ├── 01_zoom_local_maxima.ipynb
│   └── 02_reference_dataset_compare.ipynb
└── src/
    ├── compare/
    │   └── compare.py
    ├── io_ref/
    │   └── io_ref.py
    ├── peaks/
    │   └── peaks.py
    ├── preprocess/
    │   └── preprocess.py
    └── zoom/
        └── zoom.py
```

Current file state:

- `notebooks/01_zoom_local_maxima.ipynb` — empty placeholder.
- `notebooks/02_reference_dataset_compare.ipynb` — empty placeholder.
- `src/compare/compare.py` — empty placeholder.
- `src/io_ref/io_ref.py` — empty placeholder.
- `src/peaks/peaks.py` — empty placeholder.
- `src/preprocess/preprocess.py` — empty placeholder.
- `src/zoom/zoom.py` — empty placeholder.
- `LICENSE` — repository license file.

The directory names describe the intended organization, but they should not be treated as evidence that the listed functionality was implemented here.

## Getting Started

### Prerequisites and Needed Materials

There is currently no runnable code in this repository and no `requirements.txt`, environment file, dataset, or command-line entry point. No package versions can be documented from the repository itself.

For current Peak-a-boo development, use one of the maintained repositories in the **Related Repositories** section instead.

### Installation

No installation procedure is available because the repository contains only empty code and notebook placeholders.

### Usage

There is no executable usage workflow in the current repository state.

If this historical scaffold must be reconstructed, first document the intended input data and expected outputs, then implement and test each component before adding usage instructions. Do not copy private research data into a public repository.

## Related Repositories

This repository is part of the same research lineage as the following Peak-a-boo repositories:

- [`washuvis/peak-a-boo`](https://github.com/washuvis/peak-a-boo)
  - Public synthetic Peak-a-boo workbench.
  - Use this repository for the public demonstration and current public-facing review interface.

- [`washuvis/chromato-peak-app`](https://github.com/washuvis/chromato-peak-app)
  - Private internal analytical implementation.
  - Contains the research-data pipeline, peak-detection code, candidate-level ML code, and internal dashboard.

- [`ghoshsaurav/peakaboo-expert-study`](https://github.com/ghoshsaurav/peakaboo-expert-study)
  - Expert-study platform for evaluating how people review difficult chromatographic peak cases under different information conditions.

- [`ghoshsaurav/peak-detection`](https://github.com/ghoshsaurav/peak-detection)
  - This historical scaffold.

## Future Work

The recommended path is **not** to restart active development in this repository unless its early structure has a specific historical value. Current research should continue in the maintained Peak-a-boo repositories.

If this repository is intentionally revived, the minimum work would be to:

1. define the exact purpose of each planned module;
2. identify the approved input data and its format;
3. implement the source files rather than leaving placeholders;
4. add a `requirements.txt` or environment file with package versions;
5. add runnable examples or notebooks;
6. add tests for the main methods;
7. document all high-level methods in the code; and
8. update this README with real installation, usage, inputs, outputs, and validation information.

## Maintenance Note

Keep this repository marked as historical/on hold unless active work resumes. If it is no longer needed after the lab confirms that the newer repositories preserve the relevant project history, it may be appropriate to archive it rather than maintain parallel implementations.
