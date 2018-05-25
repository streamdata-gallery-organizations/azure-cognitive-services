{
  "info": {
    "name": "Azure Cognitive Services Cognitive Services Accounts Get Properties",
    "_postman_id": "88274d90-7a5a-4caa-94ad-86240aafb1c9",
    "description": "Returns a Cognitive Services account specified by the parameters.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cognitive service",
      "item": [
        {
          "id": "9ccb1be9-92bc-46c1-b95b-23b3c9233a90",
          "name": "CognitiveServicesAccounts_GetProperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.CognitiveServices/accounts/:accountName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a Cognitive Services account specified by the parameters"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ac56fec-0b2f-454c-8d4b-29061613b173"
            }
          ]
        }
      ]
    }
  ]
}