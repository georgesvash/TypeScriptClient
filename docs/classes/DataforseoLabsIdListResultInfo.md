[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsIdListResultInfo

# Class: DataforseoLabsIdListResultInfo

## Implements

- [`IDataforseoLabsIdListResultInfo`](../interfaces/IDataforseoLabsIdListResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsIdListResultInfo.md#constructor)

### Properties

- [cost](DataforseoLabsIdListResultInfo.md#cost)
- [datetime\_done](DataforseoLabsIdListResultInfo.md#datetime_done)
- [datetime\_posted](DataforseoLabsIdListResultInfo.md#datetime_posted)
- [id](DataforseoLabsIdListResultInfo.md#id)
- [metadata](DataforseoLabsIdListResultInfo.md#metadata)
- [status](DataforseoLabsIdListResultInfo.md#status)
- [url](DataforseoLabsIdListResultInfo.md#url)

### Methods

- [init](DataforseoLabsIdListResultInfo.md#init)
- [toJSON](DataforseoLabsIdListResultInfo.md#tojson)
- [fromJS](DataforseoLabsIdListResultInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsIdListResultInfo**(`data?`): [`DataforseoLabsIdListResultInfo`](DataforseoLabsIdListResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsIdListResultInfo`](../interfaces/IDataforseoLabsIdListResultInfo.md) |

#### Returns

[`DataforseoLabsIdListResultInfo`](DataforseoLabsIdListResultInfo.md)

#### Defined in

[main.ts:76572](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76572)

## Properties

### cost

• `Optional` **cost**: `number`

cost of the task, USD

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[cost](../interfaces/IDataforseoLabsIdListResultInfo.md#cost)

#### Defined in

[main.ts:76566](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76566)

___


### datetime\_done

• `Optional` **datetime\_done**: `string`

date and time when the task was completed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[datetime_done](../interfaces/IDataforseoLabsIdListResultInfo.md#datetime_done)

#### Defined in

[main.ts:76561](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76561)

___


### datetime\_posted

• `Optional` **datetime\_posted**: `string`

date and time when the task was made
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[datetime_posted](../interfaces/IDataforseoLabsIdListResultInfo.md#datetime_posted)

#### Defined in

[main.ts:76556](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76556)

___


### id

• `Optional` **id**: `string`

id of the task

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[id](../interfaces/IDataforseoLabsIdListResultInfo.md#id)

#### Defined in

[main.ts:76548](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76548)

___


### metadata

• `Optional` **metadata**: `Object`

contains parameters you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[metadata](../interfaces/IDataforseoLabsIdListResultInfo.md#metadata)

#### Defined in

[main.ts:76568](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76568)

___


### status

• `Optional` **status**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[status](../interfaces/IDataforseoLabsIdListResultInfo.md#status)

#### Defined in

[main.ts:76564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76564)

___


### url

• `Optional` **url**: `string`

URL of the task
URL you used for making an API call

#### Implementation of

[IDataforseoLabsIdListResultInfo](../interfaces/IDataforseoLabsIdListResultInfo.md).[url](../interfaces/IDataforseoLabsIdListResultInfo.md#url)

#### Defined in

[main.ts:76551](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76551)

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

[main.ts:76581](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76581)

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

[main.ts:76610](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76610)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsIdListResultInfo`](DataforseoLabsIdListResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsIdListResultInfo`](DataforseoLabsIdListResultInfo.md)

#### Defined in

[main.ts:76603](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76603)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")