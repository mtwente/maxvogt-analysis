# maxvogt-analysis

This repository contains data for spatial analyses that are part of a research project on spatial/urban design features of railway-related built structures designed by the Swiss architect Max Vogt. The data in this repository is openly available to everyone and is intended to support reproducible research.

Results of the analyses are accessible in an [online collection of Vogt's buildings](https://mtwente.github.io/maxvogt) and presented as a [poster](/docs/abstract.html) at the [Spatial Humanities 2024](https://spathum.uni-bamberg.de/) conference at the University of Bamberg.

[![GitHub issues](https://img.shields.io/github/issues/mtwente/maxvogt-analysis.svg)](https://github.com/mtwente/maxvogt-analysis/issues)
[![GitHub forks](https://img.shields.io/github/forks/mtwente/maxvogt-analysis.svg)](https://github.com/mtwente/maxvogt-analysis/network)
[![GitHub stars](https://img.shields.io/github/stars/mtwente/maxvogt-analysis.svg)](https://github.com/mtwente/maxvogt-analysis/stargazers)
[![DOI](https://zenodo.org/badge/ZENODO_RECORD.svg)](https://zenodo.org/badge/latestdoi/ZENODO_RECORD)
[![Zotero](https://img.shields.io/badge/zotero-maxvogt-bb393c?logo=zotero)](https://www.zotero.org/groups/5400359/sbb-max-vogt/library)
<br>
[![Code license](https://img.shields.io/badge/Code-AGPL_3.0-orange)](LICENSE-AGPL.md)
[![Notebook license](https://img.shields.io/badge/Notebooks-CC_BY--SA_4.0-green)](LICENSE-CCBY.md)
[![Data license](https://img.shields.io/badge/Data-CC_BY--SA_4.0-green)](LICENSE-CCBY.md)
[![Geodata license](https://img.shields.io/badge/Geodata-ODbL--1.0-lightblue)](LICENSE-ODbL.md)

## Repository Structure

The structure of this repository is based on the [Open Research Data Template](https://github.com/maehr/open-research-data-template) by [@maehr](https://www.github.com/maehr), follows the [Advanced Structure for Data Analysis](https://the-turing-way.netlify.app/project-design/project-repo/project-repo-advanced.html) of _The Turing Way_ and is organized as follows:

- `analysis/`: notebooks used to retrieve and analyze the data
- `assets/`: images, logos, etc. used in the README and other documentation
- `data/`: data files
- `docs/`: documentation for the data and the repository
- `results/`: geodata output of the analysis notebooks

Additionally, there is a [Zotero group library](https://www.zotero.org/groups/5400359/sbb-max-vogt/library) with a collection of scientific articles and news reports that are of relevance for this project.

## Data Description

See [Workflow](/docs/workflow.html) for a description of the project workflow and the data obtained for this project.

## Installation

To run the analysis locally, create a new `conda` environment based on the `environment.yml` file.

```bash
conda env create -f environment.yml
```

Activate the environment.

```bash
conda activate maxvogt
```

Open the Jupyter Notebook platform.

```bash
jupyter notebook
```

Pick a notebook from `analysis/` to start the spatial analysis for one of Max Vogt's buildings.

## Use

These data are openly available to everyone and can be used for any research or educational purpose. If you use this data in your research, please cite as specified in [CITATION.cff](CITATION.cff). The following citation formats are also available through _Zenodo_:

- [BibTeX](https://zenodo.org/record/ZENODO_RECORD/export/hx)
- [CSL](https://zenodo.org/record/ZENODO_RECORD/export/csl)
- [DataCite](https://zenodo.org/record/ZENODO_RECORD/export/dcite4)
- [Dublin Core](https://zenodo.org/record/ZENODO_RECORD/export/xd)
- [DCAT](https://zenodo.org/record/ZENODO_RECORD/export/dcat)
- [JSON](https://zenodo.org/record/ZENODO_RECORD/export/json)
- [JSON-LD](https://zenodo.org/record/ZENODO_RECORD/export/schemaorg_jsonld)
- [GeoJSON](https://zenodo.org/record/ZENODO_RECORD/export/geojson)
- [MARCXML](https://zenodo.org/record/ZENODO_RECORD/export/xm)

_Zenodo_ provides an [API (REST & OAI-PMH)](https://developers.zenodo.org/) to access the data. For example, the following command will return the metadata for the most recent version of the data

```bash
curl -i https://zenodo.org/api/records/ZENODO_RECORD
```

## Support

This project is maintained by [@mtwente](https://github.com/mtwente). Please understand that we can't provide individual support via email. We also believe that help is much more valuable when it's shared publicly, so more people can benefit from it.

| Type                                   | Platforms                                                                     |
| -------------------------------------- | ----------------------------------------------------------------------------- |
| 🚨 **Bug Reports**                     | [GitHub Issue Tracker](https://github.com/mtwente/maxvogt-analysis/issues)    |
| 📊 **Report bad data**                 | [GitHub Issue Tracker](https://github.com/mtwente/maxvogt-analysis/issues)    |
| 📚 **Docs Issue**                      | [GitHub Issue Tracker](https://github.com/mtwente/maxvogt-analysis/issues)    |
| 🎁 **Feature Requests**                | [GitHub Issue Tracker](https://github.com/mtwente/maxvogt-analysis/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                                |
| 💬 **General Questions**               | [GitHub Discussions](https://github.com/mtwente/maxvogt-analysis/discussions) |

## Roadmap

- [ ] tidy up jupyter notebooks
- [ ] embed poster on GitHub pages website
- [ ] publish via Zenodo

## Contributing

All contributions to this repository are welcome! If you find errors or problems with the data, or if you want to add new data or features, please open an issue or pull request. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Versioning

We use [SemVer](http://semver.org/) for versioning. The available versions are listed in the [tags on this repository](https://github.com/mtwente/maxvogt-analysis/tags).

## Authors and acknowledgment

- **Moritz Twente** -- _Initial work_ -- [mtwente](https://github.com/mtwente)
- **Luisa Omonsky** -- _Research_ -- [omonsgit](https://github.com/omonsgit)

The Jupyter Notebooks used for data retrieval and analysis are based on the 2021 workshop [_Capturing the Structure of Cities with Data Science workshop_](https://github.com/martinfleis/sdsc21-workshop) by [Martin Fleischmann](https://github.com/martinfleis).

Geodata used in this analysis is retrieved from [OpenStreetMap](https://www.openstreetmap.org), © OpenStreetMap contributors.

See also the list of [contributors](https://github.com/mtwente/maxvogt-analysis/graphs/contributors) who contributed to this project.

## License

The **data** in this repository, excluding OpenStreetMap geodata, is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) License – see the [LICENSE-CCBY](LICENSE-CCBY.md) file for details. By using this data, you agree to give appropriate credit to the original author(s) and to indicate if any modifications have been made.

**Geodata** in this repository, retrieved from OpenStreetMap, is released under the Open Database License – see the [LICENSE-ODbL](LICENSE-ODbL.md) file for details. By using this data, you agree to adhere to the attribution standards set out in the license and specified by the [OpenStreetMap Foundation](https://osmfoundation.org/wiki/Licence).

The **code** in this repository, excluding the Jupyter notebooks in `/analysis/`, is released under the GNU Affero General Public License v3.0 – see the [LICENSE-AGPL](LICENSE-AGPL.md) file for details. By using this code, you agree to make any modifications available under the same license.

The **Jupyter notebooks** in `/analysis/` are released under the Creative Commons Attribution 4.0 International (CC BY 4.0) License – see the [LICENSE-CCBY](LICENSE-CCBY.md) file for details. By using this data, you agree to give appropriate credit to the original author(s) and to indicate if any modifications have been made.
