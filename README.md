AIGER-Net Code Package
This package contains the source code and supporting files for AIGER-Net and its painting-style prediction workflow.
Package contents
- configs/: Base settings, random-seed settings, fold-specific settings, and configuration files for baselines, ablations, and robustness analyses.
- metadata/: Class-audit and label-harmonization files, a field dictionary, and schemas for manifests and run records.
- src/aiger_net/: Python package containing data preparation and audit utilities, dataset and fold handling, model components, training and evaluation routines, calibration methods, metrics, statistical analysis, robustness functions, reporting, and reproducibility utilities.
  - data/: Dataset builders, manifests, audit utilities, and fold construction.
  - models/: AIGER-Net and related model components, including MMTB, CASD, AECR, and shared layers.
  - calibration/: Temperature scaling, APS calibration, and rejection-threshold utilities.
- scripts/: Command-line scripts for environment and package validation, data preparation, embedding extraction, audit and fold finalization, training, internal and external evaluation, baseline runs, ablations, robustness analyses, statistical analysis, report-table generation, and reference-matrix validation. The directory also contains the full-pipeline shell script.
- records/reference_only/: CSV and JSON record files, summary-file layouts, and a record-status note.
- third_party/: Documentation and a lock file for recording third-party comparator source information.
- tests/: Automated checks for metrics, calibration, folds, statistical utilities, record validation, and reference-matrix consistency.
Package-level files
- environment.yml: Conda environment specification.
- pyproject.toml: Python package metadata and build configuration.
- Makefile: Common package commands.
- LICENSE: License text included with the package.
- ANONYMOUS_REVIEW_CHECKLIST.md and ARTIFACT_STATUS.md: Package review and artifact-status documentation.
