# Coiote Result Transformation
> Take the result from the cloud integration and transform it from "Coiote format" to "Asset Tracker" format. 

Coiote offers 2 options to perform integration with the cloud:
1. AWS
2. Azure 

Both return different data struct on their outputs, for that reason each one will be cover at the following links:

1. AWS
2. [Azure](https://github.com/MLopezJ/asset-tracker-cloud-coiote-azure-converter-js) 


## Notes

* Server timestamp is used in case an [expected](https://github.com/NordicSemiconductor/asset-tracker-cloud-docs/blob/saga/docs/cloud-protocol/state.reported.azure.json) timestamp is missing: [+ info](https://github.com/MLopezJ/coiote-result-transformation/issues/1)
