[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBingOrganicLiveHtmlTaskInfo

# Class: SerpBingOrganicLiveHtmlTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpBingOrganicLiveHtmlTaskInfo`**

## Implements

- [`ISerpBingOrganicLiveHtmlTaskInfo`](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBingOrganicLiveHtmlTaskInfo.md#constructor)

### Properties

- [cost](SerpBingOrganicLiveHtmlTaskInfo.md#cost)
- [data](SerpBingOrganicLiveHtmlTaskInfo.md#data)
- [id](SerpBingOrganicLiveHtmlTaskInfo.md#id)
- [path](SerpBingOrganicLiveHtmlTaskInfo.md#path)
- [result](SerpBingOrganicLiveHtmlTaskInfo.md#result)
- [result\_count](SerpBingOrganicLiveHtmlTaskInfo.md#result_count)
- [status\_code](SerpBingOrganicLiveHtmlTaskInfo.md#status_code)
- [status\_message](SerpBingOrganicLiveHtmlTaskInfo.md#status_message)
- [time](SerpBingOrganicLiveHtmlTaskInfo.md#time)

### Methods

- [init](SerpBingOrganicLiveHtmlTaskInfo.md#init)
- [toJSON](SerpBingOrganicLiveHtmlTaskInfo.md#tojson)
- [fromJS](SerpBingOrganicLiveHtmlTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBingOrganicLiveHtmlTaskInfo**(`data?`): [`SerpBingOrganicLiveHtmlTaskInfo`](SerpBingOrganicLiveHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBingOrganicLiveHtmlTaskInfo`](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md) |

#### Returns

[`SerpBingOrganicLiveHtmlTaskInfo`](SerpBingOrganicLiveHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:55582](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55582)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[cost](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#cost)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[cost](BaseResponseTaskInfo.md#cost)

#### Defined in

[main.ts:22602](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22602)

___


### data

• `Optional` **data**: `Object`

contains the same parameters that you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[data](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#data)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[data](BaseResponseTaskInfo.md#data)

#### Defined in

[main.ts:22608](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22608)

___


### id

• `Optional` **id**: `string`

task identifier
unique task identifier in our system in the UUID format

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[id](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[path](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpBingOrganicLiveHtmlResultInfo`](SerpBingOrganicLiveHtmlResultInfo.md)[]

array of results

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[result](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#result)

#### Defined in

[main.ts:55578](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55578)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[result_count](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#result_count)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[result_count](BaseResponseTaskInfo.md#result_count)

#### Defined in

[main.ts:22604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22604)

___


### status\_code

• `Optional` **status\_code**: `number`

status code of the task
generated by DataForSEO, can be within the following range: 10000-60000
you can find the full list of the response codes here

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[status_code](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#status_code)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_code](BaseResponseTaskInfo.md#status_code)

#### Defined in

[main.ts:22595](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22595)

___


### status\_message

• `Optional` **status\_message**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[status_message](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpBingOrganicLiveHtmlTaskInfo](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md).[time](../interfaces/ISerpBingOrganicLiveHtmlTaskInfo.md#time)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[time](BaseResponseTaskInfo.md#time)

#### Defined in

[main.ts:22600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22600)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[init](BaseResponseTaskInfo.md#init)

#### Defined in

[main.ts:55586](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55586)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[toJSON](BaseResponseTaskInfo.md#tojson)

#### Defined in

[main.ts:55608](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55608)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBingOrganicLiveHtmlTaskInfo`](SerpBingOrganicLiveHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBingOrganicLiveHtmlTaskInfo`](SerpBingOrganicLiveHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:55601](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55601)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")