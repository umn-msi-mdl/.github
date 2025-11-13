## Purpose

The Fairview Molecular Diagnostic Lab (MDL) collaborates with bioinformatics analysts at the University to Minnesota Supercomputing Institute (MSI) to develop NGS-based clinical pipelines for germline and somatic variant calling. All pipelines, software, and resources, are tracked using this organization. You can learn more about the bioinformatics team here: [`umn-msi-lmnp`](https://github.com/umn-msi-lmnp).

## Pipelines

- Inherited disease gene panel:
	- [`germline_unified_v1.0`](https://github.com/umn-msi-mdl/germline_pipeline) SNVs, indels
	- [`wgs_exome_reflex_v1`](https://github.com/umn-msi-mdl/wgs_exome_reflex_v1) Germline reflex analysis
	- [`cnv_aws_v3_cnvrf`](https://github.com/umn-msi-mdl/hadoop-cnv-msi) CNV
	- `pms2_cnv_aws_v3_cnvrf` PMS2-specific
	eflex analysis
- Whole genome sequencing (WGS):
	- [`wgs_exome_v1.0_with_mtDNA_variant_calling`](https://github.com/umn-msi-mdl/clia_wgs_exome) 
	- [`wgs_sv`](https://github.com/umn-msi-mdl/clia_wgs_sv)
- Somatic disease gene panel:
	- [`clia_hybcap`](https://github.com/umn-msi-mdl/clia_hybcap) SNVs, indels, CNV, MSI, TMB
- Pharmacogenomics:
	- [`clia_pgx`](https://github.com/umn-msi-mdl/clia_pgx)


## Other 
We develop these pipelines using an isolated set of software using [conda environments](https://github.com/umn-msi-mdl/clia_conda), [custom built tools](https://github.com/umn-msi-mdl/clia_tools), and manually maintained [resource](https://github.com/umn-msi-mdl/resources) files.

We also coordinate the [transfer of data](https://github.com/umn-msi-mdl/clia_transfer) between MSI and Fairview. FASTQs are generated for [NovaSeq](https://github.com/umn-msi-mdl/clia_bcl2fastq) and [AVITI](https://github.com/umn-msi-mdl/clia_bases2fastq) run dirs.

In addition, we facilitate [validation](https://github.com/umn-msi-mdl/mdlvalr) analysis, and maintain a set of [test data](https://github.com/umn-msi-mdl/data_test) for each pipeline. And keep records of how [validations were performed](https://github.com/umn-msi-mdl/validations). We also run [quality control](https://github.com/umn-msi-mdl/clia_qc) analysis.

Important paths:

```
/home/clinicalmdl/shared/results
/home/clinicalmdl/shared/results_test
/home/clinicalmdl/shared/analysis
/home/clinicalmdl/shared/resources
/home/clinicalmdl/shared/validations
/home/clinicalmdl/shared/transfers
/home/clinicalmdl/shared/data_test/
/home/clinicalmdl/shared/data_release/
```

