[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataYelpLanguagesTaskInfo

# Class: BusinessDataYelpLanguagesTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataYelpLanguagesTaskInfo`**

## Implements

- [`IBusinessDataYelpLanguagesTaskInfo`](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataYelpLanguagesTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataYelpLanguagesTaskInfo.md#cost)
- [data](BusinessDataYelpLanguagesTaskInfo.md#data)
- [id](BusinessDataYelpLanguagesTaskInfo.md#id)
- [path](BusinessDataYelpLanguagesTaskInfo.md#path)
- [result](BusinessDataYelpLanguagesTaskInfo.md#result)
- [result\_count](BusinessDataYelpLanguagesTaskInfo.md#result_count)
- [status\_code](BusinessDataYelpLanguagesTaskInfo.md#status_code)
- [status\_message](BusinessDataYelpLanguagesTaskInfo.md#status_message)
- [time](BusinessDataYelpLanguagesTaskInfo.md#time)

### Methods

- [init](BusinessDataYelpLanguagesTaskInfo.md#init)
- [toJSON](BusinessDataYelpLanguagesTaskInfo.md#tojson)
- [fromJS](BusinessDataYelpLanguagesTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataYelpLanguagesTaskInfo**(`data?`): [`BusinessDataYelpLanguagesTaskInfo`](BusinessDataYelpLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataYelpLanguagesTaskInfo`](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md) |

#### Returns

[`BusinessDataYelpLanguagesTaskInfo`](BusinessDataYelpLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:203230](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203230)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[cost](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#cost)

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

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[data](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#data)

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

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[id](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[path](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BusinessDataYelpLanguagesResultInfo`](BusinessDataYelpLanguagesResultInfo.md)[]

array of results

#### Implementation of

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[result](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#result)

#### Defined in

[main.ts:203226](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203226)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[result_count](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#result_count)

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

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[status_code](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#status_code)

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

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[status_message](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataYelpLanguagesTaskInfo](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md).[time](../interfaces/IBusinessDataYelpLanguagesTaskInfo.md#time)

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

[main.ts:203234](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203234)

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

[main.ts:203256](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203256)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataYelpLanguagesTaskInfo`](BusinessDataYelpLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataYelpLanguagesTaskInfo`](BusinessDataYelpLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:203249](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203249)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")