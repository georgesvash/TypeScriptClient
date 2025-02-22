[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppSearchesTaskGetAdvancedResultInfo

# Class: AppDataGoogleAppSearchesTaskGetAdvancedResultInfo

## Implements

- [`IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#constructor)

### Properties

- [check\_url](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#check_url)
- [datetime](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#datetime)
- [items](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#items)
- [items\_count](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#items_count)
- [keyword](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#keyword)
- [language\_code](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#language_code)
- [location\_code](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#location_code)
- [se\_domain](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#se_domain)
- [se\_results\_count](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#se_results_count)

### Methods

- [init](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#init)
- [toJSON](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#tojson)
- [fromJS](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppSearchesTaskGetAdvancedResultInfo**(`data?`): [`AppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md) |

#### Returns

[`AppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md)

#### Defined in

[main.ts:177820](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177820)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[check_url](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#check_url)

#### Defined in

[main.ts:177805](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177805)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[datetime](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#datetime)

#### Defined in

[main.ts:177810](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177810)

___


### items

• `Optional` **items**: [`BaseAppDataSerpElementItem`](BaseAppDataSerpElementItem.md)[]

found apps

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[items](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#items)

#### Defined in

[main.ts:177816](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177816)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of items in the results array

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[items_count](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#items_count)

#### Defined in

[main.ts:177814](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177814)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST request

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[keyword](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#keyword)

#### Defined in

[main.ts:177796](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177796)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[language_code](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#language_code)

#### Defined in

[main.ts:177802](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177802)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[location_code](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#location_code)

#### Defined in

[main.ts:177800](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177800)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[se_domain](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#se_domain)

#### Defined in

[main.ts:177798](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177798)

___


### se\_results\_count

• `Optional` **se\_results\_count**: `number`

the total number of results

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md).[se_results_count](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md#se_results_count)

#### Defined in

[main.ts:177812](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177812)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Defined in

[main.ts:177829](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177829)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Defined in

[main.ts:177858](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177858)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppSearchesTaskGetAdvancedResultInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResultInfo.md)

#### Defined in

[main.ts:177851](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177851)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")