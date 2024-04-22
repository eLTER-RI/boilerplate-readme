# Logo

Add an eLTER logo or a logo specific to the tool/software at the top of
the `README.md` file.

eLTER logos can be found [here](https://elter-ri.eu/media-center/logo).

Example:

```         
<p align="center">
  <img src="assets/eLTER-IMAGE-eLTER_logo-v01.svg" alt="eLTER Project Logo" width="300" height="auto"/>
</p>
```

<p align="center">
  <img src="assets/eLTER-IMAGE-eLTER_logo-v01.svg" alt="eLTER Project Logo" width="300" height="auto"/>
</p>

# Repository title

Add a clear and concise title for your repository.

# Badges

Optionally, add the badges of your repository. For example add the badge
for the license and the programming languages used in the repository:

```         
![](https://img.shields.io/badge/license-EUPL--1.2-orange)
![](https://img.shields.io/badge/R-v4.4.0-orange)
![](https://img.shields.io/badge/Python-3.12.0-orange)
```

![](https://img.shields.io/badge/license-EUPL--1.2-orange)
![](https://img.shields.io/badge/R-v4.4.0-orange)
![](https://img.shields.io/badge/Python-3.12.0-orange)

## Description

Brief description of the project including its objectives and what it
achieves.

## Table of Contents

Add a table of contents at the beginning of the `README.md` file.

-   [Installation and usage](#installation-and-usage)
-   [Coding style](#coding-style)
-   [Data standards](#data-standards)
-   [File naming nomenclature](#file-naming-nomenclature)
-   [Reproducibility](#reproducibility)
-   [Contributing](#contributing)
-   [Authors](#authors)
-   [License](#license)
-   [Citation](#citation)
-   [Acknowledgments](#acknowledgments)

## Installation and usage

Instructions on how to use the software, including links to any required
software and dependencies, and any necessary commands or scripts.
Provide examples:

-   On R, install the package `tidyverse`.

```         
install.packages(tidyverse)
```

## Coding style

To maintain the quality and readability of our code, we follow certain
coding standards. Contributors are expected to adhere to these
guidelines when writing code for this project:

### R

-   Our R code adheres to the [tidyverse style
    guide](https://style.tidyverse.org/). Key points include:
    -   Name variables and functions in `snake_case`
    -   Place spaces around all binary operators (=, +, -, \<-, etc.),
        except in function arguments.
    -   Always use `<-`, not `=`, for assignment.

### Python

-   We follow the [PEP 8 style
    guide](https://www.python.org/dev/peps/pep-0008/) for Python code.
    This includes guidelines on code layout, naming conventions, and
    best practices.
-   Use 4 spaces per indentation level.

### Tools for enforcing style

-   For Python, consider using tools like
    [`flake8`](https://github.com/PyCQA/flake8) or
    [`black`](https://github.com/psf/black) to automatically check and
    format code.
-   For R, you can use the [`lintr`](https://lintr.r-lib.org/) package
    or RStudio's built-in code formatting capabilities.

## Data standards

This project adheres to eLTER data standards. Please ensure all data
complies with these standards and is deposited appropriately in
[Zenodo](https://zenodo.org/communities/elter) or
[B2SHARE](https://b2share.eudat.eu/communities/LTER) repositories as per
eLTER community guidelines.

## File naming nomenclature

To ensure clarity and ease of access for all contributors, please adhere
to the following file naming conventions:

-   Use descriptive names that reflect the content or purpose of the
    file.
-   Use hyphens (-) to separate different elements of the file name, and
    underscores (\_) to denote spaces within an element.
-   Keep file names concise, avoiding unnecessary abbreviations while
    maintaining sufficient detail.
-   Include the project identifier (i.e. `eLTER`) name at the beginning
    of the files when possible.
-   Include a version number at the end of the file name such as v01.
    Change this version number each time the file is saved.
-   Include an identifier of what the file is on the file name.
-   Examples:
    -   `eLTER-CODE-data_loading-v01.R`
    -   `eLTER-DATA-temperature_sensor_data-v01.csv`

## Reproducibility

Ensure the reproducibility of your work by:

-   Providing detailed descriptions of methods and protocols in the
    documentation.
-   Including version-controlled source code for all scripts and
    analysis workflows.
-   Specifying versions and sources of external libraries and tools
    used.
-   Sharing raw data and processed results in accessible, referenced
    data repositories with clear metadata.
-   Documenting any deviations from the expected protocols.

## Contributing

The repository should have clear instructions on how to contribute to
the project. This should include different files with clear
instructions. To do so, add a folder named `.github` on the project
root. In this folder you should add the following files:

-   `CONTRIBUTING.md`
-   `CODE_OF_CONDUCT.md`
-   `PULL_REQUEST_TEMPLATE.md`
-   `ISSUE_TEMPLATE.md`
-   `BUG_REPORT.md`
-   `FEATURE_REQUEST.md`

## Authors

List of contributors to the project. Include [ORCID](https://orcid.org/)
to uniquely identify contributors and the Research Organization Registry
([ROR](https://ror.org/)) for the institution.

| Author | Affiliation | ORCID | e-mail |
| :---: | :---: | :---: | :---: |
| Allan T. Souza | [University of Helsinki](https://ror.org/040af2s02) | [0000-0002-1851-681X](https://orcid.org/0000-0002-1851-681X) | [allan.souza\@helsinki.fi](mailto:allan.souza@helsinki.fi) |

Optionally, you can also add the authors faces with the link to their
GitHub accounts. To do so, you can add the a code like the one below on
the `README.md` file:

```         
[//]: contributor-faces

<a href="https://github.com/allantsouza"><img src="https://avatars.githubusercontent.com/u/51362002?v=4" title="Allan T. Souza" width="70" height="70"></a>

[//]: contributor-faces
```

<a href="https://github.com/allantsouza"><img src="https://avatars.githubusercontent.com/u/51362002?v=4" title="Allan T. Souza" width="70" height="70"/></a>

To find the URL of your the avatar, you can query using the GitHub API,
like in this example:

```         
https://api.github.com/search/users?q=Allan+T+Souza+in%3Ausername
```

## License

Describe the license used in the project and include a file named
`LICENSE` in the root of the repository:

-   This project is licensed under the [EUPL
    License](https://eupl.eu/) - see the [LICENSE](LICENSE) file for
    details.

## Citation

Add a file containing the citation information on the repository root
folder. The file should be named `CITATION.cff`. More information about
Citation File Format (cff) files can be found
[here](https://citation-file-format.github.io/). Below there is an
example of the contents of a generic `CITATION.cff` file:

```         
cff-version: 1.2.0
message: "If you use this repository, please cite it as below."
title: "eLTER boilerplate readme"
version: 1.0.0
year: 2024
authors:
  - family-names: "Souza"
    given-names: "Allan T."
    orcid: "https://orcid.org/0000-0002-1851-681X"
    affiliation: "Institute for Atmospheric and Earth System Research (INAR), Forest Sciences, Faculty of Agriculture and Forestry, University of Helsinki, P.O. Box 27, 00014 Helsinki, Finland"
license: EUPL-1.2
url: "https://github.com/eLTER-RI/boilerplate-readme"
```

## Acknowledgments

Add the funding acknowledgment for eLTER PPP, eLTER PLUS, and/or eLTER
EnRich.

<p align="center">
  <a href="https://elter-ri.eu/elter-ppp">
    <img src="assets/eLTER-IMAGE-PPP_logo-v01.svg" alt="eLTER PLUS Logo" width="175" height="auto"/>
  </a> <a href="https://elter-ri.eu/elter-plus">
    <img src="assets/eLTER-IMAGE-PLUS_logo-v01.svg" width="175" height="auto"/>
  </a> <a href="https://elter-ri.eu/elter-enrich">
    <img src="assets/eLTER-IMAGE-EnRich_logo-v01.svg" alt="eLTER EnRich Logo" width="175" height="auto"/>
  </a>
</p>
