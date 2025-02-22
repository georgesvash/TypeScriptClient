[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ILocation

# Interface: ILocation

## Implemented by

- [`Location`](../classes/Location.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [latitude](ILocation.md#latitude)
- [location\_chain](ILocation.md#location_chain)
- [longitude](ILocation.md#longitude)
- [maps\_url](ILocation.md#maps_url)
- [neighborhood](ILocation.md#neighborhood)
- [neighborhood\_description](ILocation.md#neighborhood_description)
- [overall\_score](ILocation.md#overall_score)
- [score\_by\_categories](ILocation.md#score_by_categories)

## Properties

### latitude

• `Optional` **latitude**: `number`

hotel latitude
latitude coordinates of the hotel’s location
example:
39.4806397

#### Defined in

[main.ts:196984](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196984)

___


### location\_chain

• `Optional` **location\_chain**: [`LocationChain`](../classes/LocationChain.md)[]

elements of the location chain
additional parameters of each element of the location chain

#### Defined in

[main.ts:196992](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196992)

___


### longitude

• `Optional` **longitude**: `number`

hotel longitude
latitude coordinates of the hotel’s location
example:
-106.0512973

#### Defined in

[main.ts:196989](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196989)

___


### maps\_url

• `Optional` **maps\_url**: `string`

url to the location of the hotel in google maps

#### Defined in

[main.ts:196971](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196971)

___


### neighborhood

• `Optional` **neighborhood**: `string`

name of the neighborhood where the hotel is located

#### Defined in

[main.ts:196967](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196967)

___


### neighborhood\_description

• `Optional` **neighborhood\_description**: `string`

description of the neighborhood where the hotel is located

#### Defined in

[main.ts:196969](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196969)

___


### overall\_score

• `Optional` **overall\_score**: `number`

overall score of the hotel location
indicates the overall score of the hotel’s location in the range from 1 to 5;
calculated based on data from the hotel’s proximity to nearby things to do and restaurants, transportation, and airports;
note that the criteria are not weighted equally in the overall score

#### Defined in

[main.ts:196976](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196976)

___


### score\_by\_categories

• `Optional` **score\_by\_categories**: [`ScoreByCategories`](../classes/ScoreByCategories.md)

category scores of the hotel location
the scores of the hotel’s location tied to the categories that indicate the proximity to nearby things to do, restaurants, transportation, and airports;

#### Defined in

[main.ts:196979](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L196979)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")