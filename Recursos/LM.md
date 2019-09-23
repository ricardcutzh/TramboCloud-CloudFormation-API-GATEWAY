# DybamoDB Stack
* Stack in charge of creating the lambda functions
## Parameters

| Parameter      | Description | Type    |
| :---        |    :----:   |          ---: |
| IDTable     | Name for the ID in the DynamoDB's table    |   String |
| Bucket     | Name of the bucket in S3    |   String |

## Resources
| Name      | Description |
| :---        |    :----:   |
| RoleLambda   | Definition for the role that lambda functions will use, this definition contains access to dynamo   |
| InsertData   | Definition for the lambda function in charge of inserting data  |
| GetData   | Definition for the lambda function in charge of listing all items  |
| DeleteData   | Definition for the lambda function in charge deleting an item |


## Outputs
| Output Name      | Description |
| :---        |    :----:   |          ---: |
| InsertFunction     | ARN of the Insert function   |
| GetFunction     | ARN of the Get function   |
| DeleteFunction     | ARN of the Delete function   |