# DybamoDB Stack
* Stack in charge of creating the table to store information
## Parameters

| Parameter      | Description | Type    |
| :---        |    :----:   |          ---: |
| IDTable     | Name for the ID in the DynamoDB's table    |   String |
| IDType     | Type for the ID in the DynamoDB's table    |   String |
| Name     |  Name for the DybamoDB Table |   String |

## Resources
| Name      | Description |
| :---        |    :----:   |
| DynamoDBTable   | Definition of the DynamoDB table to store information   |

## Outputs
| Output Name      | Description |
| :---        |    :----:   |          ---: |
| DatabaseDynamo     | DynamoDB resource reference    |