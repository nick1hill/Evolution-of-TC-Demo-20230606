# Evolution of TC Demo repo

This repository is intended to be used to demo a practical docs-as-code process in the Evolution of TC conference on 6 June 2023.

The DITA source files are taken from https://github.com/dita-ot/docs repository, which are licensed under the terms of its Apache License 2.0.

This repo also has an Apache License 2.0.

This repo has the following GitHub Actions:

- Docker-based DITA Open Toolkit build of the source files into uncustomized PDF

## Contents of this repo

README.md - this file
License - Apache License 2.0 for this repo
taskbook.ditamap - ditamap used as input for building the documentation.
  - taskbook - folder with the dita files required for the document
  - .github 
    - workflows
      - buildPDF.yml -YAML file that provides instructions for the GitHub Action used to build the PDF
