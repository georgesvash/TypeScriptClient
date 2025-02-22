[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsGoogleAppCompetitorsLiveItem

# Interface: IDataforseoLabsGoogleAppCompetitorsLiveItem

## Implemented by

- [`DataforseoLabsGoogleAppCompetitorsLiveItem`](../classes/DataforseoLabsGoogleAppCompetitorsLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [app\_id](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#app_id)
- [avg\_position](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#avg_position)
- [competitor\_metrics](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#competitor_metrics)
- [full\_metrics](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#full_metrics)
- [intersections](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#intersections)
- [se\_type](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#se_type)
- [sum\_position](IDataforseoLabsGoogleAppCompetitorsLiveItem.md#sum_position)

## Properties

### app\_id

• `Optional` **app\_id**: `string`

id of the competitor app

#### Defined in

[main.ts:109362](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109362)

___


### avg\_position

• `Optional` **avg\_position**: `number`

average position of the app in Google Play SERP
Note: average position is calculated for intersected keywords only;
the value for a given application may differ when combined with different target applications

#### Defined in

[main.ts:109366](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109366)

___


### competitor\_metrics

• `Optional` **competitor\_metrics**: [`GooglePlayMetricsBundleInfo`](../classes/GooglePlayMetricsBundleInfo.md)

metrics for intersecting keywords
ranking data relevant to the keywords that the provided competitor application shares with the app in a POST request;
note: in this array ranking data is provided for the returned competitor’s app_id

#### Defined in

[main.ts:109376](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109376)

___


### full\_metrics

• `Optional` **full\_metrics**: [`GooglePlayMetricsBundleInfo`](../classes/GooglePlayMetricsBundleInfo.md)

metrics for all keywords of the application
full overview of ranking data relevant to all keywords that the provided app_id is ranking for

#### Defined in

[main.ts:109379](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109379)

___


### intersections

• `Optional` **intersections**: `number`

number of intersecting keywords

#### Defined in

[main.ts:109372](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109372)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Defined in

[main.ts:109360](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109360)

___


### sum\_position

• `Optional` **sum\_position**: `number`

sum of all app positions in Google Play SERP
Note: sum position is calculated for intersected keywords only;
the value for a given application may differ when combined with different target applications

#### Defined in

[main.ts:109370](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L109370)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")