[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageLighthouseTaskPostTaskInfo

# Class: OnPageLighthouseTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageLighthouseTaskPostTaskInfo`**

## Implements

- [`IOnPageLighthouseTaskPostTaskInfo`](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageLighthouseTaskPostTaskInfo.md#constructor)

### Properties

- [cost](OnPageLighthouseTaskPostTaskInfo.md#cost)
- [data](OnPageLighthouseTaskPostTaskInfo.md#data)
- [id](OnPageLighthouseTaskPostTaskInfo.md#id)
- [path](OnPageLighthouseTaskPostTaskInfo.md#path)
- [result](OnPageLighthouseTaskPostTaskInfo.md#result)
- [result\_count](OnPageLighthouseTaskPostTaskInfo.md#result_count)
- [status\_code](OnPageLighthouseTaskPostTaskInfo.md#status_code)
- [status\_message](OnPageLighthouseTaskPostTaskInfo.md#status_message)
- [time](OnPageLighthouseTaskPostTaskInfo.md#time)

### Methods

- [init](OnPageLighthouseTaskPostTaskInfo.md#init)
- [toJSON](OnPageLighthouseTaskPostTaskInfo.md#tojson)
- [fromJS](OnPageLighthouseTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageLighthouseTaskPostTaskInfo**(`data?`): [`OnPageLighthouseTaskPostTaskInfo`](OnPageLighthouseTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageLighthouseTaskPostTaskInfo`](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md) |

#### Returns

[`OnPageLighthouseTaskPostTaskInfo`](OnPageLighthouseTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:154310](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154310)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[cost](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#cost)

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

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[data](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#data)

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

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[id](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[path](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: \{ `[key: string]`: `any`;  }[]

array of results
in this case, the value will be null

#### Implementation of

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[result](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:154306](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154306)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[result_count](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#result_count)

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

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[status_code](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#status_code)

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

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[status_message](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageLighthouseTaskPostTaskInfo](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md).[time](../interfaces/IOnPageLighthouseTaskPostTaskInfo.md#time)

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

[main.ts:154314](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154314)

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

[main.ts:154336](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154336)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageLighthouseTaskPostTaskInfo`](OnPageLighthouseTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageLighthouseTaskPostTaskInfo`](OnPageLighthouseTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:154329](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154329)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")