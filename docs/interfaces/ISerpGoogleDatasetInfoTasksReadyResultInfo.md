[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpGoogleDatasetInfoTasksReadyResultInfo

# Interface: ISerpGoogleDatasetInfoTasksReadyResultInfo

## Implemented by

- [`SerpGoogleDatasetInfoTasksReadyResultInfo`](../classes/SerpGoogleDatasetInfoTasksReadyResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [date\_posted](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#date_posted)
- [endpoint\_advanced](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#endpoint_advanced)
- [endpoint\_html](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#endpoint_html)
- [endpoint\_regular](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#endpoint_regular)
- [id](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#id)
- [se](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#se)
- [se\_type](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#se_type)
- [tag](ISerpGoogleDatasetInfoTasksReadyResultInfo.md#tag)

## Properties

### date\_posted

• `Optional` **date\_posted**: `string`

date when the task was posted (in the UTC format)

#### Defined in

[main.ts:52166](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52166)

___


### endpoint\_advanced

• `Optional` **endpoint\_advanced**: `string`

URL for collecting the results of the SERP Advanced task
if SERP Advanced is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:52174](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52174)

___


### endpoint\_html

• `Optional` **endpoint\_html**: `string`

URL for collecting the results of the SERP HTML task
if SERP HTML is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:52177](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52177)

___


### endpoint\_regular

• `Optional` **endpoint\_regular**: `string`

URL for collecting the results of the SERP Regular task
if SERP Regular is not supported in the specified endpoint, the value will be null

#### Defined in

[main.ts:52171](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52171)

___


### id

• `Optional` **id**: `string`

task identifier of the completed task
unique task identifier in our system in the UUID format

#### Defined in

[main.ts:52159](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52159)

___


### se

• `Optional` **se**: `string`

search engine specified when setting the task

#### Defined in

[main.ts:52161](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52161)

___


### se\_type

• `Optional` **se\_type**: `string`

type of search engine
can take the following values: dataset_info

#### Defined in

[main.ts:52164](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52164)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier

#### Defined in

[main.ts:52168](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52168)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")