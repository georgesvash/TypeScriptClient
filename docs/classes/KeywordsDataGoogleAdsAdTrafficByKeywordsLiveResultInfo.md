[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo

# Class: KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo

## Implements

- [`IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#constructor)

### Properties

- [average\_cpc](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#average_cpc)
- [bid](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#bid)
- [clicks](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#clicks)
- [cost](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#cost)
- [ctr](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#ctr)
- [date\_interval](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#date_interval)
- [impressions](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#impressions)
- [keyword](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#keyword)
- [language\_code](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#language_code)
- [location\_code](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#location_code)
- [match](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#match)
- [search\_partners](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#search_partners)

### Methods

- [init](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#init)
- [toJSON](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#tojson)
- [fromJS](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo**(`data?`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md) |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md)

#### Defined in

[main.ts:118782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118782)

## Properties

### average\_cpc

• `Optional` **average\_cpc**: `number`

the average cost-per-click value
represents the cost-per-click (USD) estimated for a keyword based on the specified time period and historical data;
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[average_cpc](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#average_cpc)

#### Defined in

[main.ts:118770](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118770)

___


### bid

• `Optional` **bid**: `number`

the maximum custom bid
the bid you have specified when setting the task
represents the price you are willing to pay for an ad
the higher value you have specified, the higher metrics and cost you receive in response
learn more in this help center article

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[bid](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#bid)

#### Defined in

[main.ts:118754](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118754)

___


### clicks

• `Optional` **clicks**: `number`

number of clicks on an ad
number of clicks an ad is projected to get within the specified time period
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[clicks](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#clicks)

#### Defined in

[main.ts:118778](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118778)

___


### cost

• `Optional` **cost**: `number`

charge for an ad
amount that will be charged for running an ad within the specified time period
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[cost](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#cost)

#### Defined in

[main.ts:118774](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118774)

___


### ctr

• `Optional` **ctr**: `number`

projected click through rate (CTR) of the advertisement
number of clicks an ad is projected to receive divided by the number of ad impressions; the CTR is projected for the specified time period
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[ctr](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#ctr)

#### Defined in

[main.ts:118766](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118766)

___


### date\_interval

• `Optional` **date\_interval**: `string`

forecasting date interval in a POST array

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[date_interval](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#date_interval)

#### Defined in

[main.ts:118743](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118743)

___


### impressions

• `Optional` **impressions**: `number`

projected number of ad impressions
number of impressions an ad is projected to get within the specified time period
if there is no data, then the value is null
learn more about impressions in this help center article

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[impressions](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#impressions)

#### Defined in

[main.ts:118762](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118762)

___


### keyword

• `Optional` **keyword**: `string`

keyword in a POST array

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[keyword](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#keyword)

#### Defined in

[main.ts:118735](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118735)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[language_code](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#language_code)

#### Defined in

[main.ts:118741](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118741)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[location_code](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#location_code)

#### Defined in

[main.ts:118738](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118738)

___


### match

• `Optional` **match**: `string`

keywords match-type
can take the following values: exact, broad, phrase

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[match](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#match)

#### Defined in

[main.ts:118757](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118757)

___


### search\_partners

• `Optional` **search\_partners**: `boolean`

include Google search partners
the value you specified when setting the task
if true, the results are returned for owned, operated, and syndicated networks across Google and partner sites that host Google search;
if false, the results are returned for Google search sites only

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md).[search_partners](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md#search_partners)

#### Defined in

[main.ts:118748](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118748)

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

[main.ts:118791](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118791)

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

[main.ts:118819](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118819)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsLiveResultInfo.md)

#### Defined in

[main.ts:118812](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118812)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")