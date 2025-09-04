# RLSP-NER
## Datasets & Splits

We reuse the datasets **and their splits** released by [InstructUIE](https://github.com/BeyonderXX/InstructUIE).
- **Main benchmarks:** ACE05-E, CoNLL2003, FabNER — used to compare overall performance.
- **Ablations:** FabNER — used to analyze the contributions of different components.
- **Cross-domain transfer:** Broad Twitter Corpus and OntoNotes — used to assess generalization.

**Preprocessing & Evaluation. ** Unless otherwise noted, we follow InstructUIE’s preprocessing and evaluate with **span-level micro-F1 (%)**.

### Getting the data
1.  Visit the InstructUIE repository and follow the dataset preparation instructions.
2.  Use the released **train/dev/test** splits from InstructUIE to ensure comparability.

> **Note. ** We do not redistribute third-party datasets.  Please obtain them from their original sources and respect the corresponding licenses.

### Attribution
If you use this code or configuration, please cite the original datasets and the InstructUIE repository.
