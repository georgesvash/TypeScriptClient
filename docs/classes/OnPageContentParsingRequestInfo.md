[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageContentParsingRequestInfo

# Class: OnPageContentParsingRequestInfo

## Implements

- [`IOnPageContentParsingRequestInfo`](../interfaces/IOnPageContentParsingRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageContentParsingRequestInfo.md#constructor)

### Properties

- [id](OnPageContentParsingRequestInfo.md#id)
- [url](OnPageContentParsingRequestInfo.md#url)

### Methods

- [init](OnPageContentParsingRequestInfo.md#init)
- [toJSON](OnPageContentParsingRequestInfo.md#tojson)
- [fromJS](OnPageContentParsingRequestInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageContentParsingRequestInfo**(`data?`): [`OnPageContentParsingRequestInfo`](OnPageContentParsingRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageContentParsingRequestInfo`](../interfaces/IOnPageContentParsingRequestInfo.md) |

#### Returns

[`OnPageContentParsingRequestInfo`](OnPageContentParsingRequestInfo.md)

#### Defined in

[main.ts:151896](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151896)

## Properties

### id

• `Optional` **id**: `string`

ID of the task
required field
you can get this ID in the response of the Task POST endpoint
note: the enable_content_parsing parameter in the POST request must be set to true
example:
"07131248-1535-0216-1000-17384017ad04"

#### Implementation of

[IOnPageContentParsingRequestInfo](../interfaces/IOnPageContentParsingRequestInfo.md).[id](../interfaces/IOnPageContentParsingRequestInfo.md#id)

#### Defined in

[main.ts:151892](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151892)

___


### url

• `Optional` **url**: `string`

URL of the content to parse
required field
URL of the page to parse
example:
https://www.fujielectric.com/

#### Implementation of

[IOnPageContentParsingRequestInfo](../interfaces/IOnPageContentParsingRequestInfo.md).[url](../interfaces/IOnPageContentParsingRequestInfo.md#url)

#### Defined in

[main.ts:151885](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151885)

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

[main.ts:151905](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151905)

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

[main.ts:151923](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151923)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageContentParsingRequestInfo`](OnPageContentParsingRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageContentParsingRequestInfo`](OnPageContentParsingRequestInfo.md)

#### Defined in

[main.ts:151916](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151916)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")