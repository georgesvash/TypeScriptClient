[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo

# Interface: IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo

## Implemented by

- [`KeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo`](../classes/KeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [bid](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#bid)
- [date\_from](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#date_from)
- [date\_interval](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#date_interval)
- [date\_to](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#date_to)
- [keywords](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#keywords)
- [language\_code](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#language_code)
- [language\_name](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#language_name)
- [location\_code](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#location_code)
- [location\_coordinate](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#location_coordinate)
- [location\_name](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#location_name)
- [match](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#match)
- [pingback\_url](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#pingback_url)
- [postback\_url](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#postback_url)
- [search\_partners](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#search_partners)
- [sort\_by](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#sort_by)
- [tag](IKeywordsDataGoogleAdsAdTrafficByKeywordsTaskPostRequestInfo.md#tag)

## Properties

### bid

• `Optional` **bid**: `number`

the maximum custom bid
required field
the collected data will be based on this value
it stands for the price you are willing to pay for an ad; the higher value you specify here, the higher values you will get in the returned metrics
learn more in this help center article

#### Defined in

[main.ts:117782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117782)

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

#### Defined in

[main.ts:117838](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117838)

___


### date\_interval

• `Optional` **date\_interval**: `string`

forecasting date interval
optional field
if you specify date_interval, you don’t need to indicate date_from and date_to
possible values: next_week, next_month, next_quarter
default value: next_month

#### Defined in

[main.ts:117853](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117853)

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

#### Defined in

[main.ts:117847](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117847)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
The maximum number of keywords you can specify: 1000
The maximum number of characters for each keyword: 80
The maximum number of words for each keyword phrase: 10
the keywords you specify will be converted to a lowercase format
Note #1: Google Ads may return no data for certain groups of keywords;
Note #2: Google Ads provides combined search volume values for groups of similar keywords
to obtain search volume for similar keywords, we recommend submitting such keywords in separate requests;
Note #3: Google Ads doesn’t allow using certain symbols and characters (e.g., UTF symbols, emojis), so you can’t use them when setting a task;
to learn more about which symbols can be used, please refer to this article

#### Defined in

[main.ts:117776](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117776)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
you can receive the list of available languages of the search engine with their language_code by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/languages
example:
en

#### Defined in

[main.ts:117828](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117828)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
you can receive the list of available languages of the search engine with their language_name by making a separate request to https://api.dataforseo.com/v3/keywords_data/google_ads/languages
example:
English

#### Defined in

[main.ts:117822](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117822)

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

#### Defined in

[main.ts:117807](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117807)

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

#### Defined in

[main.ts:117816](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117816)

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

#### Defined in

[main.ts:117799](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117799)

___


### match

• `Optional` **match**: `string`

keywords match-type
required field
can take the following values: exact, broad, phrase

#### Defined in

[main.ts:117786](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117786)

___


### pingback\_url

• `Optional` **pingback\_url**: `string`

notification URL of a completed task
optional field
when a task is completed we will notify you by GET request sent to the URL you have specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/pingscript?id=$id
http://your-server.com/pingscript?id=$id&tag=$tag
Note: special symbols in pingback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Defined in

[main.ts:117878](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117878)

___


### postback\_url

• `Optional` **postback\_url**: `string`

return URL for sending task results
optional field
once the task is completed, we will send a POST request with its results compressed in the gzip format to the postback_url you specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/postbackscript?id=$id
http://your-server.com/postbackscript?id=$id&tag=$tag
Note: special symbols in postback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Defined in

[main.ts:117868](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117868)

___


### search\_partners

• `Optional` **search\_partners**: `boolean`

include Google search partners
optional field
if you specify true, the results will be delivered for owned, operated, and syndicated networks across Google and partner sites that host Google search;
default value: false – results are returned for Google search sites

#### Defined in

[main.ts:117791](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117791)

___


### sort\_by

• `Optional` **sort\_by**: `string`

results sorting parameters
optional field
Use these parameters to sort the results by relevance, impressions, ctr, average_cpc, cost, or clicks in the descending order
default value: relevance

#### Defined in

[main.ts:117858](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117858)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:117884](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L117884)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")