## Ruby

These settings apply only when `--ruby` is specified on the command line.

``` yaml
package-name: rest_client_v1
```

### Ruby multi-api

``` yaml $(ruby) && $(multiapi)
batch:
  - tag: v1
```

### Tag: v1 and ruby

These settings apply only when `--tag=v1 --ruby` is specified on the command line.
Please also specify `--ruby-client-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'v1' && $(ruby)
namespace: "Haipa::Client::V1"
output-folder: $(ruby-client-folder)/lib
```
