# The `umn-msi-mdl` GitHub Organization

## Purpose

The Fairview Molecular Diagnostic Lab (MDL) collaborates with bioinformatics analysts at the University to Minnesota Supercomputing Institute (MSI) to develop NGS-based clinical pipelines for germline and somatic variant calling. All pipelines, software, and resources, are tracked using this organization. You can learn more about the bioinformatics team here: [`umn-msi-lmnp`](https://github.com/umn-msi-lmnp).


This MSI directory contains nearly all software, data, and results related to the MDL:

```
/home/clinicalmdl/shared
```

## Pipelines

The current MDL analysis pipelines:

- Inherited disease gene panel:
	- [`germline_unified_v1.0`](https://github.umn.edu/clinicalmdl/germline_pipeline) SNVs, indels
	- [`wgs_exome_reflex_v1`](https://github.umn.edu/clinicalmdl/wgs_exome_reflex_v1) Germline reflex analysis
	- [`cnv_aws_v3_cnvrf`](https://github.umn.edu/clinicalmdl/hadoop-cnv-msi) CNV
	- `pms2_cnv_aws_v3_cnvrf` PMS2-specific
	eflex analysis
- Whole genome sequencing (WGS):
	- [`wgs_exome_v1.0_with_mtDNA_variant_calling`](https://github.umn.edu/clinicalmdl/clia_wgs_exome) 
	- [`wgs_sv`](https://github.umn.edu/clinicalmdl/clia_wgs_sv)
- Somatic disease gene panel:
	- [`clia_hybcap`](https://github.umn.edu/clinicalmdl/clia_hybcap) SNVs, indels, CNV, MSI, TMB
- Pharmacogenomics:
	- [`clia_pgx`](https://github.umn.edu/clinicalmdl/clia_pgx)


## Other 
We develop these pipelines using an isolated set of software using [conda environments](https://github.umn.edu/clinicalmdl/clia_conda), [custom built tools](https://github.umn.edu/clinicalmdl/clia_tools), and manually maintained [resource](https://github.umn.edu/clinicalmdl/resources) files.

We also coordinate the [transfer of data](https://github.umn.edu/clinicalmdl/clia_transfer) between MSI and Fairview. We move Novaseq run directories to MSI for [fastq generation](https://github.umn.edu/clinicalmdl/clia_bcl2fastq).

In addition, we facilitate [validation](https://github.umn.edu/clinicalmdl/mdlvalr) analysis, and maintain a set of [test data](https://github.umn.edu/clinicalmdl/data_test) for each pipeline. And keep records of how [validations were performed](https://github.umn.edu/clinicalmdl/validations). We also run [quality control](https://github.umn.edu/clinicalmdl/clia_qc) analysis.

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

