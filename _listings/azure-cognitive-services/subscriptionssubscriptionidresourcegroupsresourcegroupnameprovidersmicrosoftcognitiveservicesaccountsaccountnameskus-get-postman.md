{
  "info": {
    "name": "Azure Cognitive Services Cognitive Services Accounts List Skus",
    "_postman_id": "cc160443-79d6-4588-894d-4fa62776fccb",
    "description": "List available SKUs for the requested Cognitive Services account",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cognitive service",
      "item": [
        {
          "id": "3de465ab-3528-4f9e-b633-cb0d7edd3e81",
          "name": "CognitiveServicesAccounts_ListSkus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.CognitiveServices/accounts/:accountName/skus"
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
            "description": "List available SKUs for the requested Cognitive Services account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97afd91e-dc5b-4ec9-ae8e-ec2f5dcbe165"
            }
          ]
        }
      ]
    }
  ]
}