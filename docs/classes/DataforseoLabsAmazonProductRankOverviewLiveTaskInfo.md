[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsAmazonProductRankOverviewLiveTaskInfo

# Class: DataforseoLabsAmazonProductRankOverviewLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DataforseoLabsAmazonProductRankOverviewLiveTaskInfo`**

## Implements

- [`IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#constructor)

### Properties

- [cost](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#cost)
- [data](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#data)
- [id](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#id)
- [path](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#path)
- [result](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#result)
- [result\_count](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#result_count)
- [status\_code](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#status_code)
- [status\_message](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#status_message)
- [time](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#time)

### Methods

- [init](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#init)
- [toJSON](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#tojson)
- [fromJS](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsAmazonProductRankOverviewLiveTaskInfo**(`data?`): [`DataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md) |

#### Returns

[`DataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:100868](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100868)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[cost](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#cost)

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

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[data](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#data)

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

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[id](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[path](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)[]

array of results

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[result](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#result)

#### Defined in

[main.ts:100864](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100864)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[result_count](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#result_count)

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

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[status_code](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#status_code)

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

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[status_message](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md).[time](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md#time)

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

[main.ts:100872](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100872)

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

[main.ts:100894](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100894)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsAmazonProductRankOverviewLiveTaskInfo`](DataforseoLabsAmazonProductRankOverviewLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:100887](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100887)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")