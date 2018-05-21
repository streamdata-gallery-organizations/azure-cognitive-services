---
name: Azure Cognitive Services
x-slug: azure-cognitive-services
description: Enable natural and contextual interaction with tools that augment users
  experiences using the power of machine-based intelligence. Tap into an ever-growing
  collection of powerful artificial intelligence algorithms for vision, speech, language,
  and knowledge.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Cognitive Services
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Cognitive Services Cognitive Services Accounts Create
  x-api-slug: azure-cognitive-services
  description: Create Cognitive Services Account. Accounts is a resource group wide
    resource type. It holds the keys for developer to access intelligent APIs. It's
    also the resource type for billing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}
  tags: Cognitive Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-put-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts Update
  x-api-slug: azure-cognitive-services
  description: Updates a Cognitive Services account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}
  tags: Cognitive Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-patch-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts Delete
  x-api-slug: azure-cognitive-services
  description: Deletes a Cognitive Services account from the resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}
  tags: Cognitive Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-delete-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts Get Properties
  x-api-slug: azure-cognitive-services
  description: Returns a Cognitive Services account specified by the parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}
  tags: Cognitive Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountname-get-openapi.md
- name: Azure Cognitive Services Accounts List By Resource Group
  x-api-slug: azure-cognitive-services
  description: Returns all the resources of a particular type belonging to a resource
    group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccounts-get-openapi.md
- name: Azure Cognitive Services Accounts List
  x-api-slug: azure-cognitive-services
  description: Returns all the resources of a particular type belonging to a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.CognitiveServices/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidprovidersmicrosoftcognitiveservicesaccounts-get-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts List Keys
  x-api-slug: azure-cognitive-services
  description: Lists the account keys for the specified Cognitive Services account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}/listKeys
  tags: Cognitive Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnamelistkeys-post-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts Regenerate Key
  x-api-slug: azure-cognitive-services
  description: Regenerates the specified account key for the specified Cognitive Services
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}/regenerateKey
  tags: Cognitive Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnameregeneratekey-post-openapi.md
- name: Azure Cognitive Services Cognitive Services Accounts List Skus
  x-api-slug: azure-cognitive-services
  description: List available SKUs for the requested Cognitive Services account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts/{accountName}/skus
  tags: Cognitive Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnameskus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcognitiveservicesaccountsaccountnameskus-get-openapi.md
- name: Azure Cognitive Services Operations List
  x-api-slug: azure-cognitive-services
  description: Lists all the available Cognitive Services account operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////providers/Microsoft.CognitiveServices/operations
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/providersmicrosoftcognitiveservicesoperations-get-openapi.md
- name: Azure Cognitive Services Check Sku Availability List
  x-api-slug: azure-cognitive-services
  description: Check available SKUs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.CognitiveServices/locations/{location}/checkSkuAvailability
  tags: SKU
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/subscriptionssubscriptionidprovidersmicrosoftcognitiveserviceslocationslocationcheckskuavailability-post-openapi.md
- name: Azure Cognitive Services
  x-api-slug: azure-cognitive-services
  description: Enable natural and contextual interaction with tools that augment users
    experiences using the power of machine-based intelligence. Tap into an ever-growing
    collection of powerful artificial intelligence algorithms for vision, speech,
    language, and knowledge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com//
  tags: Azure Cognitive Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cognitive-services/master/_listings/azure-cognitive-services/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cognitive-services/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cognitive-services/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/cognitive-services/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cognitive-services/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---