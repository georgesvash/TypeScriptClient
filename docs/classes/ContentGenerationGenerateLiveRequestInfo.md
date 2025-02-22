[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentGenerationGenerateLiveRequestInfo

# Class: ContentGenerationGenerateLiveRequestInfo

## Implements

- [`IContentGenerationGenerateLiveRequestInfo`](../interfaces/IContentGenerationGenerateLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ContentGenerationGenerateLiveRequestInfo.md#constructor)

### Properties

- [avoid\_starting\_words](ContentGenerationGenerateLiveRequestInfo.md#avoid_starting_words)
- [avoid\_words](ContentGenerationGenerateLiveRequestInfo.md#avoid_words)
- [creativity\_index](ContentGenerationGenerateLiveRequestInfo.md#creativity_index)
- [max\_new\_tokens](ContentGenerationGenerateLiveRequestInfo.md#max_new_tokens)
- [max\_tokens](ContentGenerationGenerateLiveRequestInfo.md#max_tokens)
- [stop\_words](ContentGenerationGenerateLiveRequestInfo.md#stop_words)
- [supplement\_token](ContentGenerationGenerateLiveRequestInfo.md#supplement_token)
- [tag](ContentGenerationGenerateLiveRequestInfo.md#tag)
- [temperature](ContentGenerationGenerateLiveRequestInfo.md#temperature)
- [text](ContentGenerationGenerateLiveRequestInfo.md#text)
- [token\_repetition\_penalty](ContentGenerationGenerateLiveRequestInfo.md#token_repetition_penalty)
- [top\_k](ContentGenerationGenerateLiveRequestInfo.md#top_k)
- [top\_p](ContentGenerationGenerateLiveRequestInfo.md#top_p)

### Methods

- [init](ContentGenerationGenerateLiveRequestInfo.md#init)
- [toJSON](ContentGenerationGenerateLiveRequestInfo.md#tojson)
- [fromJS](ContentGenerationGenerateLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new ContentGenerationGenerateLiveRequestInfo**(`data?`): [`ContentGenerationGenerateLiveRequestInfo`](ContentGenerationGenerateLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IContentGenerationGenerateLiveRequestInfo`](../interfaces/IContentGenerationGenerateLiveRequestInfo.md) |

#### Returns

[`ContentGenerationGenerateLiveRequestInfo`](ContentGenerationGenerateLiveRequestInfo.md)

#### Defined in

[main.ts:159836](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159836)

## Properties

### avoid\_starting\_words

• `Optional` **avoid\_starting\_words**: `string`[]

words or phrases to avoid in the beginning of the generated text
optional field
you can specify up to 50 terms;
example:
["SEO", "search engine optimization"]

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[avoid_starting_words](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#avoid_starting_words)

#### Defined in

[main.ts:159814](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159814)

___


### avoid\_words

• `Optional` **avoid\_words**: `string`[]

words or phrases to avoid when generating a text
optional field
you can specify up to 50 terms;
example:
["term", "optimization"]

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[avoid_words](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#avoid_words)

#### Defined in

[main.ts:159808](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159808)

___


### creativity\_index

• `Optional` **creativity\_index**: `number`

creativity of content generation
optional field
if you use this field, you don’t need to use top_k / top_p / temperature
the randomness of the selection of equally probable subsequent tokens;
can take values from 0 to 1
default value: 0.8
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[creativity_index](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#creativity_index)

#### Defined in

[main.ts:159771](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159771)

___


### max\_new\_tokens

• `Optional` **max\_new\_tokens**: `number`

generation limit for new tokens
required field if max_tokens is not specified
the maximum number of new tokens for generated content;
maximum value: 300;
Note: the number does not include tokens specified in the text field;
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[max_new_tokens](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#max_new_tokens)

#### Defined in

[main.ts:159756](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159756)

___


### max\_tokens

• `Optional` **max\_tokens**: `number`

generation limit for all tokens
required field if max_new_tokens is not specified
the maximum total number of tokens for generated content;
maximum value: 1024;
Note: the number includes tokens specified in the text field
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[max_tokens](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#max_tokens)

#### Defined in

[main.ts:159763](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159763)

___


### stop\_words

• `Optional` **stop\_words**: `string`[]

words or phrases to end the text
optional field
you can specify up to 50 terms;
example:
["now","subscribe"]

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[stop_words](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#stop_words)

#### Defined in

[main.ts:159820](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159820)

___


### supplement\_token

• `Optional` **supplement\_token**: `string`

token for generating subsequent results
optional field
provided in the identical filed of the response to each request;
you can use this parameter to continue the generation of text from the initial response
supplement_token values are unique for each subsequent task

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[supplement_token](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#supplement_token)

#### Defined in

[main.ts:159826](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159826)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[tag](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#tag)

#### Defined in

[main.ts:159832](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159832)

___


### temperature

• `Optional` **temperature**: `number`

controls the randomness in the output
optional field
if you use creativity_index, this field will be ignored
the lower the temperature, the more likely the model will choose words with a higher probability of occurrence;
can take values from 0 to 1;
default value: 0.7
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[temperature](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#temperature)

#### Defined in

[main.ts:159802](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159802)

___


### text

• `Optional` **text**: `string`

initial target text
required field
text input for content generation;
can contain from 1 to 500 tokens
learn more about tokens on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[text](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#text)

#### Defined in

[main.ts:159749](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159749)

___


### token\_repetition\_penalty

• `Optional` **token\_repetition\_penalty**: `number`

token repetition
optional field
limits the repetition of the same tokens in the generated content;
can take values from 0.5 to 2;
default value: 1

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[token_repetition_penalty](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#token_repetition_penalty)

#### Defined in

[main.ts:159777](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159777)

___


### top\_k

• `Optional` **top\_k**: `number`

the number of initial tokens in each iteration for choosing a subsequent word
optional field
if you use creativity_index, this field will be ignored
the higher the number, the more high-probability tokens will be shortlisted for generation;
can take values from 1 to 100;
default value: 40
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[top_k](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#top_k)

#### Defined in

[main.ts:159785](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159785)

___


### top\_p

• `Optional` **top\_p**: `number`

excludes initial tokens with probability lower than one
optional field
if you use creativity_index, this field will be ignored
the higher the value, the less low-probability tokens may be shortlisted for generation;
can take values from 0 to 1
default value: 0.9
Note:if both top_k and top_p are used, top_k acts first;
learn more about this parameter on our help center

#### Implementation of

[IContentGenerationGenerateLiveRequestInfo](../interfaces/IContentGenerationGenerateLiveRequestInfo.md).[top_p](../interfaces/IContentGenerationGenerateLiveRequestInfo.md#top_p)

#### Defined in

[main.ts:159794](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159794)

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

[main.ts:159845](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159845)

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

[main.ts:159886](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159886)

___


### fromJS

▸ **fromJS**(`data`): [`ContentGenerationGenerateLiveRequestInfo`](ContentGenerationGenerateLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ContentGenerationGenerateLiveRequestInfo`](ContentGenerationGenerateLiveRequestInfo.md)

#### Defined in

[main.ts:159879](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L159879)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")