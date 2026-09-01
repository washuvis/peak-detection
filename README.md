# Peak Detection — Early Project Scaffold

## Status

**On hold / superseded.** This repository is an early scaffold from the chromatography peak-detection work that later developed into Peak-a-boo. It does not contain a runnable implementation: the Python source files and notebooks currently tracked here are empty placeholder files. Active development moved to the maintained Peak-a-boo repositories listed below.

If this repository must be continued for a historical reason, a successor would need to reconstruct the intended data-loading, preprocessing, peak-detection, comparison, and zoom components, add a documented environment, provide approved example data or data-access instructions, and add tests and runnable examples. Otherwise, use the maintained Peak-a-boo repositories.

## Introduction

This repository was created as an early code structure for chromatographic peak-detection work. Its directory names indicate planned components for loading reference data, preprocessing signals, detecting peaks, comparing detections with references, and examining local signal regions. However, the tracked source files and notebooks are empty, so this repository does not preserve an executable method or enough code to reproduce an analysis. The current Peak-a-boo repositories should be treated as the maintained continuation of this work.

## Repo Structure

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

### Prerequisites & Needed Materials

There is currently no runnable code in this repository and no `requirements.txt`, environment file, dataset, or command-line entry point. No package versions can be documented from the repository itself.

For current Peak-a-boo development, use one of the maintained repositories in the **Related Repositories** section.

### Installation

No installation procedure is available because the repository contains only empty code and notebook placeholders.

### Usage

There is no executable usage workflow in the current repository state.

If this historical scaffold is intentionally reconstructed, first document the exact input data, expected outputs, and purpose of each module. Then implement and test each component before adding runnable usage instructions. Do not copy private research data into this public repository.

## Related Repositories

All related Peak-a-boo repositories are maintained under the VIBE Lab `washuvis` GitHub organization:

- [`washuvis/peak-a-boo`](https://github.com/washuvis/peak-a-boo) — public synthetic Peak-a-boo workbench and current public-facing review interface.
- [`washuvis/chromato-peak-app`](https://github.com/washuvis/chromato-peak-app) — private internal analytical implementation containing the research-data pipeline, peak-detection code, candidate-level ML code, and dashboard.
- [`washuvis/peakaboo-expert-study`](https://github.com/washuvis/peakaboo-expert-study) — expert-study platform for evaluating how people review difficult chromatographic peak cases under different information conditions.
- [`washuvis/peak-detection`](https://github.com/washuvis/peak-detection) — this historical scaffold.

## Future Works

The recommended path is not to restart active development in this repository unless its early structure has a specific historical value. Current research should continue in the maintained Peak-a-boo repositories.

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

Keep this repository marked as historical/on hold unless active work resumes. If the lab later confirms that the newer repositories preserve all relevant project history, archiving this repository may be more appropriate than maintaining it as an active codebase.
