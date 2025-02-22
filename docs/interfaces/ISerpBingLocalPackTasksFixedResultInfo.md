[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpBingLocalPackTasksFixedResultInfo

# Interface: ISerpBingLocalPackTasksFixedResultInfo

## Implemented by

- [`SerpBingLocalPackTasksFixedResultInfo`](../classes/SerpBingLocalPackTasksFixedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [date\_fixed](ISerpBingLocalPackTasksFixedResultInfo.md#date_fixed)
- [endpoint\_advanced](ISerpBingLocalPackTasksFixedResultInfo.md#endpoint_advanced)
- [endpoint\_html](ISerpBingLocalPackTasksFixedResultInfo.md#endpoint_html)
- [endpoint\_regular](ISerpBingLocalPackTasksFixedResultInfo.md#endpoint_regular)
- [id](ISerpBingLocalPackTasksFixedResultInfo.md#id)
- [se](ISerpBingLocalPackTasksFixedResultInfo.md#se)
- [se\_type](ISerpBingLocalPackTasksFixedResultInfo.md#se_type)
- [tag](ISerpBingLocalPackTasksFixedResultInfo.md#tag)

## Properties

### date\_fixed

• `Optional` **date\_fixed**: `string`

date when the task was fixed (in the UTC format)

#### Defined in

[main.ts:56088](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56088)

___


### endpoint\_advanced

• `Optional` **endpoint\_advanced**: `string`

URL for collecting the results of the SERP Advanced task
if SERP Advanced is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:56096](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56096)

___


### endpoint\_html

• `Optional` **endpoint\_html**: `string`

URL for collecting the results of the SERP HTML task
if SERP HTML is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:56099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56099)

___


### endpoint\_regular

• `Optional` **endpoint\_regular**: `string`

URL for collecting the results of the SERP Regular task
if SERP Regular is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:56093](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56093)

___


### id

• `Optional` **id**: `string`

task identifier of the completed task
unique task identifier in our system in the UUID format

#### Defined in

[main.ts:56081](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56081)

___


### se

• `Optional` **se**: `string`

search engine specified when setting the task

#### Defined in

[main.ts:56083](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56083)

___


### se\_type

• `Optional` **se\_type**: `string`

type of search engine
can take the following values: local_pack

#### Defined in

[main.ts:56086](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56086)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier

#### Defined in

[main.ts:56090](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56090)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")