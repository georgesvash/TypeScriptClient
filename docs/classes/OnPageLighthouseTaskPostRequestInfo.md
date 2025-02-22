[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageLighthouseTaskPostRequestInfo

# Class: OnPageLighthouseTaskPostRequestInfo

## Implements

- [`IOnPageLighthouseTaskPostRequestInfo`](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageLighthouseTaskPostRequestInfo.md#constructor)

### Properties

- [audits](OnPageLighthouseTaskPostRequestInfo.md#audits)
- [categories](OnPageLighthouseTaskPostRequestInfo.md#categories)
- [for\_mobile](OnPageLighthouseTaskPostRequestInfo.md#for_mobile)
- [language\_code](OnPageLighthouseTaskPostRequestInfo.md#language_code)
- [language\_name](OnPageLighthouseTaskPostRequestInfo.md#language_name)
- [pingback\_url](OnPageLighthouseTaskPostRequestInfo.md#pingback_url)
- [postback\_url](OnPageLighthouseTaskPostRequestInfo.md#postback_url)
- [tag](OnPageLighthouseTaskPostRequestInfo.md#tag)
- [url](OnPageLighthouseTaskPostRequestInfo.md#url)
- [version](OnPageLighthouseTaskPostRequestInfo.md#version)

### Methods

- [init](OnPageLighthouseTaskPostRequestInfo.md#init)
- [toJSON](OnPageLighthouseTaskPostRequestInfo.md#tojson)
- [fromJS](OnPageLighthouseTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageLighthouseTaskPostRequestInfo**(`data?`): [`OnPageLighthouseTaskPostRequestInfo`](OnPageLighthouseTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageLighthouseTaskPostRequestInfo`](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md) |

#### Returns

[`OnPageLighthouseTaskPostRequestInfo`](OnPageLighthouseTaskPostRequestInfo.md)

#### Defined in

[main.ts:154151](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154151)

## Properties

### audits

• `Optional` **audits**: `string`[]

Lighthouse audits
optional field
audits are individual tests Lighthouse runs for each specific feature/optimization/metric to produce a numeric score (see official definition)  
if you ignore this field, we will return data for all audits
use this field to get data for specific audits you indicate here
note that some audits do not belong to a specific category and are stand-alone page quality measurements
in general, there can be several use cases:

1. if you ignore categories, you can use this field to get data for the specified audits only
   for example, if you ignore "categories" and specify "audits": ["metrics/cumulative-layout-shift","metrics/largest-contentful-paint","metrics/total-blocking-time"], you will get data only for these audits
2. if you specify a category, you can use this field to additionally receive audits that do not belong to the category(-ies) you specified
   for example, if you specify "categories": ["seo"] and "audits": ["metrics/cumulative-layout-shift","metrics/largest-contentful-paint","metrics/total-blocking-time"], you will get only these audits under “performance” and all audits under “seo”
   you can get the full list of possible audits here

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[audits](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#audits)

#### Defined in

[main.ts:154104](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154104)

___


### categories

• `Optional` **categories**: `string`[]

categories of Lighthouse audits
optional field
each category is a collection of audits and audit groups that applies weighting and scoring to the section (see official definition)
if you ignore this field, we will return data for all categories unless you specify audits
use this field to get data for specific categories you indicate here
possible values:
seo, pwa, performance, best_practices, accessibility

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[categories](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#categories)

#### Defined in

[main.ts:154091](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154091)

___


### for\_mobile

• `Optional` **for\_mobile**: `boolean`

applies mobile emulation
optional field
if set to true, Lighthouse will use mobile device and screen emulation to test the page against mobile environment
if set to false, the results will be provided for desktop
default value: false

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[for_mobile](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#for_mobile)

#### Defined in

[main.ts:154083](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154083)

___


### language\_code

• `Optional` **language\_code**: `string`

lighthouse language code
optional field
you can receive the list of available languages of the search engine with their language_code by making a separate request to https://api.dataforseo.com/v3/on_page/lighthouse/languages
default value:
en

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[language_code](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:154121](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154121)

___


### language\_name

• `Optional` **language\_name**: `string`

lighthouse language name
optional field
you can receive the list of available languages of the search engine with their language_name by making a separate request to https://api.dataforseo.com/v3/on_page/lighthouse/languages
default value:
English

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[language_name](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:154115](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154115)

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

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[pingback_url](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:154137](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154137)

___


### postback\_url

• `Optional` **postback\_url**: `string`

return URL for sending task results
optional field
once the task is completed, we will send a POST request with its results compressed in the gzip format to the postback_url you specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request
example:
http://your-server.com/postbackscript?id=$id
http://your-server.com/postbackscript?id=$id&tag=$tag
Note: special symbols in postback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[postback_url](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:154147](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154147)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[tag](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:154127](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154127)

___


### url

• `Optional` **url**: `string`

target URL
required field
target page should be specified with its absolute URL (including http:// or https://)
example:
https://dataforseo.com/

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[url](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#url)

#### Defined in

[main.ts:154077](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154077)

___


### version

• `Optional` **version**: `string`

lighthouse version
optional field
you can obtain the results specific to a certain Lighthouse version by specifying its number
the list of available versions is available through the Lighthouse Versions endpoint

#### Implementation of

[IOnPageLighthouseTaskPostRequestInfo](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md).[version](../interfaces/IOnPageLighthouseTaskPostRequestInfo.md#version)

#### Defined in

[main.ts:154109](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154109)

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

[main.ts:154160](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154160)

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

[main.ts:154194](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154194)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageLighthouseTaskPostRequestInfo`](OnPageLighthouseTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageLighthouseTaskPostRequestInfo`](OnPageLighthouseTaskPostRequestInfo.md)

#### Defined in

[main.ts:154187](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154187)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")