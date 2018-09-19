# Modernization Infrastructure (OSS)

This repo contains infrastructure as code (IaC) for CA-MMIS Modernization's AWS infrastructure. The repo is sorted in the following fashion:

- common: IaC re-used across environments, likely heavily parameterized to keep general
- dev: IaC specific to the development environment
- docs: Documentation on how to use the code in this repository
- prod: IaC specific to the production environment
- stage: IaC specific to the stage environment

The intent is to make as much live in `common` as possible to keep infrastructure consistent across layers.