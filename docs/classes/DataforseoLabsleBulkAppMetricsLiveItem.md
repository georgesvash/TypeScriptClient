[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsleBulkAppMetricsLiveItem

# Class: DataforseoLabsleBulkAppMetricsLiveItem

## Implements

- [`IDataforseoLabsleBulkAppMetricsLiveItem`](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsleBulkAppMetricsLiveItem.md#constructor)

### Properties

- [app\_id](DataforseoLabsleBulkAppMetricsLiveItem.md#app_id)
- [metrics](DataforseoLabsleBulkAppMetricsLiveItem.md#metrics)
- [se\_type](DataforseoLabsleBulkAppMetricsLiveItem.md#se_type)

### Methods

- [init](DataforseoLabsleBulkAppMetricsLiveItem.md#init)
- [toJSON](DataforseoLabsleBulkAppMetricsLiveItem.md#tojson)
- [fromJS](DataforseoLabsleBulkAppMetricsLiveItem.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsleBulkAppMetricsLiveItem**(`data?`): [`DataforseoLabsleBulkAppMetricsLiveItem`](DataforseoLabsleBulkAppMetricsLiveItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsleBulkAppMetricsLiveItem`](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md) |

#### Returns

[`DataforseoLabsleBulkAppMetricsLiveItem`](DataforseoLabsleBulkAppMetricsLiveItem.md)

#### Defined in

[main.ts:107961](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107961)

## Properties

### app\_id

• `Optional` **app\_id**: `string`

id of the app in a POST array

#### Implementation of

[IDataforseoLabsleBulkAppMetricsLiveItem](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md).[app_id](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md#app_id)

#### Defined in

[main.ts:107954](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107954)

___


### metrics

• `Optional` **metrics**: `Object`

metrics for the ranking keywords of the app
ranking data relevant to the keywords that the provided application ranks for on Google Play

#### Index signature

▪ [key: `string`]: [`AppMetricsInfo`](AppMetricsInfo.md)

#### Implementation of

[IDataforseoLabsleBulkAppMetricsLiveItem](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md).[metrics](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md#metrics)

#### Defined in

[main.ts:107957](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107957)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Implementation of

[IDataforseoLabsleBulkAppMetricsLiveItem](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md).[se_type](../interfaces/IDataforseoLabsleBulkAppMetricsLiveItem.md#se_type)

#### Defined in

[main.ts:107952](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107952)

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

[main.ts:107970](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107970)

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

[main.ts:107995](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107995)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsleBulkAppMetricsLiveItem`](DataforseoLabsleBulkAppMetricsLiveItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsleBulkAppMetricsLiveItem`](DataforseoLabsleBulkAppMetricsLiveItem.md)

#### Defined in

[main.ts:107988](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107988)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")