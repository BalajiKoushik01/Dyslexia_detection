# Research integrity and migration guide

## Scope of this archive

The notebook set predates the current code review. Its original README linked materials in another GitHub account. Exact authorship, data permissions, equipment and experimental environment should be checked against primary records before the contents are republished or described as original research.

## Reproduction checklist

- Preserve original notebook files and attribution; avoid destructive mass-formatting that changes output provenance.
- Inventory data sources, owners, licences, participant information and permitted purpose. Do not publish identifiable eye-movement records.
- Recreate a version-pinned Python/Jupyter environment from notebook imports.
- Identify scripts/notebooks that depend on absolute paths, obsolete APIs or missing input files.
- Record exact participant-level train/test separation, sampling and calibration methods.
- Compare preprocessing and spectral feature extraction with a known reference case.
- Report exploratory clustering as exploratory, not clinical diagnosis.
- Document negative results, confounds and model uncertainty.
- Add clean execution notebooks and CI only after the data can be reproduced legally and safely.

## Release criteria

A reproducible research release needs an environment lockfile, data manifest, recorded notebook execution, stable expected outputs, documented consent/licensing and independent review of interpretive claims. This archive does not currently meet those criteria.
