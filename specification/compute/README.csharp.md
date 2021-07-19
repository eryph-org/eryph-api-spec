# C# Compute

> see https://aka.ms/autorest

This is the AutoRest configuration file for Eryph Compute.

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-src-folder=<path to src directory`.

## Common C# settings

``` yaml $(csharp)
csharp:
  eryph: true
  license-header: MIT
  payload-flattening-threshold: 1
  clear-output-folder: true
```

``` yaml $(csharp)
namespace: Eryph.ComputeClient
output-folder: $(csharp-src-folder)/src/Eryph.ComputeClient/Generated
```
