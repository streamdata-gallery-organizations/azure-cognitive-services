---
swagger: "2.0"
x-collection-name: Azure Cognitive Services
x-complete: 0
info:
  title: Azure Cognitive Services Cognitive Services Accounts List Keys
  description: Lists the account keys for the specified Cognitive Services account.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}:
    put:
      summary: Cognitive Services Accounts Create
      description: Create Cognitive Services Account. Accounts is a resource group
        wide resource type. It holds the keys for developer to access intelligent
        APIs. It's also the resource type for billing.
      operationId: CognitiveServicesAccounts_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of Cognitive Services account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters to provide for the created account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Cognitive Service
    patch:
      summary: Cognitive Services Accounts Update
      description: Updates a Cognitive Services account
      operationId: CognitiveServicesAccounts_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-patch
      parameters:
      - in: path
        name: accountName
        description: The name of Cognitive Services account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters to provide for the created account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Cognitive Service
    delete:
      summary: Cognitive Services Accounts Delete
      description: Deletes a Cognitive Services account from the resource group.
      operationId: CognitiveServicesAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of Cognitive Services account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Cognitive Service
    get:
      summary: Cognitive Services Accounts Get Properties
      description: Returns a Cognitive Services account specified by the parameters.
      operationId: CognitiveServicesAccounts_GetProperties
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of Cognitive Services account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Cognitive Service
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts:
    get:
      summary: Accounts List By Resource Group
      description: Returns all the resources of a particular type belonging to a resource
        group
      operationId: Accounts_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccounts-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Account
  /subscriptions/{subscriptionId}/providers/Microsoft.CognitiveServices/accounts:
    get:
      summary: Accounts List
      description: Returns all the resources of a particular type belonging to a subscription.
      operationId: Accounts_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftcognitiveservicesaccounts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}/listKeys
  : post:
      summary: Cognitive Services Accounts List Keys
      description: Lists the account keys for the specified Cognitive Services account.
      operationId: CognitiveServicesAccounts_ListKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnamelistkeys-post
      parameters:
      - in: path
        name: accountName
        description: The name of Cognitive Services account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group within the users subscription
      responses:
        200:
          description: OK
      tags:
      - Cognitive Service
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---