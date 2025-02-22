[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo

# Class: SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo

## Implements

- [`ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#constructor)

### Properties

- [device](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#device)
- [language\_code](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#language_code)
- [language\_name](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#language_name)
- [location\_code](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#location_code)
- [location\_name](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#location_name)
- [os](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#os)
- [subtitles\_language](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#subtitles_language)
- [subtitles\_translate\_language](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#subtitles_translate_language)
- [tag](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#tag)
- [video\_id](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#video_id)

### Methods

- [init](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#init)
- [toJSON](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#tojson)
- [fromJS](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo**(`data?`): [`SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md) |

#### Returns

[`SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md)

#### Defined in

[main.ts:60644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60644)

## Properties

### device

• `Optional` **device**: `string`

device type
optional field
only value: desktop

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[device](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#device)

#### Defined in

[main.ts:60629](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60629)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available languages of the search engine with their language_code by making a separate request to the https://api.dataforseo.com/v3/serp/youtube/languages
example:
en

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[language_code](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#language_code)

#### Defined in

[main.ts:60625](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60625)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available languages of the search engine with their language_name by making a separate request to the https://api.dataforseo.com/v3/serp/youtube/languages
example:
English

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[language_name](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#language_name)

#### Defined in

[main.ts:60618](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60618)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name 
if you use this field, you don’t need to specify location_name
you can receive the list of available locations of the search engines with their location_code by making a separate request to the https://api.dataforseo.com/v3/serp/youtube/locations
example:
2840

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[location_code](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#location_code)

#### Defined in

[main.ts:60611](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60611)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code
if you use this field, you don’t need to specify location_code
you can receive the list of available locations of the search engine with their location_name by making a separate request to the https://api.dataforseo.com/v3/serp/youtube/locations
example:
United States

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[location_name](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#location_name)

#### Defined in

[main.ts:60604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60604)

___


### os

• `Optional` **os**: `string`

device operating system
optional field
choose from the following values: windows, macos
default value: windows

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[os](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#os)

#### Defined in

[main.ts:60634](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60634)

___


### subtitles\_language

• `Optional` **subtitles\_language**: `string`

language code of original text
you can get the language code from YouTube Video Info result

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[subtitles_language](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#subtitles_language)

#### Defined in

[main.ts:60593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60593)

___


### subtitles\_translate\_language

• `Optional` **subtitles\_translate\_language**: `string`

language code of translated text
possible values:
"az", "ay", "ak", "sq", "am", "en", "ar", "hy", "as", "af", "eu", "be", "bn", "my", "bg", "bs", "bho", "cy", "hu", "vi", "haw", "ht", "gl", "lg", "el", "ka", "gn", "gu", "gd", "da", "fy", "zu", "iw", "ig", "yi", "id", "ga", "is", "es", "it", "yo", "kk", "kn", "ca", "qu", "rw", "ky", "zh-Hant", "zh-Hans", "ko", "co", "xh", "ku", "km", "lo", "la", "lv", "ln", "lt", "lb", "mk", "mg", "ms", "ml", "dv", "mt", "mi", "mr", "mn", "und", "de", "ne", "nl", "no", "ny", "or", "om", "pa", "fa", "pl", "pt", "ps", "ro", "ru", "sm", "sa", "ceb", "nso", "sr", "si", "sd", "sk", "sl", "so", "sw", "su", "tg", "th", "ta", "tt", "te", "ti", "ts", "tr", "tk", "uz", "ug", "uk", "ur", "fil", "fi", "fr", "ha", "hi", "hmn", "hr", "cs", "sv", "sn", "ee", "eo", "et", "st", "jv", "ja", "kri"

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[subtitles_translate_language](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#subtitles_translate_language)

#### Defined in

[main.ts:60597](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60597)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[tag](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#tag)

#### Defined in

[main.ts:60640](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60640)

___


### video\_id

• `Optional` **video\_id**: `string`

ID of the video
required field
you can find video ID in the URL or ‘youtube_video’ item of YouTube Organic result
example:
Y8Wu4rSNJms

#### Implementation of

[ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md).[video_id](../interfaces/ISerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md#video_id)

#### Defined in

[main.ts:60590](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60590)

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

[main.ts:60653](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60653)

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

[main.ts:60679](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60679)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo`](SerpYoutubeVideoSubtitlesLiveAdvancedRequestInfo.md)

#### Defined in

[main.ts:60672](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60672)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")