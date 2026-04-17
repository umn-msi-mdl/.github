## Purpose

The Fairview Molecular Diagnostic Lab (MDL) collaborates with bioinformatics analysts at the University to Minnesota Supercomputing Institute (MSI) to develop NGS-based clinical pipelines for germline and somatic variant calling. All pipelines, software, and resources, are tracked using this organization. You can learn more about the bioinformatics team here: [`umn-msi-lmnp`](https://github.com/umn-msi-lmnp). To learn more about UMN's GitHUb Enterprise Cloud (GHEC), visit the [docs](https://github-docs.devex.oit.umn.edu).

🔒Everything in this GitHub org has locked permissions. If you see a 404 page, please email Todd Knutson <knut0297@umn.edu> for access.

## Pipelines

- Inherited disease gene panel:
	- [`clia_germline`](https://github.com/umn-msi-mdl/clia_germline) SNVs and indels
    - [`clia_qc`](https://github.com/umn-msi-mdl/clia_qc) Germline QC and CNV matches
	- [`cnv_aws_v3_cnvrf`](https://github.com/umn-msi-mdl/hadoop-cnv-msi) CNV
	- `pms2_cnv_aws_v3_cnvrf` PMS2/PMS2CL-specific CNV
    - [`clia_pms2`](https://github.com/umn-msi-mdl/clia_pms2) Sequencing analysis of long-range PCR for PMS2/PMS2CL
- Whole genome sequencing (WGS):
	- [`clia_wgs`](https://github.com/umn-msi-mdl/clia_wgs) WGS: SNVs, indels, SV, and reflex gene panels
	- [`clia_wgs_aws`](https://github.com/umn-msi-mdl/clia_wgs_aws) WGS: SNVs, indels, SV, and reflex gene panels
	- [`clia_wgs_ont`](https://github.com/umn-msi-mdl/clia_wgs_ont) Nanopore long read WGS: SNVs, indels, SV, and reflex gene panels
- Somatic disease gene panel:
	- [`clia_oncology`](https://github.com/umn-msi-mdl/clia_oncology) SNVs, indels, CNV, MSI, and TMB
- Pharmacogenomics:
	- [`clia_pgx`](https://github.com/umn-msi-mdl/clia_pgx) Star allele calling for 31 genes


## Other 

- [`clia_transfer`](https://github.com/umn-msi-mdl/clia_transfer) Automated transfers between MSI and MDL
- [`clia_bcl2fastq`](https://github.com/umn-msi-mdl/clia_bcl2fastq) NovaSeq demultiplexing and fastq generation
- [`clia_bases2fastq`](https://github.com/umn-msi-mdl/clia_bases2fastq) AVITI demultiplexing and fastq generation
- [`validations`](https://github.com/umn-msi-mdl/validations) Concordance and validation projects
- [`mdlvalr`](https://github.com/umn-msi-mdl/mdlvalr) R package used for validations

