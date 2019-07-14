# Haipa API Spec
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for the Haipa Api.


---
## Getting Started 
To build the API for Haipa, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information 
These are the global settings for the Haipa API.

``` yaml
title: HaipaCompute
tag: v1
```

### Tag: v1

These settings apply only when `--tag=v1` is specified on the command line.

``` yaml $(tag) == 'v1'
input-file:
- v1/swagger.json
```

