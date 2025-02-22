[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentAnalysisApi

# Class: ContentAnalysisApi

## Table of contents

### Constructors

- [constructor](ContentAnalysisApi.md#constructor)

### Properties

- [baseUrl](ContentAnalysisApi.md#baseurl)
- [http](ContentAnalysisApi.md#http)
- [jsonParseReviver](ContentAnalysisApi.md#jsonparsereviver)

### Methods

- [categoryTrendsLive](ContentAnalysisApi.md#categorytrendslive)
- [contentAnalysisAvailableFilters](ContentAnalysisApi.md#contentanalysisavailablefilters)
- [contentAnalysisCategories](ContentAnalysisApi.md#contentanalysiscategories)
- [contentAnalysisIdList](ContentAnalysisApi.md#contentanalysisidlist)
- [contentAnalysisLanguages](ContentAnalysisApi.md#contentanalysislanguages)
- [contentAnalysisLocations](ContentAnalysisApi.md#contentanalysislocations)
- [contentAnalysisSummaryLive](ContentAnalysisApi.md#contentanalysissummarylive)
- [phraseTrendsLive](ContentAnalysisApi.md#phrasetrendslive)
- [processCategoryTrendsLive](ContentAnalysisApi.md#processcategorytrendslive)
- [processContentAnalysisAvailableFilters](ContentAnalysisApi.md#processcontentanalysisavailablefilters)
- [processContentAnalysisCategories](ContentAnalysisApi.md#processcontentanalysiscategories)
- [processContentAnalysisIdList](ContentAnalysisApi.md#processcontentanalysisidlist)
- [processContentAnalysisLanguages](ContentAnalysisApi.md#processcontentanalysislanguages)
- [processContentAnalysisLocations](ContentAnalysisApi.md#processcontentanalysislocations)
- [processContentAnalysisSummaryLive](ContentAnalysisApi.md#processcontentanalysissummarylive)
- [processPhraseTrendsLive](ContentAnalysisApi.md#processphrasetrendslive)
- [processRatingDistributionLive](ContentAnalysisApi.md#processratingdistributionlive)
- [processSearchLive](ContentAnalysisApi.md#processsearchlive)
- [processSentimentAnalysisLive](ContentAnalysisApi.md#processsentimentanalysislive)
- [ratingDistributionLive](ContentAnalysisApi.md#ratingdistributionlive)
- [searchLive](ContentAnalysisApi.md#searchlive)
- [sentimentAnalysisLive](ContentAnalysisApi.md#sentimentanalysislive)

## Constructors

### constructor

• **new ContentAnalysisApi**(`baseUrl?`, `http?`): [`ContentAnalysisApi`](ContentAnalysisApi.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `baseUrl?` | `string` |
| `http?` | `Object` |
| `http.fetch` | (`url`: `RequestInfo`, `init?`: `RequestInit`) => `Promise`\<`Response`\> |

#### Returns

[`ContentAnalysisApi`](ContentAnalysisApi.md)

#### Defined in

[main.ts:12746](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12746)

## Properties

### baseUrl

• `Private` **baseUrl**: `string`

#### Defined in

[main.ts:12743](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12743)

___


### http

• `Private` **http**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `fetch` | (`url`: `RequestInfo`, `init?`: `RequestInit`) => `Promise`\<`Response`\> |

#### Defined in

[main.ts:12742](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12742)

___


### jsonParseReviver

• `Protected` **jsonParseReviver**: (`key`: `string`, `value`: `any`) => `any` = `undefined`

#### Type declaration

▸ (`key`, `value`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `value` | `any` |

##### Returns

`any`

#### Defined in

[main.ts:12744](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12744)

## Methods

### categoryTrendsLive

▸ **categoryTrendsLive**(`body`): `Promise`\<[`ContentAnalysisCategoryTrendsLiveResponseInfo`](ContentAnalysisCategoryTrendsLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisCategoryTrendsLiveRequestInfo`](ContentAnalysisCategoryTrendsLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisCategoryTrendsLiveResponseInfo`](ContentAnalysisCategoryTrendsLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:13155](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13155)

___


### contentAnalysisAvailableFilters

▸ **contentAnalysisAvailableFilters**(): `Promise`\<[`ContentAnalysisAvailableFiltersResponseInfo`](ContentAnalysisAvailableFiltersResponseInfo.md)\>

#### Returns

`Promise`\<[`ContentAnalysisAvailableFiltersResponseInfo`](ContentAnalysisAvailableFiltersResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12796](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12796)

___


### contentAnalysisCategories

▸ **contentAnalysisCategories**(): `Promise`\<[`ContentAnalysisCategoriesResponseInfo`](ContentAnalysisCategoriesResponseInfo.md)\>

#### Returns

`Promise`\<[`ContentAnalysisCategoriesResponseInfo`](ContentAnalysisCategoriesResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12907](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12907)

___


### contentAnalysisIdList

▸ **contentAnalysisIdList**(`body`): `Promise`\<[`ContentAnalysisIdListResponseInfo`](ContentAnalysisIdListResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisIdListRequestInfo`](ContentAnalysisIdListRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisIdListResponseInfo`](ContentAnalysisIdListResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12755](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12755)

___


### contentAnalysisLanguages

▸ **contentAnalysisLanguages**(): `Promise`\<[`ContentAnalysisLanguagesResponseInfo`](ContentAnalysisLanguagesResponseInfo.md)\>

#### Returns

`Promise`\<[`ContentAnalysisLanguagesResponseInfo`](ContentAnalysisLanguagesResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12870](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12870)

___


### contentAnalysisLocations

▸ **contentAnalysisLocations**(): `Promise`\<[`ContentAnalysisLocationsResponseInfo`](ContentAnalysisLocationsResponseInfo.md)\>

#### Returns

`Promise`\<[`ContentAnalysisLocationsResponseInfo`](ContentAnalysisLocationsResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12833](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12833)

___


### contentAnalysisSummaryLive

▸ **contentAnalysisSummaryLive**(`body`): `Promise`\<[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisSummaryLiveRequestInfo`](ContentAnalysisSummaryLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12987](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12987)

___


### phraseTrendsLive

▸ **phraseTrendsLive**(`body`): `Promise`\<[`ContentAnalysisPhraseTrendsLiveResponseInfo`](ContentAnalysisPhraseTrendsLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisPhraseTrendsLiveRequestInfo`](ContentAnalysisPhraseTrendsLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisPhraseTrendsLiveResponseInfo`](ContentAnalysisPhraseTrendsLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:13113](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13113)

___


### processCategoryTrendsLive

▸ **processCategoryTrendsLive**(`response`): `Promise`\<[`ContentAnalysisCategoryTrendsLiveResponseInfo`](ContentAnalysisCategoryTrendsLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisCategoryTrendsLiveResponseInfo`](ContentAnalysisCategoryTrendsLiveResponseInfo.md)\>

#### Defined in

[main.ts:13175](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13175)

___


### processContentAnalysisAvailableFilters

▸ **processContentAnalysisAvailableFilters**(`response`): `Promise`\<[`ContentAnalysisAvailableFiltersResponseInfo`](ContentAnalysisAvailableFiltersResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisAvailableFiltersResponseInfo`](ContentAnalysisAvailableFiltersResponseInfo.md)\>

#### Defined in

[main.ts:12812](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12812)

___


### processContentAnalysisCategories

▸ **processContentAnalysisCategories**(`response`): `Promise`\<[`ContentAnalysisCategoriesResponseInfo`](ContentAnalysisCategoriesResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisCategoriesResponseInfo`](ContentAnalysisCategoriesResponseInfo.md)\>

#### Defined in

[main.ts:12923](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12923)

___


### processContentAnalysisIdList

▸ **processContentAnalysisIdList**(`response`): `Promise`\<[`ContentAnalysisIdListResponseInfo`](ContentAnalysisIdListResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisIdListResponseInfo`](ContentAnalysisIdListResponseInfo.md)\>

#### Defined in

[main.ts:12775](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12775)

___


### processContentAnalysisLanguages

▸ **processContentAnalysisLanguages**(`response`): `Promise`\<[`ContentAnalysisLanguagesResponseInfo`](ContentAnalysisLanguagesResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisLanguagesResponseInfo`](ContentAnalysisLanguagesResponseInfo.md)\>

#### Defined in

[main.ts:12886](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12886)

___


### processContentAnalysisLocations

▸ **processContentAnalysisLocations**(`response`): `Promise`\<[`ContentAnalysisLocationsResponseInfo`](ContentAnalysisLocationsResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisLocationsResponseInfo`](ContentAnalysisLocationsResponseInfo.md)\>

#### Defined in

[main.ts:12849](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12849)

___


### processContentAnalysisSummaryLive

▸ **processContentAnalysisSummaryLive**(`response`): `Promise`\<[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)\>

#### Defined in

[main.ts:13007](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13007)

___


### processPhraseTrendsLive

▸ **processPhraseTrendsLive**(`response`): `Promise`\<[`ContentAnalysisPhraseTrendsLiveResponseInfo`](ContentAnalysisPhraseTrendsLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisPhraseTrendsLiveResponseInfo`](ContentAnalysisPhraseTrendsLiveResponseInfo.md)\>

#### Defined in

[main.ts:13133](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13133)

___


### processRatingDistributionLive

▸ **processRatingDistributionLive**(`response`): `Promise`\<[`ContentAnalysisRatingDistributionLiveResponseInfo`](ContentAnalysisRatingDistributionLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisRatingDistributionLiveResponseInfo`](ContentAnalysisRatingDistributionLiveResponseInfo.md)\>

#### Defined in

[main.ts:13091](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13091)

___


### processSearchLive

▸ **processSearchLive**(`response`): `Promise`\<[`ContentAnalysisSearchLiveResponseInfo`](ContentAnalysisSearchLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisSearchLiveResponseInfo`](ContentAnalysisSearchLiveResponseInfo.md)\>

#### Defined in

[main.ts:12965](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12965)

___


### processSentimentAnalysisLive

▸ **processSentimentAnalysisLive**(`response`): `Promise`\<[`ContentAnalysisSentimentAnalysisLiveResponseInfo`](ContentAnalysisSentimentAnalysisLiveResponseInfo.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `response` | `Response` |

#### Returns

`Promise`\<[`ContentAnalysisSentimentAnalysisLiveResponseInfo`](ContentAnalysisSentimentAnalysisLiveResponseInfo.md)\>

#### Defined in

[main.ts:13049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13049)

___


### ratingDistributionLive

▸ **ratingDistributionLive**(`body`): `Promise`\<[`ContentAnalysisRatingDistributionLiveResponseInfo`](ContentAnalysisRatingDistributionLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisRatingDistributionLiveRequestInfo`](ContentAnalysisRatingDistributionLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisRatingDistributionLiveResponseInfo`](ContentAnalysisRatingDistributionLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:13071](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13071)

___


### searchLive

▸ **searchLive**(`body`): `Promise`\<[`ContentAnalysisSearchLiveResponseInfo`](ContentAnalysisSearchLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisSearchLiveRequestInfo`](ContentAnalysisSearchLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisSearchLiveResponseInfo`](ContentAnalysisSearchLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:12945](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L12945)

___


### sentimentAnalysisLive

▸ **sentimentAnalysisLive**(`body`): `Promise`\<[`ContentAnalysisSentimentAnalysisLiveResponseInfo`](ContentAnalysisSentimentAnalysisLiveResponseInfo.md)\>

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `body` | [`ContentAnalysisSentimentAnalysisLiveRequestInfo`](ContentAnalysisSentimentAnalysisLiveRequestInfo.md)[] | (optional) |

#### Returns

`Promise`\<[`ContentAnalysisSentimentAnalysisLiveResponseInfo`](ContentAnalysisSentimentAnalysisLiveResponseInfo.md)\>

Successful operation

#### Defined in

[main.ts:13029](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L13029)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")