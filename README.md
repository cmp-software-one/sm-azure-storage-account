# About this Automation

Create a Storage Account in your Subcription

Refer to our table below for **Best Practices**

Refer to the section below for Azure's **Naming convention best practices**

## Fields and Best Practices

| Field         | Best practice and Options      | Limitations |
| ------------- | --------------------------------- |-|
| **Request title**       | A friendly short name to remind you why you created this account         | 256 characters|
| **Request description**        | Add more details on the need for the account          |256 characters |
| **Azure subscription ID** | Select your target Subscription ID | NA |
| **account_replciation_type** | **ZRS**, LRS, GRZ, GZRS  | Slect only one of those show |
| **account_tier** | **Standard**, Premium  | Choose one |
| **resource_group_location** | Refer to the **Azure Regions table below** | Copy from the Name column|
| **resource_group_name** | **example** rg-app or service name-subscription purpose-number | 1-90 chars, alphanumerics, underscores, parentheses, hyphens |
| **storage_account_name** | **example** stProjectAppOrService123 | 3-24 chars, lowercase and numbers only |
| **account_kind** | **storage** | Enter storage here |

Between 1 and 90 characters long.
Alphanumerics, underscores, parentheses, hyphens, periods.
Can't end with period.
Resource Group names must be unique within a subscription.

### Naming convention best practices

https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming

### Azure Regions

Select your Regions from the **Name** column

|	DisplayName	|	Name	|	RegionalDisplayName	|
|	--------------------	|	--------------------	|	--------------------	|
|	East US	|	eastus	|	(US) East US	|
|	East US 2	|	eastus2	|	(US) East US 2	|
|	South Central US	|	southcentralus	|	(US) South Central US	|
|	West US 2	|	westus2	|	(US) West US 2	|
|	West US 3	|	westus3	|	(US) West US 3	|
|	Australia East	|	australiaeast	|	(Asia Pacific) Australia East	|
|	Southeast Asia	|	southeastasia	|	(Asia Pacific) Southeast Asia	|
|	North Europe	|	northeurope	|	(Europe) North Europe	|
|	Sweden Central	|	swedencentral	|	(Europe) Sweden Central	|
|	UK South	|	uksouth	|	(Europe) UK South	|
|	West Europe	|	westeurope	|	(Europe) West Europe	|
|	Central US	|	centralus	|	(US) Central US	|
|	South Africa North	|	southafricanorth	|	(Africa) South Africa North	|
|	Central India	|	centralindia	|	(Asia Pacific) Central India	|
|	East Asia	|	eastasia	|	(Asia Pacific) East Asia	|
|	Japan East	|	japaneast	|	(Asia Pacific) Japan East	|
|	Korea Central	|	koreacentral	|	(Asia Pacific) Korea Central	|
|	Canada Central	|	canadacentral	|	(Canada) Canada Central	|
|	France Central	|	francecentral	|	(Europe) France Central	|
|	Germany West Central	|	germanywestcentral	|	(Europe) Germany West Central	|
|	Italy North	|	italynorth	|	(Europe) Italy North	|
|	Norway East	|	norwayeast	|	(Europe) Norway East	|
|	Poland Central	|	polandcentral	|	(Europe) Poland Central	|
|	Switzerland North	|	switzerlandnorth	|	(Europe) Switzerland North	|
|	UAE North	|	uaenorth	|	(Middle East) UAE North	|
|	Brazil South	|	brazilsouth	|	(South America) Brazil South	|
|	Central US EUAP	|	centraluseuap	|	(US) Central US EUAP	|
|	Israel Central	|	israelcentral	|	(Middle East) Israel Central	|
|	Qatar Central	|	qatarcentral	|	(Middle East) Qatar Central	|
|	Central US (Stage)	|	centralusstage	|	(US) Central US (Stage)	|
|	East US (Stage)	|	eastusstage	|	(US) East US (Stage)	|
|	East US 2 (Stage)	|	eastus2stage	|	(US) East US 2 (Stage)	|
|	North Central US (Stage)	|	northcentralusstage	|	(US) North Central US (Stage)	|
|	South Central US (Stage)	|	southcentralusstage	|	(US) South Central US (Stage)	|
|	West US (Stage)	|	westusstage	|	(US) West US (Stage)	|
|	West US 2 (Stage)	|	westus2stage	|	(US) West US 2 (Stage)	|
|	Asia	|	asia	|	Asia	|
|	Asia Pacific	|	asiapacific	|	Asia Pacific	|
|	Australia	|	australia	|	Australia	|
|	Brazil	|	brazil	|	Brazil	|
|	Canada	|	canada	|	Canada	|
|	Europe	|	europe	|	Europe	|
|	France	|	france	|	France	|
|	Germany	|	germany	|	Germany	|
|	Global	|	global	|	Global	|
|	India	|	india	|	India	|
|	Japan	|	japan	|	Japan	|
|	Korea	|	korea	|	Korea	|
|	Norway	|	norway	|	Norway	|
|	Singapore	|	singapore	|	Singapore	|
|	South Africa	|	southafrica	|	South Africa	|
|	Sweden	|	sweden	|	Sweden	|
|	Switzerland	|	switzerland	|	Switzerland	|
|	United Arab Emirates	|	uae	|	United Arab Emirates	|
|	United Kingdom	|	uk	|	United Kingdom	|
|	United States	|	unitedstates	|	United States	|
|	United States EUAP	|	unitedstateseuap	|	United States EUAP	|
|	East Asia (Stage)	|	eastasiastage	|	(Asia Pacific) East Asia (Stage)	|
|	Southeast Asia (Stage)	|	southeastasiastage	|	(Asia Pacific) Southeast Asia (Stage)	|
|	Brazil US	|	brazilus	|	(South America) Brazil US	|
|	East US STG	|	eastusstg	|	(US) East US STG	|
|	North Central US	|	northcentralus	|	(US) North Central US	|
|	West US	|	westus	|	(US) West US	|
|	Japan West	|	japanwest	|	(Asia Pacific) Japan West	|
|	Jio India West	|	jioindiawest	|	(Asia Pacific) Jio India West	|
|	East US 2 EUAP	|	eastus2euap	|	(US) East US 2 EUAP	|
|	West Central US	|	westcentralus	|	(US) West Central US	|
|	South Africa West	|	southafricawest	|	(Africa) South Africa West	|
|	Australia Central	|	australiacentral	|	(Asia Pacific) Australia Central	|
|	Australia Central 2	|	australiacentral2	|	(Asia Pacific) Australia Central 2	|
|	Australia Southeast	|	australiasoutheast	|	(Asia Pacific) Australia Southeast	|
|	Jio India Central	|	jioindiacentral	|	(Asia Pacific) Jio India Central	|
|	Korea South	|	koreasouth	|	(Asia Pacific) Korea South	|
|	South India	|	southindia	|	(Asia Pacific) South India	|
|	West India	|	westindia	|	(Asia Pacific) West India	|
|	Canada East	|	canadaeast	|	(Canada) Canada East	|
|	France South	|	francesouth	|	(Europe) France South	|
|	Germany North	|	germanynorth	|	(Europe) Germany North	|
|	Norway West	|	norwaywest	|	(Europe) Norway West	|
|	Switzerland West	|	switzerlandwest	|	(Europe) Switzerland West	|
|	UK West	|	ukwest	|	(Europe) UK West	|
|	UAE Central	|	uaecentral	|	(Middle East) UAE Central	|
|	Brazil Southeast	|	brazilsoutheast	|	(South America) Brazil Southeast	|

