[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo

# Interface: IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo

## Implemented by

- [`KeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo`](../classes/KeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [date\_from](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#date_from)
- [date\_to](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#date_to)
- [device](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#device)
- [keywords](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#keywords)
- [keywords\_negative](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#keywords_negative)
- [language\_code](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#language_code)
- [language\_name](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#language_name)
- [location\_code](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#location_code)
- [location\_coordinate](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#location_coordinate)
- [location\_name](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#location_name)
- [pingback\_url](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#pingback_url)
- [postback\_url](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#postback_url)
- [search\_partners](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#search_partners)
- [sort\_by](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#sort_by)
- [tag](IKeywordsDataBingKeywordsForKeywordsTaskPostRequestInfo.md#tag)

## Properties

### date\_from

• `Optional` **date\_from**: `string`

starting date of the time range
optional field
you can specify a date from the past 24 months
if you don’t specify this field, data will be provided for the last 12 months
date format: "yyyy-mm-dd"
example:
"2020-01-01"

#### Defined in

[main.ts:125213](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125213)

___


### date\_to

• `Optional` **date\_to**: `string`

ending date of the time range
optional field
if you don’t specify this field, data will be provided for the last 12 months;
minimum value: two years back from today’s date;
maximum value: one month from today’s date;
note: we do not recommend using a custom time range for the past year’s dates;
date format: "yyyy-mm-dd"
example:
"2020-03-15"

#### Defined in

[main.ts:125223](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125223)

___


### device

• `Optional` **device**: `string`

device type
optional field
specify this field if you want to get the data for a particular device type;
possible values: all, mobile, desktop, tablet
default value: all

#### Defined in

[main.ts:125205](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125205)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
you can specify the maximum of 200 keywords with each keyword containing no more than 100 characters;
the specified keywords will be converted to lowercase, data will be provided in a separate array

#### Defined in

[main.ts:125154](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125154)

___


### keywords\_negative

• `Optional` **keywords\_negative**: `string`[]

keywords negative array
optional field
These keywords will be ignored in the results array;
You can specify a maximum of 200 terms that you want to exclude from the results;
the specified keywords will be converted to lowercase format

#### Defined in

[main.ts:125199](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125199)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
supported languages:
en, fr, de

#### Defined in

[main.ts:125188](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125188)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
supported languages:
English, French, German

#### Defined in

[main.ts:125182](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125182)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available locations of the search engines with their location_code by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/locations
example:
2840

#### Defined in

[main.ts:125168](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125168)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude” format
the data will be provided for the country the specified coordinates belong to
example:
52.6178549,-155.352142

#### Defined in

[main.ts:125176](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125176)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations of the search engine with their location_name by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/locations
example:
London,England,United Kingdom

#### Defined in

[main.ts:125161](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125161)

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

[main.ts:125248](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125248)

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

[main.ts:125238](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125238)

___


### search\_partners

• `Optional` **search\_partners**: `boolean`

Bing search partners type
optional field
if you specify true, the results will be delivered for owned, operated, and syndicated networks across Bing, Yahoo, AOL and partner sites that host Bing, AOL, and Yahoo search.
default value: false – results are returned for Bing, AOL, and Yahoo search networks

#### Defined in

[main.ts:125228](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125228)

___


### sort\_by

• `Optional` **sort\_by**: `string`

results sorting parameters
optional field
Use these parameters to sort the results by search_volume, cpc, competition or relevance in the descending order
default value: relevance

#### Defined in

[main.ts:125193](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125193)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:125254](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L125254)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")