## Node.js

These settings apply only when `--nodejs` is specified on the command line.
Please also specify `--node-sdks-folder=<path to root folder of your azure-sdk-for-node clone>`.

``` yaml $(nodejs)
nodejs:
  azure-arm: true
  package-name: azure-arm-storage
  output-folder: $(node-sdks-folder)/lib/services/storageManagement2/lib
  payload-flattening-threshold: 2
  override-client-name: StorageManagementClient
```
