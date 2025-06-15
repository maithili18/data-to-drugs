# Genomics Data Curation and Annotation

This repository reflects my learning and work on workflows for variant annotation, gene symbol standardization, and basic data curation in genomics, developed during my bioinformatics studies.

## Repository Structure

- `scripts/`: Python and Bash scripts for variant annotation and data cleanup  
- `data/`: Example VCF files and gene lists for testing  
- `notebooks/`: Jupyter notebooks demonstrating usage and workflows  
- `docs/`: Standard Operating Procedures (SOPs) for curation  
- `tests/`: Basic unit tests and validations

## How to Run

You can run the scripts as follows:
```bash
python scripts/variant_annotator.py data/sample.vcf > annotated.tsv
python scripts/gene_mapper.py data/gene_list.txt > mapped_genes.tsv
bash scripts/clean_vcf.sh data/sample.vcf > cleaned_sample.vcf

## Requirements
- Python 3.8+
- pandas
- requests
- Bash
