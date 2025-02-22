[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataIdListResultInfo

# Class: AppDataIdListResultInfo

## Implements

- [`IAppDataIdListResultInfo`](../interfaces/IAppDataIdListResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataIdListResultInfo.md#constructor)

### Properties

- [cost](AppDataIdListResultInfo.md#cost)
- [datetime\_done](AppDataIdListResultInfo.md#datetime_done)
- [datetime\_posted](AppDataIdListResultInfo.md#datetime_posted)
- [id](AppDataIdListResultInfo.md#id)
- [metadata](AppDataIdListResultInfo.md#metadata)
- [status](AppDataIdListResultInfo.md#status)
- [url](AppDataIdListResultInfo.md#url)

### Methods

- [init](AppDataIdListResultInfo.md#init)
- [toJSON](AppDataIdListResultInfo.md#tojson)
- [fromJS](AppDataIdListResultInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataIdListResultInfo**(`data?`): [`AppDataIdListResultInfo`](AppDataIdListResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataIdListResultInfo`](../interfaces/IAppDataIdListResultInfo.md) |

#### Returns

[`AppDataIdListResultInfo`](AppDataIdListResultInfo.md)

#### Defined in

[main.ts:176426](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176426)

## Properties

### cost

• `Optional` **cost**: `number`

cost of the task, USD

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[cost](../interfaces/IAppDataIdListResultInfo.md#cost)

#### Defined in

[main.ts:176420](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176420)

___


### datetime\_done

• `Optional` **datetime\_done**: `string`

date and time when the task was completed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[datetime_done](../interfaces/IAppDataIdListResultInfo.md#datetime_done)

#### Defined in

[main.ts:176415](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176415)

___


### datetime\_posted

• `Optional` **datetime\_posted**: `string`

date and time when the task was made
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[datetime_posted](../interfaces/IAppDataIdListResultInfo.md#datetime_posted)

#### Defined in

[main.ts:176410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176410)

___


### id

• `Optional` **id**: `string`

id of the task

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[id](../interfaces/IAppDataIdListResultInfo.md#id)

#### Defined in

[main.ts:176402](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176402)

___


### metadata

• `Optional` **metadata**: `Object`

contains parameters you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[metadata](../interfaces/IAppDataIdListResultInfo.md#metadata)

#### Defined in

[main.ts:176422](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176422)

___


### status

• `Optional` **status**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[status](../interfaces/IAppDataIdListResultInfo.md#status)

#### Defined in

[main.ts:176418](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176418)

___


### url

• `Optional` **url**: `string`

URL of the task
URL you used for making an API call

#### Implementation of

[IAppDataIdListResultInfo](../interfaces/IAppDataIdListResultInfo.md).[url](../interfaces/IAppDataIdListResultInfo.md#url)

#### Defined in

[main.ts:176405](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176405)

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

[main.ts:176435](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176435)

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

[main.ts:176464](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176464)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataIdListResultInfo`](AppDataIdListResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataIdListResultInfo`](AppDataIdListResultInfo.md)

#### Defined in

[main.ts:176457](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176457)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")