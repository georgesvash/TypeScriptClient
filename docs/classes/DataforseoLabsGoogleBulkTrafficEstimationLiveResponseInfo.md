[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo

# Class: DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`**

## Implements

- [`IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#constructor)

### Properties

- [cost](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#cost)
- [status\_code](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#status_code)
- [status\_message](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#status_message)
- [tasks](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks)
- [tasks\_count](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks_count)
- [tasks\_error](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks_error)
- [time](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#time)
- [version](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#version)

### Methods

- [init](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#init)
- [toJSON](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo**(`data?`): [`DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md) |

#### Returns

[`DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:97917](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L97917)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[cost](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#cost)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[cost](BaseResponseInfo.md#cost)

#### Defined in

[main.ts:22510](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22510)

___


### status\_code

• `Optional` **status\_code**: `number`

general status code
you can find the full list of the response codes here

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[status_code](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#status_code)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_code](BaseResponseInfo.md#status_code)

#### Defined in

[main.ts:22503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22503)

___


### status\_message

• `Optional` **status\_message**: `string`

general informational message
you can find the full list of general informational messages here

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[status_message](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DataforseoLabsGoogleBulkTrafficEstimationLiveTaskInfo`](DataforseoLabsGoogleBulkTrafficEstimationLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[tasks](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:97913](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L97913)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[tasks_count](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[tasks_error](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[time](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md).[version](../interfaces/IDataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md#version)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[version](BaseResponseInfo.md#version)

#### Defined in

[main.ts:22500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22500)

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

[BaseResponseInfo](BaseResponseInfo.md).[init](BaseResponseInfo.md#init)

#### Defined in

[main.ts:97921](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L97921)

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

[BaseResponseInfo](BaseResponseInfo.md).[toJSON](BaseResponseInfo.md#tojson)

#### Defined in

[main.ts:97943](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L97943)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo`](DataforseoLabsGoogleBulkTrafficEstimationLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:97936](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L97936)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")