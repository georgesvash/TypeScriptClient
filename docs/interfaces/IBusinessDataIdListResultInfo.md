[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBusinessDataIdListResultInfo

# Interface: IBusinessDataIdListResultInfo

## Implemented by

- [`BusinessDataIdListResultInfo`](../classes/BusinessDataIdListResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [cost](IBusinessDataIdListResultInfo.md#cost)
- [datetime\_done](IBusinessDataIdListResultInfo.md#datetime_done)
- [datetime\_posted](IBusinessDataIdListResultInfo.md#datetime_posted)
- [id](IBusinessDataIdListResultInfo.md#id)
- [metadata](IBusinessDataIdListResultInfo.md#metadata)
- [status](IBusinessDataIdListResultInfo.md#status)
- [url](IBusinessDataIdListResultInfo.md#url)

## Properties

### cost

• `Optional` **cost**: `number`

cost of the task, USD

#### Defined in

[main.ts:187373](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187373)

___


### datetime\_done

• `Optional` **datetime\_done**: `string`

date and time when the task was completed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Defined in

[main.ts:187368](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187368)

___


### datetime\_posted

• `Optional` **datetime\_posted**: `string`

date and time when the task was made
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Defined in

[main.ts:187363](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187363)

___


### id

• `Optional` **id**: `string`

id of the task

#### Defined in

[main.ts:187355](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187355)

___


### metadata

• `Optional` **metadata**: `Object`

contains parameters you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Defined in

[main.ts:187375](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187375)

___


### status

• `Optional` **status**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Defined in

[main.ts:187371](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187371)

___


### url

• `Optional` **url**: `string`

URL of the task
URL you used for making an API call

#### Defined in

[main.ts:187358](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187358)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")