{
  "info": {
    "name": "Azure Cognitive Services Cognitive Services Accounts Delete",
    "_postman_id": "370dcd02-d263-4c31-bc68-297025585b95",
    "description": "Deletes a Cognitive Services account from the resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cognitive service",
      "item": [
        {
          "id": "4a72a87c-e6d1-49bc-a077-b16a1b83353b",
          "name": "CognitiveServicesAccounts_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a Cognitive Services account from the resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f62770ef-7b7d-4cdd-9967-8820ce98571e"
            }
          ]
        }
      ]
    }
  ]
}