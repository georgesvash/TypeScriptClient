[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo

# Interface: IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo

## Hierarchy

- [`IBaseResponseTaskInfo`](IBaseResponseTaskInfo.md)
  
  ↳ **`IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo`**

## Implemented by

- [`BusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo`](../classes/BusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [cost](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#cost)
- [data](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#data)
- [id](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#id)
- [path](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#path)
- [result](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#result)
- [result\_count](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#result_count)
- [status\_code](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#status_code)
- [status\_message](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#status_message)
- [time](IBusinessDataGoogleMyBusinessInfoTasksReadyTaskInfo.md#time)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[cost](IBaseResponseTaskInfo.md#cost)

#### Defined in

[main.ts:22697](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22697)

___


### data

• `Optional` **data**: `Object`

contains the same parameters that you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[data](IBaseResponseTaskInfo.md#data)

#### Defined in

[main.ts:22703](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22703)

___


### id

• `Optional` **id**: `string`

task identifier
unique task identifier in our system in the UUID format

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[id](IBaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22686](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22686)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[path](IBaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22701](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22701)

___


### result

• `Optional` **result**: [`BusinessDataGoogleMyBusinessInfoTasksReadyResultInfo`](../classes/BusinessDataGoogleMyBusinessInfoTasksReadyResultInfo.md)[]

array of results

#### Defined in

[main.ts:190950](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190950)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[result_count](IBaseResponseTaskInfo.md#result_count)

#### Defined in

[main.ts:22699](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22699)

___


### status\_code

• `Optional` **status\_code**: `number`

status code of the task
generated by DataForSEO, can be within the following range: 10000-60000
you can find the full list of the response codes here

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[status_code](IBaseResponseTaskInfo.md#status_code)

#### Defined in

[main.ts:22690](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22690)

___


### status\_message

• `Optional` **status\_message**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[status_message](IBaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22693](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22693)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[time](IBaseResponseTaskInfo.md#time)

#### Defined in

[main.ts:22695](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22695)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")