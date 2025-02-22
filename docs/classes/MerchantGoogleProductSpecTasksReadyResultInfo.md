[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantGoogleProductSpecTasksReadyResultInfo

# Class: MerchantGoogleProductSpecTasksReadyResultInfo

## Implements

- [`IMerchantGoogleProductSpecTasksReadyResultInfo`](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantGoogleProductSpecTasksReadyResultInfo.md#constructor)

### Properties

- [date\_posted](MerchantGoogleProductSpecTasksReadyResultInfo.md#date_posted)
- [endpoint\_advanced](MerchantGoogleProductSpecTasksReadyResultInfo.md#endpoint_advanced)
- [endpoint\_html](MerchantGoogleProductSpecTasksReadyResultInfo.md#endpoint_html)
- [id](MerchantGoogleProductSpecTasksReadyResultInfo.md#id)
- [se](MerchantGoogleProductSpecTasksReadyResultInfo.md#se)
- [se\_type](MerchantGoogleProductSpecTasksReadyResultInfo.md#se_type)
- [tag](MerchantGoogleProductSpecTasksReadyResultInfo.md#tag)

### Methods

- [init](MerchantGoogleProductSpecTasksReadyResultInfo.md#init)
- [toJSON](MerchantGoogleProductSpecTasksReadyResultInfo.md#tojson)
- [fromJS](MerchantGoogleProductSpecTasksReadyResultInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantGoogleProductSpecTasksReadyResultInfo**(`data?`): [`MerchantGoogleProductSpecTasksReadyResultInfo`](MerchantGoogleProductSpecTasksReadyResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantGoogleProductSpecTasksReadyResultInfo`](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md) |

#### Returns

[`MerchantGoogleProductSpecTasksReadyResultInfo`](MerchantGoogleProductSpecTasksReadyResultInfo.md)

#### Defined in

[main.ts:167653](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167653)

## Properties

### date\_posted

• `Optional` **date\_posted**: `string`

date when the task was posted (in the UTC format)

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[date_posted](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#date_posted)

#### Defined in

[main.ts:167643](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167643)

___


### endpoint\_advanced

• `Optional` **endpoint\_advanced**: `string`

URL for collecting the results of the Google Shopping Product Specifications Advanced task

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[endpoint_advanced](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#endpoint_advanced)

#### Defined in

[main.ts:167647](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167647)

___


### endpoint\_html

• `Optional` **endpoint\_html**: `string`

URL for collecting the results of the Google Shopping Product Specifications HTML task

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[endpoint_html](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#endpoint_html)

#### Defined in

[main.ts:167649](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167649)

___


### id

• `Optional` **id**: `string`

task identifier of the completed task
unique task identifier in our system in the UUID format

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[id](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#id)

#### Defined in

[main.ts:167636](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167636)

___


### se

• `Optional` **se**: `string`

search engine specified when setting the task

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[se](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#se)

#### Defined in

[main.ts:167638](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167638)

___


### se\_type

• `Optional` **se\_type**: `string`

type of search engine
can take the following values: shopping_specifications

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[se_type](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#se_type)

#### Defined in

[main.ts:167641](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167641)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier

#### Implementation of

[IMerchantGoogleProductSpecTasksReadyResultInfo](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md).[tag](../interfaces/IMerchantGoogleProductSpecTasksReadyResultInfo.md#tag)

#### Defined in

[main.ts:167645](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167645)

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

[main.ts:167662](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167662)

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

[main.ts:167685](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167685)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantGoogleProductSpecTasksReadyResultInfo`](MerchantGoogleProductSpecTasksReadyResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantGoogleProductSpecTasksReadyResultInfo`](MerchantGoogleProductSpecTasksReadyResultInfo.md)

#### Defined in

[main.ts:167678](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L167678)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")