[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IContentGenerationGenerateTextLiveResultInfo

# Interface: IContentGenerationGenerateTextLiveResultInfo

## Implemented by

- [`ContentGenerationGenerateTextLiveResultInfo`](../classes/ContentGenerationGenerateTextLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [generated\_text](IContentGenerationGenerateTextLiveResultInfo.md#generated_text)
- [input\_tokens](IContentGenerationGenerateTextLiveResultInfo.md#input_tokens)
- [new\_tokens](IContentGenerationGenerateTextLiveResultInfo.md#new_tokens)
- [output\_tokens](IContentGenerationGenerateTextLiveResultInfo.md#output_tokens)
- [supplement\_token](IContentGenerationGenerateTextLiveResultInfo.md#supplement_token)

## Properties

### generated\_text

• `Optional` **generated\_text**: `string`

resulting text

#### Defined in

[main.ts:160450](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L160450)

___


### input\_tokens

• `Optional` **input\_tokens**: `number`

number of input tokens

#### Defined in

[main.ts:160444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L160444)

___


### new\_tokens

• `Optional` **new\_tokens**: `number`

number of new tokens

#### Defined in

[main.ts:160448](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L160448)

___


### output\_tokens

• `Optional` **output\_tokens**: `number`

number of output tokens

#### Defined in

[main.ts:160446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L160446)

___


### supplement\_token

• `Optional` **supplement\_token**: `string`

token for generating subsequent results
you can use this parameter to continue the generation from the end of the current result;
supplement_token values are unique for each subsequent task

#### Defined in

[main.ts:160454](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L160454)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")