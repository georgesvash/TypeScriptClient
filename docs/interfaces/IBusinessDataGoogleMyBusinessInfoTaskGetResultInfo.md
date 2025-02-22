[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo

# Interface: IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo

## Implemented by

- [`BusinessDataGoogleMyBusinessInfoTaskGetResultInfo`](../classes/BusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [check\_url](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#check_url)
- [datetime](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#datetime)
- [item\_types](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#item_types)
- [items](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#items)
- [items\_count](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#items_count)
- [keyword](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#keyword)
- [language\_code](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#language_code)
- [location\_code](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#location_code)
- [se\_domain](IBusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md#se_domain)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Defined in

[main.ts:191869](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191869)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:191874](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191874)

___


### item\_types

• `Optional` **item\_types**: `string`[]

item types
types of search engine results encountered in the items array;
possible item types: google_business_info

#### Defined in

[main.ts:191878](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191878)

___


### items

• `Optional` **items**: [`BaseBusinessDataSerpElementItem`](../classes/BaseBusinessDataSerpElementItem.md)[]

array of directory items

#### Defined in

[main.ts:191883](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191883)

___


### items\_count

• `Optional` **items\_count**: `number`

item types
the number of items in the items array

#### Defined in

[main.ts:191881](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191881)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST array
keyword is returned with decoded %## (plus symbol ‘+’ will be decoded to a space character)
this field will contain the cid parameter if you specified it in the keyword field when setting a task;
example:
cid:2946633002421908862
learn more about the parameter in this help center article

#### Defined in

[main.ts:191860](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191860)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:191866](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191866)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:191864](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191864)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain as specified in a POST array

#### Defined in

[main.ts:191862](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191862)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")