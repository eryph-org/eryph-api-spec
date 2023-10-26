# C# Identity

> see https://aka.ms/autorest

This is the AutoRest configuration file for eryph identity.

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-src-folder=<path to src directory`.

## Common C# settings

``` yaml $(csharp)
  generation1-convenience-client: true
  public-clients: true
  single-top-level-client: true
  license-header: MIT
  clear-output-folder: true
```

``` yaml $(csharp)
namespace: Eryph.IdentityClient
output-folder: $(csharp-src-folder)/src/Eryph.IdentityClient/Generated
```
