## CosmosDB Triggers Relationship

A relationship type representing CosmosDB-to-AzureCFunction communication.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `AzureCosmosDBTriggers` | `radon.relationships.azure.AzureCosmosDBTriggers` | 1.0.0 | `radon.relationships.azure.Triggers` |

### Notes

* The following parameters are added to tht inputs of the `Configure` interface:
    * `COLLECTION_NAME`
    * `CONNECTION_STRING_SETTING`
    * `ACCOUNT_NAME`
    * `RESOURCE_GROUP`
* A template of this type should provide implementation artifacts that deploy the Azure Function specified at the `TARGET` side.
