# Introduction
<!-- 
==> Public templates

- Template
    - Base and fork and links
    - Descriptions
- Support
    - Disclaimer
        - Source control threat
        - License
            - In general, SOLO will release software under the GNUGPL3 license, and media under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
- Usage
    - Github specific
        - Github desktop
        - Clone
        - Branch
        - etc.
    - Python specific
        - Vscode
        - Spyder
        - Conda
        - pip

Organistaion level github list of projects? ==> js

Base repo: Metadata file (project-metadata.yml)
- PI
- Researchers
- Lab
- Unit
- Institute
- Faculty
- Entity
- StartTime
- EndTime
- Status
- ProjectName
- ProjectDesc
- SupportStaff
- SoloProjectOwner
- ResearchProjectOwner

Explain these fields in the github pages
YML explanation

Unit list: official shorthand.

Data directory in base. ==> !.gitignore

Link organisational readme to github pages

Cross link organisations -->


# BLA

This repository specifies the most basic structure of repositories used by SOLO. The other repository templates are extensions on this base template. Media files for this README can be found in the `readme-media` directory.

The remainder of this README file contains a few notes on repository naming conventions, and a support disclaimer.

## Naming conventions

SOLO uses two github organisations. The solo-fsw organisation contains internal projects (not for specific research groups), while the solo-fsw-projects organisation contains projects done for or in collaboration with specific researcher(s) / reasearch groups.

The repositories in both organisations follow the naming convention `<Project name/description>-<Date/Year if applicable>`. The solo-fsw-projects repos are further pre-pended with `<Lab/section/institute>-<PI/lead-researcher if applicable>-`. The clauses are written using lower-case letters and numbers. Underscores are used as spaces within clauses (snake_case). Dashes are used to separate clauses.
 
### Examples in solo-fsw-projects

- copan-juan_perea-manometer
- copan-fabiola_diana-prisoners_dilemma-2023
- copan-fabiola_diana-julia_folz-pdt_converter-2023
- prsm-josi_marschall-bodhi
- prsm-lowlands-2023
 
### Examples in solo-fsw

- digitimer-ds-controller
- python-markers

## Support disclaimer

What follows is a disclaimer regarding SOLO support for (mainly software) projects. We advise adding it to the root README of projects in order to encourgae researchers to use git, which in turn makes support in software development easier.

### Disclaimer
SOLO project support often includes support in the development of software. We wish to limit this support to software that is being kept under version control (read: software that uses git) in order to make support easier. As such, if your software is not under version control, we will not offer support for it.
