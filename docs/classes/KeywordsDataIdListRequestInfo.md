[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataIdListRequestInfo

# Class: KeywordsDataIdListRequestInfo

## Implements

- [`IKeywordsDataIdListRequestInfo`](../interfaces/IKeywordsDataIdListRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataIdListRequestInfo.md#constructor)

### Properties

- [datetime\_from](KeywordsDataIdListRequestInfo.md#datetime_from)
- [datetime\_to](KeywordsDataIdListRequestInfo.md#datetime_to)
- [include\_metadata](KeywordsDataIdListRequestInfo.md#include_metadata)
- [limit](KeywordsDataIdListRequestInfo.md#limit)
- [offset](KeywordsDataIdListRequestInfo.md#offset)
- [sort](KeywordsDataIdListRequestInfo.md#sort)

### Methods

- [init](KeywordsDataIdListRequestInfo.md#init)
- [toJSON](KeywordsDataIdListRequestInfo.md#tojson)
- [fromJS](KeywordsDataIdListRequestInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataIdListRequestInfo**(`data?`): [`KeywordsDataIdListRequestInfo`](KeywordsDataIdListRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataIdListRequestInfo`](../interfaces/IKeywordsDataIdListRequestInfo.md) |

#### Returns

[`KeywordsDataIdListRequestInfo`](KeywordsDataIdListRequestInfo.md)

#### Defined in

[main.ts:112256](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112256)

## Properties

### datetime\_from

• `Optional` **datetime\_from**: `string`

start time for filtering results
required field
if include_metadata is set to true, maximum value: a month from current datetime;
if include_metadata is set to false, maximum value: six months from current datetime;
must be specified in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-15 12:57:46 +00:00

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[datetime_from](../interfaces/IKeywordsDataIdListRequestInfo.md#datetime_from)

#### Defined in

[main.ts:112226](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112226)

___


### datetime\_to

• `Optional` **datetime\_to**: `string`

finish time for filtering results
required field
maximum value: current datetime;
must be specified in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2023-01-31 13:57:46 +00:00

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[datetime_to](../interfaces/IKeywordsDataIdListRequestInfo.md#datetime_to)

#### Defined in

[main.ts:112233](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112233)

___


### include\_metadata

• `Optional` **include\_metadata**: `boolean`

include task metadata in the respond
optional field
default value: false

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[include_metadata](../interfaces/IKeywordsDataIdListRequestInfo.md#include_metadata)

#### Defined in

[main.ts:112252](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112252)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned task IDs
optional field
default value: 1000
maximum value: 1000

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[limit](../interfaces/IKeywordsDataIdListRequestInfo.md#limit)

#### Defined in

[main.ts:112238](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112238)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned task IDs
optional field
default value: 0
if you specify the 10 value, the first ten tasks in the results array will be omitted

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[offset](../interfaces/IKeywordsDataIdListRequestInfo.md#offset)

#### Defined in

[main.ts:112243](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112243)

___


### sort

• `Optional` **sort**: `string`

sorting by task execution time
optional field
possible values: "asc", "desc"
default value: "asc"

#### Implementation of

[IKeywordsDataIdListRequestInfo](../interfaces/IKeywordsDataIdListRequestInfo.md).[sort](../interfaces/IKeywordsDataIdListRequestInfo.md#sort)

#### Defined in

[main.ts:112248](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112248)

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

[main.ts:112265](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112265)

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

[main.ts:112287](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112287)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataIdListRequestInfo`](KeywordsDataIdListRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataIdListRequestInfo`](KeywordsDataIdListRequestInfo.md)

#### Defined in

[main.ts:112280](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L112280)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")