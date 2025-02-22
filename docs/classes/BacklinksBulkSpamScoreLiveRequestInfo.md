[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksBulkSpamScoreLiveRequestInfo

# Class: BacklinksBulkSpamScoreLiveRequestInfo

## Implements

- [`IBacklinksBulkSpamScoreLiveRequestInfo`](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksBulkSpamScoreLiveRequestInfo.md#constructor)

### Properties

- [tag](BacklinksBulkSpamScoreLiveRequestInfo.md#tag)
- [targets](BacklinksBulkSpamScoreLiveRequestInfo.md#targets)

### Methods

- [init](BacklinksBulkSpamScoreLiveRequestInfo.md#init)
- [toJSON](BacklinksBulkSpamScoreLiveRequestInfo.md#tojson)
- [fromJS](BacklinksBulkSpamScoreLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksBulkSpamScoreLiveRequestInfo**(`data?`): [`BacklinksBulkSpamScoreLiveRequestInfo`](BacklinksBulkSpamScoreLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksBulkSpamScoreLiveRequestInfo`](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md) |

#### Returns

[`BacklinksBulkSpamScoreLiveRequestInfo`](BacklinksBulkSpamScoreLiveRequestInfo.md)

#### Defined in

[main.ts:140002](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140002)

## Properties

### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IBacklinksBulkSpamScoreLiveRequestInfo](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md).[tag](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md#tag)

#### Defined in

[main.ts:139998](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139998)

___


### targets

• `Optional` **targets**: `string`[]

domains, subdomains or webpages to get rank for
required field
you can set up to 1000 domains, subdomains or webpages
the domain or subdomain should be specified without https:// and www.
the page should be specified with absolute URL (including http:// or https://)
example:
"targets": [
"forbes.com",
"cnn.com",
"bbc.com",
"yelp.com",
"https://www.apple.com/iphone/",
"https://ahrefs.com/blog/",
"ibm.com",
"https://variety.com/",
"https://stackoverflow.com/",
"www.trustpilot.com"
]

#### Implementation of

[IBacklinksBulkSpamScoreLiveRequestInfo](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md).[targets](../interfaces/IBacklinksBulkSpamScoreLiveRequestInfo.md#targets)

#### Defined in

[main.ts:139992](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139992)

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

[main.ts:140011](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140011)

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

[main.ts:140033](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140033)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksBulkSpamScoreLiveRequestInfo`](BacklinksBulkSpamScoreLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksBulkSpamScoreLiveRequestInfo`](BacklinksBulkSpamScoreLiveRequestInfo.md)

#### Defined in

[main.ts:140026](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140026)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")