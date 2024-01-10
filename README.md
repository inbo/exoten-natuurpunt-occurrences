# Waarnemingen.be - Non-native animal and plant occurrences in Flanders and the Brussels Capital Region, Belgium

This repository is about the datasets _Non-native animal occurrences_ and _Non-native plant occurrences_ derived from https://waarnemingen.be. Natuurpunt manages and validates the source data, INBO provides technical support in publishing it to [GBIF](https://www.gbif.org/).

**Data are published automatically** (on a weekly basis): the IPT is set to auto-publication and will read the latest data directly from a Natuurpunt server. This repo is only for periodic validation and reporting data quality issues.**

## Useful links

- [Animal dataset on the IPT](https://ipt.inbo.be/resource?r=dieren-exoten-natuurpunt-occurrences)
- [Animal dataset on GBIF](https://doi.org/10.15468/k2aiak)
- [Plant dataset on the IPT](https://ipt.inbo.be/resource?r=planten-exoten-natuurpunt-occurrences)
- [Plant dataset on GBIF](https://doi.org/10.15468/smdvdo)
- [Reported issues](https://github.com/inbo/exoten-natuurpunt-occurrences/issues)

## Repo structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── .gitignore             : Files and directories to be ignored by git
│
├── data
│   ├── raw                : Darwin Core data as published on the IPT
│   └── interim            : Interim exports of the validation script GENERATED
│
├── specification          : Specification for the data (used for validation)
│
└── notebooks              : Scripts to validate the data
```
