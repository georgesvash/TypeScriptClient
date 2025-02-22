[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsLocationsResultInfo

# Class: KeywordsDataGoogleTrendsLocationsResultInfo

## Implements

- [`IKeywordsDataGoogleTrendsLocationsResultInfo`](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsLocationsResultInfo.md#constructor)

### Properties

- [country\_iso\_code](KeywordsDataGoogleTrendsLocationsResultInfo.md#country_iso_code)
- [geo\_id](KeywordsDataGoogleTrendsLocationsResultInfo.md#geo_id)
- [geo\_name](KeywordsDataGoogleTrendsLocationsResultInfo.md#geo_name)
- [location\_code](KeywordsDataGoogleTrendsLocationsResultInfo.md#location_code)
- [location\_code\_parent](KeywordsDataGoogleTrendsLocationsResultInfo.md#location_code_parent)
- [location\_name](KeywordsDataGoogleTrendsLocationsResultInfo.md#location_name)
- [location\_type](KeywordsDataGoogleTrendsLocationsResultInfo.md#location_type)

### Methods

- [init](KeywordsDataGoogleTrendsLocationsResultInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsLocationsResultInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsLocationsResultInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsLocationsResultInfo**(`data?`): [`KeywordsDataGoogleTrendsLocationsResultInfo`](KeywordsDataGoogleTrendsLocationsResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsLocationsResultInfo`](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsLocationsResultInfo`](KeywordsDataGoogleTrendsLocationsResultInfo.md)

#### Defined in

[main.ts:119029](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119029)

## Properties

### country\_iso\_code

• `Optional` **country\_iso\_code**: `string`

ISO country code of the location

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[country_iso_code](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#country_iso_code)

#### Defined in

[main.ts:119016](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119016)

___


### geo\_id

• `Optional` **geo\_id**: `string`

google trends location identifier
you can use this field for matching obtained results with the location_code parameter specified in the request

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[geo_id](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#geo_id)

#### Defined in

[main.ts:119025](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119025)

___


### geo\_name

• `Optional` **geo\_name**: `string`

google trends location name
you can use this field for matching obtained results with the location_name parameter specified in the request

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[geo_name](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#geo_name)

#### Defined in

[main.ts:119022](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119022)

___


### location\_code

• `Optional` **location\_code**: `number`

location code

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[location_code](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#location_code)

#### Defined in

[main.ts:119003](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119003)

___


### location\_code\_parent

• `Optional` **location\_code\_parent**: `number`

the code of the superordinate location
example:
"location_code": 9041134,
"location_name": "Vienna International Airport,Lower Austria,Austria",
"location_code_parent": 20044
where location_code_parent corresponds to:
"location_code": 20044,
"location_name": "Lower Austria,Austria"

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[location_code_parent](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#location_code_parent)

#### Defined in

[main.ts:119014](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119014)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[location_name](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#location_name)

#### Defined in

[main.ts:119005](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119005)

___


### location\_type

• `Optional` **location\_type**: `string`

location type
possible values according to Google’s target types

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsResultInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md).[location_type](../interfaces/IKeywordsDataGoogleTrendsLocationsResultInfo.md#location_type)

#### Defined in

[main.ts:119019](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119019)

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

[main.ts:119038](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119038)

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

[main.ts:119061](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119061)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsLocationsResultInfo`](KeywordsDataGoogleTrendsLocationsResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsLocationsResultInfo`](KeywordsDataGoogleTrendsLocationsResultInfo.md)

#### Defined in

[main.ts:119054](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119054)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")