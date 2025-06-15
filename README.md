# NGS Real Variant Filter

This project filters a real small VCF subset (from chromosome 22, 1000 Genomes Project)  
to remove low-quality variants (QUAL < 30).

## Dataset
- 1000 Genomes Project chr22 region
- Public domain data

## Structure
- `scripts/` → Python filtering script
- `data/` → Example VCF file

## How to Run
```bash
python scripts/filter_vcf.py data/chr22_subset.vcf > data/chr22_filtered.vcf
```

## Requirements
- Python 3.6+

## Disclaimer
This project uses public domain data (1000 Genomes Project).
