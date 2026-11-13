# Eye-tracking and dyslexia research notebooks

A historical collection of notebook-based experiments investigating whether features derived from eye movements during reading can be grouped or analysed using unsupervised techniques. The workflows explore binning, frequency-domain features, short-time Fourier transforms (STFT), principal component analysis and related methods.

**Status:** archival research material. These notebooks do not constitute a validated dyslexia screening or diagnostic tool, and they should not be used to label individuals or guide care.

## Attribution and provenance

Earlier versions of this README linked source notebooks under [algoasylum/Dyslexia_detection](https://github.com/algoasylum/Dyslexia_detection) and referenced the research paper *Screening for Dyslexia Using Eye Tracking during Reading* by Nilsson Benfatto and colleagues. Preserve the original authors' notices and verify the provenance and licence of each dataset and notebook before reuse. The presence of a copy here does not establish independent authorship or permission to redistribute underlying eye-tracking datasets.

## Notebook sequence

The repository's folders are organised as follows:

| Folder | Focus |
| --- | --- |
| `1_Early work/` | Exploring and manipulating eye-movement data |
| `2_Binning/` | Handling variable-length signals and spectral features |
| `3_Analysing Binned Data/` | Analysis of generated feature representations |
| `4_STFT and Perceptron/` | Short-time Fourier transforms and additional experiments |
| `Data/` | Historical data files; check provenance, privacy and licence before use |

Several notebooks may depend on older versions of Python, NumPy, Pandas, SciPy, Scikit-learn or Jupyter. No reproducible environment lockfile or end-to-end modern Python test suite is established in this repository.

## Reproducing a historical experiment

1. Inspect the relevant notebook's first cells for imports and file paths. Do not run notebooks on confidential data or connect them to sensitive services.
2. Obtain the exact original dataset under appropriate permissions; compare versions and participant/sample counts.
3. Create a fresh virtual environment and install compatible dependencies, recording exact versions.
4. Execute notebooks in the documented sequence, capturing any warnings, errors and external-file dependencies.
5. Use subject-level separation to avoid leakage. Never infer diagnostic sensitivity/specificity from clustering plots alone.
6. Record outputs, random seeds, inclusion criteria, labels (if used) and limitations.

See [research integrity notes](RESEARCH_INTEGRITY.md).

## Important limits

Unsupervised grouping does not establish a clinical diagnosis. Eye-tracking signals depend on reading material, language, age, recording hardware, calibration, participant characteristics and preprocessing. Clinical claims require independent prospective validation and appropriate ethical/regulatory review.
