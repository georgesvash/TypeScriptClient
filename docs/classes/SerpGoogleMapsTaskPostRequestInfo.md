[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleMapsTaskPostRequestInfo

# Class: SerpGoogleMapsTaskPostRequestInfo

## Implements

- [`ISerpGoogleMapsTaskPostRequestInfo`](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleMapsTaskPostRequestInfo.md#constructor)

### Properties

- [depth](SerpGoogleMapsTaskPostRequestInfo.md#depth)
- [device](SerpGoogleMapsTaskPostRequestInfo.md#device)
- [keyword](SerpGoogleMapsTaskPostRequestInfo.md#keyword)
- [language\_code](SerpGoogleMapsTaskPostRequestInfo.md#language_code)
- [language\_name](SerpGoogleMapsTaskPostRequestInfo.md#language_name)
- [location\_code](SerpGoogleMapsTaskPostRequestInfo.md#location_code)
- [location\_coordinate](SerpGoogleMapsTaskPostRequestInfo.md#location_coordinate)
- [location\_name](SerpGoogleMapsTaskPostRequestInfo.md#location_name)
- [max\_crawl\_pages](SerpGoogleMapsTaskPostRequestInfo.md#max_crawl_pages)
- [os](SerpGoogleMapsTaskPostRequestInfo.md#os)
- [pingback\_url](SerpGoogleMapsTaskPostRequestInfo.md#pingback_url)
- [postback\_data](SerpGoogleMapsTaskPostRequestInfo.md#postback_data)
- [postback\_url](SerpGoogleMapsTaskPostRequestInfo.md#postback_url)
- [priority](SerpGoogleMapsTaskPostRequestInfo.md#priority)
- [se\_domain](SerpGoogleMapsTaskPostRequestInfo.md#se_domain)
- [search\_places](SerpGoogleMapsTaskPostRequestInfo.md#search_places)
- [search\_this\_area](SerpGoogleMapsTaskPostRequestInfo.md#search_this_area)
- [tag](SerpGoogleMapsTaskPostRequestInfo.md#tag)
- [url](SerpGoogleMapsTaskPostRequestInfo.md#url)

### Methods

- [init](SerpGoogleMapsTaskPostRequestInfo.md#init)
- [toJSON](SerpGoogleMapsTaskPostRequestInfo.md#tojson)
- [fromJS](SerpGoogleMapsTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleMapsTaskPostRequestInfo**(`data?`): [`SerpGoogleMapsTaskPostRequestInfo`](SerpGoogleMapsTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleMapsTaskPostRequestInfo`](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md) |

#### Returns

[`SerpGoogleMapsTaskPostRequestInfo`](SerpGoogleMapsTaskPostRequestInfo.md)

#### Defined in

[main.ts:37459](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37459)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of results in SERP
default value: 100
max value: 700
Note: your account will be billed per each SERP containing up to 100 results;
thus, setting a depth above 100 may result in additional charges if the search engine returns more than 100 results;
if the specified depth is higher than the number of results in the response, the difference will be refunded automatically to your account balance

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[depth](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#depth)

#### Defined in

[main.ts:37403](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37403)

___


### device

• `Optional` **device**: `string`

device type
optional field
can take the values:desktop, mobile
default value: desktop
note: for mobile device, only 20 results are returned for every SERP

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[device](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#device)

#### Defined in

[main.ts:37380](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37380)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
you can specify up to 700 symbols in the keyword field
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character)
if you need to use the “%” symbol for your keyword, please specify it as “%25”;
if you need to use the “+” symbol for your keyword, please specify it as “%2B”;
if this field contains such parameters as ‘allinanchor:’, ‘allintext:’, ‘allintitle:’, ‘allinurl:’, ‘define:’, ‘filetype:’, ‘id:’, ‘inanchor:’, ‘info:’, ‘intext:’, ‘intitle:’, ‘inurl:’, ‘link:’, ‘related:’, ‘site:’, the charge per task will be multiplied by 5
Note: queries containing the ‘cache:’ parameter are not supported and will return a validation error

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[keyword](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#keyword)

#### Defined in

[main.ts:37327](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37327)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available languages of the search engine with their language_code by making a separate request to the https://api.dataforseo.com/v3/serp/google/languages
example:
en

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[language_code](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:37374](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37374)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available languages of the search engine with their language_name by making a separate request to the https://api.dataforseo.com/v3/serp/google/languages
example:
English

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[language_name](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:37367](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37367)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available locations of the search engines with their location_code by making a separate request to the https://api.dataforseo.com/v3/serp/google/locations
example:
2840

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[location_code](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#location_code)

#### Defined in

[main.ts:37349](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37349)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude,zoom” format
if “zoom” is not specified, 17z will be applied as a default value
the maximum number of decimal digits for “latitude” and “longitude”: 7
the minimum value for “zoom”: 3z
the maximum value for “zoom”: 21z
example:
52.6178549,-155.352142,20z

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[location_coordinate](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:37360](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37360)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations of the search engine with their location_name by making a separate request to the https://api.dataforseo.com/v3/serp/google/locations
example:
London,England,United Kingdom

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[location_name](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#location_name)

#### Defined in

[main.ts:37342](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37342)

___


### max\_crawl\_pages

• `Optional` **max\_crawl\_pages**: `number`

page crawl limit
optional field
number of search results pages to crawl
max value: 100
Note: the max_crawl_pages and depth parameters complement each other;
learn more at our help center

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[max_crawl_pages](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#max_crawl_pages)

#### Defined in

[main.ts:37410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37410)

___


### os

• `Optional` **os**: `string`

device operating system
optional field
if you specify desktop in the device field, choose from the following values: windows, macos
default value: windows
if you specify mobile in the device field, choose from the following values: android, ios
default value: android

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[os](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#os)

#### Defined in

[main.ts:37387](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37387)

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

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[pingback_url](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:37455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37455)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the function you used for setting a task
possible values:
advanced

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[postback_data](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#postback_data)

#### Defined in

[main.ts:37445](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37445)

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

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[postback_url](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:37439](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37439)

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

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[priority](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#priority)

#### Defined in

[main.ts:37335](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37335)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain
optional field
we choose the relevant search engine domain automatically according to the location and language you specify
however, you can set a custom search engine domain in this field
example:
google.co.uk, google.com.au, google.de, etc.

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[se_domain](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#se_domain)

#### Defined in

[main.ts:37394](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37394)

___


### search\_places

• `Optional` **search\_places**: `boolean`

search places mode
optional field
the search places mode allows to obtain Google Maps results on a certain place (e.g., Apple Store in New York)
however, due to the pecularities of our data mining algorithm, this mode might interfere with some local-intent queries – and display results for a location that is different from that specified in the request;
to prevent this interference and obtain correct results for keywords with local intent you may set this parameter to false;default value: true
Note: if the search_places mode is turned off and no results were found in the search area, the results array will be empty

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[search_places](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#search_places)

#### Defined in

[main.ts:37423](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37423)

___


### search\_this\_area

• `Optional` **search\_this\_area**: `boolean`

search this area
optional field
can take the values:true, false
default value: trueif set to false, the search_this_area mode will be turned off
Note: if the search_this_area mode is turned off, Google Maps listings might contain results beyond the displayed area

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[search_this_area](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#search_this_area)

#### Defined in

[main.ts:37416](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37416)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[tag](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:37429](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37429)

___


### url

• `Optional` **url**: `string`

direct URL of the search query
optional field
you can specify a direct URL and we will sort it out to the necessary fields. Note that this method is the most difficult for our API to process and also requires you to specify the exact language and location in the URL. In most cases, we wouldn’t recommend using this method.
example:
https://google.com/maps/search/pizza/@37.09024,-95.712891,4z

#### Implementation of

[ISerpGoogleMapsTaskPostRequestInfo](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md).[url](../interfaces/ISerpGoogleMapsTaskPostRequestInfo.md#url)

#### Defined in

[main.ts:37318](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37318)

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

[main.ts:37468](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37468)

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

[main.ts:37503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37503)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleMapsTaskPostRequestInfo`](SerpGoogleMapsTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleMapsTaskPostRequestInfo`](SerpGoogleMapsTaskPostRequestInfo.md)

#### Defined in

[main.ts:37496](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37496)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")