[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IMerchantTaskRequestInfo

# Interface: IMerchantTaskRequestInfo

## Hierarchy

- **`IMerchantTaskRequestInfo`**
  
  ↳ [`IMerchantAmazonProductsTaskPostRequestInfo`](IMerchantAmazonProductsTaskPostRequestInfo.md)

## Implemented by

- [`MerchantTaskRequestInfo`](../classes/MerchantTaskRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [depth](IMerchantTaskRequestInfo.md#depth)
- [keyword](IMerchantTaskRequestInfo.md#keyword)
- [language\_code](IMerchantTaskRequestInfo.md#language_code)
- [language\_name](IMerchantTaskRequestInfo.md#language_name)
- [location\_code](IMerchantTaskRequestInfo.md#location_code)
- [location\_coordinate](IMerchantTaskRequestInfo.md#location_coordinate)
- [location\_name](IMerchantTaskRequestInfo.md#location_name)
- [max\_crawl\_pages](IMerchantTaskRequestInfo.md#max_crawl_pages)
- [pingback\_url](IMerchantTaskRequestInfo.md#pingback_url)
- [postback\_data](IMerchantTaskRequestInfo.md#postback_data)
- [postback\_url](IMerchantTaskRequestInfo.md#postback_url)
- [price\_max](IMerchantTaskRequestInfo.md#price_max)
- [price\_min](IMerchantTaskRequestInfo.md#price_min)
- [priority](IMerchantTaskRequestInfo.md#priority)
- [se\_domain](IMerchantTaskRequestInfo.md#se_domain)
- [search\_param](IMerchantTaskRequestInfo.md#search_param)
- [sort\_by](IMerchantTaskRequestInfo.md#sort_by)
- [tag](IMerchantTaskRequestInfo.md#tag)
- [url](IMerchantTaskRequestInfo.md#url)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of results to be retrieved from the Google Shopping results page
default value: 100
max value: 700
Note: your account will be billed per each results page containing up to 100 results;
thus, setting a depth above 100 may result in additional charges if the search engine returns more than 100 results;
if the specified depth is higher than the number of results in the response, the difference will be refunded automatically to your account balance

#### Defined in

[main.ts:142843](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142843)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
you can also specify UPC/EAN in this field and we will return the results Google Shopping provides for the specified barcode number;
you can specify up to 700 symbols in the keyword filed
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character)
if you need to use the “%” symbol for your keyword, please specify it as “%25”;

#### Defined in

[main.ts:142776](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142776)

___


### language\_code

• `Optional` **language\_code**: `string`

language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available Google Shopping languages with their language_code by making a separate request to the https://api.dataforseo.com/v3/merchant/google/languages
example:
en

#### Defined in

[main.ts:142827](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142827)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available Google Shopping languages with their language_name by making a separate request to the https://api.dataforseo.com/v3/merchant/google/languages
example:
English

#### Defined in

[main.ts:142820](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142820)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available Google Shopping locations with their location_code by making a separate request to the https://api.dataforseo.com/v3/merchant/google/locations
example:
2840

#### Defined in

[main.ts:142804](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142804)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude,radius” format
the maximum number of decimal digits for “latitude” and “longitude”: 7
the minimum value for “radius”: 199.9
example:
53.476225,-2.243572,200

#### Defined in

[main.ts:142813](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142813)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available Google Shopping locations with their location_name by making a separate request to the https://api.dataforseo.com/v3/merchant/google/locations
example:
London,England,United Kingdom

#### Defined in

[main.ts:142797](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142797)

___


### max\_crawl\_pages

• `Optional` **max\_crawl\_pages**: `number`

page crawl limit
optional field
number of search results pages to crawl
max value: 7
Note: the max_crawl_pages and depth parameters complement each other;
learn more at our help center

#### Defined in

[main.ts:142850](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142850)

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

[main.ts:142912](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142912)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced, html

#### Defined in

[main.ts:142902](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142902)

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

[main.ts:142896](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142896)

___


### price\_max

• `Optional` **price\_max**: `number`

maximum product price
optional field
maximum price of the returned products listed on Google Shopping for the specified query
example:
100

#### Defined in

[main.ts:142873](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142873)

___


### price\_min

• `Optional` **price\_min**: `number`

minimum product price
optional field
minimum price of the returned products listed on Google Shopping for the specified query
example:
5

#### Defined in

[main.ts:142867](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142867)

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

[main.ts:142790](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142790)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain
optional field
we choose the relevant search engine domain automatically according to the location and language you specify
however, you can set a custom search engine domain in this field
example:
google.co.uk, google.com.au, google.de, etc.

#### Defined in

[main.ts:142834](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142834)

___


### search\_param

• `Optional` **search\_param**: `string`

additional parameters of the search query
optional field
you can use the following search URL parameters for customizing the search
example:
&tbs=ppr_min:45 – search for products that cost more than 45 USD;
&tbs=ppr_max:50 – search for products that cost less than 50 USD;
&tbs=p_ord:p – sort by ascending price;
&tbs=p_ord:pd – sort by descending price;
&tbs=p_ord:rv – sort by review score;
&tbs=ppr_max:50,p_ord:rv – sort by review score with the maximum price of 50 USD

#### Defined in

[main.ts:142861](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142861)

___


### sort\_by

• `Optional` **sort\_by**: `string`

results sorting rules
optional field
the following sorting rules are supported:
review_score, price_low_to_high, price_high_to_low
example:
sort_by:"review_score"

#### Defined in

[main.ts:142880](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142880)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:142886](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142886)

___


### url

• `Optional` **url**: `string`

direct URL of the search query
optional field
you can specify a direct URL and we will sort it out to the necessary fields. Note that this method is the most difficult for our API to process and also requires you to specify the exact language and location in the URL. In most cases, we wouldn’t recommend using this method.
example:
https://www.google.com/search?q=iphone&num=100&tbm=shop&ie=UTF-8&oe=UTF-8&tbs=vw%3A1%2Cmr%3A1%2Cprice%3A1%2Cppr_min%3A5&hl=en&gl=US&gws_rd=cr&uule=w+CAIQIFISCQs2MuSEtepUEUK33kOSuTsc

#### Defined in

[main.ts:142782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L142782)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")