# Eryph API Specifications

## Description

This repository is the canonical source for REST API specifications for eryph.

## Directory Structure

The structure of the directory should strictly follow these rules:

1. **Specification**: This folder the is root folder for all Specs related docs.

1. **API versions**: This folder will contain the OpenAPI validation Specs (Swaggers previously) and the examples folder.

1. **Examples**: the example folder will contain the examples files. it will reside under the APIs version folders as different APIs can have different examples.


The structure should appear like so:
```bash
.
\---specification
|    \---v1
|    |   \---examples
|    |       \---
\--- readme.md
```

Currently, the specifications are expected to be in Swagger JSON format (OpenAPI V2).
