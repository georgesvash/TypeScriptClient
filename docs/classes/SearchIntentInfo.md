[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SearchIntentInfo

# Class: SearchIntentInfo

## Implements

- [`ISearchIntentInfo`](../interfaces/ISearchIntentInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SearchIntentInfo.md#constructor)

### Properties

- [foreign\_intent](SearchIntentInfo.md#foreign_intent)
- [last\_updated\_time](SearchIntentInfo.md#last_updated_time)
- [main\_intent](SearchIntentInfo.md#main_intent)
- [se\_type](SearchIntentInfo.md#se_type)

### Methods

- [init](SearchIntentInfo.md#init)
- [toJSON](SearchIntentInfo.md#tojson)
- [fromJS](SearchIntentInfo.md#fromjs)

## Constructors

### constructor

• **new SearchIntentInfo**(`data?`): [`SearchIntentInfo`](SearchIntentInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISearchIntentInfo`](../interfaces/ISearchIntentInfo.md) |

#### Returns

[`SearchIntentInfo`](SearchIntentInfo.md)

#### Defined in

[main.ts:79560](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79560)

## Properties

### foreign\_intent

• `Optional` **foreign\_intent**: `string`[]

supplementary search intents
possible values: informational, navigational, commercial, transactional

#### Implementation of

[ISearchIntentInfo](../interfaces/ISearchIntentInfo.md).[foreign_intent](../interfaces/ISearchIntentInfo.md#foreign_intent)

#### Defined in

[main.ts:79551](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79551)

___


### last\_updated\_time

• `Optional` **last\_updated\_time**: `string`

date and time when search intent data was last updated
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[ISearchIntentInfo](../interfaces/ISearchIntentInfo.md).[last_updated_time](../interfaces/ISearchIntentInfo.md#last_updated_time)

#### Defined in

[main.ts:79556](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79556)

___


### main\_intent

• `Optional` **main\_intent**: `string`

main search intent
possible values: informational, navigational, commercial, transactional

#### Implementation of

[ISearchIntentInfo](../interfaces/ISearchIntentInfo.md).[main_intent](../interfaces/ISearchIntentInfo.md#main_intent)

#### Defined in

[main.ts:79548](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79548)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type
possible values: google

#### Implementation of

[ISearchIntentInfo](../interfaces/ISearchIntentInfo.md).[se_type](../interfaces/ISearchIntentInfo.md#se_type)

#### Defined in

[main.ts:79545](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79545)

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

[main.ts:79569](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79569)

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

[main.ts:79593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79593)

___


### fromJS

▸ **fromJS**(`data`): [`SearchIntentInfo`](SearchIntentInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SearchIntentInfo`](SearchIntentInfo.md)

#### Defined in

[main.ts:79586](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L79586)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")