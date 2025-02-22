[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo

# Class: KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo

## Implements

- [`IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#constructor)

### Properties

- [bid](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#bid)
- [date\_from](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_from)
- [date\_interval](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_interval)
- [date\_to](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_to)
- [keywords](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#keywords)
- [language\_code](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#language_code)
- [language\_name](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#language_name)
- [location\_code](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_code)
- [location\_coordinate](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_coordinate)
- [location\_name](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_name)
- [match](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#match)
- [search\_partners](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#search_partners)
- [sort\_by](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#sort_by)
- [tag](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#tag)

### Methods

- [init](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#init)
- [toJSON](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#tojson)
- [fromJS](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo**(`data?`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md) |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md)

#### Defined in

[main.ts:118558](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118558)

## Properties

### bid

• `Optional` **bid**: `number`

the maximum custom bid
required field
the collected data will be based on this value
it stands for the price you are willing to pay for an ad; the higher value you specify here, the higher values you will get in the returned metrics
learn more in this help center article

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[bid](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#bid)

#### Defined in

[main.ts:118472](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118472)

___


### date\_from

• `Optional` **date\_from**: `string`

starting date of the forecasting time range
required field if you specify date_to
if you indicate date_from and date_to, you don’t need to specify date_interval
minimum value is tomorrow’s date
the value you specify in date_from shouldn’t be further than date_to
date format: "yyyy-mm-dd"
example:
"2021-10-30"if Status endpoint returns false in the actual_data field, date_from can be set to the month before last and prior;
if Status endpoint returns true in the actual_data field, date_from can be set to the last month and prior

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[date_from](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_from)

#### Defined in

[main.ts:118528](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118528)

___


### date\_interval

• `Optional` **date\_interval**: `string`

forecasting date interval
optional field
if you specify date_interval, you don’t need to indicate date_from and date_to
possible values: next_week, next_month, next_quarter
default value: next_month

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[date_interval](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_interval)

#### Defined in

[main.ts:118543](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118543)

___


### date\_to

• `Optional` **date\_to**: `string`

ending date of the forecasting time range
required field if you specify date_from
if you indicate date_from and date_to, you don’t need to specify date_interval
minimum value is date_from +1 day
maximum value is current day and month of the next year
date format: "yyyy-mm-dd"
example:
"2022-10-30"

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[date_to](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#date_to)

#### Defined in

[main.ts:118537](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118537)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
The maximum number of keywords you can specify: 1000
The maximum number of characters for each keyword: 80
The maximum number of words for each keyword phrase: 10
the keywords you specify will be converted to a lowercase format
Note: Google Ads may return no data for certain groups of keywords
visit our Help Center to learn more
Also note that Google Ads doesn’t allow using certain symbols and characters (e.g., UTF symbols, emojis), so you can’t use them when setting a task;
to learn more about which symbols can be used, please refer to this article

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[keywords](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#keywords)

#### Defined in

[main.ts:118466](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118466)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
you can receive the list of available languages of the search engine with their language_code by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/languages
example:
en

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[language_code](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:118518](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118518)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
you can receive the list of available languages of the search engine with their language_name by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/languages
example:
English

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[language_name](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:118512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118512)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
optional field
if you do not indicate the location, you will receive worldwide results, i.e., for all available locations;
if you use this field, you don’t need to specify location_name or location_coordinate;
you can receive the list of available locations of the search engines with their location_code by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/locations
example:
2840

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[location_code](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:118497](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118497)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
optional field
if you do not indicate the location, you will receive worldwide results, i.e., for all available locations;
if you use this field, you don’t need to specify location_name or location_code;
location_coordinate parameter should be specified in the “latitude,longitude” format;
the data will be provided for the country the specified coordinates belong to;
example:
52.6178549,-155.352142

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[location_coordinate](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:118506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118506)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
optional field
if you do not indicate the location, you will receive worldwide results, i.e., for all available locations;
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations of the search engine with their location_name by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/locations
example:
London,England,United Kingdom

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[location_name](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:118489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118489)

___


### match

• `Optional` **match**: `string`

keywords match-type
required field
can take the following values: exact, broad, phrase

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[match](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#match)

#### Defined in

[main.ts:118476](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118476)

___


### search\_partners

• `Optional` **search\_partners**: `boolean`

include Google search partners
optional field
if you specify true, the results will be delivered for owned, operated, and syndicated networks across Google and partner sites that host Google search;
default value: false – results are returned for Google search sites

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[search_partners](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#search_partners)

#### Defined in

[main.ts:118481](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118481)

___


### sort\_by

• `Optional` **sort\_by**: `string`

results sorting parameters
optional field
Use these parameters to sort the results by relevance, impressions, ctr, average_cpc, cost, or clicks in the descending order
default value: relevance

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[sort_by](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#sort_by)

#### Defined in

[main.ts:118548](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118548)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md).[tag](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md#tag)

#### Defined in

[main.ts:118554](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118554)

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

[main.ts:118567](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118567)

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

[main.ts:118601](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118601)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveRequestInfo.md)

#### Defined in

[main.ts:118594](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118594)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")