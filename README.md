# Genomics Data Curation and Annotation

This repository provides scripts and workflows for variant annotation, gene symbol standardization, and basic data curation in genomics.

## Contents
- `scripts/`: Python + Bash scripts for annotation and cleanup
- `data/`: Example VCF and gene list
- `notebooks/`: Jupyter demo
- `docs/`: SOP for curation
- `tests/`: Basic test cases

## How to Run
```bash
python scripts/variant_annotator.py data/sample.vcf > annotated.tsv
python scripts/gene_mapper.py data/gene_list.txt > mapped_genes.tsv
bash scripts/clean_vcf.sh data/sample.vcf > cleaned_sample.vcf
```

## Requirements
- Python 3.8+
- pandas
- requests
- Bash
