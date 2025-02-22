[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleDatasetInfoTaskPostRequestInfo

# Class: SerpGoogleDatasetInfoTaskPostRequestInfo

## Implements

- [`ISerpGoogleDatasetInfoTaskPostRequestInfo`](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleDatasetInfoTaskPostRequestInfo.md#constructor)

### Properties

- [dataset\_id](SerpGoogleDatasetInfoTaskPostRequestInfo.md#dataset_id)
- [device](SerpGoogleDatasetInfoTaskPostRequestInfo.md#device)
- [language\_code](SerpGoogleDatasetInfoTaskPostRequestInfo.md#language_code)
- [language\_name](SerpGoogleDatasetInfoTaskPostRequestInfo.md#language_name)
- [os](SerpGoogleDatasetInfoTaskPostRequestInfo.md#os)
- [pingback\_url](SerpGoogleDatasetInfoTaskPostRequestInfo.md#pingback_url)
- [postback\_data](SerpGoogleDatasetInfoTaskPostRequestInfo.md#postback_data)
- [postback\_url](SerpGoogleDatasetInfoTaskPostRequestInfo.md#postback_url)
- [priority](SerpGoogleDatasetInfoTaskPostRequestInfo.md#priority)
- [tag](SerpGoogleDatasetInfoTaskPostRequestInfo.md#tag)

### Methods

- [init](SerpGoogleDatasetInfoTaskPostRequestInfo.md#init)
- [toJSON](SerpGoogleDatasetInfoTaskPostRequestInfo.md#tojson)
- [fromJS](SerpGoogleDatasetInfoTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleDatasetInfoTaskPostRequestInfo**(`data?`): [`SerpGoogleDatasetInfoTaskPostRequestInfo`](SerpGoogleDatasetInfoTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleDatasetInfoTaskPostRequestInfo`](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md) |

#### Returns

[`SerpGoogleDatasetInfoTaskPostRequestInfo`](SerpGoogleDatasetInfoTaskPostRequestInfo.md)

#### Defined in

[main.ts:51850](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51850)

## Properties

### dataset\_id

• `Optional` **dataset\_id**: `string`

ID of the dataset
required field
you can find dataset ID in the dataset URL or dataset item of Google Dataset Search result
example:
L2cvMTFqbl85ZHN6MQ==

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[dataset_id](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#dataset_id)

#### Defined in

[main.ts:51786](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51786)

___


### device

• `Optional` **device**: `string`

device type
optional field
possible value: desktop

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[device](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#device)

#### Defined in

[main.ts:51810](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51810)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
if you use this field, you don’t need to specify language_name
possible value:
en

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[language_code](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:51806](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51806)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
if you use this field, you don’t need to specify language_code
possible value:
English

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[language_name](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:51800](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51800)

___


### os

• `Optional` **os**: `string`

device operating system
optional field
choose from the following values: windows, macos
default value: windows

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[os](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#os)

#### Defined in

[main.ts:51815](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51815)

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

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[pingback_url](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:51846](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51846)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible value: advanced

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[postback_data](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#postback_data)

#### Defined in

[main.ts:51836](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51836)

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

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[postback_url](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:51831](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51831)

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

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[priority](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#priority)

#### Defined in

[main.ts:51794](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51794)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[ISerpGoogleDatasetInfoTaskPostRequestInfo](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md).[tag](../interfaces/ISerpGoogleDatasetInfoTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:51821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51821)

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

[main.ts:51859](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51859)

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

[main.ts:51885](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51885)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleDatasetInfoTaskPostRequestInfo`](SerpGoogleDatasetInfoTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleDatasetInfoTaskPostRequestInfo`](SerpGoogleDatasetInfoTaskPostRequestInfo.md)

#### Defined in

[main.ts:51878](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51878)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")