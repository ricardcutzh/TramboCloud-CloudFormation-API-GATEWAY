# API Stack
* Stack in charge of creating the API
## Parameters

| Parameter      | Description | Type    |
| :---        |    :----:   |          ---: |
| FuncAddPerson     | ARN of the lambda function that adds a person to the table   |   String |
| FuncGetPersona     | ARN of the lambda function that gets all itmes in the table    |   String |
| FuncDeletePersona     | ARN of the lambda function that deletes a person to the table    |   String |

## Resources

### API Definition
| Name      | Description |
| :---        |    :----:   |
| RicardoAPI   | Definition of the REST API |

### Insert Operation
| Name      | Description |
| :---        |    :----:   |
| InsertResource   | Definition of the API resource to add data operation |
| AddPersonaMethod   | Definition of the API method associated to the Insert Resource |
| PermisoAdd   | Definition of the permissions to execute the insert lambda function |

### Get Operation
| Name      | Description |
| :---        |    :----:   |
| GetResource   | Definition of the API resource to get data operation |
| GetPersonasMethod   | Definition of the API method associated to the Get Resource |
| PermisoGet   | Definition of the permissions to execute the get lambda function |

### Delete Operation
| Name      | Description |
| :---        |    :----:   |
| DeleteResource   | Definition of the API resource to delete data operation |
| DeletePersonasMethod   | Definition of the API method associated to the Delete Resource |
| PermisoDelete   | Definition of the permissions to execute the delete lambda function |

### Deployment
| Name      | Description |
| :---        |    :----:   |
| DeploymentTest   | Definition of the Deployment Stage of the API |
