{
  "info": {
    "name": "Azure Cognitive Services Cognitive Services Accounts List Keys",
    "_postman_id": "7a7d8edd-998a-492b-ae6d-c0680b929ef4",
    "description": "Lists the account keys for the specified Cognitive Services account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cognitive service",
      "item": [
        {
          "id": "158d5357-a096-4978-8e82-f58ec12079dc",
          "name": "CognitiveServicesAccounts_ListKeys",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.CognitiveServices/accounts/:accountName/listKeys"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account keys for the specified Cognitive Services account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "872bd892-7256-4c42-9933-f228d47ab347"
            }
          ]
        }
      ]
    }
  ]
}