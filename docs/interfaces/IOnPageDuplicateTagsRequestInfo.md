[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IOnPageDuplicateTagsRequestInfo

# Interface: IOnPageDuplicateTagsRequestInfo

## Implemented by

- [`OnPageDuplicateTagsRequestInfo`](../classes/OnPageDuplicateTagsRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [accumulator](IOnPageDuplicateTagsRequestInfo.md#accumulator)
- [id](IOnPageDuplicateTagsRequestInfo.md#id)
- [limit](IOnPageDuplicateTagsRequestInfo.md#limit)
- [offset](IOnPageDuplicateTagsRequestInfo.md#offset)
- [tag](IOnPageDuplicateTagsRequestInfo.md#tag)
- [type](IOnPageDuplicateTagsRequestInfo.md#type)

## Properties

### accumulator

• `Optional` **accumulator**: `string`

tag value
optional field
specify a title or description here if you want to receive a list of duplicate pages that contains this tag

#### Defined in

[main.ts:147134](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147134)

___


### id

• `Optional` **id**: `string`

ID of the task
required field
you can get this ID in the response of the Task POST endpoint
example:
“07131248-1535-0216-1000-17384017ad04”

#### Defined in

[main.ts:147128](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147128)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned pages
optional field
default value: 100
maximum value: 1000

#### Defined in

[main.ts:147139](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147139)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned pages
optional field
default value: 0
if you specify the 10 value, the first ten pages in the results array will be omitted and the data will be provided for the successive pages

#### Defined in

[main.ts:147144](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147144)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:147150](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147150)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:147130](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147130)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")