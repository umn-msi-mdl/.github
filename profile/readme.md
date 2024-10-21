# `clinicalmdl`

This MSI directory contains nearly all software, data, and results related to the MDL:

```
/home/clinicalmdl/shared
```

## Software

The work in the molecular diagnostics lab (MDL) includes running the following NGS analysis pipelines:

- Inherited disease [germline](https://github.umn.edu/clinicalmdl/germline_pipeline) panels (SNVs, indels): germline_unified_v1.0
- Inherited disease CNV: [cnv_aws_v3_cnvrf](https://github.umn.edu/clinicalmdl/hadoop-cnv-msi)
- Inherited disease (PMS2-specific): pms2_cnv_aws_v3_cnvrf
- Whole genome ([SNVs, Indels](https://github.umn.edu/clinicalmdl/clia_wgs_exome)): wgs_exome
- Whole genome ([structural variants](https://github.umn.edu/clinicalmdl/clia_wgs_sv)): wgs_sv
- [Hematology/Oncology](https://github.umn.edu/clinicalmdl/clia_hybcap) panels (SNVs, indels, CNV, MSI, TMB): clia_hybcap
- [Pharmacogenomics](https://github.umn.edu/clinicalmdl/clia_pgx)

Some of these pipelines require reflex analysis:

- [exome](https://github.umn.edu/clinicalmdl/wgs_exome_reflex_v1)

### Access the software

To use or run a tool/pipeline, see the readme file for that particular tool. However, you can run the command below in your Terminal shell, which will allow you to load various MDL modules.

```
export MODULEPATH="/home/clinicalmdl/shared/software/modulefiles:${MODULEPATH}"
```

We develop these pipelines using an isolated set of software using [conda environments](https://github.umn.edu/clinicalmdl/clia_conda), [custom built tools](https://github.umn.edu/clinicalmdl/clia_tools), and manually maintained [resource](https://github.umn.edu/clinicalmdl/resources) files.

We also coordinate the [transfer of data](https://github.umn.edu/clinicalmdl/clia_transfer) between MSI and Fairview. We move Novaseq run directories to MSI for [fastq generation](https://github.umn.edu/clinicalmdl/clia_bcl2fastq).

In addition, we facilitate [validation](https://github.umn.edu/clinicalmdl/mdlvalr) analysis, and maintain a set of [test data](https://github.umn.edu/clinicalmdl/data_test) for each pipeline. And keep records of how [validations were performed](https://github.umn.edu/clinicalmdl/validations). We also run [quality control](https://github.umn.edu/clinicalmdl/clia_qc) analysis.

## Raw Data

These dirs contain primarily raw fastqs and or run directories.

```
/home/clinicalmdl/shared/data_release/
	novaseq_fastqs/
	fairview_fastqs/
	novaseq_rundirs/

/home/clinicalmdl/shared/data_test/
```

## Results

```
/home/clinicalmdl/shared/results
/home/clinicalmdl/shared/results_test
```

## Analysis (i.e. Quality Control and other summaries)

```
/home/clinicalmdl/shared/analysis
```

## Resources

```
/home/clinicalmdl/shared/resources
```

## Validations

```
/home/clinicalmdl/shared/validations
```

## Transfers

Logs of all transfers

```
/home/clinicalmdl/shared/transfers
```

## Project development and testing

```
/home/clinicalmdl/shared/$USER/
	software/
	data/
	results/
	resources/
	analysis/
	validations/
```

## Philosophy

The data and software plan above is a work in progress that will take time to complete. Everything described here may not be current.

GitHub should contain the most current and accurate information and code. When developing new features, code is cloned from GitHub, modified in a development space, and pushed back. Updated software builds are generated from the repos on GitHub. There should not be any directory used for "production" processes that are found outside of `/home/clinicalmdl/shared/software`.

Documentation and details for each pipeline, software tool, or other methods should be "closest to the source code." Practically, that means we should maintain information for how to run, develop, install, contribute, etc. in the "readme" file for each GitHub repo. If it is easier or makes sense to move this information into to a Google Doc, then a link to the doc should be included in the repo's readme. The MSI wiki could be a reasonable option, but this tool is inaccessible by non-MSI staff, which limits it's availability.
