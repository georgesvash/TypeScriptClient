[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpGoogleLocalFinderTaskPostRequestInfo

# Interface: ISerpGoogleLocalFinderTaskPostRequestInfo

## Implemented by

- [`SerpGoogleLocalFinderTaskPostRequestInfo`](../classes/SerpGoogleLocalFinderTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [depth](ISerpGoogleLocalFinderTaskPostRequestInfo.md#depth)
- [device](ISerpGoogleLocalFinderTaskPostRequestInfo.md#device)
- [keyword](ISerpGoogleLocalFinderTaskPostRequestInfo.md#keyword)
- [language\_code](ISerpGoogleLocalFinderTaskPostRequestInfo.md#language_code)
- [language\_name](ISerpGoogleLocalFinderTaskPostRequestInfo.md#language_name)
- [location\_code](ISerpGoogleLocalFinderTaskPostRequestInfo.md#location_code)
- [location\_coordinate](ISerpGoogleLocalFinderTaskPostRequestInfo.md#location_coordinate)
- [location\_name](ISerpGoogleLocalFinderTaskPostRequestInfo.md#location_name)
- [min\_rating](ISerpGoogleLocalFinderTaskPostRequestInfo.md#min_rating)
- [os](ISerpGoogleLocalFinderTaskPostRequestInfo.md#os)
- [pingback\_url](ISerpGoogleLocalFinderTaskPostRequestInfo.md#pingback_url)
- [postback\_data](ISerpGoogleLocalFinderTaskPostRequestInfo.md#postback_data)
- [postback\_url](ISerpGoogleLocalFinderTaskPostRequestInfo.md#postback_url)
- [priority](ISerpGoogleLocalFinderTaskPostRequestInfo.md#priority)
- [tag](ISerpGoogleLocalFinderTaskPostRequestInfo.md#tag)
- [time\_filter](ISerpGoogleLocalFinderTaskPostRequestInfo.md#time_filter)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of results in SERP
default value for desktop: 20
max value for desktop: 500default value for mobile: 10
max value for mobile: 350
Note: your account will be billed per each SERP containing up to 20 results for desktop or up to 10 results for a mobile device;
thus, setting a depth above 20 for desktop or above 10 for mobile may result in additional charges if the search engine returns more than 20 or 10 results respectively;
if the specified depth is higher than the number of results in the response, the difference will be refunded to your account balance automatically

#### Defined in

[main.ts:39901](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39901)

___


### device

• `Optional` **device**: `string`

device type
optional field
can take the values:desktop, mobile
default value: desktop

#### Defined in

[main.ts:39884](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39884)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
you can specify up to 700 symbols in the keyword field
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character)
if you need to use the “%” symbol for your keyword, please specify it as “%25”;
if you need to use the “+” symbol for your keyword, please specify it as “%2B”

#### Defined in

[main.ts:39833](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39833)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available languages of the search engine with their language_code by making a separate request to the https://api.dataforseo.com/v3/serp/google/languages
example:en

#### Defined in

[main.ts:39879](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39879)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available languages of the search engine with their language_name by making a separate request to the https://api.dataforseo.com/v3/serp/google/languages
example:
English

#### Defined in

[main.ts:39873](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39873)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available locations of the search engines with their location_code by making a separate request to the https://api.dataforseo.com/v3/serp/google/locations
example:
2840

#### Defined in

[main.ts:39855](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39855)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude,zoom” format
if “zoom” is not specified, 17z will be applied as a default value
the maximum number of decimal digits for “latitude” and “longitude”: 7
the minimum value for “zoom”: 4z
the maximum value for “zoom”: 18z
example:
52.6178549,-155.352142,20z

#### Defined in

[main.ts:39866](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39866)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations of the search engine with their location_name by making a separate request to the https://api.dataforseo.com/v3/serp/google/locations
example:
London,England,United Kingdom

#### Defined in

[main.ts:39848](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39848)

___


### min\_rating

• `Optional` **min\_rating**: `number`

filter results by minimum rating
optional field
possible values for desktop: 3.5, 4, 4.5;
possible values for mobile: 2, 2.5, 3, 3.5, 4, 4.5

#### Defined in

[main.ts:39906](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39906)

___


### os

• `Optional` **os**: `string`

device operating system
optional field
if you specify desktop in the device field, choose from the following values: windows, macos
default value: windows
if you specify mobile in the device field, choose from the following values: android, ios
default value: android

#### Defined in

[main.ts:39891](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39891)

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

[main.ts:39947](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39947)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the function you used for setting a task
possible values:
advanced, html

#### Defined in

[main.ts:39937](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39937)

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

[main.ts:39931](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39931)

___


### priority

• `Optional` **priority**: `number`

task priority
optional field
can take the following values:
1 – normal execution priority (set by default)
2 – high execution priority
You will be additionally charged for the tasks with high execution priority.
The cost can be calculated on the Pricing page.

#### Defined in

[main.ts:39841](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39841)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:39921](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39921)

___


### time\_filter

• `Optional` **time\_filter**: `string`

filter results by open hours
optional field
using this field, you can filter places in the results by the time a place is open for visitors
note that Google may also provide results that do not match this filter
possible values: "open_now", "24_hours", "$day_value", "$day_value;$time_value";
instead of $day_value use one of these values: "monday", "tuesday", "wednesday", "thursday", "friday", "saturday", "sunday";
instead of $time_value use one of these values: "00", "01", "02", "03", "04", "05", "06", "07", "08", "09", "10", "11", "12", "13", "14", "15", "16", "17", "18", "19", "20", "21", "22", "23"
example: "tuesday;18"

#### Defined in

[main.ts:39915](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39915)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")