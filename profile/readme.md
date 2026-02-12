## Purpose

The Fairview Molecular Diagnostic Lab (MDL) collaborates with bioinformatics analysts at the University to Minnesota Supercomputing Institute (MSI) to develop NGS-based clinical pipelines for germline and somatic variant calling. All pipelines, software, and resources, are tracked using this organization. You can learn more about the bioinformatics team here: [`umn-msi-lmnp`](https://github.com/umn-msi-lmnp). To learn more about UMN's GitHUb Enterprise Cloud (GHEC), visit the [docs](https://github-docs.devex.oit.umn.edu).

## Pipelines

- Inherited disease gene panel:
	- [`germline_unified_v1.0`](https://github.com/umn-msi-mdl/germline_pipeline) SNVs, indels
    - [clia_qc](https://github.com/umn-msi-mdl/clia_qc) Germline QC and CNV matches
	- [`wgs_exome_reflex_v1`](https://github.com/umn-msi-mdl/wgs_exome_reflex_v1) Germline reflex analysis
	- [`cnv_aws_v3_cnvrf`](https://github.com/umn-msi-mdl/hadoop-cnv-msi) CNV
	- `pms2_cnv_aws_v3_cnvrf` PMS2-specific reflex analysis
- Whole genome sequencing (WGS):
	- [`wgs_exome_v1.0_with_mtDNA_variant_calling`](https://github.com/umn-msi-mdl/clia_wgs) WGS: SNVs, indels
	- [`wgs_sv`](https://github.com/umn-msi-mdl/clia_wgs_sv) WGS: SVs
- Somatic disease gene panel:
	- [`clia_hybcap`](https://github.com/umn-msi-mdl/clia_hybcap) SNVs, indels, CNV, MSI, TMB
- Pharmacogenomics:
	- [`clia_pgx`](https://github.com/umn-msi-mdl/clia_pgx) Star allele calling for 31 genes


## Other 

- [clia_transfer](https://github.com/umn-msi-mdl/clia_transfer) Automated transfers between MSI & MDL
- [clia_bcl2fastq](https://github.com/umn-msi-mdl/clia_bcl2fastq) NovaSeq fastqs
- [clia_bases2fastq](https://github.com/umn-msi-mdl/clia_bases2fastq) AVITI fastqs
- [mdlvalr](https://github.com/umn-msi-mdl/mdlvalr) Concordance and validation analysis

